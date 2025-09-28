# Personal Website

A modern, interactive, and responsive personal website showcasing work, study progress, and hobbies.

## Features

### 🎨 Modern Design
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Clean UI**: Modern interface with smooth animations and transitions
- **Color Scheme**: Professional gradient-based color palette
- **Typography**: Clean, readable fonts optimized for web

### 🏠 Home Page
- **Hero Section**: Eye-catching introduction with call-to-action buttons
- **About Cards**: Interactive cards showcasing different aspects (Work, Study, Hobbies)
- **Statistics**: Animated counters displaying key metrics
- **Contact Section**: Social media links and contact information

### 💼 Work Portfolio
- **Project Filtering**: Filter projects by category (All, Web, Mobile, Design, Other)
- **Interactive Cards**: Hover effects and detailed project modals
- **Skills Section**: Animated progress bars showing technical proficiencies
- **Project Details**: Comprehensive project information with features and technologies

### 📚 Study Section
- **Progress Tracking**: Visual progress bars for ongoing courses
- **Course History**: Completed courses with ratings and skills learned
- **Certifications**: Achievement badges and certification display
- **Learning Resources**: Favorite platforms and tools for learning

### 🎭 Hobbies Showcase
- **Interactive Gallery**: Photo gallery with lightbox functionality
- **Hobby Cards**: Detailed information about different interests
- **Music Section**: Music track display with play buttons
- **Fitness Tracker**: Progress circles and achievement displays

## Technology Stack

### Frontend
- **HTML5**: Semantic markup for accessibility and SEO
- **CSS3**: Advanced styling with Flexbox, Grid, and animations
- **JavaScript**: Interactive functionality and smooth user experience
- **Font Awesome**: Icon library for consistent iconography

### Features Implementation
- **Responsive Design**: CSS Grid and Flexbox for layout
- **Animations**: CSS transitions and JavaScript-powered animations
- **Interactive Elements**: Modal windows, lightboxes, and filtering
- **Performance**: Optimized loading and lazy loading for images
- **Accessibility**: Semantic HTML and keyboard navigation support

## File Structure

```
WEBSITE/
├── index.html          # Home page
├── work.html          # Work portfolio
├── study.html         # Learning journey
├── hobbies.html       # Hobbies showcase
├── css/
│   └── style.css      # Main stylesheet
├── js/
│   └── main.js        # Interactive functionality
├── images/            # Image assets
├── assets/           # Additional assets
└── README.md         # This file
```

## Getting Started

### Local Development
1. Clone or download the website files
2. Open terminal in the project directory
3. Start a local server:
   ```bash
   python -m http.server 8000
   ```
4. Open browser and navigate to `http://localhost:8000`

### Customization

#### Content Updates
1. **Personal Information**: Update name, contact info, and bio in HTML files
2. **Projects**: Modify project data in `js/main.js` - `getProjectData()` function
3. **Skills**: Update skill levels in the work.html file
4. **Courses**: Add/remove courses in study.html
5. **Hobbies**: Customize hobby information in `getHobbyData()` function

#### Styling
1. **Colors**: Update CSS custom properties in `:root` selector
2. **Fonts**: Change font imports and font-family declarations
3. **Layout**: Modify grid and flexbox properties as needed
4. **Animations**: Adjust transition durations and effects

#### Adding Images
1. Place image files in the `images/` directory
2. Update image paths in HTML files
3. For lazy loading, use `data-src` attribute

## Interactive Features

### Navigation
- **Sticky Navigation**: Fixed navigation bar with active link highlighting
- **Smooth Scrolling**: Smooth transitions between sections
- **Mobile Menu**: Hamburger menu for mobile devices

### Animations
- **Scroll Animations**: Elements fade in as they come into view
- **Counter Animation**: Numbers count up when visible
- **Progress Bars**: Skills animate to show proficiency levels
- **Hover Effects**: Interactive hover states on cards and buttons

### Modals and Overlays
- **Project Modals**: Detailed project information in overlay windows
- **Image Lightbox**: Full-screen image viewing with navigation
- **Hobby Details**: Expandable sections for hobby information

### Filtering and Interaction
- **Project Filtering**: Filter portfolio items by category
- **Social Links**: Connect to various social media platforms
- **Contact Information**: Easy access to contact details

## Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## Performance Optimizations
- **Lazy Loading**: Images load only when needed
- **CSS Optimization**: Efficient selectors and minimal repaints
- **JavaScript Optimization**: Event delegation and debounced functions
- **Font Loading**: Optimized web font loading strategy

## Accessibility Features
- **Semantic HTML**: Proper heading structure and landmarks
- **Keyboard Navigation**: Full keyboard accessibility
- **Color Contrast**: WCAG compliant color combinations
- **Alt Text**: Descriptive alternative text for images
- **Focus Management**: Visible focus indicators

## Deployment Options

### GitHub Pages
1. Push code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Access via `https://username.github.io/repository-name`

### Netlify
1. Connect GitHub repository to Netlify
2. Automatic deployment on code changes
3. Custom domain support available

### Vercel
1. Import project from GitHub
2. Automatic optimization and deployment
3. Global CDN and performance monitoring

## Future Enhancements
- [ ] Blog section with CMS integration
- [ ] Contact form with email functionality
- [ ] Dark/light theme toggle
- [ ] Multi-language support
- [ ] Advanced animations with GSAP
- [ ] PWA functionality for offline access

## License
This project is open source and available under the [MIT License](LICENSE).

## Contact
For questions or support, please reach out through the contact information on the website.

---

**Built with ❤️ using modern web technologies**