# Mugdho's Recipe Collection

A responsive recipe website featuring authentic South Asian cuisine, created as a web development assignment for **South Asian University**.

## About This Project

This is an HTML and CSS-based recipe website showcasing five delicious South Asian recipes. The project demonstrates modern web design principles including responsive layout, semantic HTML structure, and beautiful CSS styling using Flexbox and CSS Grid.

**Author:** Mugdho Mistry  
**Institution:** South Asian University  
**Project Type:** HTML5 + CSS3 (Pure Frontend)

---

## Recipes Featured

1. **Butter Chicken** - A classic Indian non-vegetarian dish with creamy tomato-based sauce
2. **Crispy Samosa** - Golden fried triangular pastry filled with spiced potatoes and peas
3. **Paneer Tikka** - Grilled cottage cheese marinated in yogurt and aromatic spices
4. **Rice Kheer** - Creamy rice pudding dessert flavored with cardamom and saffron
5. **Aloo Chaat** - Popular Indian street food with spiced potatoes and tamarind chutney

---

## Features

### Responsive Design
- **Desktop:** Full multi-column layout with optimized spacing
- **Tablet (768px and below):** Adjusted columns and simplified navigation
- **Mobile (480px and below):** Single-column layout optimized for touch devices

### Technologies Used
- **HTML5:** Semantic markup with proper structure
- **CSS3:** Modern styling with:
  - Flexbox for component layout
  - CSS Grid for recipe card arrangements
  - Media queries for responsive breakpoints
  - Smooth transitions and hover effects
  - Custom color scheme and typography

### Components
- Sticky Navigation Bar
- Hero Section with recipe showcase
- Recipe Card Grid
- Individual Recipe Detail Pages
- Responsive Footer
- Mobile Menu Toggle (JavaScript)

---

## Project Structure

```
recipe-website/
├── index.html           # Homepage with recipe gallery
├── recipe1.html         # Butter Chicken recipe
├── recipe2.html         # Crispy Samosa recipe
├── recipe3.html         # Paneer Tikka recipe
├── recipe4.html         # Rice Kheer recipe
├── recipe5.html         # Aloo Chaat recipe
├── css/
│   └── styles.css       # Main stylesheet
├── images/
│   ├── recipe1.jpg      # Butter Chicken image
│   ├── recipe2.jpg      # Crispy Samosa image
│   ├── recipe3.jpg      # Paneer Tikka image
│   ├── recipe4.jpg      # Rice Kheer image
│   └── recipe5.jpg      # Aloo Chaat image
└── README.md            # This file
```

---

## Design Specifications

### Color Palette
- **Primary:** Terracotta (#C44B1B)
- **Secondary:** Espresso (#2D1B0E)
- **Accent:** Peach (#E8A87C)
- **Neutral:** Sage Green (#7A9E7E), Blush (#F5E6E1)

### Typography
- **Headings:** Playfair Display (serif)
- **Accent Text:** Lora (serif italic)
- **Body:** DM Sans (sans-serif)

### Layout Techniques
- **Grid:** 3-column recipe card layout on desktop
- **Flexbox:** Navigation, footer, and component alignment
- **Hover Effects:** Smooth transitions on interactive elements

---

## Setup Instructions

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.)
- No backend or server required

### Installation Steps

1. **Clone or Download:**
   ```bash
   git clone <repository-url>
   cd recipe-website
   ```

2. **Add Recipe Images:**
   - Place recipe images in the `images/` folder
   - Required images: `recipe1.jpg`, `recipe2.jpg`, `recipe3.jpg`, `recipe4.jpg`, `recipe5.jpg`
   - Recommended dimensions: 600x400px
   - Supported formats: JPG, PNG, WebP

3. **Open in Browser:**
   - Simply open `index.html` in your web browser
   - Or use Live Server extension in VS Code for live preview

### Local Server (Optional)
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js http-server
npx http-server
```

Then visit `http://localhost:8000` in your browser.

---

## Deployment

### GitHub Pages Deployment

1. **Create a GitHub Repository:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Recipe website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to repository settings
   - Scroll to "GitHub Pages" section
   - Select `main` branch as source
   - Click "Save"

3. **Access Your Site:**
   - Your site will be available at: `https://<your-username>.github.io/<repo-name>/`

---

## Assignment Requirements Met

### HTML (20 points)
- ✓ Semantic HTML5 markup
- ✓ Proper document structure with DOCTYPE and meta tags
- ✓ Multi-page website with consistent navigation
- ✓ Forms and interactive elements
- ✓ Accessibility considerations (alt text, semantic tags)

### CSS Styling (25 points)
- ✓ External stylesheet (styles.css)
- ✓ Custom color scheme and typography
- ✓ Creative design with multiple colors and fonts
- ✓ Hover effects and transitions
- ✓ Pseudo-classes usage (:hover, :active, etc.)

### Layout & Flexbox/Grid (15 points)
- ✓ Flexbox for navigation and footer
- ✓ CSS Grid for recipe card layout
- ✓ Proper alignment and spacing
- ✓ Component-based layout structure

### Responsiveness (15 points)
- ✓ Mobile-first responsive design
- ✓ Media queries for tablet (768px) and mobile (480px)
- ✓ Readable on all device sizes
- ✓ Adaptive navigation and layout

### Navigation (10 points)
- ✓ Clear navigation links on all pages
- ✓ Active page indicator
- ✓ Footer navigation with recipe links
- ✓ Mobile menu toggle functionality

### Code Quality (5 points)
- ✓ Clean, well-organized code
- ✓ Consistent indentation
- ✓ Meaningful class and ID names
- ✓ Comments where necessary

### Creativity & Originality (10 points)
- ✓ Authentic South Asian cuisine focus
- ✓ Unique color scheme and visual design
- ✓ Well-crafted recipe content
- ✓ Professional presentation

---

## Browser Compatibility

The website is compatible with:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

---

## Future Enhancements

- [ ] Recipe search functionality
- [ ] User ratings and comments section
- [ ] Video recipe tutorials
- [ ] Shopping list generator
- [ ] Recipe suggestions based on ingredients
- [ ] Dark mode toggle
- [ ] Social media sharing buttons
- [ ] Print-friendly recipe pages

---

## Credits

**Project Created By:** Mugdho Mistry  
**For:** South Asian University Web Development Assignment

Recipes sourced from authentic South Asian culinary traditions.

---

## License

This project is created for educational purposes as part of a university assignment.

---

## Support

For questions or issues regarding this project, please contact:
- **Email:** mugdho@example.com
- **GitHub:** [@mugdho-mistry](https://github.com/mugdho-mistry)

---

## Useful Resources

- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS-Tricks Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [GitHub Pages Documentation](https://pages.github.com/)

---

**Updated:** 2026  
**Version:** 1.0
