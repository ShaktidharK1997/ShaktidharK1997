# Shaktidhar's Blog

Personal blog built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme, deployed on GitHub Pages.

MS CS NYU Graduate. Data Scientist at Louis Vuitton.

Currently spending my time making agents to simplify my life.

## Local Development

```bash
# Clone with submodules
git clone --recurse-submodules https://github.com/ShaktidharK1997/ShaktidharK1997.git

# Run local server
hugo server -D
```

## Creating New Posts

```bash
hugo new content posts/my-new-post.md
```

Then edit the file in `content/posts/` and set `draft: false` when ready to publish.

## Deployment

The site is automatically built and deployed to GitHub Pages via GitHub Actions when changes are pushed to the `main` branch.
