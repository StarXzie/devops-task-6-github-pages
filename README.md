# Task 6: Host a Static Website with GitHub Pages

**DevOps Internship – Elevate Labs**

## Objective
Deploy a simple HTML website using GitHub Pages.

## What I did
1. Created `index.html` (the default file GitHub Pages loads) and `style.css` for styling.
2. Created a new GitHub repository and pushed both files to the `main` branch.
3. Went to **Settings → Pages**, selected **Deploy from a branch**, chose `main` and the `/ (root)` folder, and saved.
4. Waited a minute for the build, then opened the live link GitHub provided.
5. Customized the look with CSS (gradient header, cards, hover effect, responsive layout).

## Live website
`https://<your-username>.github.io/<repo-name>/`

## Files
- `index.html` – page content
- `style.css` – styling
- `screenshot.png` – screenshot of the live site (add yours)

## Interview Questions

1. **What is GitHub Pages?** A free static site hosting service from GitHub that serves HTML, CSS and JS directly from a repository.
2. **Can you host dynamic apps here?** No. There is no server-side code (PHP, Node, Python backends, databases). Only static files, though client-side JS and external APIs work.
3. **What are the limits of GitHub Pages?** Published sites are limited to about 1 GB, with a soft bandwidth limit of 100 GB/month and a soft limit of 10 builds per hour. Static content only, and not meant for commercial SaaS or sensitive data.
4. **How do you update the website?** Commit and push changes to the publishing branch; GitHub rebuilds and redeploys automatically.
5. **What happens when you delete the repo?** The site is taken down and the URL stops working (404).
6. **What is the default file that loads?** `index.html` in the root (or chosen) folder.
7. **Can you use a custom domain?** Yes. Add it under Settings → Pages (this creates a `CNAME` file) and point your DNS records (A/ALIAS or CNAME) to GitHub; HTTPS can be enforced for free.
