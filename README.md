# bsprenger.github.io

Personal website and blog for bsprenger, built with Jekyll using the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template.

## About

This site showcases projects, experiments, and learnings in robotics, machine learning, and software engineering.

## Running Locally

To run this site locally:

1. Install Ruby and Jekyll
2. Run `bundle install`
3. Run `bundle exec jekyll serve`
4. Navigate to `http://localhost:4000`

## Structure

- `_posts/` - Blog posts
- `_portfolio/` - Portfolio items
- `_pages/` - Static pages (About, CV, etc.)
- `_config.yml` - Site configuration

## Adding Content

### Blog Posts

Create a new file in `_posts/` with the format `YYYY-MM-DD-title.md` and include front matter:

```yaml
---
title: "Your Post Title"
date: YYYY-MM-DD
permalink: /posts/YYYY/MM/post-title/
tags:
  - tag1
  - tag2
---
```

## License

This site uses the Academic Pages template, which is licensed under the MIT License.