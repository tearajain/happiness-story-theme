# Visual Design Guide - The Happiness Story Theme

## 📐 Overview

This comprehensive design guide documents all visual elements, colors, typography, components, and interactions for The Happiness Story Shopify theme.

---

## 🎨 COLOR PALETTE

### Primary Colors

#### Dark Charcoal (Primary Background)
```
Color: #2a2a2a
Usage: Main page background, hero section
RGB: 42, 42, 42
HSL: 0°, 0%, 16%
Contrast: AAA compliant with white text
```

#### Secondary Dark Gray
```
Color: #3a3a3a
Usage: Card backgrounds, section dividers, darker overlays
RGB: 58, 58, 58
HSL: 0°, 0%, 23%
Contrast: AAA compliant with white text
```

#### Accent Gold
```
Color: #c4a26a
Usage: CTA buttons, highlights, hover states, accent text
RGB: 196, 162, 106
HSL: 31°, 51%, 59%
Contrast: AAA compliant with dark backgrounds
```

### Secondary Colors

#### Text Primary (White)
```
Color: #ffffff
Usage: Main text, headings on dark backgrounds
RGB: 255, 255, 255
Contrast: Perfect with #2a2a2a
```

#### Text Secondary (Light Gray)
```
Color: #b0b0b0
Usage: Subtitles, descriptions, secondary text
RGB: 176, 176, 176
HSL: 0°, 0%, 69%
```

#### Text Tertiary (Medium Gray)
```
Color: #a0a0a0
Usage: Italicized text, captions, disabled states
RGB: 160, 160, 160
HSL: 0°, 0%, 63%
```

#### Background Light (Cream)
```
Color: #f5f1e8
Usage: Header background, light section backgrounds
RGB: 245, 241, 232
HSL: 38°, 62%, 95%
Contrast: AAA compliant with dark text
```

### Color Usage Chart

| Component | Background | Text | Border |
|-----------|------------|------|--------|
| Hero Section | #2a2a2a | #ffffff | #c4a26a |
| Cards | #3a3a3a | #ffffff | #c4a26a (on hover) |
| Header | #f5f1e8 | #2a2a2a | #e0dcd1 |
| CTA Buttons | #c4a26a | #ffffff | N/A |
| Hover State | Lighten to #d4b27a | #ffffff | N/A |

---

## 🔤 TYPOGRAPHY

### Font Family
```
Primary: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', sans-serif
Fallback: Arial, sans-serif
```

### Font Sizes & Hierarchy

#### Headings
```
H1 (Page Title)
- Size: 48px (desktop), 32px (mobile)
- Weight: 600 (semi-bold)
- Line Height: 1.2
- Letter Spacing: -1px
- Color: #ffffff (on dark) or #2a2a2a (on light)
- Example: "Three ways to give something unforgettable"

H2 (Section Title)
- Size: 36px (desktop), 28px (mobile)
- Weight: 700 (bold)
- Line Height: 1.3
- Letter Spacing: -0.5px
- Color: #ffffff
- Example: "Curated Hampers"

H3 (Card Title)
- Size: 24px (desktop), 20px (mobile)
- Weight: 600
- Line Height: 1.4
- Color: #ffffff

H4 (Subsection Title)
- Size: 18px
- Weight: 600
- Line Height: 1.4
- Color: #ffffff
```

#### Body Text
```
Body (Primary)
- Size: 16px
- Weight: 400 (regular)
- Line Height: 1.6
- Letter Spacing: 0
- Color: #ffffff (on dark) or #2a2a2a (on light)

Body (Small)
- Size: 14px
- Weight: 400
- Line Height: 1.5
- Color: #b0b0b0 (secondary text)

Body (Tiny)
- Size: 12px
- Weight: 600
- Letter Spacing: 1px
- Text Transform: uppercase
- Color: #999999 (labels)
```

#### Italic Text (Subtitles)
```
Size: 13px (or parent size - 1px)
Weight: 400
Style: italic
Color: #a0a0a0
Example: "For someone you love"
```

### Line Heights
```
Headings: 1.2 - 1.4
Body: 1.5 - 1.8
Tight spacing: 1.2
Normal spacing: 1.6
Loose spacing: 1.8
```

---

## 🎯 KEY COMPONENTS

### Hero Section "Three Ways to Give"

#### Background
```
Background: Linear gradient from #2a2a2a to #3a3a3a (135deg)
Height: 400px (min height)
Padding: 100px (top/bottom) on desktop
Alignment: Center, both vertical and horizontal
```

