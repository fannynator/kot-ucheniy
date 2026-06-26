---
name: Feline Learning Framework
colors:
  surface: '#fbf8ff'
  surface-dim: '#d7d8f4'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f2ff'
  surface-container: '#edecff'
  surface-container-high: '#e6e6ff'
  surface-container-highest: '#e0e0fc'
  on-surface: '#181a2e'
  on-surface-variant: '#564338'
  inverse-surface: '#2d2f44'
  inverse-on-surface: '#f1efff'
  outline: '#897266'
  outline-variant: '#ddc1b3'
  surface-tint: '#9b4500'
  primary: '#9b4500'
  on-primary: '#ffffff'
  primary-container: '#ff8c42'
  on-primary-container: '#6a2d00'
  inverse-primary: '#ffb68d'
  secondary: '#2b4cda'
  on-secondary: '#ffffff'
  secondary-container: '#4967f4'
  on-secondary-container: '#fffbff'
  tertiary: '#785a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cfa53f'
  on-tertiary-container: '#513c00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbc9'
  primary-fixed-dim: '#ffb68d'
  on-primary-fixed: '#331200'
  on-primary-fixed-variant: '#763300'
  secondary-fixed: '#dee1ff'
  secondary-fixed-dim: '#bac3ff'
  on-secondary-fixed: '#001159'
  on-secondary-fixed-variant: '#0031c4'
  tertiary-fixed: '#ffdf9b'
  tertiary-fixed-dim: '#edc157'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5b4300'
  background: '#fbf8ff'
  on-background: '#181a2e'
  surface-variant: '#e0e0fc'
  kitten-orange: '#FF8C42'
  math-blue: '#4361EE'
  reward-gold: '#FFD166'
  success-green: '#06D6A0'
  error-red: '#EF476F'
  soft-bg: '#F8F9FA'
typography:
  display-lg:
    fontFamily: plusJakartaSans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: plusJakartaSans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
  headline-md:
    fontFamily: plusJakartaSans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: rubik
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: rubik
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  math-display:
    fontFamily: spaceMono
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 24px
  label-caps:
    fontFamily: plusJakartaSans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  gutter: 16px
  margin-mobile: 20px
  margin-desktop: 40px
  container-max: 1200px
---

## Brand & Style

The brand personality is energetic, nurturing, and intellectually stimulating, specifically tailored for early childhood education. It balances the whimsy of a "kitten" theme with the structured nature of math and language learning. The visual language aims to evoke curiosity and joy, transforming educational friction into a rewarding play state.

The design system adopts a **Tactile / Skeuomorphic** style layered over a clean **Minimalist** foundation. While the layout remains uncluttered to prevent cognitive overload, individual interactive elements feature soft shadows, "squishy" button states, and glossy finishes. This physical metaphor helps children understand affordances and encourages engagement through sensory-rich visual feedback.

## Colors

The palette is anchored by "Kitten Orange," a high-energy primary color that drives action and attention. "Math Blue" provides a stabilizing secondary tone used for instructional content and logical tasks, while "Reward Gold" is reserved for achievements and celebratory moments.

This design system uses a light-mode default to maintain a paper-like familiarity. Backgrounds are not pure white but a very soft gray (#F8F9FA) to reduce eye strain during prolonged learning sessions. High-contrast "Success Green" and "Error Red" are used sparingly but decisively for immediate feedback in gamified exercises.

## Typography

Typography focuses on maximum legibility and friendliness. **Plus Jakarta Sans** is used for headlines; its rounded terminals and open apertures feel welcoming and modern. For body text, **Rubik** is employed because its subtly rounded corners maintain the playful aesthetic without sacrificing the reading speed required for instructions.

To differentiate mathematical formulas and technical data, **Space Mono** is utilized. This monospace choice provides clear character distinction (crucial for numbers and Russian characters) and adds a "computer lab" feel to the learning environment. Headlines scale down aggressively for mobile devices to ensure that instructions never fall below the fold.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for tablet and desktop to maintain focus, while adopting a fluid, single-column approach for mobile. A strict 8px spatial rhythm governs all padding and margins.

On desktop, content is centered within a 1200px container with 40px outer margins. On mobile, margins are tightened to 20px to maximize the interactive surface area for small fingers. Spacing between interactive elements (like math tiles) should never be less than 16px (gutter) to prevent accidental taps and "fat-finger" errors.

## Elevation & Depth

Depth is used to simulate a physical "learning tray." The design system avoids complex ambient shadows in favor of **Tonal Layers** and **Hard-Edge Depth Shadows**. 

Interactive elements like buttons and cards feature a "bottom-heavy" shadow (a darker shade of the element's color) to create a 3D effect. When pressed, these elements shift downward, reducing the shadow's height to simulate physical compression. Background layers use subtle inner shadows to appear recessed, while modal overlays use a soft backdrop blur (12px) to keep the user's focus on the active task.

## Shapes

The shape language is defined by significant **Roundedness**. There are no sharp corners in the design system, echoing the soft nature of the brand's kitten mascot. 

Standard components use a 0.5rem (8px) radius, while primary call-to-action buttons use 1rem (16px) or full pill-shapes to appear more "clickable" and friendly. Containers and cards use the `rounded-xl` (1.5rem) setting to create large, approachable blocks of content that feel safe and non-intimidating for children.

## Components

### Buttons
Buttons are the core gamification driver. Primary buttons must feature a "3D lift" effect using a 4px solid bottom border in a darker tint of the button's background color. On hover, the button should lift slightly; on click, it should depress to a flat state.

### Learning Cards
Cards are used to frame math problems or Russian vocabulary. They should have a white background, a 2px soft-colored border (matching the subject category), and a `rounded-xl` corner radius.

### Chips & Progress Tags
Chips are used for category selection (e.g., "Addition," "Nouns"). These should be pill-shaped with high-contrast text and a semi-transparent version of the primary color as the background.

### Input Fields
Inputs for math answers should be oversized (minimum 64px height) with a `math-display` font style. They use a thick 3px border that turns "Math Blue" when focused and "Success Green" upon a correct answer.

### Gamification Elements
Include a "Star Counter" component in the top navigation—a rounded container with a "Reward Gold" star icon that pulses gently when a user earns points. Progress bars should be thick (12px height) with a rounded track and a vibrant gradient fill to visualize movement toward a goal.