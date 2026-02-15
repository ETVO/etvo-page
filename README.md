# 🎨 ETVO - Frontend Implementation

Frontend for my older personal portfolio and marketing website, built to integrate with the [etvo-manage](https://github.com/ETVO/etvo-manage) CMS backend.

## 🎯 Overview

This was my public-facing portfolio and marketing website that consumed content from the etvo-manage CMS. It displayed portfolio work, services, blog posts, and contact information in a clean, responsive layout.

**✨ The real highlight here is the custom CMS backend!** Check out [etvo-manage](https://github.com/ETVO/etvo-manage) to see a fully custom content management system I built from scratch with PHP—it's where all the interesting backend magic happened.

**Note:** This site is no longer live. For my current portfolio, visit [epr-works.pages.dev](https://epr-works.pages.dev).

## 🛠️ Tech Stack

- **PHP** - Template rendering and backend integration
- **Bootstrap 5** - Responsive framework
- **SCSS** - Custom styling
- **Laravel Mix** - Asset compilation
- **FSLightbox** - Image gallery functionality

## 🔗 Backend Integration

This frontend connected to the [etvo-manage](https://github.com/ETVO/etvo-manage) CMS to fetch:
- Portfolio content and images
- Blog posts
- Service descriptions
- Contact information

The integration happened through `integrate.php`, which included the CMS utilities and constants.

## 🚀 Running This Project

### Prerequisites

- PHP 7.4+
- Node.js and npm
- Access to etvo-manage CMS backend

### Installation

```bash
# Clone the repository
git clone https://github.com/ETVO/etvo-page.git
cd etvo-page

# Install npm dependencies
npm install

# Build assets
npx mix

# For development with watch mode
npx mix watch
```

### Setup

1. Ensure the `etvo-manage` backend is set up in the correct directory
2. Configure your web server to serve the project
3. The site will pull content dynamically from the CMS

## 📁 Project Structure

```
etvo-page/
├── src/
│   ├── js/          # JavaScript files
│   └── scss/        # SCSS stylesheets
├── assets/          # Compiled assets (generated)
├── partials/        # Page sections (header, footer, etc.)
├── index.php        # Homepage
├── blog.php         # Blog listing
└── single.php       # Individual blog post
```

## 👤 Author

**Estevão Pereira Rolim** - [@ETVO](https://github.com/ETVO) | [LinkedIn](https://linkedin.com/in/estevao-p-rolim)

---

*Frontend for the etvo-manage CMS. Built with PHP, Bootstrap, and Laravel Mix.*

*README created in collaboration with Claude AI.*