#### Title
```
Text: "Three ways to give something unforgettable."
Size: 48px (desktop)
Weight: 600
Color: #ffffff
Margin Bottom: 20px
```

#### Subtitle
```
Text: "A premium Indian gifting studio..."
Size: 18px
Color: #cccccc (light gray)
Weight: 300 (light)
Line Height: 1.8
Max Width: 800px
```

### Card Component

#### Container
```
Background: Gradient (varies by card)
  Card 1: Linear gradient from #4a4a4a to #3a3a3a
    Card 2: Linear gradient from #3a3a3a to #2a2a2a
      Card 3: Linear gradient from #1f4a3f to #1a3a35 (green tint)
      Padding: 50px (all sides)
      Border Radius: 8px
      Box Shadow: 0 10px 40px rgba(0,0,0,0.3) on hover
      Transition: transform 0.3s, box-shadow 0.3s
      ```

      #### Card Number (01, 02, 03)
      ```
      Size: 64px
      Weight: 700
      Color: #c4a26a
      Opacity: 0.3 (semi-transparent)
      Margin Bottom: 20px
      ```

      #### Card Subtitle (e.g., "For someone you love")
      ```
      Size: 13px
      Color: #a0a0a0
      Style: italic
      Margin Bottom: 15px
      ```

      #### Card Title
      ```
      Size: 36px
      Weight: 700
      Color: #ffffff
      Margin Bottom: 20px
      ```

      #### Card Description
      ```
      Size: 14px
      Color: #b0b0b0
      Line Height: 1.8
      Margin Bottom: 25px
      Max Length: 120 characters for consistency
      ```

      #### Card Link
      ```
      Text: "Shop hampers →" or "Get a quote →"
      Size: 14px
      Weight: 600
      Color: #c4a26a
      Text Decoration: None
      Transition: color 0.3s
      Hover Color: #e0c080
      Display: inline-block
      ```

      ### Button Styles

      #### Primary Button (CTA)
      ```
      Background: #c4a26a
      Text Color: #ffffff
      Padding: 12px 30px
      Border Radius: 25px
      Font Weight: 600
      Font Size: 14px
      Border: None
      Cursor: pointer
      Hover State: Background #b8934f
      Transition: background 0.3s
      Letter Spacing: 0.5px
      ```

      #### Secondary Button
      ```
      Background: transparent
      Border: 1px solid #c4a26a
      Text Color: #c4a26a
      Padding: 10px 25px
      Border Radius: 4px
      Hover: Background #c4a26a, Text #ffffff
      ```

      ### Header/Navigation

      #### Header Background
      ```
      Background: #f5f1e8 (cream)
      Padding: 20px 40px
      Position: Sticky (stays at top)
      Z-index: 100
      Border Bottom: 1px solid #e0dcd1
      ```

      #### Logo
      ```
      Text: "THE HAPPINESS STORY"
      Base Color: #2a2a2a
      Accent ("HAPPINESS"): #c4a26a
      Accent Style: italic
      Font Size: 16px
      Font Weight: 600
      Letter Spacing: 2px
      ```

      #### Navigation Links
      ```
      Text Color: #2a2a2a
      Font Size: 14px
      Font Weight: 500
      Hover Color: #c4a26a
      Spacing: 40px between items
      Transition: color 0.3s
      ```

      #### "GET A QUOTE" Button
      ```
      Background: #c4a26a
      Text: "GET A QUOTE"
      Color: #ffffff
      Padding: 10px 25px
      Border Radius: 25px
      Font Weight: 600
      Font Size: 12px
      Letter Spacing: 1px
      Text Transform: uppercase
      ```

      ---

      ## 📐 SPACING & LAYOUT

      ### Base Unit: 8px
      ```
      4px = 0.5 unit (fine adjustments)
      8px = 1 unit (base)
      16px = 2 units
      24px = 3 units
      32px = 4 units
      40px = 5 units
      48px = 6 units
      56px = 7 units
      64px = 8 units
      80px = 10 units
      100px = 12.5 units
      ```

      ### Section Padding
      ```
      Top/Bottom: 80px - 100px (desktop)
      Left/Right: 40px (desktop), 20px (mobile)
      ```

      ### Card Grid
      ```
      Desktop: 3 columns
      Tablet: 2 columns
      Mobile: 1 column
      Gap: 40px
      Max Width: 1400px
      ```

      ### Announcement Bar
      ```
      Padding: 10px 20px
      Background: #3a3a3a
      Text Color: #999999
      Font Size: 14px
      Height: 40px
      ```

      ---

      ## 📱 RESPONSIVE BREAKPOINTS

      ```
      Mobile: < 600px
        - Single column layouts
          - 20px side padding
            - 32px vertical spacing
              - Reduced font sizes

              Tablet: 600px - 1024px
                - 2 column grids
                  - 30px side padding
                    - 60px vertical spacing

                    Desktop: > 1024px
                      - 3 column grids
                        - 40px side padding
                          - 80-100px vertical spacing
                            - Max width: 1400px

                            Large Desktop: > 1440px
                              - Centered container
                                - Increased spacing
                                  - Larger typography
                                  ```

                                  ---

                                  ## ✨ ANIMATIONS & INTERACTIONS

                                  ### Hover Effects
                                  ```
                                  Cards: translateY(-5px) with box-shadow increase
                                  Buttons: Slight color shift
                                  Links: Color change + underline fade-in
                                  Transition Timing: 0.3s ease
                                  ```

                                  ### Transitions
                                  ```
                                  Standard: 0.3s ease
                                  Fast: 0.15s ease
                                  Slow: 0.5s ease
                                  Easing: cubic-bezier(0.4, 0, 0.2, 1)
                                  ```

                                  ### Scroll Behavior
                                  ```
                                  Smooth scrolling on all internal links
                                  Scroll padding: 80px (for fixed header)
                                  ```

                                  ---

                                  ## 🎭 VISUAL HIERARCHY

                                  ### Emphasis Levels

                                  **Level 1 (Maximum Emphasis)**
                                  - Gold accent color (#c4a26a)
                                  - Large text (48px+)
                                  - Bold weight (700)
                                  - High contrast
                                  - Example: Page titles, main CTA buttons

                                  **Level 2 (High Emphasis)**
                                  - White text (#ffffff)
                                  - Medium-large text (24-36px)
                                  - Semi-bold weight (600)
                                  - Example: Card titles, section headers

                                  **Level 3 (Medium Emphasis)**
                                  - Light gray text (#b0b0b0)
                                  - Standard text (16px)
                                  - Regular weight (400)
                                  - Example: Body text, descriptions

                                  **Level 4 (Low Emphasis)**
                                  - Medium gray text (#a0a0a0)
                                  - Small text (12-14px)
                                  - Regular or italic
                                  - Example: Captions, subtitles, metadata

                                  ---

                                  ## 🎯 BEFORE & AFTER COMPARISON

                                  ### Before (Current Live)
                                  - Burgundy accent bar (#8B3A3A)
                                  - "HAPPINESS" centered in logo
                                  - Blue/lavender hero (#A8BFDE)
                                  - Light background (#f5f1e8)
                                  - Warm color palette
                                  - Feature boxes with cream color (#F5E6D3)

                                  ### After (New Design)
                                  - No top accent bar
                                  - "HAPPINESS" in gold italic
                                  - Dark hero section (#2a2a2a)
                                  - Premium dark aesthetic
                                  - Modern color palette
                                  - Subtle gradient cards (#3a3a3a to #2a2a2a)

                                  ---

                                  ## ✅ Implementation Checklist

                                  - [ ] Update all CSS variables to match color palette
                                  - [ ] Modify header styling (background, logo, navigation)
                                  - [ ] Update hero section (dark background, centered text)
                                  - [ ] Redesign three-column cards (gradients, styling)
                                  - [ ] Update button styles (gold color, hover effects)
                                  - [ ] Adjust typography hierarchy
                                  - [ ] Test responsive breakpoints
                                  - [ ] Verify color contrast (WCAG AAA)
                                  - [ ] Test animations and transitions
                                  - [ ] Cross-browser testing
                                  - [ ] Mobile device testing

                                  ---

                                  ## 📚 Additional Resources

                                  - [WCAG Color Contrast Checker](https://webaim.org/resources/contrastchecker/)
                                  - [Google Fonts - System Fonts](https://fonts.google.com/knowledge/glossary/system_fonts)
                                  - [CSS Gradient Generator](https://cssgradient.io/)
                                  - [Shopify Liquid Documentation](https://shopify.dev/api/liquid)

                                  ---

                                  **Last Updated:** June 2026
                                  **Version:** 1.0
                                  **Status:** Complete and Ready for Implementation
