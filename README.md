# My Hugo Blog

A modern, fast, and responsive blog built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## ✨ Features

- **Fast Loading**: Built with Hugo, one of the fastest static site generators
- **Responsive Design**: Looks great on desktop, tablet, and mobile devices
- **Dark/Light Mode**: Automatic theme switching based on user preference
- **SEO Optimized**: Built-in SEO features including meta tags, structured data, and sitemap
- **Search Functionality**: Fast client-side search powered by Fuse.js
- **Social Sharing**: Easy sharing buttons for popular social platforms
- **Categories & Tags**: Organize content with categories and tags
- **Table of Contents**: Automatic TOC generation for longer posts

## 🚀 Quick Start

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (Extended version required)
- [Git](https://git-scm.com/)

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/ayush/hugosample.git
   cd hugosample
   ```

2. Initialize submodules:
   ```bash
   git submodule update --init --recursive
   ```

3. Start the development server:
   ```bash
   hugo server -D
   ```

4. Open your browser and visit `http://localhost:1313`

### Creating Content

1. Create a new post:
   ```bash
   hugo new content posts/my-new-post.md
   ```

2. Edit the generated markdown file in `content/posts/`

3. Set `draft: false` in the front matter when ready to publish

## 📁 Project Structure

```
.
├── archetypes/          # Content templates
├── content/             # Content files
│   ├── posts/          # Blog posts
│   └── about.md        # About page
├── data/               # Data files
├── layouts/            # Custom layouts (overrides theme)
├── static/             # Static files (images, etc.)
├── themes/             # Hugo themes
│   └── PaperMod/      # PaperMod theme (submodule)
├── hugo.yaml          # Hugo configuration
└── README.md          # This file
```

## ⚙️ Configuration

The main configuration is in `hugo.yaml`. Key settings include:

- **baseURL**: Your site's base URL
- **title**: Site title
- **params**: Theme-specific parameters
- **menu**: Navigation menu items
- **markup**: Content rendering settings

## 🎨 Customization

### Changing Theme Colors

Edit the CSS variables in your custom CSS file or override the theme's variables.

### Adding Custom Layouts

Create files in the `layouts/` directory to override theme layouts.

### Social Icons

Update the `socialIcons` section in `hugo.yaml`:

```yaml
params:
  socialIcons:
    - name: github
      url: "https://github.com/yourusername"
    - name: twitter
      url: "https://twitter.com/yourusername"
```

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions. The workflow:

1. Triggers on push to `main` branch
2. Builds the site with Hugo
3. Deploys to GitHub Pages

### Manual Deployment

To deploy manually:

1. Build the site:
   ```bash
   hugo --gc --minify
   ```

2. Deploy the `public/` directory to your hosting provider

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Links

- [Hugo Documentation](https://gohugo.io/documentation/)
- [PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod)
- [Hugo Themes](https://themes.gohugo.io/)

## 📞 Support

If you have questions or need help:

- Check the [Hugo Documentation](https://gohugo.io/documentation/)
- Open an issue in this repository
- Reach out on social media

---

Built with ❤️ using Hugo and PaperMod
