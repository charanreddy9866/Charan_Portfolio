# 🚀 Charan Reddy's Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features dark mode, smooth animations, and a clean design showcasing full-stack development and machine learning expertise.

**Live Site:** https://charanreddy9866.github.io/Charan_Portfolio/

---

## ✨ Features

- 🌙 **Dark Mode Toggle** - Switch between light and dark themes with persistent storage
- ⚡ **Smooth Animations** - Scroll-triggered animations powered by AOS (Animate On Scroll)
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- ♿ **Accessible Design** - Semantic HTML and ARIA-friendly
- 🎨 **Modern UI** - Clean design with beautiful color palette and typography
- 🔝 **Back-to-Top Button** - Quick navigation to page top
- 📧 **Contact Form** - Integrated with Formspree for email submissions
- 🎯 **Smooth Scroll Navigation** - Active link tracking with smooth scrolling

---

## 📂 Project Structure

```
Charan_Portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css      # All styles (responsive & dark mode)
│   ├── img/
│   │   ├── Profile.jpg     # Profile picture
│   │   ├── JUSTIN.png      # Client testimonial image
│   │   └── Charan 2025.pdf # Resume PDF
│   └── pdf/                # Additional PDFs if needed
└── README.md               # This file
```

---

## 🎨 Design Features

### Color Palette
- **Primary:** #8d5fc1 (Purple)
- **Dark:** #7c4fb0 (Dark Purple)
- **Light:** #b89dd9 (Light Purple)
- **Accent:** #ff6b6b (Red), #51cf66 (Green)
- **Text:** #1a1a2e (Dark), #555 (Gray)
- **Background:** #ffffff (Light), #0f0f1e (Dark)

### Typography
- **Headings:** Playfair Display (elegant serif)
- **Body:** Poppins (modern sans-serif)
- **Sizes:** Responsive scaling from mobile to desktop

### Animations
- Page load slide-in effects
- Card hover lift animations
- Skill bar fill animations with shimmer
- Scroll-triggered section animations
- Smooth hover transitions on links and buttons

---

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Git (for version control)
- GitHub account (for hosting)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/charanreddy9866/Charan_Portfolio.git
   cd Charan_Portfolio
   ```

2. **Open locally:**
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```

3. **View live site:**
   Visit https://charanreddy9866.github.io/Charan_Portfolio/

---

## ✏️ Customization

### Update Your Information

1. **Edit `index.html`:**
   - Change name, title, email, phone
   - Update profile image path
   - Modify social media links
   - Add/remove projects
   - Update skills and experience

2. **Update Resume:**
   - Replace `assets/img/Charan 2025.pdf` with your resume

3. **Update Profile Image:**
   - Replace `assets/img/Profile.jpg` with your photo
   - Recommended size: 400x400px

### Modify Styles

Edit `assets/css/styles.css`:

```css
/* Change primary color */
--primary-color: #8d5fc1; /* Change this value */

/* Adjust font sizes */
--big-font-size: 3.5rem;

/* Modify spacing */
.section {
  padding-block: 6rem 4rem;
}
```

### Change Contact Form

The form uses Formspree. To use your own email:

1. Go to https://formspree.io
2. Create account and set up form
3. Replace `action="https://formspree.io/f/mnnpoano"` in index.html with your Formspree endpoint

---

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid & Flexbox
- **JavaScript (Vanilla)** - No frameworks, lightweight
- **AOS.js** - Scroll animations
- **Font Awesome** - Icons
- **Google Fonts** - Typography
- **Formspree** - Contact form backend

---

## 🌙 Dark Mode

Dark mode preference is saved to browser's local storage:

```javascript
// Enable dark mode
body.classList.add('dark-mode');
localStorage.setItem('theme', 'dark');

// Disable dark mode
body.classList.remove('dark-mode');
localStorage.setItem('theme', 'light');
```

The theme persists across browser sessions.

---

