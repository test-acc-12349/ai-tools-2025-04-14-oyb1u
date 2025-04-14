# AI Tools Directory 🤖

> The ultimate directory of AI tools and resources for developers, creators, and businesses.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge-id/deploy-status)](https://app.netlify.com/sites/your-site/deploys)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Directory Structure](#directory-structure)
- [Customization](#customization)
  - [Adding Directory Items](#adding-directory-items)
  - [Modifying Categories](#modifying-categories)
  - [Updating Hero Section](#updating-hero-section)
  - [Styling Changes](#styling-changes)
- [Deployment](#deployment)
- [Domain Setup](#domain-setup)
- [Troubleshooting](#troubleshooting)
- [Resources](#resources)
- [Support](#support)

## Overview

AI Tools Directory is a responsive, modern directory website showcasing artificial intelligence tools and resources. Built with HTML5, CSS3, and JavaScript, it features a clean 3-column grid layout optimized for discovery and exploration.

## Features

- 🎯 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 💨 Fast loading times
- 📱 Mobile-friendly design
- 🌓 Dark/light mode toggle
- 🔗 SEO-friendly structure

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-tools-directory.git
```

2. Navigate to project directory:
```bash
cd ai-tools-directory
```

3. Install dependencies:
```bash
npm install
```

4. Start development server:
```bash
npm run dev
```

## Directory Structure

```
ai-tools-directory/
├── assets/
│   ├── images/
│   ├── css/
│   └── js/
├── data/
│   └── tools.json
├── components/
├── layouts/
├── pages/
├── public/
└── README.md
```

## Customization

### Adding Directory Items

Add new tools by editing `data/tools.json`:

```json
{
  "id": "tool-name",
  "title": "Tool Name",
  "description": "Tool description",
  "category": "category-name",
  "url": "https://toolurl.com",
  "image": "/images/tool-image.png"
}
```

### Modifying Categories

Edit categories in `data/categories.js`:

```javascript
export const categories = [
  {
    id: "category-id",
    name: "Category Name",
    description: "Category description"
  }
];
```

### Updating Hero Section

Modify the hero section in `components/Hero.js`:

```html
<section class="hero">
  <h1>Your New Title</h1>
  <p>Your new description</p>
</section>
```

### Styling Changes

Customize colors in `assets/css/variables.css`:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --background-color: #your-color;
  --text-color: #your-color;
}
```

## Deployment

1. Build the project:
```bash
npm run build
```

2. Deploy to Netlify:
```bash
netlify deploy --prod
```

## Domain Setup

1. Purchase domain from preferred registrar
2. Add domain in Netlify:
   - Go to Site settings > Domain management
   - Click "Add custom domain"
   - Follow DNS configuration instructions

## Troubleshooting

Common issues and solutions:

- **Build Failures**: Clear cache and node_modules
```bash
rm -rf .cache node_modules
npm install
```

- **Image Loading Issues**: Ensure correct path in tools.json
- **Category Filters Not Working**: Check category IDs match in tools.json

## Resources

- [Documentation](https://docs.yoursite.com)
- [Style Guide](https://styleguide.yoursite.com)
- [API Reference](https://api.yoursite.com)

## Support

- 📧 Email: support@aitools.com
- 💬 Discord: [Join our community](https://discord.gg/aitools)
- 🐦 Twitter: [@aitools](https://twitter.com/aitools)

---

## License

MIT © [Your Name]

---

*Made with ❤️ by [Your Name]*