# Ran Tan - Software Engineer

Personal portfolio website showcasing software engineering expertise in machine learning, large-scale data management, recommender systems, computer vision, and robotics.

## About

Built with [Jekyll](https://jekyllrb.com/) and the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme, this site serves as a professional portfolio and blog.

## Tech Stack

- **Jekyll** - Static site generator
- **Minimal Mistakes** - Jekyll theme
- **Markdown** - Content authoring
- **GitHub Pages** - Hosting platform

## Site Structure

```
github.io/
├── _config.yml          # Site configuration
├── _data/
│   └── navigation.yml    # Navigation menu
├── _pages/             # Site pages (Home, About, Expertise, Contact)
├── _posts/             # Blog posts (YYYY-MM-DD-title.md format)
└── assets/             # Images, CSS, JS
```

## Local Development

### Prerequisites

- Ruby and Bundler installed
- [Ruby 3.4+](https://www.ruby-lang.org/en/) recommended

### Setup

```bash
# Install dependencies
bundle install

# Start local development server
bundle exec jekyll serve

# Visit http://localhost:4000
```

### Build

```bash
# Build static site
bundle exec jekyll build

# Output will be in _site/ directory
```

## Content

### Pages

- **Home** - Welcome and quick navigation
- **About** - Personal journey and approach
- **Expertise** - Detailed technical skills and experience
- **Contact** - GitHub links and collaboration information
- **Posts** - Blog posts on ML, data, CV, and robotics

### Blog Posts

Blog posts are written in Markdown with Jekyll front matter:

```markdown
---
title: "Post Title"
date: 2024-12-01 09:00:00 -0500
categories:
  - machine-learning
  - data-engineering
---

Post content here...
```

Place new posts in `_posts/` directory with format: `YYYY-MM-DD-title.md`

## Deployment

Site is hosted on GitHub Pages and automatically deployed from the `master` branch.

```bash
# Commit changes
git add .
git commit -m "Update site"

# Push to GitHub
git push origin master

# Site will be available at: https://ran-tan.github.io
```

## License

© 2025 Ran Tan. Built with GitHub Pages.
