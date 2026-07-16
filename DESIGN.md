# Design System — Transways India Corporation

## Overview
Light and modern design system for a pan-India trucking & logistics platform. Built on clean typography, generous spacing, and a professional blue accent color.

## Colors

### Core Palette
- **Primary**: `#0066cc` (Modern Blue)
- **Primary Dark**: `#0052a3` (Darker Blue for hover states)
- **Secondary**: `#00a8ff` (Bright Sky Blue)
- **Accent**: `#f97316` (Orange for CTAs and highlights)
- **Success**: `#22c55e` (Green for positive states)
- **Warning**: `#eab308` (Yellow for alerts)

### Text Colors
- **Text**: `#1a202c` (Charcoal — main body text)
- **Text Light**: `#718096` (Gray — secondary labels)
- **Text Lighter**: `#a0aec0` (Light Gray — captions, footer)

### Backgrounds
- **Background**: `#ffffff` (White — main)
- **Background Light**: `#f7fafc` (Off-white — alternate sections)
- **Background Alt**: `#edf2f7` (Light Gray-Blue — hero section)

### Borders & Shadows
- **Border**: `#e2e8f0` (Light Gray)
- **Shadow Light**: `rgba(0, 0, 0, 0.1)` — card hover effects
- **Shadow Brand**: `rgba(0, 102, 204, 0.3)` — primary button hover

### Footer
- **Background**: `#1a202c` (Dark charcoal)
- **Border Overlay**: `rgba(255, 255, 255, 0.1)` — subtle dividers

## Typography

- **Font Family**: System stack
  ```
  -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 
  'Oxygen', 'Ubuntu', 'Cantarell', sans-serif
  ```
- **Body**: 16px, line-height 1.6, color: Text
- **Headings**:
  - H1: 3.5rem, font-weight 800, line-height 1.1 (hero); 2rem on mobile
  - H2: 2.5rem, font-weight 800 (sections); 1.75rem on mobile
  - H3: 1.25rem, font-weight 700
  - H4: 1.1rem, font-weight 700
- **Labels**: 0.875rem, font-weight 700, uppercase, letter-spacing 0.15em

## Spacing Scale

- **xs**: 0.5rem (8px)
- **sm**: 1rem (16px)
- **md**: 1.5rem (24px)
- **lg**: 2rem (32px)
- **xl**: 3rem (48px)
- **2xl**: 4rem (64px)

## Components

### Navigation
- **Background**: White with 1px bottom border
- **Logo**: Primary color with truck emoji icon
- **Links**: Text color, hover changes to primary

### Buttons
- **Primary Button** (`.btn-primary`)
  - Background: Primary (#0066cc)
  - Hover: Primary Dark (#0052a3) with translateY(-2px) + brand shadow
  - Padding: sm vertical × lg horizontal
- **Secondary Button** (`.btn-secondary`)
  - Background: Transparent with 2px Primary border
  - Hover: Becomes Primary with white text
- **Large Button** (`.btn-large`)
  - Padding: md vertical × 2xl horizontal
  - Font-size: 1.1rem

### Cards (Services, Coverage, etc.)
- **Padding**: lg
- **Border**: 1px solid border color
- **Border Radius**: 0.75rem
- **Hover**: Border darkens to primary, shadow adds
- **Transition**: all 0.3s ease

### Hero Section
- **Background**: Gradient from light gray-blue to off-white
- **Label**: Small, uppercase, primary color
- **Heading**: Large (3.5rem), charcoal text
- **Subtitle**: 1.25rem, light gray text
- **Buttons**: Flex row with gap-md, wrap on mobile

### Stats Section
- **Grid**: 4 columns (auto-fit)
- **Number**: 2.5rem, Primary color, bold
- **Label**: Small text, light gray

### Forms
- **Input Padding**: sm
- **Border**: 1px solid border color
- **Border Radius**: 0.375rem
- **Focus**: Primary border + brand shadow

### Footer
- **Background**: Dark charcoal
- **Grid**: 3 columns (auto-fit)
- **Text**: Light gray by default, white on hover
- **Divider**: Subtle border with 10% white opacity

## Responsive Design

- **Mobile Breakpoint**: 768px
- **Adjustments**:
  - Hero heading: 3.5rem → 2rem
  - Section headings: 2.5rem → 1.75rem
  - Button layout: flex-direction column on mobile
  - Grid columns: Switch to single column
  - Nav gap: Reduce from lg to md

## Motion

- **Default Transition**: 0.3s ease
- **Button Hover**: translateY(-2px)
- **Color Changes**: 0.3s ease
