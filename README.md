# Health & AI Summit 2025 - Landing Page

A modern, responsive landing page for the Health & AI Summit 2025 hosted by Paveway Ltd. This project features a professional design with video background, interactive countdown timer, and comprehensive event information.

## 🚀 Live Demo

Open `index.html` in your browser or serve it using a local web server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## ✨ Features

### 📱 Responsive Design
- Fully responsive layout that works on desktop, tablet, and mobile devices
- Mobile-first approach with progressive enhancement
- Optimized touch interactions for mobile users

### 🎥 Video Background
- Full-screen video background in hero section
- Semi-transparent dark overlay for text readability
- Fallback background image for mobile devices

### ⏰ Live Countdown Timer
- Real-time countdown to August 5, 2025 at 9:00 AM EST
- Updates every second with days, hours, minutes, and seconds
- Beautiful animated display with glassmorphism effects

### 🎨 Modern UI/UX
- Clean, professional design with beautiful typography
- Smooth animations and hover effects
- Custom scrollbar and scroll-triggered animations
- Glassmorphism and gradient effects

### 📧 Interactive Contact Form
- Validated contact form with email verification
- Real-time notifications for user feedback
- Smooth form animations and error handling

### 🔗 Smooth Navigation
- Fixed header with smooth scrolling navigation
- Mobile hamburger menu with slide animations
- Auto-hiding header on scroll down, appearing on scroll up

## 📋 Event Information

- **Event**: Health & AI Summit 2025
- **Host**: Paveway Ltd
- **Date**: August 5, 2025
- **Time**: 9:00 AM EST
- **Location**: New York City, USA

## 🏗️ Project Structure

```
├── index.html          # Main HTML file with semantic structure
├── styles.css          # Comprehensive CSS with responsive design
├── script.js           # JavaScript for interactivity and countdown
└── README.md           # Project documentation
```

## 🎯 Sections Included

1. **Header Navigation** - Fixed header with logo and navigation menu
2. **Hero Section** - Video background with event title and call-to-action buttons
3. **Countdown Timer** - Live countdown to the event date
4. **Why Attend** - 6 compelling reasons to attend the summit
5. **Topics** - 8 key topics that will be covered at the event
6. **Speakers** - 4 featured speakers with photos and bios
7. **Contact Form** - Interactive form for inquiries
8. **Footer** - Company information and social links

## 🎨 Design Features

### Color Palette
- Primary Blue: `#2563eb` (Professional and trustworthy)
- Success Green: `#10b981` (Health and growth)
- Warning Amber: `#fbbf24` (Attention and energy)
- Dark Gray: `#1f2937` (Professional and modern)

### Typography
- Font Family: Inter (Modern, clean, and highly readable)
- Responsive font sizes with proper hierarchy
- Optimized line heights and letter spacing

### Animations
- Fade-in animations on scroll
- Smooth hover effects on cards and buttons
- Parallax effect on hero section (desktop only)
- Slide-in notifications

## 📱 Mobile Optimization

- Hamburger menu for mobile navigation
- Touch-friendly button sizes (minimum 44px)
- Optimized images and video fallbacks
- Reduced motion for performance on mobile
- Mobile-specific layout adjustments

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and accessibility
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript ES6+** - Interactive functionality
- **Font Awesome** - Professional icons
- **Google Fonts** - Inter typography
- **Unsplash API** - High-quality placeholder images

## ⚡ Performance Features

- Optimized images with proper sizing
- Lazy loading for non-critical resources
- Preloading of critical assets
- Efficient CSS animations
- Mobile video fallbacks

## 🔧 Customization

### Changing the Event Date
Update the countdown timer target date in `script.js`:
```javascript
const targetDate = new Date('August 5, 2025 09:00:00 EST').getTime();
```

### Updating Content
All content is easily editable in `index.html`. No placeholder text is used - everything is professionally written and relevant to the healthcare AI theme.

### Styling Modifications
The CSS is well-organized with clear section comments. Key variables for colors and spacing can be found at the top of each section.

## 🌐 Browser Support

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Contact Information

For questions about the Health & AI Summit 2025:
- Email: info@pavewayltd.com
- Location: New York City, USA

---

*"Empowering the Future of Health, One Innovation at a Time."* - Paveway Ltd
