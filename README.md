# 90 Projects in 90 Days — Index

Live site: https://90projects.marekstepan.cz

This repository hosts the public index of my 90 Projects in 90 Days initiative. Each project is small, focused, deployed, and linked here.

## Add a project link
Edit index.html and append a list item inside the <ol>:

<li>
  <a href="https://p01.<your-domain>" target="_blank" rel="noopener">
    Project 1 – Hello Web
  </a>
</li>

- Use p01, p02, … for project subdomains (set up as CNAMEs in DNS to your hosting platform).
- After deployment, replace <your-domain> with your real domain (e.g., p01.example.cz).

## How this index is hosted
- Served via GitHub Pages (custom domain set with a CNAME file).
- Custom domain for the index: 90projects.marekstepan.cz.

## Development
- Static site: open index.html locally to preview, then commit and push.
- Keep links up to date as projects go live.

## License
This repository is licensed under the MIT License. See LICENSE for details.
