# Tysan Clan Website - Design Guide

## 🎨 Color Palette

### Primary Colors
- **Tysan Orange**: `#ff6600` - Main brand color, used for headings, links, and accents
- **Orange Light**: `#ff8833` - Hover states and secondary headings
- **Orange Dark**: `#cc5200` - Active/pressed states

### Background Colors
- **Dark Background**: `#0a0a0a` - Main page background (with gradient)
- **Dark Card**: `#1a1a1a` - Content panel background
- **Card Hover**: `#252525` - Content panel on hover

### Text Colors
- **Text Light**: `#e0e0e0` - Primary text color
- **Text Muted**: `#999999` - Secondary text, lead paragraphs, footer

## 🏗️ Layout Structure

```
┌─────────────────────────────────────────────┐
│  Navigation Bar (Dark + Orange Border)      │
│  - Logo (Orange, uppercase)                 │
│  - Menu items (Light text, orange hover)   │
└─────────────────────────────────────────────┘
│                                             │
│  ┌───────────────────────────────────────┐ │
│  │                                       │ │
│  │  Content Panel (Dark card)           │ │
│  │  - Orange border with glow           │ │
│  │  - Rounded corners                   │ │
│  │  - Shadow effects                    │ │
│  │                                       │ │
│  └───────────────────────────────────────┘ │
│                                             │
┌─────────────────────────────────────────────┐
│  Footer (Dark + Orange Top Border)          │
│  - Copyright | Links                        │
└─────────────────────────────────────────────┘
```

## 📝 Typography

### Headings
- **H1**: 2.5rem (2rem mobile)
  - Color: Tysan Orange
  - Bottom border: 3px solid orange
  - Weight: 700

- **H2**: 2rem (1.5rem mobile)
  - Color: Orange Light
  - Weight: 700

- **H3-H6**: 
  - Color: Tysan Orange
  - Weight: 700

### Body Text
- **Font Family**: System font stack (-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, etc.)
- **Line Height**: 1.8
- **Color**: Light (#e0e0e0)

### Special Text
- **Lead Paragraph**: 1.25rem, light weight, muted color
- **Links**: Orange with underline on hover
- **Code**: Orange light on dark background

## 🎭 Component Styles

### Navigation
```
Properties:
- Background: rgba(10, 10, 10, 0.95) with backdrop blur
- Border bottom: 2px solid orange
- Box shadow: Orange glow (0.3 opacity)
- Transitions: 0.3s ease

Hover Effects:
- Brand: Lighter orange + text shadow glow
- Links: Orange text + subtle background
```

### Content Panels
```
Properties:
- Background: #1a1a1a
- Border: 1px solid orange (0.2 opacity)
- Border radius: 12px
- Padding: 3rem (1.5rem mobile)
- Box shadow: Dark with orange glow on hover

Hover Effects:
- Enhanced shadow with orange glow
- Brighter border (0.4 opacity)
```

### Buttons
```
Primary Button:
- Background: Tysan Orange
- Text: White
- Padding: 0.75rem 1.5rem
- Border radius: 6px

Hover:
- Background: Orange Light
- Box shadow: Orange glow
- Transform: translateY(-2px)
```

### Tables
```
Header:
- Background: Orange (0.2 opacity)
- Border bottom: 2px solid orange
- Text: Orange

Rows:
- Hover: Orange background (0.1 opacity)
- Border: Orange (0.1 opacity)
```

### Lists
```
Unordered/Ordered:
- Line height: 1.8
- Item spacing: 0.5rem

Blockquotes:
- Left border: 4px solid orange
- Padding left: 1.5rem
- Italic style
- Muted color
```

## 🎬 Animations & Transitions

### Standard Transition
```scss
transition: all 0.3s ease;
```

Used for:
- Navigation links
- Content panels
- Buttons
- Links
- Cards

### Hover Effects
- **Navigation**: Color change + background tint
- **Content Panels**: Enhanced shadow + border glow
- **Buttons**: Color shift + lift effect (translateY)
- **Links**: Color change + underline
- **Tables**: Background tint on rows

## 📱 Responsive Breakpoints

### Mobile (max-width: 768px)
- H1: 2rem (from 2.5rem)
- H2: 1.5rem (from 2rem)
- Content panel padding: 1.5rem (from 3rem)
- Content panel margin: 1rem (from 2rem)

### Navigation
- Mobile menu toggles at 992px (Bootstrap 5 default)
- Hamburger icon: Orange custom SVG

## 🎯 Key Design Principles

1. **Dark Theme**: Professional dark background with proper contrast
2. **Orange Accents**: Strategic use of brand color for emphasis
3. **Subtle Glows**: Orange glow effects on borders and shadows
4. **Smooth Transitions**: All interactive elements have smooth 0.3s transitions
5. **Hover Feedback**: Clear visual feedback on all interactive elements
6. **Readability**: High contrast text (e0e0e0 on dark) with generous line-height (1.8)
7. **Modern Aesthetics**: Backdrop blur, rounded corners, layered shadows
8. **Responsive**: Mobile-first approach with appropriate breakpoints

## 🔧 Customization

To change the brand color, modify these variables in `css/main.scss`:

```scss
$tysan-orange: #ff6600;        // Main brand color
$tysan-orange-light: #ff8833;  // Lighter variant
$tysan-orange-dark: #cc5200;   // Darker variant
```

All orange accents throughout the site will automatically update.

## 📦 Dependencies

- **Bootstrap 5.3.0**: Grid system, utilities, components
- **Jekyll 4.4.1**: Static site generator
- **Sass**: CSS preprocessing

## 🌐 Browser Support

The design uses modern CSS features supported by:
- Chrome/Edge 88+
- Firefox 85+
- Safari 14+
- All modern mobile browsers

Features used:
- CSS Custom Properties (variables)
- Backdrop filter
- CSS Grid & Flexbox
- CSS Transitions & Transforms
- Linear gradients

---

**Design completed: January 15, 2026**

