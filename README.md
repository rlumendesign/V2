# RLumen Portfolio Website

A responsive, static portfolio website for RLumen, built with HTML, CSS, and JavaScript.

## Files
- `index.html` — website content
- `style.css` — layout, typography, colors, and hover effects
- `script.js` — mobile menu and email-compose contact form
- `assets/rlumen-brand-graphic.png` — supplied brand graphic

## Preview
Double-click `index.html` to open it in a web browser.

## Add images
1. Upload your image to the `assets` folder.
2. For the headshot, replace the entire `<div class="portrait-placeholder" ...> ... </div>` block with `<img class="profile-photo" src="assets/headshot.jpg" alt="Ronald A. Lalaguna" />` and add `.profile-photo{width:100%;height:310px;object-fit:cover;border-radius:20px}` to `style.css`.
3. For a portfolio placeholder, replace its `<div class="project-media placeholder-media"> ... </div>` block with `<div class="project-media"><img src="assets/project-name.jpg" alt="Description of the project"></div>`.
4. For a certificate, replace `<div class="certificate-placeholder"> ... </div>` with `<div class="project-media"><img src="assets/certificate-name.jpg" alt="Certificate title"></div>` and update the title, provider, and date.
5. For real testimonials, replace bracketed placeholder text and reviewer details. Get permission before publishing names and quotes.

The contact form opens the visitor's email application. It does not submit to a server.
