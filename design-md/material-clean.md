# Material Clean Mobile Design System

## 1. Design Principles

* Based on Material Design 3 principles
* Structured, systematic, and scalable
* Clear hierarchy through elevation and color roles
* Consistent behavior across components
* Designed for Android-first, cross-platform compatible
* Emphasize usability and predictability

---

## 2. Color System

### 2.1 Light Mode

* Primary: #6750A4

* On Primary: #FFFFFF

* Primary Container: #EADDFF

* Secondary: #625B71

* Secondary Container: #E8DEF8

* Background: #FFFBFE

* Surface: #FFFBFE

* Surface Variant: #E7E0EC

* Text Primary: #1C1B1F

* Text Secondary: #49454F

* Outline: #79747E

* Divider: #E7E0EC

* Error: #B3261E

### 2.2 Dark Mode

* Primary: #D0BCFF

* On Primary: #381E72

* Primary Container: #4F378B

* Secondary: #CCC2DC

* Secondary Container: #4A4458

* Background: #1C1B1F

* Surface: #1C1B1F

* Surface Variant: #49454F

* Text Primary: #E6E1E5

* Text Secondary: #CAC4D0

* Outline: #938F99

* Error: #F2B8B5

### 2.3 Rules

* Use semantic color roles (Primary, Surface, Container)
* Avoid hardcoding colors outside system
* Maintain consistency across components
* Respect Material contrast guidelines

---

## 3. Typography

* Font Family:

  * Android: Roboto (default)
  * iOS: System fallback

### Scale (Material-based)

* Display: 32 / Regular
* Headline: 24 / SemiBold
* Title: 20 / Medium
* Body: 14–16 / Regular
* Label: 12–14 / Medium

### Rules

* Follow Material type scale hierarchy
* Use labels for buttons and small UI
* Maintain consistent usage across screens
* Line height: 1.4 – 1.5

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

* Use consistent spacing tokens
* Align components to grid
* Maintain predictable layout rhythm

---

## 5. Layout & Safe Area

* Respect safe area
* Use structured layout sections
* Follow Material layout guidelines
* Use consistent margins (16–24)

---

## 6. Touch & Interaction

* Minimum touch target:

  * Android: 48dp
  * iOS: 44pt

* Feedback:

  * Ripple effect (Android)
  * Opacity/scale fallback (iOS)

* Maintain consistent interaction patterns

---

## 7. Navigation Patterns

### Bottom Navigation

* 3–5 items
* Icons + labels
* Active state clearly indicated

### Top App Bar

* Standard Material header
* Title + actions

### Navigation Behavior

* Stack-based navigation
* Modal for dialogs and temporary actions

---

## 8. Components

### 8.1 Button

Variants:

* Filled
* Outlined
* Text

Rules:

* Height: 40–48
* Radius: 8–12
* Use semantic color roles
* Ripple feedback required on Android

---

### 8.2 Card

* Background: Surface or Surface Variant
* Radius: 12–16
* Padding: 16
* Elevation-based hierarchy

---

### 8.3 List

* Structured rows
* Optional leading/trailing icons
* Divider-based separation
* Consistent alignment

---

### 8.4 Input (Text Field)

* Filled or outlined variants
* Label + helper text
* Clear error state
* Focus: primary color

---

## 9. Motion

* Duration: 150–300ms

### Style

* Standard Material easing curves
* Consistent transitions
* Motion communicates hierarchy and state

---

## 10. Elevation & Depth

* Use elevation levels:

  * 0 (background)
  * 1–2 (cards)
  * 3+ (dialogs, overlays)

* Shadows define hierarchy

* Maintain consistency across screens

---

## 11. Iconography

* Material Icons (preferred)
* Consistent stroke and style
* Sizes:

  * Small: 18
  * Default: 24
  * Large: 32

---

## 12. Accessibility

* Follow Material accessibility guidelines
* Ensure contrast compliance
* Support screen readers
* Provide clear labels and states

---

## 13. Platform Adaptation

### Android

* Full Material behavior (ripple, elevation)
* Native feel prioritized

### iOS

* Replace ripple with opacity/scale
* Slightly increase spacing
* Reduce strict Material visual density

---

## 14. Do / Don't

### Do

* Follow Material system consistently
* Use semantic tokens
* Maintain predictable behavior

### Don't

* Mix non-Material styles
* Override system patterns arbitrarily
* Use inconsistent elevation or color roles

---
