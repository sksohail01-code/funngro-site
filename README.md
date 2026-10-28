# Funngro 2-page website
Static site: index.html (Teens), companies.html (Companies), plus robots.txt, sitemap.xml, SEO-AUDIT.md.

## Push to Git
git init && git add . && git commit -m "Funngro 2-page site"
git branch -M main && git remote add origin <YOUR_REPO_URL> && git push -u origin main

## Deploy on Render
Static Site, publish directory `./`, build command `echo no build` (or use render.yaml as a Blueprint).
After deploy, replace https://funngro-site.onrender.com in the HTML files, sitemap.xml and robots.txt with your real URL.
