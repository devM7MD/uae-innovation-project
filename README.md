# Color Test Website

A modern website showcasing Tailwind CSS color combinations and interactive elements.

## :art: Color Palette Documentation

### Main Colors

#### Dark Backgrounds
| Color | Class | Hex | Usage |
|-------|-------|-----|-------|
| Neutral 950 | `bg-neutral-950` | `#030712` | Primary background |
| Neutral 900 | `bg-neutral-900` | `#171717` | Navbar & Footer |
| Slate 950 | `bg-slate-950` | `#020617` | Secondary background |
| Gray 950 | `bg-gray-950` | `#030712` | Alternative background |
| Zinc 900 | `bg-zinc-900` | `#18181B` | Container background |

#### Primary Colors
| Color | Class | Hex | Usage |
|-------|-------|-----|-------|
| Violet 200 | `bg-violet-200` | `#DDD6FE` | Primary buttons |
| Blue 300 | `bg-blue-300` | `#93C5FD` | Secondary buttons |
| Purple 300 | `bg-purple-300` | `#D8B4FE` | Accent elements |
| Fuchsia 400 | `bg-fuchsia-400` | `#E879F9` | Hover states |

#### Accent Colors
| Color | Class | Hex | Usage |
|-------|-------|-----|-------|
| Emerald 500 | `bg-emerald-500` | `#10B981` | Success/Action |
| Amber 400 | `bg-amber-400` | `#FBBF24` | Warning/Highlight |
| Rose 400 | `bg-rose-400` | `#FB7185` | Error/Alert |
| Cyan 400 | `bg-cyan-400` | `#22D3EE` | Info |

#### Text Colors
| Color | Class | Usage |
|-------|-------|-------|
| Zinc 400 | `text-zinc-400` | Body text |
| White | `text-white` | Primary text |
| Neutral 900 | `text-neutral-900` | Text on light backgrounds |

### Special Effects

#### Gradients

##### Text Gradients
```css
bg-gradient-to-r from-violet-200 via-blue-300 to-purple-300
text-transparent bg-clip-text
```

##### Background Gradients
```css
bg-gradient-to-br from-neutral-900 to-slate-950
```

#### Transparency & Blur Effects
```css
/* Navbar and Footer */
bg-neutral-900/50 backdrop-blur-sm
/* Shadows */
shadow-lg shadow-[color]/50
```

### Interactive States

#### Hover Effects
```css
/* Links */
hover:text-fuchsia-400
/* Buttons */
hover:bg-fuchsia-400
/* Text */
hover:text-zinc-300
```

#### Transitions
```css
/* Basic transitions */
transition-colors
/* Complex transitions */
transition-all
```

## :pencil: Usage Guidelines

### 1. Dark Backgrounds
- Use `bg-neutral-950` as the main background color
- Apply `bg-neutral-900` for elevated surfaces like navbar and footer
- Utilize `bg-slate-950` or `bg-gray-950` for variety in dark sections
- Use `bg-zinc-900` for container backgrounds

### 2. Text Hierarchy
- Primary headings: `text-white`
- Section headings: `text-purple-300`
- Body text: `text-zinc-400`
- Interactive text: `text-blue-300` or `text-violet-200`

### 3. Interactive Elements
- Primary buttons: `bg-violet-200`
- Secondary buttons: `bg-blue-300`
- Hover states: `hover:bg-fuchsia-400`
- Action buttons: `bg-emerald-500`

### 4. Accessibility Considerations
- Maintain high contrast ratios
- Use dark text (`text-neutral-900`) on light backgrounds
- Ensure hover states are clearly visible
- Keep text readable with appropriate background combinations

### 5. Decorative Elements
- Use gradients sparingly for visual interest
- Apply backdrop-blur effects for depth
- Implement shadows to indicate elevation
- Combine colors thoughtfully in gradients

## :rocket: Getting Started

1. Include Tailwind CSS in your project:
```html
<head>
     <script src="https://unpkg.com/@tailwindcss/browser@4"></script>
</head>
```
2. Apply the color classes in your HTML elements.
3. Customize as needed by adjusting colors and effects.

Enjoy designing with Tailwind CSS! :purple_heart:

