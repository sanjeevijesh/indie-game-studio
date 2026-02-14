# 🎮 GameCraft Studios Website

A modern, fully-featured indie game studio website built with HTML, CSS, and JavaScript. This professional website template showcases game development services, upcoming releases, team information, and the complete technology stack used in game development.

![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Key Features

### 🎨 Theme & Design
- **Dark/Light Mode Toggle**: Fully implemented theme switcher with persistent preference storage
  - Optimized contrast ratios for accessibility (WCAG AA compliant)
  - Smooth theme transitions
  - Independent color scheme for each mode
  - All text elements properly visible in both themes
- **Responsive Design**: Seamless experience across desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **RTL/LTR Support**: Built-in language direction toggle for international accessibility

### 🎯 Interactive Features
- **Game Showcase**: Dynamic filtering system with embedded YouTube trailers
- **Mobile Navigation**: Smooth hamburger menu with auto-close functionality
- **Lazy Loading**: Performance-optimized iframe loading for game trailers
- **Scroll Animations**: Intersection Observer API for fade-in effects on scroll
- **Counter Animations**: Animated statistics counters with visibility triggers
- **Smooth Scrolling**: Native browser smooth scrolling for anchor links

### 📋 Forms & Integration
- **Newsletter Integration**: Subscription forms ready for backend integration
- **Contact Forms**: Functional contact form with client-side validation
- **Form Validation**: Built-in validation with user-friendly error handling

### 🔧 Technical Features
- **Custom 404 Page**: User-friendly error page with helpful navigation
- **SEO Ready**: Semantic HTML5 structure with proper meta tags
- **LocalStorage**: Persistent theme and language direction preferences
- **Performance Optimized**: Lazy loading, efficient animations, minimal repaints
- **Cross-Browser Compatible**: Works on all modern browsers

## 📄 Pages Overview

### 1. 🏠 Home (`index.html`)
- **Hero Section**: Eye-catching banner with call-to-action buttons
- **Statistics Section**: Animated counters showcasing studio achievements
- **Game Releases**: Upcoming games with category filtering
  - YouTube trailer embeds with lazy loading
  - Genre-based filtering (All, Metroidvania, Roguelike, Platformer, Action)
  - Smooth fade animations on filter change
- **Testimonials**: Player and partner reviews with star ratings
- **Dev Blog**: Latest development blog post previews
- **Community Hub**: Social media links (Steam, Discord, Twitter, YouTube)
- **Newsletter**: Email subscription form

### 2. 👥 About (`about.html`)
- **Studio Story**: Mission, vision, and founding narrative
- **Core Values**: Philosophy and development principles
- **Team Profiles**: Individual team member showcases
  - Photos, roles, and bios
  - Social media links for each member
- **Milestones**: Studio achievements and timeline

### 3. 🛠️ Tools & Tech (`tools.html`)
- **Game Engines**: Unity, Unreal Engine, Godot
- **Art & Design**: Photoshop, Blender, Aseprite, Krita
- **Programming**: Visual Studio Code, Git, GitHub
- **Audio Production**: FMOD, Audacity, FL Studio
- **Project Management**: Jira, Trello, Notion
- **Complete Tech Stack**: Detailed tool descriptions with features

### 4. 💼 Services (`services.html`)
- **Full Game Development**: End-to-end game creation
- **Game Porting**: Platform optimization and adaptation
- **Art & Assets**: 2D/3D art, animations, UI/UX design
- **Sound Design**: Music composition and audio engineering
- **QA Testing**: Quality assurance and bug tracking
- **Consultation**: Expert guidance and support
- Detailed service cards with feature lists and benefits

### 5. 📧 Contact (`contact.html`)
- **Contact Form**: Name, email, subject, message fields
- **Contact Information**: 
  - Email address
  - Phone number
  - Physical address
  - Office hours
- **Social Links**: All social media platforms
- **Newsletter Signup**: Additional subscription option

### 6. ❓ FAQ (`faq.html`)
- **General Questions**: Studio information
- **Game Development**: Process and timeline queries
- **Technical Support**: Platform and compatibility
- **Business Inquiries**: Partnership and collaboration
- Accordion-style expandable answers

### 7. 📰 Press Kit (`press-kit.html`)
- **Studio Information**: Official company details
- **Downloadable Assets**: Logos, screenshots, artwork
- **Awards & Recognition**: Achievements and accolades
- **Press Coverage**: Media mentions and articles
- **Statistics**: Player count, reviews, reach
- **Contact for Press**: Media inquiry information

### 8. 🔒 Privacy Policy (`privacy-policy.html`)
- **Data Collection**: Information gathering policies
- **Cookie Usage**: Cookie consent and management
- **User Rights**: GDPR/CCPA compliance information
- **Contact Details**: Privacy-related inquiries
- Region-specific information sections

### 9. 🚫 404 Error Page (`404.html`)
- Custom error page design
- Search functionality placeholder
- Quick navigation links
- Helpful suggestions for users
- Maintains consistent branding

## Technologies Used

### Frontend
- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Flexbox, Grid, animations
- **JavaScript (Vanilla)**: ES6+ features, DOM manipulation, event handling

### External Libraries
- **Font Awesome 6.4.0**: Icon library for UI elements
- **Google Fonts**: Typography (system fonts fallback)

### APIs & Integrations
- **YouTube Embed API**: For game trailers
- **Intersection Observer API**: Scroll animations
- **Local Storage API**: RTL/LTR preference persistence

## 📁 File Structure

```
indie-game-studio/
│
├── 📄 index.html                # Homepage with game showcase
├── 📄 about.html                # About page with team info
├── 📄 tools.html                # Tools & Technologies
├── 📄 services.html             # Service offerings
├── 📄 contact.html              # Contact form and info
├── 📄 faq.html                  # Frequently Asked Questions
├── 📄 press-kit.html            # Press and media resources
├── 📄 privacy-policy.html       # Privacy policy and terms
├── 📄 404.html                  # Custom error page
├── 📄 htaccess                  # Apache server configuration
├── 📄 README.md                 # This file
│
├── 📁 css/
│   └── 📄 style.css             # Main stylesheet (~2300 lines)
│       ├── Root variables
│       ├── Base styles
│       ├── Component styles
│       ├── Page-specific styles
│       ├── Dark theme styles
│       ├── RTL support
│       └── Media queries
│
└── 📁 js/
    └── 📄 main.js               # Main JavaScript (~337 lines)
        ├── Mobile navigation
        ├── Game filtering
        ├── Form handling
        ├── Scroll animations
        ├── Counter animations
        ├── Lazy loading
        ├── Theme toggle
        └── RTL toggle
```

## 🚀 Setup Instructions

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, Atom)
- Local web server (for development)

### Quick Start

#### Option 1: Simple File Opening (Limited Functionality)
1. Download and extract the project files
2. Double-click `index.html` to open in your browser
   - ⚠️ Note: Some features may not work due to CORS restrictions

#### Option 2: Local Development Server (Recommended)

**Using Python** (Built-in on Mac/Linux, easy install on Windows):
```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```
Then open: `http://localhost:8000`

**Using Node.js**:
```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server -p 8000
```
Then open: `http://localhost:8000`

**Using PHP**:
```bash
php -S localhost:8000
```
Then open: `http://localhost:8000`

**Using VS Code Live Server Extension**:
1. Install "Live Server" extension in VS Code
2. Right-click `index.html`
3. Select "Open with Live Server"
4. Browser opens automatically

### Production Deployment

#### Apache Server
1. Rename `htaccess` to `.htaccess`
   ```bash
   mv htaccess .htaccess
   ```
2. Upload all files via FTP/SFTP to your web hosting
3. Ensure `.htaccess` is in the root directory
4. Configure custom 404 error page in `.htaccess`:
   ```apache
   ErrorDocument 404 /404.html
   ```
5. Access your domain

#### Nginx Server
Add to your `nginx.conf` or site configuration:
```nginx
server {
    listen 80;
    server_name yourdomain.com;
    root /path/to/indie-game-studio;
    index index.html;

    # Custom 404 page
    error_page 404 /404.html;

    # Cache static assets
    location ~* \.(jpg|jpeg|png|gif|ico|css|js|svg|woff|woff2)$ {
        expires 1y;
        add_header Cache-Control "public, immutable";
    }

    # Gzip compression
    gzip on;
    gzip_types text/css application/javascript application/json;
}
```

