# iPortfolio - Anish Gupta

A modern, responsive portfolio website for Anish Gupta, built with HTML5, CSS3, JavaScript, and Bootstrap 5.3.3. This site showcases professional experience, technical skills, projects, and services, with a sleek glassmorphism-inspired design and interactive UI elements.

![Portfolio Preview](./assets/img/WhatsApp%20Image%202025-06-12%20at%2020.46.27_0b4ba1bd.jpg)

## 🚀 Features

- Modern glassmorphism and neon-glow UI
- Responsive, mobile-first layout
- Smooth scrolling, transitions, and floating animations
- Dynamic typing animation in the hero section
- Filterable portfolio gallery with lightbox
- Animated statistics and counters
- Contact form with Netlify Forms integration (no backend required)
- Google Maps integration
- Social media links and direct contact info

## 📂 Main Sections

1. **Hero** – Name, dynamic typing, bold intro, full-screen background
2. **About** – Professional summary, personal info, contact details
3. **Skills** – Card-based layout, tag-style skills, frontend/backend/frameworks/design
4. **Resume** – Education, professional experience, hackathon/freelance history
5. **Portfolio** – Filterable gallery, project cards, lightbox, project details
6. **Services** – Service cards with icons and descriptions
7. **Contact** – Netlify-powered form, Google Maps, social links

## 🛠️ Technologies Used

- HTML5, CSS3, JavaScript (ES6+)
- Bootstrap 5.3.3
- AOS (Animate On Scroll)
- Typed.js (typing animation)
- Isotope (portfolio filtering)
- GLightbox (image lightbox)
- Swiper (testimonials carousel)
- Waypoints, PureCounter (scroll/number animations)
- Bootstrap Icons
- Google Fonts: Roboto, Poppins, Raleway

## 📁 Project Structure

```
iPortfolio-1.0.0/
├── index.html              # Main website file
├── thank-you.html          # Netlify form redirect page
├── service-details.html    # Service details (optional)
├── starter-page.html       # Starter template (optional)
├── assets/
│   ├── css/
│   │   └── main.css
│   ├── js/
│   │   └── main.js
│   ├── img/                # Images, portfolio, testimonials
│   ├── scss/               # SCSS source files
│   └── vendor/             # Third-party libraries
│       ├── aos/
│       ├── bootstrap/
│       ├── bootstrap-icons/
│       ├── glightbox/
│       ├── isotope-layout/
│       ├── swiper/
│       ├── typed.js/
│       └── waypoints/
└── forms/
    └── contact.php         # (Legacy, not used with Netlify)
```

