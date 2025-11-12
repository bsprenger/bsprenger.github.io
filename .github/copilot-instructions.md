# GitHub Copilot Instructions

## Repository Overview

This is a personal GitHub Pages blog built with Jekyll. The repository serves as the source for a technical blog focusing on robotics, machine learning, and reinforcement learning topics.

## Repository Structure

- `index.md` - Main landing page with recent posts listing
- `_posts/` - Directory containing blog post markdown files
- `README.md` - Repository documentation

## Blog Post Guidelines

### Post Format

Blog posts should follow Jekyll's standard naming convention and format:

**File Naming:**
- Posts must be named: `YYYY-MM-DD-title.md`
- Example: `2025-02-25-test.md`

**Front Matter:**
- Each post must include YAML front matter with `title` and `date` fields
- Example:
  ```yaml
  ---
  title: "Your Post Title"
  date: 2025-03-17
  ---
  ```

**Content:**
- Use Markdown for formatting
- Include clear headings and sections
- Code blocks should specify the language for syntax highlighting
- Technical content should be well-explained and accessible

### Content Style

- Write in a clear, technical yet approachable style
- Include practical examples and code snippets where relevant
- Use proper terminology for robotics and ML concepts
- Break down complex topics into digestible sections

## Jekyll Configuration

This is a standard GitHub Pages Jekyll site that:
- Uses default GitHub Pages Jekyll configuration
- Automatically builds and deploys when changes are pushed to the main branch
- Supports standard Jekyll/Liquid templating in markdown files

## When Making Changes

- New blog posts go in the `_posts/` directory
- Follow the established naming convention and front matter format
- Test markdown rendering if adding complex formatting
- Keep the index.md structure consistent when modifying the landing page
- Ensure all internal links use correct Jekyll/Liquid syntax

## Build and Deployment

- GitHub Pages automatically builds and deploys the site
- No local build process or dependencies are tracked in this repository
- Changes to markdown files are immediately reflected after GitHub Pages rebuilds
