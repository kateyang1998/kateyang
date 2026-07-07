# Kate Yang - Portfolio Website

A modern, responsive portfolio website showcasing my work as a Software Developer and UX Designer. Built with vanilla HTML, CSS, and JavaScript featuring smooth animations, mobile-first design, accessibility-focused implementation, and consistent user experience across all devices.

## 🌟 Features

### Design & User Experience
- **Modern Design System**: Cohesive visual identity with consistent typography, colors, and spacing
- **Smooth Animations**: Custom CSS animations with staggered loading effects for enhanced user engagement
- **Responsive Design**: Mobile-first approach optimized for all screen sizes from 320px to desktop
- **Accessibility Focused**: WCAG AA compliant with proper heading hierarchy, contrast ratios, and semantic HTML
- **Interactive Elements**: Hover effects, smooth transitions, and engaging micro-interactions

### Technical Features
- **Mobile Navigation**: Hamburger menu with smooth slide animations
- **Typed Text Animation**: Dynamic typing effect using Typed.js library
- **Optimized Performance**: Efficient CSS with minimal JavaScript for fast loading
- **Cross-browser Compatibility**: Tested across modern browsers and mobile devices
- **SEO Friendly**: Proper meta tags, semantic HTML structure, and descriptive content

## 🏗️ Project Structure

```
kateyang.github.io/
├── index.html              # Home page with introduction and about section
├── resume.html             # Professional experience, skills, and certifications
├── projects.html           # UX design projects and development work showcase
├── gallery.html            # Photography and creative work gallery
├── case-study-pages/
│   ├── redesign-youtube.html   # YouTube Music App redesign case study
│   ├── smarthome-app.html      # Smart Home Mobile App case study
│   ├── k-studio.html           # K Studio case study
│   ├── bakery-shop.html        # Kate's Bakery Shop case study
│   ├── recipe-app.html         # Recipe App case study
│   ├── medical-app.html        # Medical App case study
│   ├── college-website.html    # College Website case study
│   ├── renovation-website.html # Renovation Consultant Website case study
│   ├── yoga-studio.html        # Serenity Yoga Studio Website case study
│   ├── sweet-shop.html         # Kate's Sweet Shop Website case study
│   └── jk-collective.html      # JK Collective Inc. Company Website case study
├── case-study-images/          # Case study visuals (personas, wireframes, prototypes, logos)
├── case-study-resources/       # Source reports/PDFs referenced by case studies
├── styles/
│   ├── main.css            # Core styles and responsive design
│   ├── projects.css        # Project-specific styling
│   ├── case-study.css      # Case study page layouts and components
│   ├── gallery.css         # Gallery layout and image styling
│   └── normalize.css       # CSS reset for browser consistency
├── js/
│   └── script.js           # Interactive functionality and animations
├── images/                 # Project images and assets
├── photos/                 # Gallery photographs
└── .github/
    └── workflows/          # GitHub Actions for deployment
```

## 🎨 Design System

### Color Palette
- **Primary**: `rgb(56, 121, 125)` - Accessible dark teal for headers, links, and accents (WCAG AA compliant)
- **Secondary**: `rgb(76, 131, 135)` - Lighter teal for metadata and secondary information
- **Background**: `rgb(254, 252, 241)` - Warm cream for comfortable reading
- **Text Primary**: `#333` for main content
- **Text Secondary**: `#666` for supporting text
- **Text Tertiary**: `#6a6a6a` for italic metadata (dates, collaboration info)
- **Interactive**: Hover states with opacity and transform effects

### Typography
- **Font Family**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Responsive Scaling**: Progressive font sizes across breakpoints
- **Hierarchy**: Clear distinction between headings (h1-h5), subheadings, and body text
- **Accessibility**: Proper heading levels (no skipped levels) for screen readers

### Layout System
- **Three-Column Grid**: Consistent layout across Resume and Projects pages
- **Flexible Grid**: Gallery uses responsive CSS Grid with auto-fit columns
- **Case Study Layout**: Full-width hero sections with centered content containers (max-width: 1200px)
- **Mobile-First**: Progressive enhancement from mobile to desktop

## 📱 Responsive Breakpoints

- **Desktop**: 1100px and above - Full three-column layouts, wide case study content
- **Tablet Landscape**: 899px - 1099px - Two-column adjustments, optimized spacing
- **Tablet Portrait**: 609px - 899px - Stacked mobile navigation, single-column layouts
- **Mobile Large**: 459px - 609px - Single column, larger touch targets
- **Mobile Medium**: 393px - 459px - Optimized for iPhone 14 Pro and similar
- **Mobile Small**: 320px - 393px - Compact layout for older devices

## 🚀 Pages Overview

### Home (index.html)
- Personal introduction with animated typing effect
- Professional photo with hover animations and floating effects
- About me section with staggered text animations
- Responsive grid layout transitioning to mobile stack

### Resume (resume.html)
- **Work Experience**: Detailed professional history with three-column layout
- **Skills**: Organized by category (Technical, Design, Professional)
- **Certifications**: Google UX Design and AI Learning Path certificates
- **Animations**: Staggered loading effects for each section

