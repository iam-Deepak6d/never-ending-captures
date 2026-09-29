# Never Ending Captures — Portfolio

Responsive static photography + film portfolio. It has **no framework, no build step, no database and no required third-party form service**. The fonts are local system fallbacks and all website media is stored in the project.

## Included
- Desktop, tablet and mobile responsive design
- Local logo, photography and video assets
- Cinematic hero section
- Weddings / Portraits / Lifestyle / Interiors sections
- Film modal with the supplied video
- Mobile menu and scroll animations
- WhatsApp + email enquiry buttons
- Netlify-ready (`netlify.toml`)
- GitHub Pages-ready (`.nojekyll`)

## Before launch
Open `assets/js/config.js` and contact details are already configured in `assets/js/config.js`. Update them there if needed before launch.

## GitHub Pages
1. Create a new GitHub repository.
2. Upload **everything inside this folder** to the repository root.
3. GitHub → repository → Settings → Pages.
4. Source: **Deploy from a branch** → Branch `main` → Folder `/ (root)` → Save.
5. GitHub will show your live Pages address.

## Netlify
Upload the whole folder using Netlify's manual deploy, or connect the GitHub repository to Netlify. The site is static and needs no build command.

## Custom domain
Once hosted, add your domain in the hosting provider's Domain settings and follow the DNS records the provider displays. Do not hard-code DNS records into this project.

## Important video note
The original supplied video was 1920×1080 and large. The included `assets/video/nec-film.mp4` is a web-optimized 720p version so static hosting can serve it reliably. Keep the original master video separately for editing/archive.
