# Spacing

An adaptive spacing scale based on `clamp()`.
Includes positive and negative values, as well as dedicated variables for `gap`.

| Variable | Default Value | Description |
|----------|---------------|-------------|
| `--spacing-unit` | `clamp(0.25rem, 0.5vw + 0.1rem, 0.5rem)` | Base unit used to calculate all spacing values ​​|
| `--space-0` | `0` | Zero spacing |
| `--space-0-5` | `calc(var(--spacing-unit) * 0.5)` | 0.5 units |
| `--space-1` | `calc(var(--spacing-unit) * 1)` | 1 unit |
| `--space-1-5` | `calc(var(--spacing-unit) * 1.5)` | 1.5 units |
| `--space-2` | `calc(var(--spacing-unit) * 2)` | 2 units |
| `--space-2-5` | `calc(var(--spacing-unit) * 2.5)` | 2.5 |
| `--space-3` | `calc(var(--spacing-unit) * 3)` | 3 |
| `--space-3-5` | `calc(var(--spacing-unit) * 3.5)` | 3.5 |
| `--space-4` | `calc(var(--spacing-unit) * 4)` | 4 |
| `--space-5` | `calc(var(--spacing-unit) * 5)` | 5 |
| `--space-6` | `calc(var(--spacing-unit) * 6)` | 6 |
| `--space-7` | `calc(var(--spacing-unit) * 7)` | 7 |
| `--space-8` | `calc(var(--spacing-unit) * 8)` | 8 |
| `--space-9` | `calc(var(--spacing-unit) * 9)` | 9 |
| `--space-10` | `calc(var(--spacing-unit) * 10)` | 10 |
| `--space-12` | `calc(var(--spacing-unit) * 12)` | 12 |
| `--space-14` | `calc(var(--spacing-unit) * 14)` | 14 |
| `--space-16` | `calc(var(--spacing-unit) * 16)` | 16 |
| `--space-20` | `calc(var(--spacing-unit) * 20)` | 20 |
| `--space-24` | `calc(var(--spacing-unit) * 24)` | 24 |
| `--space-n-0-5` | `calc(var(--space-0-5) * -1)` | Negative padding -0.5 |
| `--space-n-1` | `calc(var(--space-1) * -1)` | -1 |
| `--space-n-1-5` | `calc(var(--space-1-5) * -1)` | -1.5 |
| `--space-n-2` | `calc(var(--space-2) * -1)` | -2 |
| `--space-n-2-5` | `calc(var(--space-2-5) * -1)` | -2.5 |
| `--space-n-3` | `calc(var(--space-3) * -1)` | -3 |
| `--space-n-4` | `calc(var(--space-4) * -1)` | -4 |
| `--space-n-5` | `calc(var(--space-5) * -1)` | -5 |
| `--space-n-6` | `calc(var(--space-6) * -1)` | -6 |
| `--space-n-8` | `calc(var(--space-8) * -1)` | -8 |
| `--space-n-10` | `calc(var(--space-10) * -1)` | -10 |
| `--space-n-12` | `calc(var(--space-12) * -1)` | -12 |
| `--space-n-16` | `calc(var(--space-16) * -1)` | -16 |
| `--gap-0` … `--gap-16` | same values ​​as `--space-*` | Semantic variables for `gap` (in grid / flex) |
