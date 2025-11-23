# Sidereal Cog Website

A modern, clean website built with Astro to showcase development projects and host legal pages. Follows the Sidereal Cog brand guidelines.

## Features

- Project showcase with filterable cards
- About/Contact page
- Privacy Policy page
- Responsive design
- Fast, static-first architecture with Astro
- Brand-aligned design with CSS custom properties

## Getting Started

### Development

```bash
npm run dev
```

Visit `http://localhost:4321` to view the site.

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Customization

### Adding Projects

Edit `/src/pages/index.astro` and update the `projects` array:

```javascript
const projects = [
  {
    title: "Your Project Name",
    description: "A description of your project",
    link: "https://github.com/yourusername/project",
    tags: ["JavaScript", "React", "Open Source"]
  },
  // Add more projects...
];
```

### Updating Contact Information

Edit `/src/pages/about.astro` to add your contact details and information about your work.

### Customizing Privacy Policy

Edit `/src/pages/privacy.astro` to reflect your actual data collection practices and legal requirements.

### Brand Customization

All brand tokens are defined in `/src/styles/global.css`. Update the CSS custom properties to adjust colors, spacing, typography, and more.

## Project Structure

```
/
├── src/
│   ├── layouts/
│   │   └── BaseLayout.astro    # Main layout with header/footer
│   ├── pages/
│   │   ├── index.astro          # Homepage with projects
│   │   ├── about.astro          # About/Contact page
│   │   └── privacy.astro        # Privacy Policy page
│   └── styles/
│       └── global.css           # Brand design tokens and global styles
├── public/                      # Static assets
└── package.json
```

## Deployment

This site can be deployed to any static hosting service:

- **Netlify**: Connect your repo and deploy automatically
- **Vercel**: Import your project and deploy with zero config
- **GitHub Pages**: Build and deploy with GitHub Actions
- **Cloudflare Pages**: Connect repo for automatic deployments

## Technologies

- [Astro](https://astro.build/) - Static site builder
- CSS Custom Properties - For theming
- Google Fonts (Inter) - Typography

## License

Update with your preferred license.
