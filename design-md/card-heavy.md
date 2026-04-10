# Card Heavy Mobile Design System

## 1. Design Principles

* Card-first layout architecture
* Every piece of content lives inside a card
* Strong visual separation between sections
* Emphasize modularity and reusability
* Designed for feed, marketplace, and discovery apps
* Content should feel scannable and chunked

---

## 2. Color System

### 2.1 Light Mode

* Primary: #3B82F6
* Background: #F3F4F6
* Surface (Card): #FFFFFF
* Surface Alt: #F9FAFB
* Text Primary: #111827
* Text Secondary: #6B7280
* Border: #E5E7EB
* Divider: #E5E7EB
* Success: #10B981
* Warning: #F59E0B
* Error: #EF4444

### 2.2 Dark Mode

* Primary: #60A5FA
* Background: #0B0F14
* Surface (Card): #111827
* Surface Alt: #1F2937
* Text Primary: #F9FAFB
* Text Secondary: #9CA3AF
* Border: #1F2937

### 2.3 Rules

* Cards must stand out from background
* Use subtle contrast between cards and screen
* Avoid flat, undifferentiated layouts
* Maintain consistent card appearance across app

---

## 3. Typography

* Font Family:

  * iOS: System
  * Android: Roboto

### Scale

* Large Title: 26 / Bold
* Title: 20 / SemiBold
* Body: 15–16 / Regular
* Caption: 13 / Regular
* Small: 11 / Medium

### Rules

* Text should be optimized for quick scanning
* Limit long paragraphs
* Use hierarchy inside cards

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

* Spacing defines grouping
* Cards should have internal padding (16–20)
* Vertical spacing between cards: 12–16

---

## 5. Layout & Safe Area

* Respect safe area
* Use vertical scrolling layout
* Cards stacked with consistent spacing
* Avoid edge-to-edge card collisions

---

## 6. Touch & Interaction

* Minimum touch target:

  * iOS: 44pt
  * Android: 48dp

* Entire card can be clickable

* Feedback:

  * Scale: 0.98
  * Shadow increase or slight lift

---

## 7. Navigation Patterns

* Feed-first navigation
* Stack for detail views

### Tab Bar

* Standard bottom tab
* Content-heavy sections per tab

### Stack

* Tap card → push detail page
* Modal for quick actions

---

## 8. Components

### 8.1 Card (Core Component)

* Background: Surface
* Radius: 12–16
* Padding: 16–20
* Shadow: soft
* Layout:

  * Header (optional)
  * Content
  * Actions

---

### 8.2 Button

Variants:

* Primary
* Secondary
* Inline (within card)

Rules:

* Height: 40–44
* Radius: 10–12
* Often embedded inside cards

---

### 8.3 List (Card List)

* Cards stacked vertically
* Optional horizontal scroll cards
* Group related content

---

### 8.4 Input

* Usually inside cards or forms
* Radius: 10–12
* Clear separation from background

---

## 9. Motion

* Duration: 150–250ms

### Style

* Cards can “lift” on press
* Smooth transitions between list → detail
* Emphasize continuity

---

## 10. Elevation & Depth

* Cards are primary elevation unit
* Use shadows in light mode
* Use contrast in dark mode
* Avoid mixing too many elevation levels

---

## 11. Iconography

* Clean and consistent
* Often paired with text inside cards
* Sizes:

  * Small: 16
  * Default: 20–24
  * Large: 28

---

## 12. Accessibility

* Cards must have clear boundaries
* Ensure readable text inside cards
* Support screen readers (card as group)

---

## 13. Platform Adaptation

### iOS

* Softer shadows
* More spacing between cards

### Android

* Slightly stronger elevation
* Denser layout possible

---

## 14. Do / Don't

### Do

* Use cards consistently across screens
* Group related content into cards
* Keep layout modular

### Don't

* Mix card and non-card layouts randomly
* Overcrowd cards with too much content
* Use inconsistent card styles

---
