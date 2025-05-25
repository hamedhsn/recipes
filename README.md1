# Personal Recipe Website

A modern recipe website built with [Docusaurus](https://docusaurus.io/), featuring a beautiful recipe blog to share your favorite dishes and cooking tips.

## 🌟 Features

- **Recipe Blog**: Share your favorite recipes and cooking tips
- **Responsive Design**: Looks great on all devices
- **GitHub Pages Deployment**: Automatic deployment via GitHub Actions
- **Modern UI**: Clean, professional design with dark mode support
- **Search Functionality**: Easy to find recipes
- **Tag System**: Organize recipes by categories

## 🚀 Quick Start

### Prerequisites

- Node.js 18 or higher
- npm or yarn

### Local Development

1. Clone this repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Building for Production

```bash
npm run build
```

The static files will be generated in the `build` directory.

## 📝 Customization

### Personal Information

1. **Update site configuration** in `docusaurus.config.ts`:
   - Change `title`, `tagline`, and `url`
   - Update `organizationName` and `projectName` for GitHub Pages
   - Modify navigation items and footer links

2. **Update homepage** in `src/pages/index.tsx`:
   - Customize the hero section
   - Update feature descriptions in `src/components/HomepageFeatures/index.tsx`

### Adding Recipe Blog Posts

Create new `.md` files in the `recipes/` directory:

```markdown
---
slug: your-recipe-slug
title: Your Recipe Title
authors: [your-name]
tags: [cooking, baking, easy]
---

# Your Recipe Title

Recipe content goes here...

<!-- truncate -->

## Ingredients

- List your ingredients here

## Instructions

1. Step by step instructions
2. Continue with more steps

## Tips

- Add helpful cooking tips
```

### Styling

- Main styles: `src/css/custom.css`
- Component styles: Individual `.module.css` files

## 🚀 Deployment to GitHub Pages

### Automatic Deployment

This repository includes a GitHub Actions workflow that automatically deploys to GitHub Pages when you push to the `main` branch.

### Setup Instructions

1. **Enable GitHub Pages**:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Set source to "GitHub Actions"

2. **Update configuration**:
   - In `docusaurus.config.ts`, update:
     - `url`: Your GitHub Pages URL (e.g., `https://hamedhsn.github.io`)
     - `baseUrl`: Your repository name (e.g., `/recipes/`)
     - `organizationName`: Your GitHub username
     - `projectName`: Your repository name

3. **Push to main branch**:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

The site will be automatically built and deployed to GitHub Pages.

### Manual Deployment

You can also deploy manually using:

```bash
npm run deploy
```

## 📁 Project Structure

```
├── .github/workflows/    # GitHub Actions workflows
├── recipes/             # Recipe blog posts
├── src/
│   ├── components/      # React components
│   ├── css/            # Global styles
│   └── pages/          # Static pages (homepage)
├── static/             # Static assets
├── docusaurus.config.ts # Main configuration
└── package.json        # Dependencies and scripts
```

## 🛠️ Available Scripts

- `npm start` - Start development server
- `npm run build` - Build for production
- `npm run serve` - Serve built site locally
- `npm run deploy` - Deploy to GitHub Pages
- `npm run clear` - Clear Docusaurus cache

## 📚 Recipe Writing Tips

- Use clear, descriptive titles
- Include prep time, cook time, and servings
- Add high-quality images
- Use the `<!-- truncate -->` marker to create excerpts
- Tag recipes appropriately (e.g., vegetarian, quick, dessert)
- Include helpful tips and variations

## 📚 Learn More

- [Docusaurus Documentation](https://docusaurus.io/)
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

## 🤝 Contributing

Feel free to customize this template for your own use! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Built with ❤️ using [Docusaurus](https://docusaurus.io/)
