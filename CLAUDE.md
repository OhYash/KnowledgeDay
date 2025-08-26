# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Knowledge•Day is a Jekyll-based static blog website with an integrated newsletter system. The site serves educational content through both web presence and email newsletter, hence being called a "blog-letter". The project uses a custom theme based on Flexible-Jekyll and includes personalization features for newsletter subscribers.

## Development Commands

### Setup
```bash
# Install Ruby dependencies
bundle install

# Install Node.js dependencies  
npm install
```

### Build & Development
```bash
# Build Jekyll site only
jekyll build

# Development server with live reload (default gulp task)
gulp

# Individual tasks
gulp sass          # Compile SCSS to CSS
gulp img           # Optimize images
gulp jekyll-build  # Build Jekyll site
gulp browser-sync  # Start development server
```

### Production Build
```bash
# Build optimized site for production
jekyll build --env=production
```

## Architecture

### Core Structure
- **Jekyll Static Site**: Main blog engine using Liquid templating
- **Gulp Build System**: Handles SCSS compilation, image optimization, and live reload
- **Personalization System**: JavaScript-based URL parameter processing for personalized newsletter content

### Key Directories
- `_posts/`: Blog articles in Markdown format (2017-2022 content)
- `_layouts/`: Jekyll layout templates (main, post, default)
- `_includes/`: Reusable components including personalization scripts
- `assets/`: Static assets (CSS/SCSS, images, fonts)
- `_site/`: Generated static site output

### Personalization Features
The site includes a unique personalization system in `_includes/post_greetings.html:2-25` that:
- Processes URL parameter `r` (base64 encoded reader name)
- Dynamically replaces elements with `name="reader-fname"` 
- Removes `.personal-text` CSS class to show personalized content
- Enables personalized newsletter experience

### Content Management
- Blog posts use frontmatter with img, tags, and optional external-link fields
- Images stored in `assets/img/` with automatic optimization
- Social sharing integration for Twitter and Facebook
- Tag-based categorization system

### Styling System
- SCSS-based styling in `assets/css/scss/`
- Modular architecture with parts/ subdirectory
- Font Awesome integration for icons
- Responsive design with media queries

## Configuration Files
- `_config.yml`: Jekyll configuration with site metadata and author info
- `Gemfile`: Ruby gem dependencies including Jekyll plugins
- `package.json`: Node.js dependencies for Gulp build system
- `gulpfile.js`: Build automation and development server setup