## 📱 Responsive Breakpoints

| Screen Size | Width | Adjustments |
|------------|-------|------------|
| Desktop | 1200px+ | Full layout |
| Laptop | 992px - 1200px | Grid adjustments |
| Tablet | 768px - 992px | Stacked layout |
| Mobile | 576px - 768px | Single column |
| Small Mobile | <576px | Reduced padding |

---

## 🚀 Deployment

### GitHub Pages (Automatic)

1. Push changes to `main` branch:
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push origin main
   ```

2. Your site updates automatically (1-2 minutes)

3. Visit: `https://yourusername.github.io/Charan_Portfolio/`

### Other Hosting Options

- **Netlify:** Drag & drop folder
- **Vercel:** Connect GitHub repo
- **AWS S3:** Upload and configure
- **Custom Domain:** Update DNS settings

---

## 🔧 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📋 Sections Overview

### 1. **Hero Section**
- Welcome message
- Title and subtitle
- Call-to-action buttons
- Profile image with animation

### 2. **About**
- Personal bio
- Key information (name, age, location, email)
- Download resume button
- Social media links

### 3. **Education & Experience**
- Educational background
- Work experience
- Companies, roles, and achievements
- Animated timeline cards

### 4. **Projects**
- Project showcase
- Tags and descriptions
- GitHub links
- Hover effects

### 5. **Services**
- Service offerings
- Icons and descriptions
- 6 core competencies
- Hover animations

### 6. **Skills**
- Skill categories
- Proficiency percentages
- Animated progress bars
- Descriptions

### 7. **Testimonials**
- Client feedback
- Profile image and name
- Location

### 8. **Contact**
- Contact information (phone, email, address)
- Contact form
- Form validation

### 9. **Footer**
- Copyright notice
- Social media links

---

## 🐛 Troubleshooting

### Dark mode not saving?
- Check if localStorage is enabled in browser settings
- Clear browser cache and try again

### Images not loading?
- Verify image paths in HTML
- Ensure images are in `assets/img/` folder
- Check file permissions

### Form not sending?
- Verify Formspree endpoint URL
- Check email address in form settings
- Test on different browser

### Animations not smooth?
- Disable browser extensions
- Clear cache
- Check browser hardware acceleration

---

## 📈 Performance Tips

1. **Optimize Images:**
   - Use WebP format where possible
   - Compress images before uploading
   - Keep images under 500KB

2. **Improve Load Time:**
   - Lazy load images
   - Minimize CSS/JS
   - Enable browser caching

3. **SEO:**
   - Update meta tags in `<head>`
   - Use descriptive alt text for images
   - Add structured data

---

## 🎯 Future Enhancements

- [ ] Blog section
- [ ] Project case studies
- [ ] Video testimonials
- [ ] Newsletter signup
- [ ] Analytics integration
- [ ] CMS integration
- [ ] Multi-language support
- [ ] PDF generation

---

## 📝 License

This project is open source and available under the MIT License.

---

## 🤝 Contributing

Found a bug or have suggestions? 

1. Fork the repository
2. Create feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -m 'Add improvement'`)
4. Push to branch (`git push origin feature/improvement`)
5. Open Pull Request

---

## 📧 Contact

- **Email:** kcharanreddy2407@gmail.com
- **Phone:** +1 (551) 375 6924
- **Location:** New Jersey, USA

### Social Links
- [LinkedIn](https://www.linkedin.com/in/charan-reddy-k-a45a23276/)
- [GitHub](https://github.com/charanreddy9866)
- [Twitter](https://x.com/Charanreddy2407)
- [Instagram](https://www.instagram.com/mr.cr__/)

---

## 📚 Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS-Tricks](https://css-tricks.com/)
- [AOS Documentation](https://michalsnik.github.io/aos/)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)

---

**Last Updated:** August 2025  
**Version:** 2.0 (Redesigned)

---

Made with ❤️ by Charan Reddy
