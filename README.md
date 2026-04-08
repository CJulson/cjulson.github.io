# Connor Julson — Portfolio

Minimalist personal portfolio site. Built with vanilla HTML, CSS, and JS. No build tools or dependencies required.

## File structure

```
portfolio/
├── index.html          ← About / Welcome page
├── resume.html         ← Résumé embed
├── extracurricular.html ← Clubs & volunteer work
├── experience.html     ← Professional experience
├── social.html         ← Social media links
├── style.css           ← All styles
└── images/             ← Your photos go here
    ├── profile.jpg
    ├── interests.jpg
    ├── pisec.jpg
    ├── cybersec-club.jpg
    ├── melee.jpg
    ├── desktop-support.jpg
    ├── cybersec-intern.jpg
    └── asset-mgmt.jpg
```

## Setup for GitHub Pages

1. Create a new GitHub repository (e.g. `connorjulson.github.io` or `portfolio`)
2. Upload all files preserving the structure above
3. Go to **Settings → Pages**, set source to `main` branch, root `/`
4. Your site will be live at `https://USERNAME.github.io/REPO`

## Adding your photos

- Drop your photos into an `images/` folder in the repo
- Name them to match the `src` attributes in the HTML (see structure above)
- Or just update the `src` values to match whatever filenames you use
- If an image is missing, the site gracefully shows a placeholder — nothing breaks

## Embedding your resume

1. Upload your resume PDF to Google Drive
2. Set sharing: **Anyone with the link → Viewer**
3. Copy the file ID from the share URL: `drive.google.com/file/d/FILE_ID/view`
4. Open `resume.html`, find the commented-out `<iframe>` block
5. Replace `FILE_ID` with your actual ID and uncomment the iframe
6. Remove the placeholder `<div>` below it
7. Update the "Open in Google Drive" button's `href` with your full share link

## Customization checklist

- [ ] Add photos to `images/` folder
- [ ] Add Google Drive resume embed to `resume.html`
- [ ] Update LinkedIn URL in `social.html` (already set to your profile)
- [ ] Add a second social profile in `social.html` (GitHub recommended)
- [ ] Update footer year if needed