#### Static Hosting Platforms

**Netlify**:
1. Push code to GitHub/GitLab
2. Connect repository to Netlify
3. Build settings:
   - Build command: (leave empty)
   - Publish directory: `/` or `.`
4. Deploy!

**Vercel**:
1. Push code to GitHub/GitLab
2. Import project in Vercel
3. Framework preset: "Other"
4. Deploy!

**GitHub Pages**:
1. Push code to GitHub repository
2. Go to Settings → Pages
3. Source: Deploy from branch
4. Branch: `main` or `master`, folder: `/ (root)`
5. Save and wait for deployment

**Cloudflare Pages**:
1. Push code to GitHub/GitLab
2. Connect repository to Cloudflare Pages
3. Build settings: None (static site)
4. Deploy!

### Environment-Specific Configuration

**For Production**:
- Update all placeholder content (images, text, links)
- Replace example email addresses with real ones
- Configure actual backend endpoints for forms
- Add Google Analytics or tracking code
- Update meta tags for SEO
- Add real social media links
- Replace placeholder team photos
- Update copyright year

## 🔧 Troubleshooting

### Common Issues

#### Theme Toggle Not Working
**Problem**: Dark mode toggle doesn't switch themes
**Solution**: 
- Check browser console for JavaScript errors
- Ensure `main.js` is loaded correctly
- Clear browser cache and LocalStorage
- Verify `data-theme` attribute is being set on `<html>` element

#### Forms Not Submitting
**Problem**: Contact/newsletter forms show alerts but don't send data
**Solution**: 
- Forms are frontend-only by default
- Implement backend API endpoint (see "Adding Backend Functionality")
- Or integrate with third-party service (FormSpree, Netlify Forms, etc.)

#### Images Not Loading
**Problem**: Placeholder images from Unsplash not showing
**Solution**: 
- Replace Unsplash URLs with your own images
- Check internet connection (Unsplash URLs require internet)
- Verify image URLs are correct and accessible

#### YouTube Videos Not Loading
**Problem**: Embedded videos show errors
**Solution**: 
- Check if video URLs are correct
- Verify videos are not region-restricted
- Ensure proper iframe embed code from YouTube
- Check if AdBlocker is interfering

#### Animations Not Smooth
**Problem**: Scroll animations or transitions are janky
**Solution**: 
- Check browser performance/hardware acceleration
- Reduce animation complexity in CSS
- Use `will-change` property sparingly
- Test on different devices

#### Mobile Menu Not Closing
**Problem**: Hamburger menu stays open after clicking links
**Solution**: 
- Check JavaScript console for errors
- Verify event listeners are attached correctly
- Clear browser cache
- Test in incognito/private mode

#### RTL Toggle Not Working
**Problem**: Language direction doesn't switch
**Solution**: 
- Clear LocalStorage: `localStorage.clear()`
- Check browser console for errors
- Verify `dir` attribute is being set on `<html>`

### Browser Compatibility Issues

**Internet Explorer**:
- This website uses modern JavaScript (ES6+)
- IE11 and below are not supported
- Consider adding polyfills if IE support is required

**Safari**:
- Some CSS features may need `-webkit-` prefix
- Test thoroughly on Safari/iOS Safari

### Performance Issues

