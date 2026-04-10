# Content First Mobile Design System

## 1. Design Principles

* Content is the primary focus, UI is secondary
* Reduce visual noise to near zero
* Typography drives the experience
* Maximize readability and immersion
* UI should disappear when not needed
* Designed for reading, writing, and content consumption

---

## 2. Color System

### 2.1 Light Mode

* Primary: #111827 (used sparingly)
* Background: #FFFFFF
* Surface: #FFFFFF
* Text Primary: #0F172A
* Text Secondary: #475569
* Border: #E5E7EB
* Divider: #F1F5F9
* Highlight: #FEF3C7

### 2.2 Dark Mode

* Primary: #E5E7EB
* Background: #0B0F14
* Surface: #0B0F14
* Text Primary: #F8FAFC
* Text Secondary: #94A3B8
* Border: #1F2937

### 2.3 Rules

* Avoid strong accent colors
* Maintain soft contrast for long reading sessions
* Use highlight color only for emphasis (selection, notes)
* Background and surface should feel unified

---

## 3. Typography

* Font Family:

  * iOS: System (San Francisco)
  * Android: Roboto
  * Optional: serif for reading (e.g. Georgia)

### Scale

* Large Title: 28 / Bold
* Title: 22 / SemiBold
* Body: 17–18 / Regular
* Caption: 13 / Regular
* Small: 11 / Medium

### Rules

* Body text is the most important element
* Line height: 1.6 – 1.8
* Maximize readability
* Avoid overly dense layouts
* Use paragraph spacing generously

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

* Use spacing to separate paragraphs
* Avoid tight UI grouping
* Prefer vertical flow

---

## 5. Layout & Safe Area

* Respect safe area
* Default padding: 16–20
* Narrow reading width preferred
* Avoid full-width text on large screens

---

## 6. Touch & Interaction

* Minimum touch target:

  * iOS: 44pt
  * Android: 48dp

* Interaction should be minimal:

  * Tap to reveal controls
  * Long press for actions

* Avoid constant visible buttons

---

## 7. Navigation Patterns

* Stack-based navigation

### Behavior

* Scroll-driven experience
* Navigation UI hidden or minimal
* Floating actions only when necessary

---

## 8. Components

### 8.1 Text Block (Core Component)

* Primary content container
* Large readable text
* Generous line height
* Clear paragraph spacing

---

### 8.2 Button

Variants:

* Primary (rarely used)
* Inline (text link style)

Rules:

* Avoid heavy button usage
* Prefer inline actions

---

### 8.3 Card

* Minimal or none
* Used only for grouping metadata
* Avoid heavy visual styling

---

### 8.4 Input

* Clean and distraction-free
* Minimal borders
* Focus on text entry experience

---

## 9. Motion

* Duration: 150–250ms

### Style

* Subtle and almost invisible
* Smooth scroll is critical
* No playful animations

---

## 10. Elevation & Depth

* Flat design
* No shadows
* Depth created by spacing only

---

## 11. Iconography

* Minimal icons
* Only when necessary
* Sizes:

  * Small: 14–16
  * Default: 18–20

---

## 12. Accessibility

* High readability is top priority
* Support dynamic type scaling
* Ensure comfortable contrast
* Avoid long unbroken text blocks

---

## 13. Platform Adaptation

### iOS

* Smooth scrolling
* Gesture-driven interactions

### Android

* Ensure performance with long content
* Respect system text scaling

---

## 14. Do / Don't

### Do

* Let content lead the experience
* Use typography to create hierarchy
* Keep UI minimal

### Don't

* Overuse buttons or UI elements
* Add unnecessary decoration
* Interrupt reading flow

---
