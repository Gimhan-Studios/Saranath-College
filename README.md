# සාරානාත් විද්‍යාලය – Website

මේ site එකේ files 2යි: `index.html` (HTML + CSS + JavaScript සේරම එකේ) සහ `logo.jpg` (පාසල් ලාංඡනය). Upload කරද්දී **දෙකම එකම තැනට** දාන්න.
Build කරන්න ඕන නෑ, server-side code නෑ. ඒ නිසා ඕනම static hosting එකක free එකේ host කරන්න පුළුවන්.

## ක්‍රමය 1: Netlify Drop (ලේසිම ක්‍රමය, විනාඩි 1යි)
1. https://app.netlify.com/drop එකට යන්න
2. `saranath-site` folder එක ඒකට drag & drop කරන්න
3. Link එක ලැබෙනවා (උදා: `random-name.netlify.app`)
4. Free account එකක් හදලා Site settings → Change site name → `saranath-vidyalaya` වගේ නමක් දාන්න

## ක්‍රමය 2: GitHub Pages (ස්ථිරව තියාගන්න හොඳම ක්‍රමය)
1. https://github.com එකේ free account එකක් හදන්න
2. New repository → නම `saranath-vidyalaya` → Public → Create
3. "uploading an existing file" click කරලා `index.html` සහ `logo.jpg` දෙකම upload කරන්න → Commit
4. Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save
5. විනාඩි 1-2කින් site එක live: `https://<username>.github.io/saranath-vidyalaya/`

## ක්‍රමය 3: Cloudflare Pages
https://pages.cloudflare.com → Create project → Direct Upload → folder එක upload කරන්න.

## වෙනස් කරන්න පුළුවන් දේවල්
- **පාසල් වර්ණ**: `index.html` එකේ උඩම `:root{ ... }` එකේ `--main` (නිල්), `--gold` (රන්) අගයන් වෙනස් කරන්න
- **නිවාස වර්ණ**: `<!-- නිවාස නම්/වර්ණ -->` comment එක යට තියෙන `background:` අගයන්
- **ලාංඡනය**: වඩා හොඳ quality logo එකක් තියෙනවා නම් ඒක `logo.jpg` නමින්ම replace කරන්න (හතරැස් image එකක් හොඳයි)
- **අලුත් අවුරුද්දක් timeline එකට**: `<div class="item reveal">...</div>` block එකක් copy කරලා අගයන් වෙනස් කරන්න

"වසර 144" අගය හැම අවුරුද්දකම automatic update වෙනවා.
