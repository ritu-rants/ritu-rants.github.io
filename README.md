# Ritu Rants

A personal blog powered by [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

## Quick Start

### 1. Clone this repo

```bash
git clone https://github.com/YOUR_USERNAME/riturants.git
cd riturants
```

### 2. Deploy to GitHub Pages

Push all these files to your `riturants` repository. Then:

1. Go to your repo on GitHub → **Settings** → **Pages**
2. Under "Source", select **GitHub Actions**
3. GitHub will auto-detect the Jekyll site and build it

Your site will be live at `https://YOUR_USERNAME.github.io/riturants/`

### 3. Writing a new post

Create a new file in `_posts/` with this naming format:

```
_posts/YYYY-MM-DD-your-post-title.md
```

Start the file with front matter:

```yaml
---
layout: post
title: "Your Post Title"
subtitle: "Optional subtitle here"
date: YYYY-MM-DD
---

Your post content in Markdown goes here.
```

Commit and push — GitHub Pages will rebuild automatically.

### 4. Optional: Custom domain

1. Buy a domain (e.g. `riturants.com`) from Namecheap, Porkbun, etc.
2. Add a `CNAME` file to this repo containing just: `riturants.com`
3. In your domain registrar, add a CNAME record pointing to `YOUR_USERNAME.github.io`
4. In GitHub repo Settings → Pages, enter your custom domain

### 5. Local development (optional)

If you want to preview locally before pushing:

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000` in your browser.

## Project Structure

```
riturants/
├── _config.yml          # Site settings
├── _layouts/
│   ├── default.html     # Base layout
│   └── post.html        # Blog post layout
├── _posts/              # Your blog posts go here
├── assets/css/
│   └── style.css        # All styles
├── about.md             # About page
├── index.html           # Homepage
├── Gemfile              # Ruby dependencies
└── README.md            # You're reading this
```

## License

Content is © Ritu. Code is free to use.
