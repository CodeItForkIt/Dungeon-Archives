<%* const SOURCE_SUFFIXES = [ "aag", "aatm", "abh", "ai", "al", "alcos", "alee", "alrod", "awm", "azfyt", "aitfr", "aitfr-avt", "aitfr-dn", "aitfr-fcd", "aitfr-isf", "aitfr-thp", "bam", "bgdia", "bgg", "bmt", "bqgt", "cm", "crcotn", "coa", "cos", "dc", "dd", "dip", "dmg", "dmtcrg", "dsotdq", "ditlcot", "dod", "dodk", "dosi", "drde", "eepc", "eet", "efa", "efr", "egw", "egw_dd", "egw_fs", "egw_tor", "egw_us", "erlw", "esk", "ffotr", "fraif", "fraif-tllol", "frhof", "fs", "ftd", "ggr", "gos", "gotsf", "hat-lmi", "hat-tg", "hbtd", "hf", "hffotm", "hfstcm", "hwaitw", "hwcs", "hftt", "hol", "hotb", "hotdq", "idrotf", "imr", "jttrc", "kkw", "kftgv", "lfl", "lk", "llk", "lmop", "lr", "lrdt", "lox", "mcv1sc", "mcv2dc", "mcv3mc", "mcv4ec", "mff", "mgelft", "mm", "mot", "mpmm", "mpp", "mtf", "mabjov", "mismv1", "nf", "nrh", "nrh-ass", "nrh-at", "nrh-avitw", "nrh-awol", "nrh-coi", "nrh-tcmc", "nrh-tlt", "oga", "oow", "oota", "phb", "psa", "psd", "psi", "psk", "psx", "psz", "pabtso", "paf", "pip", "pota", "qftis", "rmbre", "rmr", "rot", "rotos", "rtg", "sac", "sads", "sais", "scag", "scc", "scc-arir", "scc-ck", "scc-hfmt", "scc-tmm", "screen", "sdw", "skt", "slw", "sato", "scoee", "sja", "tce", "td", "tlk", "ttp", "tftyt", "tftyt-atg", "tftyt-dit", "tftyt-tfof", "tftyt-thsot", "tftyt-tsc", "tftyt-toh", "tftyt-wpm", "toa", "tob1-2023", "tod", "tofw", "tor", "uatmc", "us", "uthftlh", "vd", "veor", "vgm", "vnotee", "vrgr", "wbtw", "wdh", "wdmm", "wtthc", "xdmg", "xge", "xmm", "xmts", "xphb", "xsac", "xscreen", "rhw", "srd", "basicrules", "srd52", "basicrules2024", ];

const LOWERCASE_WORDS = [ "a", "an", "the", "and", "but", "or", "for", "nor", "of", "to", "in", "on", "at", "by", "up", "as", ];

const NOT_CATEGORIES = [ "adult", "ancient", "young", "wyrmling", "lesser", "greater", "elder", "dire", "swarm", "deep", "high", "wood", "dark", "wild", "shadow", "sea", "cave", "drow", "half", "were", ];

const looksLikeSource = (word) => { if (word.length < 2 || word.length > 8) return false; let allAlNum = true; for (let i = 0; i < word.length; i++) { const c = word.charCodeAt(i); const isLetter = (c >= 97 && c <= 122); const isDigit = (c >= 48 && c <= 57); if (isLetter === false && isDigit === false) { allAlNum = false; break; } } return allAlNum; };

const titleCaseWord = (word, isFirst, isLast) => { let isLower = false; for (let i = 0; i < LOWERCASE_WORDS.length; i++) { if (LOWERCASE_WORDS[i] === word) { isLower = true; break; } } if (isLower === true && isFirst === false && isLast === false) return word; return word.charAt(0).toUpperCase() + word.slice(1); };

