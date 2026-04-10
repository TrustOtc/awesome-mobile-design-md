# Data Dashboard Mobile Design System

## 1. Design Principles

* Data-first, UI serves information
* High information density with clarity
* Prioritize quick scanning and comparison
* Use visual hierarchy to surface key metrics
* Designed for monitoring, analytics, and decision-making
* Emphasize precision over decoration

---

## 2. Color System

### 2.1 Light Mode

* Primary: #2563EB

* Background: #F8FAFC

* Surface: #FFFFFF

* Surface Alt: #F1F5F9

* Text Primary: #0F172A

* Text Secondary: #475569

* Border: #E2E8F0

* Divider: #E5E7EB

* Positive: #16A34A

* Negative: #DC2626

* Neutral: #64748B

### 2.2 Dark Mode

* Primary: #3B82F6

* Background: #020617

* Surface: #0F172A

* Surface Alt: #1E293B

* Text Primary: #E2E8F0

* Text Secondary: #94A3B8

* Border: #1E293B

* Positive: #22C55E

* Negative: #EF4444

* Neutral: #64748B

### 2.3 Rules

* Use color to indicate state (positive / negative)
* Avoid decorative colors
* Maintain high contrast for numbers
* Keep palette controlled and functional

---

## 3. Typography

* Font Family:

  * iOS: System
  * Android: Roboto
  * Optional: Monospace for numbers

### Scale

* Large Metric: 28–32 / Bold
* Title: 18–20 / SemiBold
* Body: 14–15 / Regular
* Caption: 12 / Regular
* Small: 11 / Medium

### Rules

* Numbers are the most important element
* Align numbers consistently (right-aligned where needed)
* Use tabular numbers if possible
* Line height: 1.4 – 1.5

---

## 4. Spacing System

Base unit: 4

* xs: 4
* sm: 8
* md: 12
* lg: 16
* xl: 20
* xxl: 24

### Rules

* Compact but readable spacing
* Group related data tightly
* Separate sections clearly

---

## 5. Layout & Safe Area

* Respect safe area
* Use grid-like structure
* Modular sections (cards or panels)
* Allow vertical scrolling for dashboards

---

## 6. Touch & Interaction

* Minimum touch target:

  * iOS: 44pt
  * Android: 48dp

* Interaction types:

  * Tap for detail
  * Long press for actions
  * Swipe for quick filters

* Feedback:

  * Subtle highlight or elevation

---

## 7. Navigation Patterns

* Tab + Stack hybrid

### Tab Bar

* Sections like:

  * Overview
  * Analytics
  * Reports

### Stack

* Drill-down into detailed data views
* Modal for filters and settings

---

## 8. Components

### 8.1 Metric Card (Core Component)

* Display key values

* Layout:

  * Label
  * Value (large)
  * Trend (optional)

* Background: Surface

* Radius: 12–16

* Padding: 16

---

### 8.2 Chart

* Types:

  * Line
  * Bar
  * Pie

Rules:

* Keep charts simple
* Avoid overloading with data
* Use consistent color mapping

---

### 8.3 Table / List

* Structured rows
* Clear alignment
* Minimal decoration
* Optional sorting/filtering

---

### 8.4 Button

Variants:

* Primary
* Secondary
* Icon button

Rules:

* Height: 36–44
* Radius: 8–10
* Functional appearance only

---

### 8.5 Input / Filter

* Used for filtering data
* Compact design
* Clear states

---

## 9. Motion

* Duration: 100–200ms

### Style

* Minimal motion
* Smooth transitions for data updates
* Avoid distracting animations

---

## 10. Elevation & Depth

* Use light elevation for cards
* Avoid heavy shadows
* Separate sections using layout and borders

---

## 11. Iconography

* Functional icons only
* Used for actions and indicators
* Sizes:

  * Small: 14–16
  * Default: 18–20
  * Large: 24

---

## 12. Accessibility

* Ensure readability of numbers
* Provide clear color + text indicators
* Avoid relying only on color for trends
* Support screen readers for data

---

## 13. Platform Adaptation

### iOS

* Smooth transitions between views
* Gesture-based navigation

### Android

* Stronger structure and density
* Material-compatible components

---

## 14. Do / Don't

### Do

* Highlight key metrics clearly
* Keep data structured and aligned
* Use color to indicate meaning

### Don't

* Overload charts with too much data
* Use decorative UI elements
* Make data hard to scan

---
