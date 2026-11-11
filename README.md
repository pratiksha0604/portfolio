# Pratiksha Bhende - Portfolio

Optimized portfolio website (minified CSS/JS, lazy loading, SEO, accessibility) deployed on Netlify.

## Live site
**https://pratiksha0604-portfolio.netlify.app**
(Replace with your actual subdomain if you choose a different one.)

## Project structure
```
index.html
netlify.toml
css/style.css, style.min.css
js/main.js, main.min.js
images/profile.svg
```

## Deployment steps
1. Push the production branch to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Production build"
   git branch -M main
   git remote add origin https://github.com/pratiksha0604/portfolio.git
   git push -u origin main
   ```
2. In Netlify: **Add new site -> Import an existing project -> GitHub**, select the repo. Build command: *(leave empty)*. Publish directory: `.`
3. `netlify.toml` (included) sets the publish directory, SPA redirect (`/* -> /index.html 200`) and caching/security headers.
4. **Site configuration -> Change site name** and set `pratiksha0604-portfolio` -> `https://pratiksha0604-portfolio.netlify.app`.
5. Verify: open the live URL, click every nav link, test the contact form and the mobile menu, then confirm this README has the final URL.

## Verification checklist
- [ ] Live site loads over HTTPS
- [ ] Nav links (Home, About, Projects, Contact) scroll correctly
- [ ] Refreshing / opening an unknown path serves the site (redirect works)
- [ ] Contact form validation works
- [ ] Mobile hamburger menu works

Author: Pratiksha Bhende - [GitHub](https://github.com/pratiksha0604)