**Slow Page Load**:
- Enable lazy loading for images
- Optimize image file sizes (use WebP format)
- Minify CSS and JavaScript
- Enable Gzip compression on server
- Use CDN for static assets

**Memory Leaks**:
- Remove event listeners properly
- Clean up observers when elements are removed
- Don't create too many animation loops

## 🎨 Customization Guide

### Theme Customization

The website features both **Light Mode** (default) and **Dark Mode** themes. Both can be customized independently.

#### Light Mode Colors
Edit these CSS variables in `:root` (around line 8 in `style.css`):
```css
:root {
    --primary-color: #2563eb;      /* Main brand color (blue) */
    --secondary-color: #1e293b;    /* Dark accent */
    --text-color: #334155;         /* Body text */
    --light-bg: #f8fafc;           /* Light backgrounds */
    --white: #ffffff;              /* White surfaces */
    --border-color: #e2e8f0;       /* Borders and dividers */
    --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
    --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
}
```

#### Dark Mode Colors
Edit these CSS variables in `[data-theme="dark"]` (around line 1535 in `style.css`):
```css
[data-theme="dark"] {
    --primary-color: #3b82f6;      /* Brighter blue for dark mode */
    --secondary-color: #f8fafc;    /* Light text */
    --text-color: #e2e8f0;         /* Body text (light) */
    --light-bg: #1e293b;           /* Dark backgrounds */
    --white: #0f172a;              /* Dark surfaces */
    --border-color: #334155;       /* Dark borders */
    --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.3);
    --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.4);
}
```

### Branding

**Update Logo and Studio Name**:
1. Find and replace "GameCraft Studios" in all HTML files
2. Modify the logo icon in the `.logo` class (line 55-67 in `style.css`)
3. Update favicon and social media preview images

**Update Fonts**:
```css
body {
    font-family: 'Your Font', 'Segoe UI', Tahoma, sans-serif;
}
```

### Content Updates

**Games Section** (`index.html`):
```html
<div class="game-card" data-category="your-genre">
    <div class="game-trailer">
        <iframe src="YOUR_YOUTUBE_URL"></iframe>
    </div>
    <div class="game-info">
        <h3>Your Game Title</h3>
        <p class="game-genre">Genre</p>
        <p class="game-desc">Description</p>
        <!-- ... -->
    </div>
</div>
```

**Add New Game Categories**:
1. Add filter button in HTML: `<button class="filter-btn" data-filter="new-category">New Category</button>`
2. Add category to game cards: `data-category="new-category"`

**Team Members** (`about.html`):
- Replace placeholder images with real team photos
- Update names, roles, and bio text
- Modify social media links

**Services** (`services.html`):
- Customize service offerings
- Add/remove service cards
- Update pricing or features

**Contact Information** (`contact.html`):
- Update email, phone, address
- Modify office hours
- Change map embed (if adding one)

### Adding Backend Functionality

**Contact Form**:
```javascript
// In js/main.js, replace the alert with actual API call
// Example with fetch API:
fetch('/api/contact', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify(formData)
})
.then(response => response.json())
.then(data => console.log(data));
```

**Newsletter Subscription**:
```javascript
// Similar approach for newsletter forms
fetch('/api/subscribe', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify({ email: email })
});
```

## 🔧 Features Breakdown

### JavaScript Functionality (`main.js`)

1. **Mobile Navigation** (Lines 2-26)
   - Hamburger menu toggle with smooth animation
   - Auto-close on navigation link click
   - Click-outside-to-close functionality
   - Transition effects for menu items

2. **Game Filtering System** (Lines 28-68)
   - Category-based dynamic filtering
   - Smooth fade-in/fade-out transitions
   - Active button state management
   - Multi-category support per game card

3. **Smooth Scrolling** (Lines 70-85)
   - Anchor link smooth scroll behavior
   - Browser-native implementation
   - Fallback for older browsers

4. **Dynamic Header Shadow** (Lines 87-101)
   - Shadow intensity changes based on scroll position
   - Enhances visual depth on scroll

