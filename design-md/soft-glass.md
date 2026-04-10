# Soft Glass Mobile Design System

## 1. Design Principles

* iOS-inspired, soft and elegant
* Use translucency and blur to create depth
* Light, airy, and calm visual tone
* Emphasize layering instead of hard separation
* Content floats above background
* Designed for premium, polished experiences

---

## 2. Color System

### 2.1 Light Mode (Primary)

* Primary: #2563EB (blue)
* Background: #F2F4F7
* Surface (Glass): rgba(255, 255, 255, 0.7)
* Surface Elevated: rgba(255, 255, 255, 0.85)
* Text Primary: #0F172A
* Text Secondary: #64748B
* Border: rgba(15, 23, 42, 0.08)
* Divider: rgba(15, 23, 42, 0.06)
* Success: #22C55E
* Warning: #F59E0B
* Error: #EF4444

### 2.2 Dark Mode

* Primary: #60A5FA
* Background: #0A0E14
* Surface (Glass): rgba(17, 24, 39, 0.6)
* Surface Elevated: rgba(17, 24, 39, 0.8)
* Text Primary: #F8FAFC
* Text Secondary: #94A3B8
* Border: rgba(255, 255, 255, 0.08)
* Divider: rgba(255, 255, 255, 0.05)

### 2.3 Rules

* Always use blur + translucency for glass surfaces
* Avoid fully opaque cards unless necessary
* Maintain contrast between layers
* Background should subtly show through surfaces

---

## 3. Typography

* Font Family:

  * iOS: System (San Francisco)
  * Android: Roboto (or custom rounded font if available)

### Scale

* Large Title: 30 / Bold
* Title: 22 / SemiBold
* Body: 16 / Regular
* Caption: 13 / Regular
* Small: 11 / Medium

### Rules

* Slightly more spacious typography
* Line height: 1.5 – 1.6
* Use lighter font weights where possible
* Avoid overly dense text blocks

---

## 4. Spacing System

Base unit: 4

* xs: 4
* sm: 8
* md: 12
* lg: 16
* xl: 24
* xxl: 32

### Rules

* More breathing room than standard UI
* Use generous padding inside components
* Emphasize visual comfort

---

## 5. Layout & Safe Area

* Respect safe area at all times
* Default screen padding: 16–20
* Floating components should not touch screen edges
* Use layered layout (background + floating surfaces)

---

## 6. Touch & Interaction

* Minimum touch target:

  * iOS: 44pt
  * Android: 48dp

* Feedback:

  * Scale: 0.97
  * Opacity: subtle change

* Optional: light blur intensification on press

---

## 7. Navigation Patterns

* Tab + Stack hybrid

### Tab Bar

* Floating tab bar (not fully attached to bottom)
* Glass background with blur
* Rounded corners (radius 20–24)

### Stack

* Transparent or glass headers
* Content scrolls under header (iOS style)

---

## 8. Components

### 8.1 Button

Variants:

* Primary (filled)
* Secondary (glass)
* Ghost (text)

Rules:

* Height: 44–48
* Radius: 14–18
* Primary: solid color
* Secondary: glass background + border
* Use soft shadows or glow

---

### 8.2 Card

* Background: glass surface
* Radius: 16–20
* Padding: 16–20
* Blur required
* Shadow: soft and diffused

---

### 8.3 List Item

* Height: 56–72
* Background: transparent or glass
* Use spacing instead of dividers
* Optional: floating grouped lists

---

### 8.4 Input

* Background: glass surface
* Radius: 12–16
* Border: subtle
* Focus: highlight + slight glow
* Placeholder: soft contrast

---

## 9. Motion

* Duration: 180–300ms

### Style

* Smooth, fluid transitions
* iOS-like spring animations
* Emphasize continuity and softness

---

## 10. Elevation & Depth

* Use blur + layering instead of heavy shadows

* Depth hierarchy:

  * Background
  * Glass Surface
  * Elevated Glass

* Shadows are soft and diffused

---

## 11. Iconography

* Rounded, friendly icon style
* Prefer SF Symbols style where possible
* Sizes:

  * Small: 16
  * Default: 20–24
  * Large: 28–32

---

## 12. Accessibility

* Ensure contrast over blurred backgrounds
* Avoid overly transparent text
* Support dynamic type scaling

---

## 13. Platform Adaptation

### iOS

* Full glassmorphism support
* Blur heavily used

### Android

* Reduce blur intensity if performance issues
* Fallback to semi-transparent surfaces

---

## 14. Do / Don't

### Do

* Use blur and translucency consistently
* Keep UI soft and elegant
* Maintain spacing and layering

### Don't

* Use hard borders excessively
* Overuse strong shadows
* Mix too many solid surfaces with glass

---
