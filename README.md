# 🎮 GAMELAND - Modern Portfolio Website

![GAMELAND Preview](https://github.com/user-attachments/assets/c9a3e15f-c8fc-4ffc-9713-59c7b692b721)

A cutting-edge portfolio website featuring immersive 3D animations, stylish preloader, and interactive music toggle. Designed for modern developers and creatives looking to showcase their work in an engaging way.

## ✨ Key Features

### 🎨 Visual Experience
- **3D Card Effects** - Interactive hover cards with depth and perspective
- **Scroll Mask Animation** - Dynamic image reveals on scroll
- **Stylish Preloader** - Elegant loading animation before content appears
- **Smooth Animations** - Fluid transitions and movements throughout

### 🎵 Interactive Elements
- **Music Toggle** - Background audio control with visual feedback
- **Responsive Design** - Seamless experience across all devices
- **Parallax Effects** - Layered depth for enhanced visual appeal

### 📱 Technical Excellence
- **Mobile-First Approach** - Optimized for touch and mobile interactions
- **Performance Optimized** - Fast loading and smooth animations
- **Clean Code Structure** - Maintainable and scalable architecture

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic markup structure |
| **SCSS/CSS** | Advanced styling with BEM methodology |
| **JavaScript (ES6+)** | Interactive functionality |
| **GSAP** | Professional-grade animations |
| **GreenSock ScrollTrigger** | Scroll-based animations |
| **Modern CSS3** | 3D transforms, flexbox, grid |

## 🚀 Getting Started

### Prerequisites
- Modern web browser with CSS3 and JavaScript ES6+ support
- Local server for development (optional)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/gameland-portfolio.git
```

2. Navigate to the project directory:
```bash
cd gameland-portfolio
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## 📁 Project Structure

```
gameland-portfolio/
├── index.html              # Main HTML file
├── css/
│   ├── main.css           # Compiled CSS
│   └── styles.scss        # SCSS source files
├── js/
│   ├── main.js            # Main JavaScript file
│   ├── animations.js      # GSAP animations
│   └── music-player.js    # Audio controls
├── assets/
│   ├── images/            # Image resources
│   ├── models/            # 3D models (if any)
│   └── audio/             # Background music
└── README.md              # This file
```

## 🎯 Usage Examples

### Music Toggle
The website features a background music player with toggle controls:
- Click the music icon to play/pause
- Visual feedback shows audio state
- Volume controls (if implemented)

### 3D Card Interaction
Hover over portfolio cards to experience:
- Depth and perspective shifts
- Smooth transition animations
- Content reveals on interaction

### Scroll Animations
As you scroll through the website:
- Images reveal with mask effects
- Elements fade in and out smoothly
- Parallax layers create depth

## 🔧 Development

### SCSS Structure
```scss
// BEM Methodology Example
.block {}
.block__element {}
.block--modifier {}
```

### Animation Setup
```javascript
// Example GSAP animation
gsap.from('.card', {
  duration: 1,
  opacity: 0,
  y: 50,
  stagger: 0.2,
  ease: "power3.out"
});
```

### Adding New Sections
1. Create HTML structure with appropriate BEM classes
2. Style in SCSS following existing patterns
3. Add animations in JavaScript files
4. Test across different viewport sizes

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Opera 50+

## 📱 Responsive Breakpoints

| Device | Breakpoint | Features |
|--------|------------|----------|
| Mobile | < 768px | Touch-optimized, simplified animations |
| Tablet | 768px - 1024px | Adapted layouts, reduced effects |
| Desktop | > 1024px | Full 3D effects, complex animations |

## 🎨 Customization

### Changing Colors
Modify the SCSS variables in `_variables.scss`:
```scss
$primary-color: #ff6b6b;
$secondary-color: #4ecdc4;
$background-dark: #121212;
```

### Adding Content
1. Portfolio Items: Add cards in the portfolio section
2. Music: Replace audio files in `/assets/audio/`
3. Images: Optimize images for web and add to `/assets/images/`

## 📊 Performance Tips

1. **Image Optimization**: Use WebP format with JPEG fallbacks
2. **Animation Optimization**: Use `will-change` property strategically
3. **Lazy Loading**: Implement for images below the fold
4. **Code Splitting**: Separate animation logic for better loading

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- GSAP team for the amazing animation library
- Inspiration from modern gaming websites
- Community contributors for feedback and testing

## 📞 Support

For issues, questions, or suggestions:
1. Check the [Issues](https://github.com/yourusername/gameland-portfolio/issues) page
2. Create a new issue with detailed description
3. Email: your.email@example.com

---

**Built with ❤️ for the creative community** | **Version 1.0.0**

---

<div align="center">
  
### ⭐ If you like this project, give it a star on GitHub!

[![GitHub stars](https://img.shields.io/github/stars/yourusername/gameland-portfolio?style=social)](https://github.com/yourusername/gameland-portfolio)
[![GitHub forks](https://img.shields.io/github/forks/yourusername/gameland-portfolio?style=social)](https://github.com/yourusername/gameland-portfolio)

</div>
