# Netflix Clone - Landing Page

A responsive Netflix landing page clone built with HTML and CSS, featuring a modern design with trending content sections and service highlights.

## 🎯 Project Overview

This project is a front-end clone of Netflix's landing page, created to practice and demonstrate HTML and CSS skills. It replicates Netflix's visual design and user interface elements including the hero section, trending movies showcase, and feature cards.

## ✨ Features

- **Hero Section**: Eye-catching header with background image and call-to-action
- **Email Sign-up**: Input field for email collection with "Get Started" button
- **Trending Now Section**: Display of top 6 trending content with numbered rankings
- **Reasons to Join**: Four feature cards highlighting Netflix's key benefits
- **Hover Effects**: Interactive elements with smooth transitions
- **Netflix Branding**: Authentic color scheme and typography

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox layout
- **Google Fonts**: Poppins font family
- **Assets**: Custom images and icons

## 📁 Project Structure

```
netflix-clone/
│
├── index.html
├── css/
│   └── style.css
├── assets/
│   ├── logo.svg
│   ├── favicon.ico
│   ├── background.jpg
│   ├── trending1.webp
│   ├── trending2.webp
│   ├── trending3.webp
│   ├── trending4.webp
│   ├── trending5.webp
│   ├── trending6.webp
│   ├── television.png
│   ├── download.png
│   ├── binoculars.png
│   └── happy-face.png
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/netflix-clone.git
```

2. Navigate to the project directory:
```bash
cd netflix-clone
```

3. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

Or simply double-click the `index.html` file.

## 📸 Screenshots

### Hero Section
The landing page features a full-width hero section with Netflix branding and email signup.

### Trending Now
Displays top 6 trending content with large numbered rankings.

### More Reasons to Join
Four feature cards highlighting key Netflix benefits with icons.

## 🎨 CSS Features Implemented

- **Flexbox Layout**: For responsive and flexible content arrangement
- **Positioning**: Absolute and relative positioning for overlays and ranking numbers
- **Pseudo-elements**: `::before` for hero section overlay
- **Transitions**: Smooth hover effects on interactive elements
- **Custom Styling**: Form inputs, buttons, and cards
- **Google Fonts**: Poppins font family integration

## 📝 Code Highlights

### Hero Section Overlay
```css
#header::before {
  content: '';
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.65);
  z-index: 1;
}
```

### Trending Card Hover Effect
```css
.card1:hover {
  transform: scale(1.05);
}
```

### Feature Cards Layout
```css
.card_section_02 {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}
```

## 🔄 Future Enhancements

- [ ] Add responsive design for mobile and tablet devices
- [ ] Implement JavaScript for interactive carousel/slider
- [ ] Add form validation for email input
- [ ] Create additional pages (sign-in, browse, etc.)
- [ ] Integrate with a movie API for dynamic content
- [ ] Add animations and micro-interactions
- [ ] Implement dark/light theme toggle
- [ ] Add accessibility improvements (ARIA labels, keyboard navigation)

## 🐛 Known Issues

- Not fully responsive on mobile devices (fixed padding values)
- No JavaScript functionality (static page only)
- Email form doesn't submit anywhere
- Missing media queries for smaller screens

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is for educational purposes only. Netflix and its logo are trademarks of Netflix, Inc.

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/ratul-03)

## 🙏 Acknowledgments

- Netflix for the design inspiration
- Google Fonts for the Poppins font family
- All contributors and supporters of this project

## 📞 Contact

For any questions or feedback, please reach out:
- Email: ratulsikder856@gmail.com

---

⭐ If you found this project helpful, please consider giving it a star!

**Note**: This is a clone project created for educational purposes and is not affiliated with or endorsed by Netflix, Inc.
