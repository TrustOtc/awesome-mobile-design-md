# Midnight Pro Mobile Design System

## 1. Design Principles

* Dark-first design (Dark mode is primary, not secondary)
* High contrast for clarity and focus
* Futuristic and slightly expressive (subtle neon accents)
* Reduce visual noise, emphasize content and actions
* Depth through contrast, not shadows
* Designed for prolonged usage (reduce eye strain)

---

## 2. Color System

### 2.1 Dark Mode (Primary)

* Primary: #7C5CFF (indigo/purple accent)
* Background: #05070A
* Surface: #0B0F14
* Elevated Surface: #111827
* Text Primary: #E5E7EB
* Text Secondary: #9CA3AF
* Border: #1F2937
* Divider: #111827
* Success: #22C55E
* Warning: #F59E0B
* Error: #EF4444

### 2.2 Light Mode (Fallback)

* Primary: #5B4DFF
* Background: #FFFFFF
* Surface: #F9FAFB
* Text Primary: #111827
* Text Secondary: #6B7280
* Border: #E5E7EB

### 2.3 Rules

* Dark mode is default entry experience
* Never use pure black (#000000)
* Use accent color sparingly for actions and highlights
* Avoid large bright areas to reduce eye fatigue
* Maintain strong contrast for readability

---

## 3. Typography

* Font Family:

  * iOS: System (San Francisco)
  * Android: Roboto

### Scale

* Large Title: 26 / Bold
* Title: 20 / SemiBold
* Body: 15 / Regular
* Caption: 13 / Regular
* Small: 11 / Medium

### Rules

* Slightly tighter typography for dense information
* Line height: 1.4 – 1.5
* Avoid overly large text blocks in dark UI
* Use weight instead of color to indicate hierarchy

---

## 4. Spacing System

Base unit: 4

* xs: 4
* sm: 8
* md: 12
* lg: 16
* xl: 20
* xxl: 28

### Rules

* Slightly tighter spacing than light UI systems
* Maintain consistent rhythm
* Avoid excessive whitespace in dark layouts

---

## 5. Layout & Safe Area

* Respect safe area (top and bottom gestures)
* Default padding: 16
* Prefer centered content blocks
* Avoid edge-to-edge bright elements

---

## 6. Touch & Interaction

* Minimum touch target:

  * iOS: 44pt
  * Android: 48dp

* Feedback:

  * Opacity: 0.85
  * Scale: 0.97

* Use glow or accent highlight for active states

---

## 7. Navigation Patterns

* Tab + Stack hybrid

### Tab Bar

* Background: Surface
* Active icon: Primary color
* Inactive icon: muted gray
* Subtle top border

### Stack

* Dark header with subtle separation
* Modal overlays use elevated surface

---

## 8. Components

### 8.1 Button

Variants:

* Primary (accent filled)
* Secondary (outlined)
* Ghost (text)

Rules:

* Height: 44–48
* Radius: 12
* Primary uses accent color
* Hover/press: slight glow or brightness increase
* Disabled: low opacity (0.4–0.5)

---

### 8.2 Card

* Background: Surface / Elevated Surface
* Radius: 14–16
* Padding: 16
* No heavy shadow
* Use contrast layering instead

---

### 8.3 List Item

* Height: 56–68
* Background: transparent or surface
* Divider: very subtle
* Highlight on press (slight surface lift)

---

### 8.4 Input

* Background: Surface
* Border: 1px subtle
* Radius: 10–12
* Focus: accent border + slight glow
* Text: high contrast

---

## 9. Motion

* Duration: 120–220ms
* Faster interactions than light UI

### Style

* Smooth, slightly sharp easing
* Avoid bouncy animations

---

## 10. Elevation & Depth

* Avoid traditional shadows

* Use layered surfaces instead:

  * Background < Surface < Elevated Surface

* Optional: subtle glow for emphasis

---

## 11. Iconography

* Stroke-based icons
* Slightly brighter than text
* Sizes:

  * Small: 16
  * Default: 20–24
  * Large: 28

---

## 12. Accessibility

* Ensure high contrast ratios
* Avoid low-opacity text for important info
* Support font scaling

---

## 13. Platform Adaptation

### iOS

* More blur allowed (dark glass feel)
* Smoother transitions

### Android

* Slightly stronger elevation contrast
* Clearer separation between layers

---

## 14. Do / Don't

### Do

* Keep UI dark, calm, and focused
* Use accent color strategically
* Maintain hierarchy via contrast

### Don't

* Overuse bright colors
* Use heavy shadows
* Create large flat bright surfaces in dark mode

---
