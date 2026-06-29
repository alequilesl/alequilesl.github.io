---
name: Professional Synthesis
colors:
  surface: '#fbf8fa'
  surface-dim: '#dcd9db'
  surface-bright: '#fbf8fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f4'
  surface-container: '#f0edef'
  surface-container-high: '#eae7e9'
  surface-container-highest: '#e4e2e3'
  on-surface: '#1b1b1d'
  on-surface-variant: '#45474c'
  inverse-surface: '#303032'
  inverse-on-surface: '#f3f0f2'
  outline: '#75777d'
  outline-variant: '#c5c6cd'
  surface-tint: '#545f73'
  primary: '#091426'
  on-primary: '#ffffff'
  primary-container: '#1e293b'
  on-primary-container: '#8590a6'
  inverse-primary: '#bcc7de'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#1e1200'
  on-tertiary: '#ffffff'
  tertiary-container: '#35260c'
  on-tertiary-container: '#a38c6a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e3fb'
  primary-fixed-dim: '#bcc7de'
  on-primary-fixed: '#111c2d'
  on-primary-fixed-variant: '#3c475a'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#fadfb8'
  tertiary-fixed-dim: '#ddc39d'
  on-tertiary-fixed: '#271902'
  on-tertiary-fixed-variant: '#564427'
  background: '#fbf8fa'
  on-background: '#1b1b1d'
  surface-variant: '#e4e2e3'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 800px
  gutter: 24px
  section-gap: 64px
  stack-gap: 16px
---

## Brand & Style

This design system is engineered for professional storytelling, focusing on clarity, authority, and modern minimalism. The target audience includes recruiters, technical leads, and potential collaborators who value efficiency and precision. 

The aesthetic leverages **Minimalism** with a focus on high-quality typography and structured whitespace. By stripping away extraneous decoration, the content—your experience and skills—becomes the focal point. The emotional response should be one of reliability and understated sophistication, positioning the individual as a high-caliber professional who communicates with intent.

## Colors

The palette is anchored in a sophisticated **Navy Blue (#1e293b)**, used for primary headings and high-priority interactions to convey stability. **Slate Gray (#64748b)** serves as the secondary color for body text and metadata, providing enough contrast for readability while softening the overall visual weight. 

Backgrounds utilize a very light gray (**#f8fafc**) to reduce eye strain compared to pure white, creating a subtle canvas for content. A functional **Blue Accent (#3b82f6)** is reserved for interactive states (links, hover effects) to guide the user’s eye without disrupting the professional tone.

## Typography

The design system utilizes **Inter** exclusively to ensure a systematic and utilitarian feel that remains highly legible across all resolutions. 

- **Hierarchy:** Use `headline-xl` for the primary name/title. `headline-lg` should denote major sections (Experiencia, Educación).
- **Readability:** Body text uses a generous 1.6 line-height to ensure long-form descriptions remain approachable. 
- **Spanish Nuances:** Given the slightly longer word lengths in Spanish, tight letter spacing is used on headlines to maintain visual density, while labels use increased tracking for better scannability in navigation and tags.

## Layout & Spacing

This design system employs a **Fixed Grid** philosophy for the central content column to mirror the structure of a physical resume, optimized for readability. 

- **Desktop:** A single-column layout centered on the screen with a maximum width of 800px. This prevents line lengths from becoming too long, which is critical for reading speed.
- **Breakpoints:** At 768px (Tablet), margins reduce to 32px. Below 480px (Mobile), margins reduce to 20px and font sizes shift to mobile-specific variables.
- **Rhythm:** Use a vertical rhythm based on 8px increments. Sections (Experiencia, Proyectos) are separated by `section-gap` to provide clear visual breathing room.

## Elevation & Depth

To maintain a "clean" and "professional" look, this design system avoids heavy shadows in favor of **Tonal Layers** and **Subtle Outlines**.

- **Surfaces:** Main content sits on the background level. Individual "cards" for projects or roles use a white background with a very thin border (1px) in a light gray shade.
- **Shadows:** Only used to indicate interactivity or focus. Use a single, highly diffused ambient shadow (0px 4px 20px rgba(30, 41, 59, 0.05)) for hovered cards or active modals.
- **Depth:** Content should feel like paper layers rather than a 3D environment. Use slight color shifts (e.g., a slightly darker gray background for a code snippet or quote block) to create hierarchy.

## Shapes

The shape language is consistently **Rounded** (0.5rem / 8px). This softens the "corporate" feel of the navy blue and makes the UI feel modern and approachable. 

- **Base Radius:** Apply 8px to cards, buttons, and input fields.
- **Large Elements:** Use 16px (rounded-lg) for larger containers or hero sections if applicable.
- **Small Elements:** Use 4px for small badges, tags, or checkboxes to maintain a crisp appearance at smaller scales.

## Components

- **Buttons:** Primary buttons use the Navy Blue background with white text. Hover states should slightly lighten the background color. Transition should be a smooth 200ms ease.
- **Experience Cards:** Use a vertical timeline layout. The company logo/icon should be placed in a 48x48px rounded container. Use `body-md` for descriptions and `label-md` for dates.
- **Skill Chips:** Subtle gray backgrounds (#f1f5f9) with Slate Gray text. No borders. These should wrap naturally within their container.
- **Input Fields:** For a contact form, use a 1px border (#e2e8f0). On focus, the border shifts to the Blue Accent with a soft 3px glow (box-shadow).
- **Icons:** Use a consistent stroke-based icon set (like Lucide or Heroicons) with a 1.5px or 2px weight to match the Inter typeface's visual weight.
- **Progress Bars:** If used for skills, keep them thin (6px height) using a light gray track and a Navy Blue fill to remain professional and avoid a "game-like" appearance.