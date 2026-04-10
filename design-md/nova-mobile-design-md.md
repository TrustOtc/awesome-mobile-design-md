# DESIGN.md

## 1. Design Principles

* Clean, minimal, and content-first
* Native mobile feel (prioritize iOS conventions, compatible with Android)
* High readability and strong visual hierarchy
* Subtle depth, avoid heavy shadows
* Consistent spacing and rhythm
* Support both Light and Dark mode from the ground up

## 2. Color System

### 2.1 Light Mode

* Primary: #3B82F6 (blue)
* Background: #FFFFFF
* Surface: #F9FAFB
* Text Primary: #111827
* Text Secondary: #6B7280
* Border: #E5E7EB
* Success: #10B981
* Warning: #F59E0B
* Error: #EF4444

### 2.2 Dark Mode

* Primary: #60A5FA
* Background: #0B0F14
* Surface: #111827
* Text Primary: #F9FAFB
* Text Secondary: #9CA3AF
* Border: #1F2937
* Success: #34D399
* Warning: #FBBF24
* Error: #F87171

### 2.3 Rules

* Never use pure black (#000000) or pure white (#FFFFFF) in dark mode
* Maintain minimum contrast ratio for readability
* Use Primary color sparingly for actions and highlights


## 3. Typography

* Font Family:

  * iOS: System (San Francisco)
  * Android: Roboto

### Scale

* Large Title: 28 / Bold
* Title: 22 / SemiBold
* Body: 16 / Regular
* Caption: 13 / Regular
* Small: 11 / Medium

### Rules

* Line height: 1.4 – 1.6
* Avoid more than 3 font weights in one screen
* Prioritize readability over style


## 4. Spacing System

Base unit: 4

* xs: 4
* sm: 8
* md: 12
* lg: 16
* xl: 24
* xxl: 32

### Rules

* Use consistent spacing scale only
* Avoid arbitrary values
* Prefer vertical rhythm


## 5. Layout & Safe Area

* Respect safe area (top notch & bottom gesture)
* Default screen padding: 16
* Content max width: full width (mobile-first)
* Avoid edge-to-edge text without padding


## 6. Touch & Interaction

* Minimum touch target:

  * iOS: 44pt
  * Android: 48dp

* Use clear press feedback:

  * opacity change or subtle scale (0.98)

* Avoid hover-only interactions (mobile-first)


## 7. Navigation Patterns

* Use Tab + Stack hybrid

### Tab Bar

* Bottom navigation
* Max 5 items
* Icons + label

### Stack

* Push for drill-down
* Modal for temporary tasks


## 8. Components

### 8.1 Button

Variants:

* Primary (filled)
* Secondary (outlined)
* Ghost (text only)

Rules:

* Height: 44–48
* Border radius: 12
* Primary button uses Primary color
* Disabled state: reduced opacity


### 8.2 Card

* Background: Surface
* Radius: 16
* Padding: 16
* Shadow: subtle (or none in dark mode)


### 8.3 List Item

* Height: 56–72
* Left: icon/avatar
* Right: chevron or action
* Divider: subtle


### 8.4 Input

* Height: 44–48
* Radius: 10–12
* Border: 1px
* Focus: highlight with Primary color


## 9. Motion

* Use subtle animations only
* Duration: 150–300ms

### iOS feel

* spring-like transitions

### Android feel

* ease-in-out


## 10. Elevation & Shadow

Light mode:

* Use very soft shadows

Dark mode:

* Avoid shadows
* Use contrast (surface vs background)


## 11. Iconography

* Use consistent icon set (e.g. Lucide / Material Icons)
* Stroke-based preferred
* Size:

  * Small: 16
  * Default: 20–24
  * Large: 28–32


## 12. Accessibility

* Support dynamic font scaling
* Maintain sufficient contrast
* Avoid relying on color alone for meaning


## 13. Platform Adaptation

### iOS

* More spacing
* More blur / translucency allowed

### Android

* Slightly denser layout
* Respect Material behaviors


## 14. Do / Don't

### Do

* Keep UI simple
* Maintain consistency
* Use spacing system strictly

### Don't

* Mix too many colors
* Use inconsistent radius/spacing
* Overuse shadows or gradients

