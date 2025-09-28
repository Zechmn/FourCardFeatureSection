# Four Card Feature Section

## Overview

This is a static HTML/CSS project implementing a responsive feature section layout with four cards. The project showcases AI-powered tools through an elegant card-based design with colored accent bars and icons. It follows a Frontend Mentor challenge pattern, focusing on modern CSS techniques including CSS Grid, Flexbox, and responsive design principles. The layout adapts from a diamond-shaped desktop arrangement to a stacked mobile layout.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static Site Structure**: Pure HTML5 and CSS3 implementation without JavaScript frameworks
- **Responsive Design Pattern**: Mobile-first approach using CSS Grid for desktop layout and Flexbox for alignment
- **Component-Based Styling**: BEM (Block Element Modifier) methodology for CSS class naming and organization
- **CSS Custom Properties**: Centralized color management through CSS variables for consistent theming

### Layout System
- **Grid-Based Cards Layout**: CSS Grid creates the distinctive diamond pattern on desktop with three columns
- **Flexible Container**: Centered container with max-width constraints and responsive padding
- **Card Component Design**: Each card features colored top borders, content sections, and icon positioning
- **Typography Hierarchy**: Multi-weight font system using Inter font family with distinct heading and body text styling

### Responsive Behavior
- **Breakpoint Strategy**: Single major breakpoint transitioning from mobile stack to desktop grid
- **Adaptive Spacing**: Fluid spacing system using relative units and CSS clamp for optimal viewing
- **Icon and Image Handling**: Responsive images with proper alt text and consistent sizing across devices

### Visual Design System
- **Color Palette**: Four distinct accent colors (cyan, red, orange, blue) with neutral grays and whites
- **Shadow and Elevation**: Subtle box-shadows providing depth without overwhelming the clean aesthetic
- **Border Radius**: Consistent 8px border radius across all card elements for modern appearance

## External Dependencies

### Fonts
- **Inter Font Family**: Primary typeface loaded via system font stack fallback
- **Google Fonts (Poppins)**: Referenced in style guide as alternative font option

### Assets
- **Static Images**: Local icon files (supervisor, team-builder, karma, calculator icons)
- **Favicon**: 32x32 PNG favicon for browser tab identification
- **No External CDNs**: All assets are self-hosted for offline functionality

### Browser Compatibility
- **Modern CSS Features**: Utilizes CSS Grid, Flexbox, and Custom Properties
- **Progressive Enhancement**: Graceful degradation for older browsers through fallback fonts and layout methods
