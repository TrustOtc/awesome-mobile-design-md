# Enterprise Neutral Mobile Design System

## 1. Design Principles

* Professional, stable, and trustworthy
* Function over form, clarity over decoration
* High information density with clear structure
* Minimal visual noise
* Consistent and predictable interactions
* Designed for productivity and efficiency

---

## 2. Color System

### 2.1 Light Mode (Primary)

* Primary: #2563EB (blue)
* Background: #FFFFFF
* Surface: #F5F7FA
* Surface Alt: #EEF2F7
* Text Primary: #111827
* Text Secondary: #6B7280
* Border: #D1D5DB
* Divider: #E5E7EB
* Success: #16A34A
* Warning: #D97706
* Error: #DC2626

### 2.2 Dark Mode

* Primary: #3B82F6
* Background: #0F172A
* Surface: #111827
* Surface Alt: #1F2937
* Text Primary: #E5E7EB
* Text Secondary: #9CA3AF
* Border: #374151

### 2.3 Rules

* Use a limited color palette (primarily blue + grayscale)
* Avoid decorative or vibrant colors
* Color should indicate state, not style
* Maintain strict visual consistency

---

## 3. Typography

* Font Family:

  * iOS: System (San Francisco)
  * Android: Roboto

### Scale

* Large Title: 24 / Bold
* Title: 20 / SemiBold
* Body: 14–15 / Regular
* Caption: 12 / Regular
* Small: 11 / Medium

### Rules

* Slightly smaller font sizes for higher density
* Line height: 1.4 – 1.5
* Use weight for hierarchy, not color
* Avoid overly large headings

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

* Compact layout preferred
* Reduce excessive whitespace
* Maintain strict alignment

---

## 5. Layout & Safe Area

* Respect safe area
* Default padding: 12–16
* Use structured layout (grid / sections)
* Align elements precisely

---

## 6. Touch & Interaction

* Minimum touch target:

  * iOS: 44pt
  * Android: 48dp

* Feedback:

  * Subtle opacity change (0.9–0.95)
  * No playful animations

* Prioritize speed and predictability

---

## 7. Navigation Patterns

* Tab + Stack hybrid or Stack-heavy

### Tab Bar

* Simple, minimal styling
* No decorative elements
* Clear active state

### Stack

* Standard headers
* Clear title + back behavior
* Modal for forms or workflows

---

## 8. Components

### 8.1 Button

Variants:

* Primary (filled)
* Secondary (outline)
* Tertiary (text)

Rules:

* Height: 40–44
* Radius: 6–10 (less rounded)
* No gradients
* Disabled: grayscale + opacity

---

### 8.2 Card

* Background: Surface
* Radius: 8–12
* Padding: 12–16
* Minimal shadow or none
* Strong border preferred

---

### 8.3 List Item

* Height: 48–64
* Structured layout (label + value)
* Divider: clear and consistent
* No unnecessary icons

---

### 8.4 Input

* Background: #FFFFFF (or Surface)
* Radius: 6–10
* Border: clear (1px)
* Focus: primary color border
* Error: clear red state

---

## 9. Motion

* Duration: 100–200ms

### Style

* Minimal animation
* No bounce or playful motion
* Fast transitions

---

## 10. Elevation & Depth

* Prefer flat design
* Use borders instead of shadows
* Clear separation through layout

---

## 11. Iconography

* Simple, functional icons
* Stroke-based
* Sizes:

  * Small: 14–16
  * Default: 18–20
  * Large: 24

---

## 12. Accessibility

* High contrast text
* Clear error and success states
* Support screen readers
* Support font scaling

---

## 13. Platform Adaptation

### iOS

* Slightly more spacing
* Native transitions

### Android

* Slightly denser layout
* Follow Material behavior for inputs and lists

---

## 14. Do / Don't

### Do

* Keep UI structured and predictable
* Use consistent spacing and alignment
* Prioritize usability over aesthetics

### Don't

* Use bright or playful colors
* Add unnecessary animations
* Over-design components

---