### Projects (projects.html)
- **UX Design Projects**: 11 projects spanning mobile apps and websites, each with images and descriptions
- **Project Cards**: Numbered system with project type, team info, and preview images
- **Case Study Links**: Direct links to detailed case study pages for every project
- **Interactive Images**: Hover effects with smooth transitions

### Gallery (gallery.html)
- **Photography Showcase**: 30+ high-quality photographs
- **Responsive Grid**: Auto-adjusting columns based on screen size
- **Image Optimization**: Lazy loading with progressive enhancement
- **Smooth Animations**: Staggered loading with hover interactions

### Case Study Pages
Eleven comprehensive case studies, most following the design thinking process (Project Overview, Empathize, Define, Ideate, Prototype, Final Solution, Reflect):
- **Mobile App UX**: K Studio, Kate's Bakery Shop, Recipe App, Medical App, Smart Home App, and the YouTube Music Redesign
- **Website & Brand**: College Website and Renovation Consultant Website (research, logo/brand design, and prototypes)
- **Design & Build**: Serenity Yoga Studio (responsive, WCAG-accessible landing page) and JK Collective Inc. (a live company site designed in Figma and built with React/Vite)
- **Design System**: Kate's Sweet Shop, centered on a full design system — foundation styles and reusable components

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with WCAG AA accessibility standards
- **CSS3**:
  - Flexbox and CSS Grid for layouts
  - Custom animations with keyframes
  - Consistent color variables throughout
  - Media queries for responsive design
  - Accessibility-focused contrast ratios
- **JavaScript (ES6+)**:
  - Mobile menu functionality
  - Typed.js integration for text animations
  - Smooth scrolling and interactive elements
- **External Libraries**:
  - [Typed.js](https://github.com/mattboldt/typed.js/) for typing animations

## 🌐 Live Website

Visit the live portfolio at: [https://kateyang1998.github.io/kateyang/](https://kateyang1998.github.io/kateyang/)

## 📋 Local Development

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Optional: Local web server for development

### Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/kateyang1998/kateyang.git
   ```

2. Navigate to the project directory:
   ```bash
   cd kateyang
   ```

3. Open with a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8080

   # Using Node.js
   npx serve .

   # Using PHP
   php -S localhost:8080
   ```

4. Or simply open `index.html` in your browser for basic viewing.

## 🎯 Performance Optimizations

- **Minimal Dependencies**: Only essential external libraries (Typed.js)
- **Optimized Images**: CDN-hosted images with lazy loading
- **Efficient CSS**: Consolidated styles with minimal redundancy
- **Progressive Loading**: Staggered animations prevent overwhelming users
- **Mobile-First CSS**: Reduces unnecessary desktop styles on mobile
- **Accessibility**: Optimized for screen readers and keyboard navigation

## ♿ Accessibility Features

- **WCAG AA Compliant**: Color contrast ratios meet accessibility standards
- **Semantic HTML**: Proper heading hierarchy (h1 → h2 → h3, no skipped levels)
- **Alt Text**: Descriptive alternative text for all images
- **Keyboard Navigation**: Full site navigation via keyboard
- **Screen Reader Support**: Proper ARIA labels and semantic structure
- **Focus States**: Clear visual indicators for interactive elements

## 🔧 Browser Support

- **Modern Browsers**: Chrome 60+, Firefox 60+, Safari 12+, Edge 79+
- **Mobile Browsers**: iOS Safari 12+, Chrome Mobile 60+
- **Features Used**: CSS Grid, Flexbox, CSS Animations, ES6 JavaScript

## 📈 Future Enhancements

- [ ] Add blog section for technical articles
- [ ] Implement dark mode toggle
- [ ] Add contact form with backend integration
- [x] Complete case study pages for all projects
- [ ] Add loading animations and skeleton screens
- [ ] Implement service worker for offline functionality
- [ ] Add animation preferences (prefers-reduced-motion support)

## 👩‍💻 About Kate Yang

Software Developer and UX Designer passionate about creating innovative solutions and exceptional user experiences. Co-Founder of JK Collective Inc., a web and software development company, with prior professional experience as a Co-op Software Developer at Conestoga SMART Centre and Magenta Health Inc. (contributing to the OSCAR EMR healthcare application).

**Skills**: Java, C#, HTML5, CSS3, JavaScript, React, Node.js, Express.js, Vite, SQL, MySQL, PostgreSQL, UX Design, Design Systems, Figma, Adobe Creative Suite

## 📄 License

This project is open source and available for other developers and designers to learn from and use.

---

⭐ **If you like this portfolio, please give it a star on GitHub!**

📧 **Contact**: [kateyangqingru@gmail.com](mailto:kateyangqingru@gmail.com)
🔗 **LinkedIn**: [linkedin.com/in/kateyangqingru](https://www.linkedin.com/in/kateyangqingru/)
🐙 **GitHub**: [github.com/kateyang1998](https://github.com/kateyang1998)
