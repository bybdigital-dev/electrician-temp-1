# Riakona Electrical Solutions and Projects Website

## Overview

This is a static website for Riakona Electrical Solutions and Projects, an electrician business. The website features a modern, animated design with electrical-themed visual effects including circuit lines, sparks, and glowing animations. It's built as a single-page application with multiple sections showcasing services, projects, reviews, and contact information. The site emphasizes visual appeal with smooth animations and responsive design to attract potential customers in the electrical services industry.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static HTML/CSS/JavaScript**: Pure client-side implementation with no backend dependencies
- **Single Page Application**: All content contained in index.html with section-based navigation
- **Component-Based CSS**: Modular stylesheets separated into main.css for core styles and animations.css for motion effects
- **Mobile-First Design**: Responsive layout with mobile navigation toggle and breakpoint-based styling

### Styling Framework
- **CSS Custom Properties**: Centralized color scheme and design tokens using CSS variables
- **Google Fonts Integration**: Inter for body text and Orbitron for brand elements
- **Font Awesome Icons**: Icon library for electrical and UI symbols
- **Animation System**: Custom keyframe animations for electrical effects (sparks, circuit lines, power pulses)

### JavaScript Architecture
- **Vanilla JavaScript**: No frameworks or libraries, pure DOM manipulation
- **Module Pattern**: Organized into initialization functions for different features
- **Event-Driven**: Scroll-based animations, navigation interactions, and form handling
- **Progressive Enhancement**: Core functionality works without JavaScript, animations enhance the experience

### Navigation System
- **Smooth Scrolling**: CSS and JavaScript-powered section navigation
- **Active State Management**: Dynamic highlighting of current section in navigation
- **Mobile Menu**: Hamburger-style toggle for responsive navigation
- **Scroll Effects**: Navbar styling changes based on scroll position

### Content Sections
- **Hero Section**: Full-screen banner with animated electrical effects and call-to-action buttons
- **Services Grid**: Animated service cards with hover effects
- **Projects Gallery**: Image showcase with lightbox or hover animations
- **Reviews Carousel**: Customer testimonials with rating display
- **Contact Form**: Client inquiry capture with validation

## External Dependencies

### Content Delivery Networks
- **Google Fonts API**: Inter and Orbitron font families for typography
- **Font Awesome CDN**: Icon library for electrical and interface symbols
- **Version**: Font Awesome 6.4.0 for modern icon support

### Browser APIs
- **Intersection Observer**: For scroll-based animations and section detection
- **CSS Custom Properties**: For dynamic theming and consistent design tokens
- **CSS Grid and Flexbox**: For responsive layout management
- **CSS Animations**: For electrical effects and interactive elements

### No Backend Dependencies
- Pure static website requiring only web server for hosting
- No database, server-side processing, or API integrations
- Contact form would require external service integration for submission handling
- Images and assets served directly from file system