MEGSART WEBSITE — QUICK START

FILES
- index.html: your complete responsive website
- images/: replaceable artwork photo slots (see below)

1) ADD YOUR WHATSAPP NUMBER
Open index.html in a text editor (Notepad is fine).
Near the bottom, find:
const WHATSAPP_NUMBER = "";
Replace the empty string with your full number including country code, digits only.
India example: const WHATSAPP_NUMBER = "919876543210";
Do not include +, spaces, or hyphens. Save the file.
Test the site by opening index.html in your browser and clicking an enquiry button.

2) ADD YOUR OWN ART PHOTOS
Copy your photos into the images folder and use these exact filenames:
- hero-art.jpg       (featured artwork at the top)
- mini-canvas.jpg    (mini canvas example)
- custom-art.jpg     (custom artwork)
- painted-gift.jpg   (painted object / gift)
- pastel-art.jpg     (another artwork)
- handmade-gift.jpg  (handmade gift)
- your-idea.jpg      (custom idea)
- artist-desk.jpg    (your workspace or art process)
You can use .jpg photos. If your photos are .png, either convert them to JPG or update the corresponding filename in index.html.
The current online sample photos are only placeholders. Replace them before publishing so the gallery shows your actual work.

3) EDIT TITLES, DESCRIPTIONS, PRICES
Open index.html and search for the sample titles such as “Little Canvas Dreams”.
Edit the title, description, and “Price on enquiry” text to match your work. Do not add a price unless you want it public.

4) FREE PUBLISHING WITH GITHUB PAGES
A. Sign in or create a free account at https://github.com/
B. Create a new public repository named megsart-website.
C. Upload index.html and the images folder (including your photos) to the repository root.
D. In the repository, open Settings → Pages.
E. Under “Build and deployment”, choose “Deploy from a branch”.
F. Choose branch “main” and folder “/ (root)”, then Save.
G. Wait for the Pages deployment to finish. GitHub will show the published website URL in Settings → Pages. It will usually look like https://YOUR-USERNAME.github.io/megsart-website/
H. Open the URL on your phone and test every WhatsApp button.

NOTES
- GitHub Pages is free for a public repository, but the website is public and anyone with the link can see it.
- No customer payment or checkout is included; customers contact you on WhatsApp.
- A custom domain is optional and usually costs money.
- Whenever you change the files and upload the updates to GitHub, the site will republish.
