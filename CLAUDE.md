# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a Jekyll-based GitHub Pages site for BJ McGill's personal website. The site showcases programming projects, creative writing, and professional background.

## Site Architecture

- **Jekyll Configuration**: `_config.yml` - Uses jekyll-theme-cayman with kramdown markdown processor
- **Main Content**: `index.md` - Primary landing page with project showcases and personal information
- **Creative Writing**: Individual markdown files for stories and articles:
  - `A-Fairy-Story.md`
  - `The-Garden-of-Gaia.md`
  - `Sympathy-for-the-Devil.md`
- **Static Assets**: `Babel6Jul2011.pdf` - PDF document for "The Children of Babel"

## Development Commands

This is a static Jekyll site hosted on GitHub Pages. No build commands are required locally - GitHub Pages automatically builds and deploys changes when pushed to main branch.

For local development (if Jekyll is installed):
```bash
bundle exec jekyll serve  # Serve site locally at http://localhost:4000
```

## Content Structure

The site follows a simple flat file structure with:
- Personal introduction and professional background on main page
- Direct links to GitHub repositories for programming projects
- Individual markdown files for creative writing pieces
- External links to published works and other platforms

## Site Theme and Styling

Uses the Cayman theme which provides:
- Responsive design
- Clean typography
- GitHub integration
- Mobile-friendly layout

When editing content, maintain the existing markdown structure and link patterns for consistency with the theme.