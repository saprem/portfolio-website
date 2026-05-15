# Portfolio Website

A modern, responsive portfolio website with dark/light theme toggle, smooth animations, and professional design. Built with pure HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Dark/Light Theme**: Toggle between dark and light themes with localStorage persistence
- **Smooth Animations**: Scroll-triggered animations and smooth transitions
- **Professional Sections**:
  - Hero section with social links
  - About section with stats
  - Skills section with categorized technologies
  - Projects showcase with links
  - Contact form with validation
- **Modern UI/UX**: Clean design with gradient accents and smooth interactions
- **Accessibility**: ARIA labels and keyboard navigation support
- **Performance Optimized**: Lightweight and fast loading

## Quick Start

### Option 1: Open Directly

Simply open `index.html` in your web browser:

```bash
open index.html
```

### Option 2: Use a Local Server

For the best experience, use a local web server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (http-server):**
```bash
npx http-server
```

**Using PHP:**
```bash
php -S localhost:8000
```

Then open your browser and navigate to `http://localhost:8000`

## Customization

### 1. Personal Information

Edit `index.html` to customize:

- **Name and Title**: Update the hero section
- **Social Links**: Replace with your GitHub, LinkedIn, Twitter, and email
- **About Section**: Write your own bio and update stats
- **Skills**: Add/remove technologies you work with
- **Projects**: Add your actual projects with links
- **Contact Info**: Update email, phone, and location

### 2. Colors and Styling

Edit `styles.css` to customize colors:

```css
:root {
    --accent-primary: #6366f1;  /* Primary accent color */
    --accent-secondary: #8b5cf6; /* Secondary accent color */
    /* Modify other variables as needed */
}
```

### 3. Theme

The website supports both light and dark themes. The theme preference is saved in localStorage and persists across sessions.

## File Structure

```
portfolio-website/
│
├── index.html          # Main HTML file
├── styles.css          # All styles and responsive design
├── script.js           # JavaScript for interactions
└── README.md           # This file
```

## Sections Overview

### Hero Section
- Eye-catching introduction
- Call-to-action buttons
- Social media links
- Animated scroll indicator

### About Section
- Personal introduction
- Professional stats (projects, clients, experience)
- Profile image placeholder

### Skills Section
- Categorized skills (Frontend, Backend, Tools)
- Interactive skill tags
- Icon-based categories

### Projects Section
- Grid layout of projects
- Project descriptions and tags
- Demo and code links

### Contact Section
- Contact information
- Working contact form with validation
- Form submission notification

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Push your code:
```bash
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/portfolio.git
git push -u origin main
```
3. Go to Settings > Pages
4. Select the main branch as source
5. Your site will be live at `https://yourusername.github.io/portfolio`

### Netlify

1. Drag and drop the folder to Netlify
2. Or connect your GitHub repository
3. Your site will be live instantly

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts

## Enhancements & Ideas

Here are some ideas to enhance your portfolio:

- Add a blog section
- Include a timeline/experience section
- Add project filtering by technology
- Implement a particle background effect
- Add testimonials section
- Include downloadable resume
- Add loading screen animation
- Implement multi-language support
- Add Google Analytics
- Include a services section

## Technologies Used

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- JavaScript (ES6+)
- Font Awesome Icons

## Performance

- No external dependencies (except Font Awesome CDN)
- Optimized CSS with CSS variables
- Smooth animations with CSS transitions
- Efficient JavaScript with event delegation
- Mobile-first responsive design

## Credits

- Icons: [Font Awesome](https://fontawesome.com/)
- Inspired by modern portfolio designs

## License

This project is open source and available under the MIT License. Feel free to use it for your own portfolio!

## Support

If you have any questions or run into issues, feel free to open an issue in the repository.

## Next Steps

1. Replace placeholder content with your actual information
2. Add your profile picture (or create a custom avatar)
3. Update project details with your real projects
4. Customize colors to match your personal brand
5. Deploy to GitHub Pages or your hosting provider
6. Share your portfolio with the world!

---

**Happy coding!** 🚀
