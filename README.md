# John Rey L. Laput — Portfolio Website

A responsive personal portfolio built with plain HTML, CSS, and vanilla JavaScript.

## Files
- `index.html` — page structure and portfolio content
- `style.css` — dark navy / black responsive design
- `script.js` — mobile menu, scroll reveal, and current footer year
- `assets/` — place optional images and documents here

## Run locally
1. Extract the ZIP file.
2. Open the `john_rey_laput_portfolio` folder.
3. Double-click `index.html` to open it in a browser.
4. For a local development server, open the folder in VS Code and use the Live Server extension.

No Node.js, PHP, database, or build step is required. Google Fonts are loaded from the internet; the site still works with fallback fonts if offline.

## Personalize before publishing
1. **Profile photo:** The hero currently uses a monogram avatar (`JL`). To use a photo, add `assets/profile.jpg` and replace the `<div class="avatar">JL</div>` in `index.html` with:
   `<img class="avatar" src="assets/profile.jpg" alt="John Rey L. Laput">`
   Then add `object-fit: cover;` to `.avatar` in `style.css`.
2. **Projects:** Your supplied CV did not list specific projects. Replace the placeholder in the Projects section with your actual projects, screenshots, technology stack, and working demo/source links. Do not publish a project link until it is live and verified.
3. **CV download:** If you want a public CV download, put a public-safe PDF at `assets/John-Rey-Laput-CV.pdf` and add a link such as:
   `<a href="assets/John-Rey-Laput-CV.pdf" download>Download CV</a>`
   Review the PDF first and remove personal details you do not want public.
4. **Contact details:** Confirm the email and phone number in `index.html` before publishing. Remove the phone link if you prefer not to publish it.
5. **SEO:** Update the page title and description in the `<head>` if your professional focus changes.

## Deploy free
- **GitHub Pages:** create a repository, upload the contents of this folder, and enable Pages in repository Settings.
- **Netlify:** drag the extracted folder into Netlify's manual deploy area, or connect a Git repository.
- **Cloudflare Pages:** connect a Git repository and use the project root; no build command is needed.

## Accuracy note
Education, location, skills, objective, email, and phone details were taken from the supplied CV. The CV did not provide a work-history section, project descriptions, certificates, or portfolio links, so those have not been fabricated. Character references and personal details such as birthdate, civil status, gender, and religion are intentionally excluded from the public site.
