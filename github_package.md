# 🌟 Neon Blog Template Collection

<div align="center">

![Neon Blog Header](https://img.shields.io/badge/NEON-BLOG-ff0080?style=for-the-badge&logo=github&logoColor=white)
![Version](https://img.shields.io/badge/VERSION-1.0.0-00ffff?style=for-the-badge)
![License](https://img.shields.io/badge/LICENSE-MIT-ff8000?style=for-the-badge)

*High-contrast neon aesthetics meet modern web design*

[🚀 Live Demo](#live-demo) • [📦 Quick Start](#quick-start) • [🎨 Features](#features) • [📝 Documentation](#documentation)

</div>

---

## ✨ Features

### 🎯 **Multiple Format Support**
- **Interactive HTML** - Click-to-edit content areas
- **Markdown Templates** - Static site generator ready
- **Template Variables** - Dynamic content injection
- **GitHub Pages** - Deploy-ready configuration

### 🎨 **Neon Design System**
- High-contrast color palette (Cyan `#00ffff`, Magenta `#ff0080`, Orange `#ff8000`)
- Animated gradient backgrounds and flowing wave effects
- Responsive design with mobile-first approach
- Professional typography with neon accent highlights

### 🛠️ **Developer Experience**
- Zero dependencies - Pure HTML/CSS/JS
- Semantic HTML structure with accessibility features
- CSS custom properties for easy theme customization
- Comprehensive documentation and examples

---

## 🚀 Quick Start

### Option 1: Use Template (Recommended)
```bash
# Use this repository as a template
gh repo create my-neon-blog --template YOUR_USERNAME/neon-blog-template
cd my-neon-blog
```

### Option 2: Clone & Customize
```bash
git clone https://github.com/YOUR_USERNAME/neon-blog-template.git
cd neon-blog-template
# Open index.html in your browser
```

### Option 3: Download & Extract
Download the latest release and extract to your project folder.

---

## 📁 Project Structure

```
neon-blog-template/
├── 📄 index.html              # Interactive click-to-edit version
├── 📁 templates/
│   ├── 📄 blog-post.md        # Markdown template
│   ├── 📄 template-vars.html  # Variable-based template
│   └── 📄 config.json         # Template configuration
├── 📁 assets/
│   ├── 📁 css/
│   │   ├── 📄 neon-core.css   # Core neon styles
│   │   └── 📄 animations.css  # Animation effects
│   └── 📁 js/
│       └── 📄 editor.js       # Click-to-edit functionality
├── 📁 examples/
│   ├── 📄 tech-blog.html      # Example tech blog
│   └── 📄 portfolio.html      # Example portfolio
├── 📄 README.md
├── 📄 LICENSE
└── 📄 CONTRIBUTING.md
```

---

## 🎨 Usage Examples

### Interactive HTML Version
```html
<!-- Click-to-edit areas automatically save content -->
<div class="editable-area" contenteditable="true">
  Click here to start writing...
</div>
```

### Markdown Template
```markdown
---
title: "{{blog_title}}"
subtitle: "{{blog_subtitle}}"
tags: [{{tags}}]
---

# {{blog_title}}

{{content_introduction}}

## {{section_title}}

{{main_content}}
```

### Template Variables
```javascript
const blogConfig = {
  title: "Your Amazing Blog Post",
  subtitle: "Exploring the future of web design",
  author: "Your Name",
  tags: ["neon", "design", "web", "css"],
  content: {
    introduction: "Your introduction text...",
    mainContent: "Your main content..."
  }
};
```

---

## 🎯 Template Variations

### 📝 Blog Post Template
Perfect for articles, tutorials, and long-form content.
- Clean typography with neon accents
- Multiple content sections with animated dividers
- Tag system with gradient styling

### 🎨 Portfolio Template  
Showcase your work with style.
- Project galleries with hover effects
- Animated skill bars and progress indicators
- Contact forms with neon styling

### 📊 Landing Page Template
Convert visitors with high-impact design.
- Hero sections with animated backgrounds
- Call-to-action buttons with glow effects
- Testimonial sections with neon borders

---

## 🛠️ Customization Guide

### Color Scheme
```css
:root {
  --neon-cyan: #00ffff;
  --neon-magenta: #ff0080;
  --neon-orange: #ff8000;
  --bg-dark: #0a0a0a;
  --bg-secondary: #1a0033;
}
```

### Typography
```css
.blog-title {
  font-family: 'Your Custom Font', serif;
  background: linear-gradient(45deg, var(--neon-magenta), var(--neon-cyan));
  -webkit-background-clip: text;
}
```

### Animations
```css
@keyframes neon-glow {
  0%, 100% { filter: brightness(1); }
  50% { filter: brightness(1.3); }
}
```

---

## 📱 Responsive Design

The template is fully responsive with breakpoints at:
- **Mobile**: < 600px
- **Tablet**: 600px - 1024px  
- **Desktop**: > 1024px

All animations and effects are optimized for performance across devices.

---

## 🚀 Deployment Options

### GitHub Pages
1. Enable GitHub Pages in repository settings
2. Select source branch (usually `main`)
3. Your site will be live at `https://yourusername.github.io/repo-name`

### Netlify
```bash
# Build command (if needed)
npm run build

# Publish directory
dist
```

### Vercel
```json
{
  "name": "neon-blog",
  "version": 2,
  "builds": [
    { "src": "*.html", "use": "@vercel/static" }
  ]
}
```

---

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md).

### Development Setup
```bash
git clone https://github.com/YOUR_USERNAME/neon-blog-template.git
cd neon-blog-template
# No build process needed - open index.html directly
```

### Commit Message Convention
We use conventional commits for clear project history:

```
feat: add new neon color scheme options
fix: resolve mobile responsiveness issues  
docs: update README with deployment instructions
style: improve CSS organization and comments
refactor: optimize animation performance
test: add cross-browser compatibility tests
```

---

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Inspired by synthwave and cyberpunk aesthetic
- Built with modern CSS Grid and Flexbox
- Accessibility guidelines following WCAG 2.1
- Performance optimized with CSS containment

---

## 📞 Support

- 🐛 [Report Bugs](https://github.com/YOUR_USERNAME/neon-blog-template/issues)
- 💡 [Request Features](https://github.com/YOUR_USERNAME/neon-blog-template/issues)
- 💬 [Discussions](https://github.com/YOUR_USERNAME/neon-blog-template/discussions)

---

<div align="center">

**Made with 💜 and lots of neon**

[![Star this repo](https://img.shields.io/github/stars/YOUR_USERNAME/neon-blog-template?style=social)](https://github.com/YOUR_USERNAME/neon-blog-template)
[![Follow on GitHub](https://img.shields.io/github/followers/YOUR_USERNAME?style=social)](https://github.com/YOUR_USERNAME)

</div>

---

## 🔧 File Templates

### Markdown Blog Template (`templates/blog-post.md`)
```markdown
---
title: "{{title}}"
subtitle: "{{subtitle}}"
author: "{{author}}"
date: "{{date}}"
tags: [{{#tags}}"{{.}}"{{#unless @last}}, {{/unless}}{{/tags}}]
image: "{{featured_image}}"
---

# {{title}}

*{{subtitle}}*

## Introduction

{{introduction}}

![Featured Image]({{featured_image}})

## {{section_1_title}}

{{section_1_content}}

---

## {{section_2_title}}

{{section_2_content}}

## Conclusion

{{conclusion}}

### Tags
{{#tags}}
- {{.}}
{{/tags}}

---

*Published on {{date}} by {{author}}*
```

### Template Variables Configuration (`templates/config.json`)
```json
{
  "blog": {
    "title": "{{blog_title}}",
    "subtitle": "{{blog_subtitle}}",
    "author": "{{author_name}}",
    "baseUrl": "{{site_url}}",
    "description": "{{site_description}}"
  },
  "theme": {
    "primaryColor": "{{primary_color}}",
    "secondaryColor": "{{secondary_color}}",
    "accentColor": "{{accent_color}}",
    "backgroundColor": "{{bg_color}}"
  },
  "content": {
    "sections": [
      {
        "id": "introduction",
        "title": "{{intro_title}}",
        "content": "{{intro_content}}",
        "editable": true
      },
      {
        "id": "main",
        "title": "{{main_title}}",
        "content": "{{main_content}}",
        "editable": true
      },
      {
        "id": "conclusion",
        "title": "{{conclusion_title}}",
        "content": "{{conclusion_content}}",
        "editable": true
      }
    ]
  },
  "meta": {
    "tags": [{{tags}}],
    "category": "{{category}}",
    "publishDate": "{{publish_date}}",
    "lastModified": "{{last_modified}}"
  }
}
```

### Suggested Commit Messages

**Initial Setup:**
```
feat: initialize neon blog template with core functionality

- Add responsive HTML template with click-to-edit areas
- Implement CSS animations and neon color scheme  
- Create markdown template with variable support
- Set up project structure and documentation
```

**Feature Additions:**
```
feat: add template variable system for dynamic content

- Implement JSON configuration for blog metadata
- Add Handlebars-style template syntax support
- Create example configurations for different blog types
- Update documentation with template usage examples
```

**Style Improvements:**
```
style: enhance neon visual effects and animations

- Improve gradient transitions and glow effects
- Add smooth hover animations for interactive elements
- Optimize CSS for better performance on mobile devices
- Refactor color variables for easier customization
```

**Documentation Updates:**
```
docs: create comprehensive README with setup instructions

- Add quick start guide with multiple installation options
- Document all template variations and customization options
- Include deployment guides for GitHub Pages, Netlify, Vercel
- Add contributing guidelines and commit message conventions
```

**Bug Fixes:**
```
fix: resolve mobile responsiveness and cross-browser compatibility

- Fix animation performance issues on iOS Safari
- Correct text wrapping in editable content areas
- Resolve CSS Grid fallbacks for older browsers
- Update media queries for better tablet experience
```