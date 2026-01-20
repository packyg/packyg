# Personal Portfolio Website

A modern, responsive personal portfolio website for software engineers. Built with vanilla HTML, CSS, and JavaScript - no frameworks required.

## Features

- **Modern Design**: Clean, professional design with gradient accents and smooth animations
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark Theme**: Easy-on-the-eyes dark color scheme optimized for readability
- **Smooth Animations**: Fade-in effects, hover transitions, and scroll animations
- **Interactive Elements**: Mobile menu, smooth scrolling, parallax effects
- **Performance Optimized**: Lightweight with no external dependencies (except Google Fonts)

## Sections

1. **Hero/Landing**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal introduction with statistics showcase
3. **Skills**: Organized tech stack display by category (Frontend, Backend, DevOps)
4. **Projects**: Featured projects with descriptions and links
5. **Contact**: Multiple contact methods with hover effects

## Customization Guide

### 1. Personal Information

Replace all placeholders in `index.html`:
- `[Your Name]` - Your full name
- `[YourName]` - Your short name/username
- `[X]`, `[Y]`, `[Z]` - Your statistics (years of experience, projects, etc.)
- `[your.email@example.com]` - Your email address
- `[yourusername]` - Your GitHub username
- `[yourprofile]` - Your LinkedIn profile
- `[yourhandle]` - Your Twitter handle
- `[hobby/interest placeholder]` - Your hobbies or interests

### 2. Skills

Edit the skill categories and tags in the Skills section to match your tech stack.

### 3. Projects

Update the three project cards with:
- Project names
- Descriptions
- Technologies used
- Links to live demos and GitHub repos
- Replace placeholder images with actual project screenshots

### 4. Colors

Customize the color scheme in `styles.css` by modifying the CSS variables:

```css
:root {
    --primary: #6366f1;        /* Primary color */
    --secondary: #8b5cf6;      /* Secondary color */
    --background: #0f172a;     /* Main background */
    --surface: #1e293b;        /* Card/section background */
    --text: #f1f5f9;          /* Primary text color */
    --accent: #ec4899;        /* Accent color */
}
```

### 5. Fonts

The site uses Inter font from Google Fonts. To change:
- Update the Google Fonts link in `index.html`
- Modify `font-family` in `styles.css`

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch and root folder
4. Your site will be available at `https://yourusername.github.io/repo-name`

### Netlify

1. Sign up at [netlify.com](https://netlify.com)
2. Connect your Git repository
3. Deploy with default settings
4. Your site will be live in minutes

### Vercel

1. Sign up at [vercel.com](https://vercel.com)
2. Import your Git repository
3. Deploy with zero configuration
4. Instant deployment with automatic HTTPS

## Local Development

Simply open `index.html` in your browser. No build process required!

For a local server (optional):

```bash
# Python 3
python -m http.server 8000

# Node.js (with http-server)
npx http-server

# PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Optional Enhancements

Some optional features are included but commented out:

1. **Dynamic Typing Effect**: Uncomment in `script.js` to enable rotating job titles
2. **Easter Egg**: Try the Konami code (↑↑↓↓←→←→BA) for a surprise!

## File Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # All styles and animations
├── script.js           # Interactive functionality
└── README.md          # Documentation
```

## Performance Tips

- Add actual project images (optimize them first - use WebP format)
- Consider lazy loading images if you add many
- Minify CSS and JS for production
- Add a favicon.ico file
- Set up analytics (Google Analytics, Plausible, etc.)

## SEO Optimization

1. Update the meta description in `index.html`
2. Add Open Graph tags for social sharing
3. Include a sitemap.xml
4. Add robots.txt
5. Ensure all images have alt text

## License

Free to use for personal projects. Customize as needed!

## Credits

Built with ❤️ using vanilla HTML, CSS, and JavaScript.
