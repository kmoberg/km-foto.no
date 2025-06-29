KM-Foto Splash Page

A one-file, responsive splash/landing page for km-foto.no / studiomoberg.no designed for GitHub Pages hosting. It shows a fullscreen slideshow of hero images with a short animated intro and a link to the main studio site.

<p align="center">
  <img src="assets/preview.jpg" alt="Screenshot" width="640" />
</p>



⸻

✨ Features
	•	Pure HTML + CSS – no frameworks, build steps, or JavaScript required.
	•	Accessible: honours prefers-reduced-motion and contains semantic markup.
	•	Custom-time CSS variable --slide-duration makes it trivial to change how long each slide stays visible.
	•	Easily swap hero images by editing the <div class="slide"> blocks.

⸻

🚀 Quick start (GitHub Pages)
	1.	Fork or clone this repo.
	2.	Copy your photographs into /assets and update index.html accordingly.
	3.	Commit & push to main (or create a gh-pages branch).
	4.	In Repo Settings → Pages, choose the branch and / (root) folder. Save.
	5.	GitHub will deploy automatically; your site appears at https://<username>.github.io/<repo>/.

Tip: If you want the page to live at a custom domain (e.g. km-foto.no), add a CNAME file containing that domain, and point your DNS A/ALIAS/ANAME to GitHub Pages’ IPs.

⸻

🛠 Customization

What	How
Slide duration	In index.html, edit :root { --slide-duration: 4s; }
Images	Replace /assets/hero*.jpg and/or add more <div class="slide"> blocks. Each slide’s animation-delay is calculated automatically.
Text copy	Update the <h1> content – the first <span class="lead"> is the big heading, the rest are .sub.
Colours / overlay strength	Tweak .slideshow::after { background: rgba(0,0,0,0.45); } or link colours in the CSS section.


⸻

🧩 Folder structure

.
├── index.html       # The entire site 👈
├── assets/
│   ├── hero1.jpg
│   ├── hero2.jpg
│   ├── hero3.jpg
│   ├── hero4.jpg
│   └── preview.jpg  # Optional screenshot for the README
├── LICENSE.md
└── README.md        # You are here

Feel free to reorganise; GitHub Pages will serve any static files.

⸻

📜 License
	•	Code – MIT (see LICENSE.md).
	•	Images – © Karl Mathias Moberg, all rights reserved. You may not reuse them without written permission.

⸻

📮 Contact

Questions, feedback, or licensing requests? Drop me a line at post@studiomoberg.no.