# Colors

All semantic colors are registered via `@property` to support animation.
They automatically adapt to light/dark themes and high contrast.

| Variable | Default value (light) | Description |
|------------|-------------------------------|----------|
| `--color-primary` | `#2563eb` | Primary brand color |
| `--color-primary-dark` | `#1d4ed8` | Dark shade of primary |
| `--color-primary-light` | `#60a5fa` | Light shade of primary |
| `--color-primary-alpha-10` | `rgba(37,99,235,0.1)` | Primary with 10% opacity |
| `--color-primary-alpha-20` | `rgba(37,99,235,0.2)` | Primary with 20% opacity |
| `--color-primary-alpha-50` | `rgba(37,99,235,0.5)` | Primary with 50% opacity |
| `--color-primary-hover` | `var(--color-primary-dark)` | Hover color |
| `--color-primary-active` | `#1e40af` | Active color |
| `--color-primary-focus` | `var(--color-primary-alpha-20)` | Focus color (usually outline) |
| `--color-secondary` | `#7c3aed` | Secondary color |
| `--color-secondary-dark` | `#6d28d9` | Dark shade of secondary |
| `--color-secondary-light` | `#a78bfa` | Light shade of secondary |
| `--color-secondary-alpha-10` | `rgba(124,58,237,0.1)` | Secondary with 10% opacity |
| `--color-success` | `#22c55e` | Success color |
| `--color-success-dark` | `#16a34a` | Dark success shade |
| `--color-success-light` | `#86efac` | Light success shade |
| `--color-success-alpha-10` | `rgba(34,197,94,0.1)` | Success with 10% opacity |
| `--color-warning` | `#eab308` | Warning color |
| `--color-warning-dark` | `#ca8a04` | Dark warning shade |
| `--color-warning-light` | `#fde047` | Light warning shade |
| `--color-warning-alpha-10` | `rgba(234,179,8,0.1)` | Warning with 10% opacity |
| `--color-danger` | `#ef4444` | Error color |
| `--color-danger-dark` | `#dc2626` | Dark error shade |
| `--color-danger-light` | `#fca5a5` | Light error shade |
| `--color-danger-alpha-10` | `rgba(239,68,68,0.1)` | Error with 10% opacity |
| `--color-info` | `#06b6d4` | Info color |
| `--color-info-dark` | `#0891b2` | Dark info shade |
| `--color-info-light` | `#67e8f9` | Light info shade |
| `--color-info-alpha-10` | `rgba(6,182,212,0.1)` | Information with 10% transparency |
| `--color-neutral-50` … `--color-neutral-900` | See `colors.css` | Neutral scale from light gray to dark gray |
| `--color-canvas` | `Canvas` (system) | Page background (OS) |
| `--color-canvas-text` | `CanvasText` (system) | Text color on background (OS) |
| `--color-highlight` | `Highlight` (system) | Highlight color (OS) |
| `--color-highlight-text` | `HighlightText` (system) | Text color on highlight |
| `--color-field` | `Field` (system) | Input field background |
| `--color-field-text` | `FieldText` (system) | Input field text |
| `--color-button` | `ButtonFace` (system) | Button background |
| `--color-button-text` | `ButtonText` (system) | Button text |
| `--color-text` | `var(--color-neutral-800)` | Main text color |
| `--color-text-muted` | `var(--color-neutral-500)` | Muted text |
| `--color-text-inverse` | `var(--color-neutral-50)` | Inverse text (on dark background) |
| `--color-bg` | `var(--color-neutral-50)` | Main page background |
| `--color-bg-card` | `#ffffff` | Background for cards and modals |
| `--color-border` | `var(--color-neutral-200)` | Border color |
| `--color-border-focus` | `var(--color-primary)` | Border color on focus |
