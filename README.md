# Saumya Rastogi - Jekyll Resume Website

This is a Jekyll-powered resume website for Saumya Rastogi, a Principal Data Scientist with expertise in AI, machine learning, and analytics.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Dark Mode**: Toggle between light and dark themes with preference saving
- **Smooth Navigation**: Active section highlighting and smooth scrolling
- **Modular Structure**: Clean Jekyll architecture with reusable components
- **SEO Optimized**: Built-in SEO tags and meta information
- **GitHub Pages Ready**: Optimized for GitHub Pages deployment

## Structure

```
├── _config.yml          # Jekyll configuration
├── _data/               # Data files (YAML)
│   ├── education.yml
│   ├── experience.yml
│   ├── projects.yml
│   ├── skills.yml
│   └── personal.yml
├── _includes/           # Reusable components
│   ├── navigation.html
│   ├── footer.html
│   └── sections/
├── _layouts/            # Page layouts
│   ├── default.html
│   └── home.html
├── _sass/               # SCSS partials
├── assets/              # Static assets
│   ├── css/
│   ├── js/
│   └── images/
├── index.md             # Homepage content
└── Gemfile             # Ruby dependencies
```

## Local Development

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Run locally:**
   ```bash
   bundle exec jekyll serve
   ```

3. **View in browser:**
   Open `http://localhost:4000`

## Deployment

### GitHub Pages
1. Push to your GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Manual Deployment
```bash
bundle exec jekyll build
```
Upload the `_site` folder to your web server.

## Customization

### Update Personal Information
Edit the files in `_data/` directory:
- `education.yml` - Education background
- `experience.yml` - Work experience
- `skills.yml` - Technical and professional skills
- `projects.yml` - Notable projects and achievements
- `personal.yml` - Personal interests

### Modify Styles
Edit SCSS files in `_sass/` directory:
- `_variables.scss` - Color schemes and design tokens
- `_base.scss` - Base styles and dark mode
- `_navigation.scss` - Navigation styles
- `_profile.scss` - Profile header styles
- `_sections.scss` - Section layouts
- `_components.scss` - UI components
- `_responsive.scss` - Mobile responsiveness

### Update Content
- Edit `index.md` for the main profile description
- Modify `_config.yml` for site-wide settings
- Update layouts in `_layouts/` for structural changes

## Technologies Used

- **Jekyll** - Static site generator
- **SCSS** - Styling with variables and mixins
- **Vanilla JavaScript** - Dark mode and navigation
- **CSS Grid/Flexbox** - Responsive layouts
- **GitHub Pages** - Hosting platform

## Browser Support

- Chrome/Safari/Firefox (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is open source and available under the [MIT License](LICENSE).
