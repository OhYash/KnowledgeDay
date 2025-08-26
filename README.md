# Knowledge•Day

Blog letter started by OhYash during Covid 19 pandemic. Serves curiosity striking information and knowledge both with web presence, and email newsletter.  
Hence being called a blog-letter.

Never miss a post. Subscribe for free on the website - https://KnowledgeDay.in

## Quick Start

### Prerequisites
- Ruby (for Jekyll)
- Node.js (for Gulp build system)
- Bundler gem

### Setup
```bash
# Install Ruby dependencies
bundle install

# Install Node.js dependencies  
npm install
```

### Development
```bash
# Start development server with live reload
gulp

# Build Jekyll site only
jekyll build

# Individual tasks
gulp sass          # Compile SCSS to CSS
gulp img           # Optimize images
gulp jekyll-build  # Build Jekyll site
```

### Production Build
```bash
# Build optimized site for production
jekyll build --env=production
```

## Architecture

### Core Technology Stack
- **Jekyll Static Site**: Main blog engine using Liquid templating
- **Gulp Build System**: Handles SCSS compilation, image optimization, and live reload
- **Newsletter System**: Custom .NET application for email delivery
- **Personalization System**: JavaScript-based URL parameter processing for personalized newsletter content

### Key Features
- **Personalized Newsletter Experience**: Dynamic content replacement using URL parameters with base64 encoded reader names
- **Responsive Design**: Mobile-first SCSS architecture with modular styling
- **Content Management**: Markdown-based blog posts with frontmatter metadata
- **Image Optimization**: Automated image compression and optimization
- **Social Integration**: Built-in Twitter and Facebook sharing
- **Tag-based Categorization**: Organized content discovery

### Project Structure
- `_posts/`: Blog articles in Markdown format (2017-2022 content)
- `_layouts/`: Jekyll layout templates (main, post, default)
- `_includes/`: Reusable components including personalization scripts
- `assets/`: Static assets (CSS/SCSS, images, fonts)
- `_site/`: Generated static site output

## Website Tech

Everything is self served.

Newsletter is served using dotnet based application developed inhouse; and  
Web/blog is a static website built using Jekyll framework. (no database, no delay)  

Theme used: [Flexible-Jekyll](Flexible-Jekyll)

## Contributing

This website now accepts code contribution. Please check [CONTRIBUTING.md](/CONTRIBUTING.md) for more details.