## ⚙️ Getting Started

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd iPortfolio-1.0.0
   ```
2. **Open in your browser**
   - Open `index.html` directly, or
   - Use a local server:
     ```bash
     # Python
     python -m http.server 8000
     # or Node.js
     npx serve
     ```
3. **Deploy to Netlify**
   - Connect your GitHub repo to Netlify
   - Set the publish directory to `iPortfolio-1.0.0` (or project root)
   - Netlify will auto-detect the contact form and handle submissions

## 📝 Customization

- Update `index.html` with your info, skills, and projects
- Replace images in `assets/img/`
- Edit `main.css` for color/theme tweaks
- Add or update portfolio/service items as needed

## 💡 Netlify Contact Form Setup

- The contact form uses Netlify Forms (no backend required)
- After submission, users are redirected to `thank-you.html`
- Make sure `thank-you.html` is present in the project root and deployed
- Form submissions appear in your Netlify dashboard

## 📄 License

MIT License. See LICENSE for details.

---

**Anish Gupta**  
Email: anishgupta4099@gmail.com  
LinkedIn: [Anish Gupta](https://www.linkedin.com/in/anish-gupta-696245324)  
GitHub: [anishgupta6801](https://github.com/anishgupta6801)

*Last updated: July 3, 2025*

2. **About**
   - Professional summary
   - Personal information
   - Contact details

3. **Skills**
   - Modern card-based layout
   - Tag-style skill representation
   - Two main categories:
     - Programming Languages & Frameworks
     - Design & Prototyping
   - Interactive hover effects

4. **Resume**
   - Educational background (BCA)
   - Professional experience
   - Social Media Ambassador role
   - Freelance work history

5. **Portfolio**
   - Filterable project gallery
   - Interactive project cards
   - Lightbox image viewing
   - Project details modal

6. **Services**
   - Service cards with icons
   - Detailed service descriptions
   - Interactive hover effects

7. **Contact**
   - Contact form with validation
   - Google Maps integration
   - Social media links
   - Direct contact information

## 🛠 Technologies Used

### Frontend
- HTML5
- CSS3 with modern features
- JavaScript (ES6+)
- Bootstrap 5.3.3

### Libraries & Frameworks
- AOS (Animate On Scroll)
- Typed.js (Text animation)
- Isotope (Portfolio filtering)
- GLightbox (Image lightbox)
- Swiper (Testimonials carousel)
- Waypoints (Scroll triggers)
- PureCounter (Statistics animation)

### Icons & Fonts
- Bootstrap Icons
- Google Fonts:
  - Roboto
  - Poppins
  - Raleway

## 📦 Project Structure

```
iPortfolio/
├── index.html                 # Main website file
├── portfolio-details.html     # Portfolio item details
├── service-details.html       # Service details
├── assets/
│   ├── css/
│   │   └── main.css          # Main stylesheet
│   ├── js/
│   │   └── main.js           # Main JavaScript file
│   ├── img/                   # Image assets
│   │   ├── portfolio/        # Portfolio images
│   │   └── testimonials/     # Testimonial images
│   ├── scss/                 # SCSS source files
│   └── vendor/               # Third-party libraries
│       ├── aos/              # Animate On Scroll
│       ├── bootstrap/        # Bootstrap framework
│       ├── bootstrap-icons/  # Bootstrap icons
│       ├── glightbox/        # Lightbox library
│       ├── isotope-layout/   # Portfolio filtering
│       ├── swiper/           # Testimonials slider
│       ├── typed.js/         # Typing animation
│       └── waypoints/        # Scrolling animations
└── forms/
    └── contact.php           # Contact form handler

```

## ⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   ```

2. **Navigate to project directory**
   ```bash
   cd iPortfolio
   ```

3. **Open in browser**
   - Open `index.html` in a modern web browser
   - Or use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve
     ```

## 🎨 Customization

### Colors
The website uses a carefully chosen color palette that can be customized in `assets/css/main.css`:
- Primary: Custom dark theme with glassmorphism
- Accent: Neon effects for highlights
- Background: Dark gradients with overlay effects

### Content
1. Update `index.html` with your personal information
2. Replace images in `assets/img/` with your own
3. Modify portfolio items in the Portfolio section
4. Update resume information in the Resume section
5. Customize services in the Services section

### Styling
1. Main styles are in `assets/css/main.css`
2. Custom animations can be added in the CSS file
3. Bootstrap classes can be modified for layout changes

## 🚀 Performance Optimizations

- Optimized image loading with lazy loading
- Minified CSS and JavaScript files
- Efficient animation handling with AOS
- Browser compatibility fixes
- Mobile-first responsive design

## 🔐 Browser Compatibility

Tested and working on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS/Android)

## 👥 Credits

- Design Template: iPortfolio by BootstrapMade
- Icons: Bootstrap Icons
- Images: Custom and portfolio work
- Animations: AOS Library

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🤝 Contact

Anish Gupta
- Email: anishgupta4099@gmail.com
- LinkedIn: [Anish Gupta](https://www.linkedin.com/in/anish-gupta-696245324)
- GitHub: [anishgupta6801](https://github.com/anishgupta6801)

---

*Last Updated: June 21, 2025*
