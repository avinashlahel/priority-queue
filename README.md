# Priority Queue - Modern Landing Page

A beautiful, responsive landing page for a software development and consulting firm specializing in AI automation, chatbots, and mobile applications.

## 🚀 Features

### Design & User Experience
- **Modern & Clean Design**: Soothing color palette with pale blues, soft greens, and gentle grays
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle hover effects, scroll animations, and interactive elements
- **Accessibility First**: WCAG compliant with proper semantic markup and keyboard navigation

### Technical Features
- **Pure HTML5/CSS3/JavaScript**: No frameworks or dependencies
- **CSS Variables**: Easy theming and customization
- **Google Fonts**: Montserrat and Roboto for modern typography
- **SVG Illustrations**: Scalable, lightweight graphics
- **Performance Optimized**: Fast loading with optimized assets

### Sections Included
1. **Header**: Sticky navigation with smooth scrolling
2. **Hero Section**: Compelling headline with call-to-action buttons
3. **Services**: Three main service cards (AI Automation, Chatbots, Mobile Development)
4. **About Us**: Company information with animated statistics
5. **Portfolio**: Showcase of recent projects
6. **Testimonials**: Client feedback and reviews
7. **Footer**: Contact information and social links

## 🎨 Color Palette

```css
--color-primary: #e3f2fd;          /* Pale Blue */
--color-primary-light: #f3f8ff;    /* Lighter Pale Blue */
--color-accent: #b2dfdb;           /* Soft Green */
--color-accent-light: #e0f2f1;     /* Lighter Soft Green */
--color-background: #f5f5f5;       /* Gentle Gray */
--color-text: #263238;             /* Deep Charcoal */
--color-text-light: #546e7a;       /* Lighter Text */
```

## 📁 Project Structure

```
priority-queue/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── TODO.txt            # Original requirements
```

## 🛠️ Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. That's it! The page is ready to use

### Local Development
For local development, you can use any local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🎯 Customization

### Changing Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --color-primary: #your-color;
    --color-accent: #your-accent-color;
    /* ... other variables */
}
```

### Updating Content
- **Company Information**: Edit the content in `index.html`
- **Services**: Modify the feature cards in the services section
- **Portfolio**: Update the portfolio items with your projects
- **Contact Information**: Change the footer contact details

### Adding New Sections
1. Add the HTML structure in `index.html`
2. Style the new section in `styles.css`
3. Add any JavaScript functionality in `script.js`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## ♿ Accessibility Features

- **Semantic HTML**: Proper use of landmarks and headings
- **Keyboard Navigation**: Full keyboard accessibility
- **Screen Reader Support**: ARIA labels and alt text
- **Focus Management**: Visible focus indicators
- **Reduced Motion**: Respects user's motion preferences
- **High Contrast**: Support for high contrast mode

## 🚀 Performance Features

- **Optimized Images**: SVG graphics for scalability
- **Minimal JavaScript**: Lightweight and efficient
- **CSS Optimization**: Efficient selectors and minimal repaints
- **Lazy Loading**: Intersection Observer for animations
- **Throttled Events**: Optimized scroll event handling

## 🔧 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 Code Quality

- **Clean Code**: Well-commented and organized
- **Semantic Markup**: Meaningful HTML structure
- **CSS Best Practices**: BEM methodology and CSS variables
- **JavaScript Standards**: Modern ES6+ features
- **Cross-browser Compatibility**: Tested across major browsers

## 🎨 Design Principles

- **Minimalism**: Clean, uncluttered design
- **Typography**: Clear hierarchy and readability
- **Whitespace**: Generous spacing for better readability
- **Consistency**: Unified design language throughout
- **User-Centered**: Focus on user experience and accessibility

## 🔮 Future Enhancements

Potential additions for future versions:
- Contact form with backend integration
- Blog section
- Case studies detail pages
- Multi-language support
- Dark mode toggle
- Advanced animations
- CMS integration

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

For questions or support, please contact:
- Email: hello@priorityqueue.com
- Phone: +1 (555) 123-4567

---

**Built with ❤️ using HTML5, CSS3, and Vanilla JavaScript** 