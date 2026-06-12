# 🎨 CSS Functions — Complete Reference

A comprehensive reference of every CSS function, organized by category. Each file is clean, uncommented, and ready to use.

---

## 📁 Structure

```
css-functions-repo/
├── transform/          # translate, rotate, scale, skew, matrix (2D & 3D)
├── color/              # rgb, hsl, oklch, oklab, color-mix, light-dark
├── math/               # calc, clamp, min, max, trig, pow, sqrt, round
├── filter/             # blur, brightness, contrast, drop-shadow, backdrop-filter
├── gradient/           # linear, radial, conic — and repeating variants
├── shape/              # clip-path: circle, polygon, inset, path, shape-outside
├── sizing/             # minmax, repeat, fit-content, attr, url, env
├── custom-properties/  # var(), design tokens, @property
├── animation/          # cubic-bezier, steps(), linear() easing library
└── examples/           # 10 real-world patterns combining multiple functions
```

---

## ⚡ Quick Cheatsheet

```css
/* Math */
width: calc(100% - 2rem);
font-size: clamp(1rem, 2.5vw, 2rem);
padding: min(20px, 3%);

/* Transforms */
transform: translateX(50px) rotate(45deg) scale(1.2);
transform: perspective(500px) rotateY(30deg);

/* Colors */
color: oklch(0.7 0.2 120);
background: color-mix(in srgb, red 40%, blue);
background: light-dark(#fff, #111);

/* Gradients */
background: linear-gradient(135deg, #667eea, #764ba2);
background: conic-gradient(red, yellow, green, blue, red);

/* Filters */
filter: blur(4px) brightness(1.2) saturate(1.5);
backdrop-filter: blur(12px) saturate(1.8);

/* Shapes */
clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
clip-path: circle(50%);

/* Grid */
grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));

/* Variables */
color: var(--color-primary);
padding: var(--spacing, 1rem);

/* Timing */
transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
animation-timing-function: steps(8, end);
```

---

## 🌐 Browser Support

All functions target modern browsers (Chrome 111+, Firefox 108+, Safari 15.4+). Newer functions like `oklch()`, `color-mix()`, `light-dark()`, and `linear()` easing require the latest browser versions.

---

## 👤 Author

**Shahriar Kabir** · [GitHub](https://github.com/shahriarkabir07) · shahriar.kabir.swe@gmail.com
