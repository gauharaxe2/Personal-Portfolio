# Era AXE Portfolio Website

A modern, responsive agency portfolio website built by CEO Gauhar Nadeem (also known as Gauhar AXE) with HTML, CSS, and JavaScript. This professional website showcases services, portfolio, team members, and includes an interactive contact form.

## 🌟 Features

### ✅ Currently Implemented
- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern Navigation**: Fixed header with smooth scrolling and mobile hamburger menu
- **Hero Section**: Eye-catching hero section with gradient background and call-to-action buttons
- **About Section**: Company information with statistics and animated counters
- **Services Section**: Grid layout showcasing 6 different services with hover effects
- **Portfolio Section**: Filterable portfolio gallery with category filtering
- **Team Section**: Team member profiles with social media links
- **Contact Section**: Interactive contact form with validation
- **Animations**: AOS (Animate On Scroll) library for smooth scroll animations
- **Modern Styling**: CSS Grid, Flexbox, gradients, and modern design patterns
- **Interactive Elements**: Hover effects, form validation, and smooth transitions

### 🎯 Website Sections
1. **Home** - Hero section with main call-to-action
2. **About** - Company story and statistics
3. **Services** - Service offerings with detailed descriptions
4. **Portfolio** - Project showcase with filtering
5. **Team** - Team member profiles
6. **Contact** - Contact form and company information

## 🚀 Technical Implementation

### Technologies Used
- **HTML5**: Semantic markup and modern structure
- **CSS3**: Custom properties, Grid, Flexbox, animations
- **JavaScript**: ES6+, DOM manipulation, form handling
- **External Libraries**:
  - AOS (Animate On Scroll) for animations
  - Font Awesome for icons
  - Google Fonts (Inter font family)

### File Structure
```
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styling and responsive design
├── js/
│   └── script.js       # Interactive functionality
└── README.md           # Project documentation
```

### Key Features Implementation

#### Navigation
- Fixed header that changes style on scroll
- Mobile-responsive hamburger menu
- Smooth scrolling to sections
- Active link highlighting

#### Portfolio Filtering
- Category-based filtering (All, Web Design, Branding, Marketing)
- Smooth transitions when filtering
- Hover effects on portfolio items

#### Contact Form
- Client-side validation
- Success/error notifications
- Form submission simulation
- User-friendly error messages

#### Animations
- Scroll-triggered animations using AOS library
- Counter animations for statistics
- Hover effects throughout the site
- Loading states for interactive elements

## 🎨 Design Features

### Color Scheme
- Primary: #6366f1 (Indigo)
- Secondary: #f59e0b (Amber)
- Text Dark: #1f2937
- Text Light: #6b7280
- Background Light: #f9fafb

### Typography
- Primary font: Inter (Google Fonts)
- Responsive font sizes
- Proper hierarchy and spacing

### Layout
- CSS Grid for main layouts
- Flexbox for component alignment
- Mobile-first responsive design
- Modern card-based design patterns

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🛠️ Customization

### Colors
Update CSS custom properties in `:root`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #f59e0b;
    /* ... other variables */
}
```

### Content
- Update text content directly in `index.html`
- Replace placeholder images with actual images
- Modify service descriptions in the services section
- Update portfolio items with real projects

### Contact Form
The contact form currently simulates submission. To make it functional:
1. Add your backend endpoint
2. Update the form submission handler in `script.js`
3. Configure email service (e.g., EmailJS, FormSubmit, or custom backend)

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📊 Performance

- Optimized CSS with custom properties
- Minimal JavaScript for fast loading
- External libraries loaded from CDNs
- Responsive images with placeholder fallbacks

## 🚀 Deployment

This is a static website that can be deployed to any static hosting service:

1. **GitHub Pages**: Push to GitHub and enable Pages
2. **Netlify**: Drag and drop the project folder
3. **Vercel**: Connect your GitHub repository
4. **Traditional hosting**: Upload files via FTP

## 📈 Future Enhancements

### Planned Features
- Blog section with article management
- Client testimonials carousel
- Case study pages for portfolio items
- Multi-language support
- Dark mode toggle
- Advanced animations and micro-interactions

### Backend Integration
- CMS integration for content management
- Real contact form submission
- Newsletter subscription
- Analytics integration
- SEO optimization tools

## 📞 Support

For questions or issues:
1. Check the browser console for JavaScript errors
2. Verify all external libraries are loading correctly
3. Ensure CSS and JS files are properly linked
4. Test responsiveness across different devices

## 📄 License

This project is open source and available under the MIT License.

---

**Last Updated**: January 2024
**Version**: 1.0.0