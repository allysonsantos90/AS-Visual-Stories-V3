AS VISUAL STORIES — V7
======================

Files are arranged for GitHub Pages publishing from the repository root.
Keep index.html, all page HTML files, and the assets folder together.

Pages:
- index.html
- weddings.html
- wedding-stories.html
- events.html
- cinematic-stories.html
- about.html

Assets:
- assets/site.css
- assets/site.js
- assets/allyson-portrait.jpg

Publishing:
1. Replace the existing site files with the contents of this V7 package.
2. Upload the assets folder itself (not just the files inside it).
3. Confirm GitHub Pages is set to deploy from main / root.
4. Test the site in a private/incognito browser window.

Wedding Stories:
The Craig & Sophie YouTube playlist is embedded in an on-page modal:
https://www.youtube-nocookie.com/embed/videoseries?list=PLRB-UZtx63s8

The collection page is prepared for individual video cards, two at a time.
To publish exact video titles and descriptions, add the individual video URLs
and their YouTube descriptions. These details are not guessed or fabricated.

Console:
The site JavaScript uses guarded localStorage access and has no asynchronous
message-channel listener. If the "A listener indicated an asynchronous response"
error remains, test with browser extensions disabled; that message is commonly
injected by extensions and is not proof of a site JavaScript error.
