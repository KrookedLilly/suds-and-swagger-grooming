# Suds & Swagger Pet Grooming

Professional pet grooming and boarding website for Suds & Swagger Pet Grooming, located in Spokane Valley, WA.

## About

Suds & Swagger offers both professional pet grooming (dogs and cats, all breeds and sizes) and pet boarding services. Owner Angel Lyons brings 20+ years of grooming experience and AKC S.A.F.E. certification.

## Tech Stack

- **HTML** — single-page static site
- **Tailwind CSS** — via Play CDN (no build step required)
- **Alpine.js** — via CDN for mobile navigation toggle
- **Google Fonts** — Raleway + Nunito Sans

No build tools, no npm, no bundlers. The site is a single `index.html` file that works as-is.

## Deploying to GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings > Pages** in the repository.
3. Under **Source**, select **Deploy from a branch**.
4. Set the branch to `main` and folder to `/ (root)`.
5. Click **Save**. The site will be live at `https://<username>.github.io/<repo-name>/` within a few minutes.

To use a custom domain, add the domain to the `CNAME` file and configure DNS accordingly.
