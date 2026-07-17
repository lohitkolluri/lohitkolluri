# Noir Minimalist GitHub Profile README Redesign

## Overview
Redesign Lohit Kolluri's GitHub profile README with a clean, professional noir (black & white) theme using animated SVGs. The design emphasizes readability, information hierarchy, and subtle animations that guide the eye without distraction.

## Design Principles
- **Noir palette**: Pure black (`#0a0a0a`), white (`#ffffff`), and grays (`#141414`, `#2a2a2a`, `#888888`)
- **Editorial typography**: System sans-serif, generous spacing, high contrast
- **Subtle motion**: Fade-ins, gentle pulses, line draws — no flashy effects
- **Information-first**: Content hierarchy is clear, animations support scanning

## Sections

### 1. Hero Banner (`assets/hero.svg`)
- Full-width banner with name, tagline, and social links
- Animated typing effect for tagline (Platform Engineer etc.)
- Subtle animated parallel lines or geometric frame
- Clean row of social badges below

### 2. About Me (`assets/about.svg`)
- Card with the about text
- Gentle border pulse or fade-in animation
- Clean typography with hierarchy

### 3. Tech Stack (`assets/techstack.svg`)
- Monochrome SVG icons for each technology
- Grid layout, responsive
- Subtle hover-scale animation

### 4. GitHub Stats (`assets/stats.svg`)
- Animated metric cards showing stars, commits, PRs, repos
- Number counter animation (count up from 0)
- Clean card design with minimal borders

### 5. Section Dividers (inline SVGs)
- Thin animated line between each section
- Left-to-right line draw animation
- Simple and elegant

### 6. Footer (`assets/footer.svg`)
- Minimal footer with visitor counter
- Same style as hero

## Technical Constraints
- SVGs must be self-contained (no external font loads)
- CSS `@keyframes` for all animations
- No JavaScript
- Dark mode only (GitHub default is dark, and noir works best on dark)
- Referenced via `<img>` tags in README.md

## Color Palette
| Token | Hex | Usage |
|-------|-----|-------|
| `--bg-primary` | `#0a0a0a` | Page background |
| `--bg-card` | `#141414` | Card/surface backgrounds |
| `--border` | `#2a2a2a` | Borders and separators |
| `--text-primary` | `#ffffff` | Primary text, headings |
| `--text-secondary` | `#888888` | Secondary text, labels |
| `--accent` | `#e0e0e0` | Subtle accents, hover states |

## File Structure
```
lohitkolluri/
├── README.md              # Main profile with embedded SVG references
├── assets/
│   ├── hero.svg          # Animated hero banner
│   ├── about.svg         # About me card
│   ├── techstack.svg     # Tech stack grid
│   ├── stats.svg         # GitHub stats cards
│   ├── divider.svg       # Animated section divider
│   └── footer.svg        # Footer section
└── docs/superpowers/specs/
    └── 2026-07-17-noir-profile-redesign.md  # This spec
```