const fixCapitalization = (name) => { if (name.indexOf("-") !== -1) return name; if (name.indexOf(" ") === -1) return name;

let prefix = ""; let body = name;

if (name.indexOf(" - ") !== -1) { const sepIdx = name.indexOf(" - "); prefix = name.slice(0, sepIdx); body = name.slice(sepIdx + 3); prefix = prefix.charAt(0).toUpperCase() + prefix.slice(1); }

const words = body.split(" "); let fixed = ""; for (let i = 0; i < words.length; i++) { if (words[i].length === 0) continue; if (fixed.length > 0) fixed = fixed + " "; const w = words[i].toLowerCase(); fixed = fixed + titleCaseWord(w, i === 0, i === words.length - 1); }

if (prefix.length > 0) return prefix + " - " + fixed; return fixed; };

const getNewName = (oldName) => { const lower = oldName.toLowerCase(); const raw = lower.split("-");

const parts = []; for (let i = 0; i < raw.length; i++) { const p = raw[i]; if (p.length === 0) continue; let isSource = false; for (let j = 0; j < SOURCE_SUFFIXES.length; j++) { if (SOURCE_SUFFIXES[j] === p) { isSource = true; break; } } if (isSource === false) parts.push(p); }

if (parts.length === 0) return oldName;

while (parts.length > 1 && looksLikeSource(parts[parts.length - 1]) === true) { parts.pop(); }

if (parts.length === 0) return oldName;

const first = parts[0];

let isNotCat = false; for (let i = 0; i < NOT_CATEGORIES.length; i++) { if (NOT_CATEGORIES[i] === first) { isNotCat = true; break; } }

let hasDigit = false; for (let i = 0; i < first.length; i++) { const c = first.charCodeAt(i); if (c >= 48 && c <= 57) { hasDigit = true; break; } }

const longEnough = parts.length >= 3; const isCategory = (longEnough === true && isNotCat === false && hasDigit === false && first.length <= 12);

if (isCategory === true) { const cat = first.charAt(0).toUpperCase() + first.slice(1); let subtype = ""; for (let i = 1; i < parts.length; i++) { if (i > 1) subtype = subtype + " "; subtype = subtype + titleCaseWord(parts[i], i === 1, i === parts.length - 1); } let result = cat + " - " + subtype; while (result.indexOf(" ") !== -1) { result = result.replace(" ", " "); } return result; }

let result = ""; for (let i = 0; i < parts.length; i++) { if (i > 0) result = result + " "; result = result + titleCaseWord(parts[i], i === 0, i === parts.length - 1); } while (result.indexOf(" ") !== -1) { result = result.replace(" ", " "); } return result; };

const doRename = (oldName, newName, file) => { const parentPath = file.parent.path; if (parentPath === "/" || parentPath === "") { return newName + ".md"; } return parentPath + "/" + newName + ".md"; };

let count = 0; let skipped = 0; let conflicts = 0;

const files = app.vault.getMarkdownFiles();

for (let i = 0; i < files.length; i++) { const file = files[i]; const oldName = file.basename; const newName = getNewName(oldName);

if (oldName === newName) { skipped = skipped + 1; continue; }

const newPath = doRename(oldName, newName, file); const existing = app.vault.getAbstractFileByPath(newPath); if (existing) { conflicts = conflicts + 1; continue; }

await app.fileManager.renameFile(file, newPath); count = count + 1; }

const files2 = app.vault.getMarkdownFiles();

for (let i = 0; i < files2.length; i++) { const file = files2[i]; const oldName = file.basename; const newName = fixCapitalization(oldName);

if (oldName === newName) { skipped = skipped + 1; continue; }

const newPath = doRename(oldName, newName, file); const existing = app.vault.getAbstractFileByPath(newPath); if (existing) { conflicts = conflicts + 1; continue; }

await app.fileManager.renameFile(file, newPath); count = count + 1; }

new Notice("Done! Renamed " + count + ", skipped " + skipped + ", conflicts " + conflicts + "."); %>