5. **Form Handling** (Lines 103-146)
   - Contact form submission with validation
   - Newsletter subscription processing
   - Form reset after submission
   - Ready for backend API integration

6. **Scroll Animations** (Lines 148-173)
   - Intersection Observer API implementation
   - Fade-in effects on scroll into view
   - Optimized performance with threshold settings
   - Applied to cards, sections, and items

7. **Counter Animation** (Lines 175-213)
   - Animated statistics counters
   - Triggers when section becomes visible
   - Smooth counting animation
   - Prevents re-animation on subsequent views

8. **Lazy Loading** (Lines 215-231)
   - YouTube iframe lazy loading
   - Loads videos only when near viewport
   - Significant performance improvement
   - Reduces initial page load time

9. **Active Page Indicator** (Lines 233-239)
   - Highlights current page in navigation
   - Automatic detection based on URL
   - Visual feedback for user orientation

10. **Page Load Animation** (Lines 241-248)
    - Smooth fade-in on page load
    - Prevents flash of unstyled content
    - Professional loading experience

11. **RTL Toggle** (Lines 250-271)
    - Language direction switching (RTL/LTR)
    - LocalStorage persistence
    - Maintains preference across sessions
    - Smooth 360° rotation animation

12. **Dark/Light Theme Toggle** (Lines 273-309) ⭐ NEW
    - Seamless theme switching
    - LocalStorage preference persistence
    - Smooth icon transition (moon ↔ sun)
    - Loads saved theme on page load
    - 360° rotation animation on toggle
    - Applies `data-theme="dark"` attribute to `<html>`

13. **FAQ Accordion** (Lines 311-334)
    - Expandable/collapsible question answers
    - Auto-close other items when opening new one
    - Smooth height transition
    - Icon rotation on toggle

### CSS Architecture (`style.css`)

#### Core Styles (Lines 1-175)
- CSS Variables for theming
- Reset and base styles
- Typography system
- Button components
- Utility classes

#### Layout Components (Lines 176-530)
- Header and navigation
- Hero sections
- Statistics grid
- Game cards
- Testimonials
- Blog cards
- Community section
- Footer

#### Page-Specific Styles (Lines 530-1534)
- About page
- Tools page
- Services page
- Contact page
- FAQ page
- Press Kit page
- Privacy Policy page
- 404 Error page

#### Dark Theme Styles (Lines 1535-1760) ⭐ NEW
- Complete dark mode color overrides
- Proper contrast ratios for accessibility
- Independent theming for all components
- Text visibility optimizations:
  - All headings (h1-h6) → `#f1f5f9`
  - Body text → `#e2e8f0`
  - Muted text → `#cbd5e1`
  - Footer text → `#e2e8f0`
  - Link colors → `#3b82f6`
  - Button visibility fixes
  - Community icon colors
  - Form input styling

#### Theme Toggle Button (Lines 1678-1719)
- Fixed position styling
- Hover effects
- RTL support
- Mobile responsive positioning
- Icon styling

#### RTL Support (Throughout)
- Bidirectional layout support
- Text alignment adjustments
- Icon positioning
- Navigation reversals

#### Responsive Design (Lines 1761-2300)
- Mobile breakpoint (< 768px)
- Tablet breakpoint (768px - 1024px)
- Desktop optimization (> 1024px)
- Touch-friendly tap targets
- Responsive typography
- Flexible grids and layouts

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimizations

1. **Lazy Loading**: iframes load only when visible
2. **CSS Optimization**: Efficient selectors and minimal repaints
3. **JavaScript Optimization**: Event delegation and debouncing
4. **Browser Caching**: Configured via .htaccess
5. **Smooth Animations**: Hardware-accelerated transforms

## ♿ Accessibility

