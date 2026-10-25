# Christian Rizarri — Portfolio Setup & Publishing Guide

## About this website
- Name: Christian Rizarri
- School: Cebu Eastern College
- Course: Information Technology
- Design: Modern dark blue
- Projects featured: EquiAid and FixMo
- Profile image: SVG placeholder (replace when you have a photo)
- Contact: christianrizarri2005@gmail.com

The website uses plain HTML, CSS, and JavaScript. It does not require a framework or paid hosting. Project descriptions are intentionally cautious: add your own real contribution, screenshots, links, and verified features before submission.

## Files
- `index.html` — page content
- `style.css` — design and mobile responsiveness
- `script.js` — mobile navigation and current year
- `assets/profile-placeholder.svg` — placeholder profile illustration; replace it with a photo you have permission to publish
- `README.md` — this guide

## 1. Preview on your computer
1. Download and extract the ZIP.
2. Open Visual Studio Code.
3. Choose **File → Open Folder** and select `christian_rizarri_personalized_portfolio`.
4. Open `index.html` in your browser, or use the Microsoft Live Preview extension.
5. Test the menu, section links, email link, and phone-width layout.

## 2. Personalize before publishing
1. In `index.html`, check the About section and make sure it accurately describes you.
2. Under Skills, keep only areas you are currently learning or can discuss honestly.
3. Under each project, replace the contribution prompt with the work you personally did. Do not claim unbuilt features or results.
4. Replace `assets/profile-placeholder.svg` with your own permitted photo. If you use a JPG, update the `src` path in `index.html`, for example `assets/profile.jpg`.
5. Replace the generic GitHub link `https://github.com/` with your actual profile URL, or remove that link if you do not have a profile.
6. Decide whether you want your email displayed publicly. It is currently visible and may receive spam if published.

## 3. Publish with GitHub Pages (recommended for this plain website)
1. Sign in or create an account at https://github.com.
2. Create a **Public** repository named `portfolio`.
3. Open the new repository and choose **Add file → Upload files**.
4. Extract this ZIP first. Upload the contents of the folder (the `index.html`, `style.css`, `script.js`, `README.md`, and `assets` folder), not the ZIP itself. Keep the `assets` folder intact.
5. Enter a commit message such as `Add student portfolio` and commit the files.
6. Open **Settings → Pages** in the repository.
7. Under **Build and deployment**, select **Deploy from a branch**.
8. Select branch `main` and folder `/(root)`, then click **Save**.
9. Wait for GitHub Pages to publish. Copy the public HTTPS link shown on the Pages screen. It usually looks like `https://YOUR-USERNAME.github.io/portfolio/`.
10. Open the published link in a private/incognito browser window and on your phone. Test all sections and the email link.

## 4. Updating the site
1. Edit the files locally.
2. Upload the changed files to the same GitHub repository, preserving paths.
3. Commit the changes and wait for deployment to finish.
4. Refresh the same live website URL.

## Final submission checklist
- [ ] The live HTTPS URL opens while signed out.
- [ ] The site works on both desktop and mobile.
- [ ] No placeholder profile photo or contribution prompts remain unless intentionally retained.
- [ ] Skills and project contributions are accurate.
- [ ] The email and GitHub links are correct and intentional to publish.
- [ ] Screenshots are taken from the finished live site.
- [ ] You can explain the main files and how you published an update.
- [ ] If required by your teacher, include a short note explaining any AI or template assistance used.

## AI/template disclosure suggestion
"I used AI assistance to help create and organize the initial HTML, CSS, JavaScript, and publishing instructions. I reviewed and personalized the content and should be prepared to explain the code and changes I made."


## Project preview pages

This portfolio includes two local front-end mockups linked from the project cards:

- `equiaid-preview.html` — EquiAid social assistance dashboard concept with searchable/filterable fictional household records.
- `fixmo-preview.html` — FixMo service finder concept with searchable/filterable fictional worker profiles and sample profile dialogs.

These are demonstration interfaces only. They do not connect to a database or provide real AI scoring, account login, messaging, booking, or payments. Keep the prototype disclaimer visible, and replace fictional data with approved test data only if your project team is ready.

When publishing on GitHub Pages, upload both preview HTML files alongside `index.html`, `style.css`, `script.js`, and the `assets` folder. The links work as long as the files stay in the same root folder.
