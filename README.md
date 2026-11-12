# Saranath College – Website

## Files
| File | What it is |
|---|---|
| `index.html` | The whole website (HTML + CSS + JavaScript) |
| `logo.jpg` | College crest |
| `hero.jpg` | **(add this)** Big background photo of the school, ideally the main building or front gate. Use a landscape photo about 1920px wide. Once you put it in this folder, it shows up automatically. |
| `principal.jpg` | **(add this)** Principal's photo, upright (portrait) format. Once you put it in this folder, it shows up automatically. |

The site still looks fine without `hero.jpg` and `principal.jpg`. Until you add them it shows a blue crest design instead.

## Free hosting (choose one)

### Netlify Drop (easiest, about 1 minute)
1. Go to https://app.netlify.com/drop
2. Drag the whole `saranath-site` folder onto the page
3. You get a live link. Make a free account, then go to Site settings → Change site name and pick something like `saranath-college`

### GitHub Pages (best for keeping it long-term)
1. Make a free account at https://github.com
2. New repository → name it `saranath-college` → Public → Create
3. Click "uploading an existing file" → upload **every** file in this folder → Commit
4. Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save
5. Live in 1–2 minutes at `https://<username>.github.io/saranath-college/`

### Cloudflare Pages
https://pages.cloudflare.com → Create project → Direct Upload → upload the folder.

## Making changes
- **Colours**: change `--navy`, `--blue` and `--gold` in the `:root{ ... }` block at the top of `index.html`
- **Principal's message**: search for `PRINCIPAL'S MESSAGE` in `index.html`
- **Intro screen**: the motto letters appear one by one, and visitors can tap anywhere or press SKIP
- The "144 Years" figure updates by itself every year
