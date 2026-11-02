
# AS Visual Stories — corrected GitHub Pages package

## IMPORTANT: upload the whole `videos` folder
Your current page URL is:
`https://allysonsantos90.github.io/videos/wedding-event-films.html`

This package preserves that URL structure. Upload the **contents of this `videos` folder** into the existing repository's `videos/` directory, including the `assets/` folder. Do not upload only the HTML files.

Expected repository layout:
```
repository/
└── videos/
    ├── index.html
    ├── cinematic-stories.html
    ├── wedding-event-films.html
    ├── about.html
    └── assets/
        ├── site.css
        ├── site.js
        └── allyson-portrait.jpg
```

The missing CSS/assets path is what caused the unstyled page in the screenshot.

## Features
- Fixed relative asset paths for the `/videos/` URL
- Updated About section using the portrait you supplied
- Instagram embeds for the five post URLs you supplied, plus Follow button
- Craig & Sophie YouTube playlist embedded as a single player using the playlist ID previously shared
- Clearer EN/PT selected-state control
- Responsive layout

Instagram embeds require the posts to be public and Instagram's embed script to load. If a post is unavailable for embedding, the profile Follow button remains available.
