# My Portfolio Website

A beautiful, responsive portfolio website showcasing mixed media work with sections for about me, portfolio projects, testimonials, and a contact form.

## Features

✨ **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
🎨 **Modern Styling** - Beautiful gradient colors and smooth animations
📱 **Mobile Friendly** - Optimized for all screen sizes
📧 **Contact Form** - Functional contact form with validation
💬 **Testimonials** - Showcase client feedback and reviews
🖼️ **Portfolio Grid** - Display your mixed media work in an elegant grid layout
⚡ **Smooth Scrolling** - Smooth navigation between sections

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **JavaScript (Vanilla)** - Interactive elements and form handling
- **GitHub Pages** - Free hosting

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Styling and responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## Sections

### 1. Navigation
Sticky navigation bar with links to all sections

### 2. Hero Section
Eye-catching welcome section with call-to-action button

### 3. About Me
Information about you, your experience, and skills

### 4. Portfolio
Grid showcase of your mixed media projects with hover effects

### 5. Testimonials
Client testimonials and feedback displayed in cards

### 6. Contact Form
Functional contact form for visitors to get in touch

### 7. Footer
Social media links and copyright information

## Getting Started

### Prerequisites
- A GitHub account
- Basic knowledge of HTML/CSS/JavaScript (optional)

### Installation

1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/calexenamel85-art/portfolio.git
   cd portfolio
   ```

2. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll to "GitHub Pages" section
   - Set source to "main" branch
   - Your site will be published at `https://calexenamel85-art.github.io/portfolio/`

3. **Customize Your Portfolio**
   - Edit `index.html` with your information
   - Update project images in the portfolio section
   - Modify colors in `styles.css` by changing CSS variables
   - Add your social media links in the footer

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;      /* Main color */
    --secondary-color: #ec4899;    /* Accent color */
    --dark-bg: #0f172a;
    --light-bg: #f8fafc;
    /* ... other variables */
}
```

### Adding Projects
In `index.html`, add new portfolio items:
```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <img src="your-image-url" alt="Project Name">
        <div class="portfolio-overlay">
            <p>Project Category</p>
        </div>
    </div>
    <div class="portfolio-info">
        <h3>Project Title</h3>
        <p>Project description</p>
    </div>
</div>
```

### Adding Testimonials
Add new testimonial cards:
```html
<div class="testimonial-card">
    <div class="stars">★★★★★</div>
    <p class="testimonial-text">"Your testimonial text here"</p>
    <p class="testimonial-author">- Author Name, Title</p>
</div>
```

### Contact Form Integration
The contact form currently shows a success message. For actual email functionality, integrate with services like:
- **Formspree** - https://formspree.io
- **EmailJS** - https://www.emailjs.com
- **Basin** - https://usebasin.com

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Live Demo
Visit your portfolio at: `https://calexenamel85-art.github.io/portfolio/`

## Tips for Success

1. **High-Quality Images** - Use clear, high-resolution images for your portfolio projects
2. **Professional Copy** - Write engaging descriptions for your work
3. **Keep It Updated** - Regularly add new projects and testimonials
4. **Mobile Testing** - Always test on mobile devices before publishing
5. **Social Links** - Update footer with your actual social media profiles
6. **SEO** - Consider adding meta descriptions and keywords to index.html

## Future Enhancements

Consider adding these features:
- Blog section
- Light/Dark mode toggle
- Filtering system for projects by category
- Image gallery/lightbox for projects
- Newsletter subscription
- Analytics tracking
- Comment system

## License

This project is open source and available under the MIT License.

## Support

For issues or suggestions, please create an issue in the repository or contact me through the portfolio contact form.

---

**Happy Creating!** 🎨✨