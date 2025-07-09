# Buff.Labs Proposal Deck

A professional pitch deck presentation for AI-powered creative solutions.

## 🗂️ File Structure

```
BuffLabs Pitch Deck/
├── index.html          # Main presentation file
├── README.md           # This documentation
└── assets/
    ├── styles.css      # Main stylesheet
    ├── icons.svg       # Custom SVG icon library
    ├── AI Agents.svg               # Original AI Agents icon
    ├── Content Generation Engine.svg # Original Content Generation icon
    ├── image generation static image.svg # Original Static Image icon
    ├── image set.svg               # Original Image Set icon
    └── video generation.svg        # Original Video Generation icon
```

## 🎨 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile
- **Custom Icons**: Pixel-art style custom SVG icons for each solution
- **Smooth Navigation**: Fixed navigation header with smooth scrolling
- **Parallax Effects**: Background parallax effects for visual appeal
- **Professional Typography**: Clean typography using Google Fonts (Inter, Space Grotesk, Syne)
- **Modular Structure**: Separated CSS and SVG assets for better maintainability

## 🚀 Usage

1. **Open the presentation**: Simply open `index.html` in any modern web browser
2. **Navigate**: Use the navigation menu or scroll through the sections
3. **Customize**: 
   - Edit content in `index.html`
   - Modify styles in `assets/styles.css`
   - Replace icons in `assets/icons.svg`

## 📐 Sections

1. **Introduction**: Hero section with company branding
2. **Services**: Overview of AI-powered services offered
3. **Challenges**: Client pain points and challenges addressed
4. **Solutions**: Detailed solutions with custom icons
5. **Proposal**: Pricing and partnership details
6. **Next Steps**: Clear action items for moving forward

## 🎯 Icon System

The presentation uses a custom icon system with 5 specialized icons:

- **Content Generation Engine**: Magic wand icon for text generation
- **Image Generation**: Eye/scanner icon for static image creation
- **Video Generation**: Camera icon for video production
- **Image Set**: Polaroid stack icon for photo sets
- **AI Agents**: Hierarchy icon for AI automation

Icons are stored as SVG symbols in `assets/icons.svg` and referenced throughout the presentation.

## 🛠️ Customization

### Changing Colors
Edit CSS variables in `assets/styles.css`:
```css
:root {
    --primary-color: #0099ff;    /* Main brand color */
    --text-color: #555555;       /* Body text */
    --heading-color: #111111;    /* Headings */
    --bg-color: #f9f9f9;         /* Background */
    --border-color: #e0e0e0;     /* Borders */
}
```

### Adding New Icons
1. Add new symbol to `assets/icons.svg`
2. Reference using: `<use href="assets/icons.svg#your-icon-id"></use>`

### Modifying Content
Update text content directly in `index.html` while maintaining the existing structure.

## 📱 Browser Support

- Chrome/Edge 88+
- Firefox 85+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technical Notes

- **CSS Grid & Flexbox**: Modern layout techniques for responsive design
- **CSS Custom Properties**: For easy theming and customization
- **SVG Sprites**: Efficient icon delivery system
- **Semantic HTML**: Proper document structure for accessibility
- **Performance Optimized**: Minimal external dependencies

---

**Built with ❤️ for Buff.Labs** 