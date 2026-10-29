# Khaya Dlamini: AI coach website

A static website with four pages. No build step. It works free on GitHub Pages.

## Files
- `index.html`: home page with the laptop-to-book scroll animation
- `about.html`: your introduction and story
- `services.html`: offers, prices, who you teach, how a session works
- `contact.html`: WhatsApp and email buttons
- `style.css`, `script.js`: design and behaviour
- `config.js`: **your WhatsApp number and email**
- `khaya.jpg`: your photo

## Your contact details
They are set in `config.js`. The WhatsApp buttons open a chat with a message already typed. The "Email me" buttons open the visitor's email app addressed to you.

Check the email address is exactly right (it is set to `khayadlamini352@gmail.com`).

## Edit the content
- Prices: open `services.html` and search for `EDIT PRICE`.
- Your story: open `about.html` and change the text in the "story" section.

## Put it on GitHub
1. On github.com click **New repository**. Name it `yourusername.github.io` for a main address, or any name for `yourusername.github.io/name`.
2. Upload all the files in this folder (or use `git add .`, `git commit`, `git push` from VS Code).
3. In the repository go to **Settings, Pages**. Under "Build and deployment" choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After about a minute your site is live at the address shown on that page.
