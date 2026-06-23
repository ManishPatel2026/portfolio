# Manish Patel — Portfolio

Senior Graphic Designer portfolio site. Built with plain HTML/CSS/JS.

## Structure

```
portfolio-site/
├── index.html                        # Main portfolio / homepage
├── case-studies/
│   ├── mountain-warehouse.html       # Mountain Warehouse case study
│   └── (add more case studies here)
├── assets/
│   └── images/
│       └── (add project images here)
└── README.md
```

## Adding a new case study

1. Duplicate an existing file in `/case-studies/`
2. Rename it e.g. `selfridges.html`
3. Update the content inside
4. Link to it from `index.html` by updating the project card's href

## Adding images

Place images in `/assets/images/` and reference them in HTML like:
`<img src="../assets/images/your-image.jpg" alt="Description">`

## Deploying to GitHub Pages

1. Push this folder to a GitHub repo named `yourusername.github.io`
2. Go to Settings → Pages → Source: Deploy from branch → main
3. Your site will be live at `https://yourusername.github.io`

## Custom domain (optional)

Add a file called `CNAME` to the root containing just your domain:
`manishpatel.co.uk`
Then point your domain's DNS to GitHub Pages.
