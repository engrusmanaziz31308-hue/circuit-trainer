# Circuit Trainer - website files

Upload everything in this folder to the ROOT of your GitHub repository
(the repository published with GitHub Pages). Keep the folder structure:

    index.html               the app
    about.html               About page
    privacy.html             Privacy policy
    sw.js                    service worker (offline support, network-first)
    manifest.webmanifest     app manifest (install as an app)
    robots.txt               search engine rules
    sitemap.xml              list of pages for search engines
    ads.txt                  AdSense publisher line (add after approval)
    icons/                   app icons
    guides/                  guide pages and guides index

Before publishing, replace the placeholders:
- [YOUR-SITE-URL] in robots.txt and sitemap.xml (example: yourname.github.io/circuit-trainer)
- [Your name], [Your city], [your email], [DATE] in about.html and privacy.html

When you publish a new version of the app, change CACHE in sw.js (for example
circuit-trainer-v3 to circuit-trainer-v4) so visitors get the update.
