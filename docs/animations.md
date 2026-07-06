# Animations

Durations, easing functions, and ready-made transitions.

| Variable | Default Value | Description |
|------------|-----------------------|----------|
| `--duration-fast` | `100ms` | Very fast change |
| `--duration-base` | `200ms` | Base animation time |
| `--duration-slow` | `300ms` | Slow |
| `--duration-slower` | `500ms` | Very slow |
| `--ease-linear` | `linear` | Linear function |
| `--ease-in` | `cubic-bezier(0.4, 0, 1, 1)` | Acceleration at the start |
| `--ease-out` | `cubic-bezier(0, 0, 0.2, 1)` | Deceleration at the end |
| `--ease-in-out` | `cubic-bezier(0.4, 0, 0.2, 1)` | Acceleration and deceleration |
| `--ease-bounce` | `cubic-bezier(0.68, -0.55, 0.265, 1.55)` | Bounce effect |
| `--ease-spring` | `cubic-bezier(0.34, 1.56, 0.64, 1)` | Spring effect |
| `--transition-default` | `all var(--duration-base) var(--ease-in-out)` | Standard transition |
| `--transition-fast` | `all var(--duration-fast) var(--ease-out)` | Fast transition |
| `--transition-slow` | `all var(--duration-slow) var(--ease-in-out)` | Slow transition |
| `--transition-bounce` | `all var(--duration-slower) var(--ease-bounce)` | Bounce transition |
| `--transition-spring` | `all var(--duration-slower) var(--ease-spring)` | Spring-like transition |
| `--transition-opacity` | `opacity var(--duration-base) var(--ease-out)` | Opacity only |
| `--transition-transform` | `transform var(--duration-base) var(--ease-in-out)` | Transform only |
| `--transition-colors` | `color, background-color, border-color, outline-color var(--duration-base) var(--ease-in-out)` | Colors only |