- ✅ **Semantic HTML5**: Proper element usage for screen readers
- ✅ **ARIA Labels**: Where appropriate for interactive elements
- ✅ **Keyboard Navigation**: Full keyboard accessibility
- ✅ **Focus Indicators**: Visible focus states for all interactive elements
- ✅ **Alt Text**: Descriptive alt text for all images
- ✅ **Color Contrast**: WCAG AA compliant in both light and dark modes
  - Light mode: Dark text on light backgrounds
  - Dark mode: Light text on dark backgrounds with optimized contrast
- ✅ **RTL Language Support**: Right-to-left text direction
- ✅ **Responsive Text**: Scalable font sizes
- ✅ **Skip Links**: Easy navigation for screen reader users
- ✅ **Form Labels**: Proper label associations
- ✅ **Reduced Motion**: Respects `prefers-reduced-motion` (future enhancement)

## 🌟 What's New in Version 2.0

### ✨ Dark Mode Implementation
- **Theme Toggle Button**: Fixed-position theme switcher
- **Persistent Preferences**: Saves theme choice in LocalStorage
- **Optimized Contrast**: All text elements properly visible in dark mode
  - Footer text and links fully readable
  - Community section icons visible
  - "Get In Touch" button properly displayed
  - All headings, paragraphs, and UI elements optimized
- **Smooth Transitions**: Seamless switching between themes
- **Icon Animation**: 360° rotation on theme change

### 🎯 Additional Pages
- FAQ page with accordion functionality
- Press Kit page for media resources
- Privacy Policy page for compliance

### 🐛 Bug Fixes
- Fixed low contrast issues in dark mode footer
- Fixed invisible community icons in dark mode
- Fixed secondary button visibility in dark mode hero section
- Improved text readability across all sections

## 🚀 Future Enhancements

Potential features to add:
- [ ] Backend API integration for contact and newsletter forms
- [ ] Blog system with CMS integration (WordPress, Strapi, or custom)
- [ ] Game release countdown timers with real-time updates
- [ ] Multi-language support (i18n) with language switcher
- [x] ~~Dark mode toggle~~ ✅ **COMPLETED**
- [ ] Advanced search functionality for games and content
- [ ] User authentication system for community features
- [ ] Game download portal with version management
- [ ] Community forum integration (Discourse, phpBB)
- [ ] Analytics integration (Google Analytics, Plausible)
- [ ] Newsletter email automation (Mailchimp, SendGrid)
- [ ] Social media feed integration
- [ ] Live chat support widget
- [ ] Game rating and review system
- [ ] Wishlisting functionality
- [ ] Achievement/Trophy showcase
- [ ] Developer diary with markdown support
- [ ] Video devlog integration
- [ ] Patreon/Ko-fi supporter integration
- [ ] Steam/Epic Games Store API integration
- [ ] Discord widget for live member count

## License

This is a template project. Customize and use as needed for your game studio website.

## 📞 Support & Contact

For questions, issues, or customization requests:
- 📧 Email: hello@gamecraftstudios.com
- 🌐 Website: [Your Domain]
- 💬 Discord: [Your Discord Server]
- 🐦 Twitter: [@YourStudio]

## 🙏 Credits

- **Design & Development**: GameCraft Studios Website Template
- **Icons**: [Font Awesome 6.4.0](https://fontawesome.com/)
- **Placeholder Images**: [Unsplash](https://unsplash.com/)
- **Video Embeds**: YouTube Embed API
- **Fonts**: System font stack (Segoe UI, Roboto, San Francisco, etc.)

## 📜 License

This is a template project. Feel free to customize and use for your game studio website.

**MIT License** - See LICENSE file for details

## 🏆 Acknowledgments

Special thanks to the indie game development community for inspiration and feedback.

---

<div align="center">

**Version**: 2.0.0  
**Last Updated**: February 11, 2026  
**Changelog**:
- v2.0.0: Added dark/light theme toggle, FAQ page, Press Kit page, Privacy Policy page, fixed contrast issues
- v1.0.0: Initial release with all core pages and features

Made with ❤️ for indie game developers

[⬆ Back to Top](#-gamecraft-studios-website)

</div>
