# Recipe Discovery App Design Guidelines

## Design Approach: Design System Based
**Selected System**: Material Design with minimalist SaaS adaptations
**Justification**: This productivity-focused app requires clean, efficient interfaces that prioritize functionality while maintaining visual appeal for daily use by remote workers.

## Core Design Elements

### Color Palette
**Light Mode:**
- Primary: 219 78% 47% (Modern blue for trust and productivity)
- Secondary: 219 15% 25% (Deep slate for text)
- Background: 0 0% 98% (Warm white)
- Surface: 0 0% 100% (Pure white cards)
- Success: 142 72% 29% (Green for ingredient matches)

**Dark Mode:**
- Primary: 219 78% 65% (Lighter blue for contrast)
- Secondary: 219 15% 85% (Light text)
- Background: 222 47% 7% (Deep dark blue)
- Surface: 222 47% 11% (Elevated surfaces)
- Success: 142 72% 45% (Brighter green)

### Typography
- **Primary Font**: Inter (Google Fonts) - Clean, readable sans-serif
- **Accent Font**: JetBrains Mono (Google Fonts) - For ingredient tags and cooking times
- **Hierarchy**: text-xs to text-4xl, weights 400-600

### Layout System
**Spacing Units**: Tailwind units of 2, 4, 8, 12, 16 for consistent rhythm
- Micro spacing: p-2, m-2
- Component spacing: p-4, gap-4  
- Section spacing: p-8, my-8
- Layout spacing: p-12, gap-12
- Large spacing: p-16, my-16

### Component Library

**Navigation**: Clean header with logo, search, and minimal menu items
**Ingredient Input**: Tag-based input with autocomplete dropdown and clear visual hierarchy
**Recipe Cards**: Compact cards with ingredient match percentage, cooking time, and difficulty indicators
**Filters**: Subtle sidebar filters with checkbox groups and range sliders
**Recipe Detail**: Full-width layout with image, ingredients list, and step-by-step instructions
**Pantry Management**: Grid-based ingredient management with add/remove functionality

### Key Design Principles
1. **Scannable Information**: Recipe cards show essential info at a glance
2. **Progressive Disclosure**: Detailed information revealed on demand
3. **Visual Hierarchy**: Clear distinction between primary and secondary content
4. **Efficient Interactions**: Minimal clicks to find and view recipes
5. **Clean Typography**: Generous whitespace and consistent text sizing

### Images
**Hero Section**: No large hero image - focus on immediate functionality with ingredient input prominently displayed
**Recipe Cards**: Small thumbnail images (aspect ratio 4:3) for visual recipe identification
**Recipe Detail**: Medium-sized hero image (aspect ratio 16:9) at top of detailed view
**Ingredient Icons**: Small SVG icons from Heroicons for common ingredients and categories

### Interactive Elements
- Subtle hover states on cards with slight elevation
- Smooth transitions for filter applications
- Ingredient tag animations when adding/removing
- Loading states for recipe search results
- Empty states with helpful guidance for new users

This design creates a professional, efficient tool that helps remote workers quickly discover recipes without visual clutter or unnecessary complexity.