# .github

This repository contains:

1. **GitHub Pages Profile Site** - A Jekyll-powered profile site hosted at [trinhnx.dev](https://trinhnx.dev)
2. **GitHub Profile README** - Located in `profile/README.md` for profile display

## 🚀 Quick Start

### Local Development

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Build the site:
   ```bash
   bundle exec jekyll build
   ```

3. Serve locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit: `http://localhost:4000`

## 📝 Customization

### Update Profile Information

Edit `_config.yml` to change:
- Site title
- Description
- Author name
- GitHub username
- Social links

### Modify Content

Edit `index.md` to update:
- About section
- Skills
- Projects
- Contact information

### Change Styling

Customize the look in `assets/css/style.css`

### Custom Domain

The site is configured for the custom domain `trinhnx.dev` via the `CNAME` file.

## 📂 Structure

```
.
├── _config.yml           # Jekyll configuration
├── _layouts/             # Page layouts
│   ├── default.html      # Default layout
│   └── profile.html      # Profile-specific layout
├── _includes/            # Reusable components
│   ├── header.html
│   ├── footer.html
│   └── social-links.html
├── assets/
│   └── css/
│       └── style.css     # Custom styles
├── index.md              # Main profile page
├── profile/
│   └── README.md         # GitHub profile README
└── CNAME                 # Custom domain configuration
```

## 🌐 GitHub Pages

This site is built with Jekyll and can be deployed to GitHub Pages. The `CNAME` file configures the custom domain.

## 📄 License

See [LICENSE](LICENSE) file for details.

