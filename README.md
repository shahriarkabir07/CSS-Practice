# 🎨 CSS Functions — Complete Reference Repository

> A comprehensive, organized reference of every CSS function — from everyday utilities to cutting-edge CSS Level 4+ features. Each file is heavily commented and ready to copy-paste.

---

## 📁 Repository Structure

```
css-functions-repo/
│
├── transform/
│   └── transform-functions.css       # 2D & 3D transform functions
│
├── color/
│   └── color-functions.css           # Color definition & manipulation
│
├── math/
│   └── math-functions.css            # Arithmetic, trig & rounding
│
├── filter/
│   └── filter-functions.css          # Visual filter effects
│
├── gradient/
│   └── gradient-functions.css        # Linear, radial & conic gradients
│
├── shape/
│   └── shape-functions.css           # Clip paths & float shapes
│
├── sizing/
│   └── sizing-functions.css          # Grid, counters, env() & url()
│
├── custom-properties/
│   └── custom-properties.css         # CSS variables & @property
│
├── animation/
│   └── animation-functions.css       # Easing & timing functions
│
└── examples/
    └── practical-examples.css        # Real-world combined patterns
```

---

## 📖 Function Index

### 🔄 Transform Functions
`/transform/transform-functions.css`

| Function | Description | Example |
|---|---|---|
| `translate(x, y)` | Move element on X and Y axes | `translate(50px, 100px)` |
| `translateX(x)` | Move element on X axis | `translateX(50px)` |
| `translateY(y)` | Move element on Y axis | `translateY(100px)` |
| `translateZ(z)` | Move element on Z axis (3D) | `translateZ(50px)` |
| `translate3d(x,y,z)` | Move element in 3D space | `translate3d(10px, 20px, 30px)` |
| `scale(x, y)` | Scale element on X and Y | `scale(1.5, 2)` |
| `scaleX(x)` | Scale element on X axis | `scaleX(1.5)` |
| `scaleY(y)` | Scale element on Y axis | `scaleY(2)` |
| `scaleZ(z)` | Scale element on Z axis (3D) | `scaleZ(2)` |
| `scale3d(x,y,z)` | Scale element in 3D space | `scale3d(1.5, 1.5, 1.5)` |
| `rotate(angle)` | Rotate element by angle | `rotate(45deg)` |
| `rotateX(angle)` | Rotate around X axis (3D) | `rotateX(45deg)` |
| `rotateY(angle)` | Rotate around Y axis (3D) | `rotateY(45deg)` |
| `rotateZ(angle)` | Rotate around Z axis (3D) | `rotateZ(45deg)` |
| `rotate3d(x,y,z,a)` | Rotate in 3D space | `rotate3d(1, 1, 0, 45deg)` |
| `skew(x, y)` | Skew element on X and Y | `skew(20deg, 10deg)` |
| `skewX(angle)` | Skew element on X axis | `skewX(20deg)` |
| `skewY(angle)` | Skew element on Y axis | `skewY(10deg)` |
| `matrix(a,b,c,d,e,f)` | 2D matrix transformation | `matrix(1, 0.5, -0.5, 1, 30, 10)` |
| `matrix3d(...)` | 4×4 3D matrix transformation | `matrix3d(1,0,0,0, 0,1,0,0, ...)` |
| `perspective(n)` | Add depth to 3D transforms | `perspective(500px)` |

---

### 🎨 Color Functions
`/color/color-functions.css`

| Function | Description | Example |
|---|---|---|
| `rgb(r, g, b)` | RGB color model | `rgb(255, 99, 71)` |
| `rgba(r, g, b, a)` | RGB with alpha | `rgba(255, 99, 71, 0.5)` |
| `hsl(h, s, l)` | Hue, saturation, lightness | `hsl(120, 100%, 50%)` |
| `hsla(h, s, l, a)` | HSL with alpha | `hsla(120, 100%, 50%, 0.3)` |
| `hwb(h, w, b)` | Hue, whiteness, blackness | `hwb(120 10% 10%)` |
| `lab(l, a, b)` | Perceptual Lab color space | `lab(50% -40 59)` |
| `lch(l, c, h)` | Cylindrical Lab (LCH) | `lch(50% 80 120)` |
| `oklch(l, c, h)` | Improved perceptual LCH | `oklch(0.7 0.2 120)` |
| `oklab(l, a, b)` | Improved perceptual Lab | `oklab(0.6 -0.1 0.15)` |
| `color(space r g b)` | Color in a given colorspace | `color(display-p3 1 0.5 0)` |
| `color-mix(in space, c1, c2)` | Blend two colors | `color-mix(in srgb, red 50%, blue)` |
| `light-dark(light, dark)` | Respond to color scheme | `light-dark(#333, #eee)` |

---

### 🧮 Math Functions
`/math/math-functions.css`

| Function | Description | Example |
|---|---|---|
| `calc(expression)` | Arithmetic with mixed units | `calc(100% - 2rem)` |
| `min(a, b, ...)` | Smallest of the values | `min(50%, 400px)` |
| `max(a, b, ...)` | Largest of the values | `max(300px, 50%)` |
| `clamp(min, val, max)` | Constrain value to a range | `clamp(1rem, 2.5vw, 2rem)` |
| `sin(angle)` | Sine of angle | `sin(30deg)` |
| `cos(angle)` | Cosine of angle | `cos(60deg)` |
| `tan(angle)` | Tangent of angle | `tan(45deg)` |
| `asin(value)` | Arcsine → angle | `asin(0.5)` |
| `acos(value)` | Arccosine → angle | `acos(0.5)` |
| `atan(value)` | Arctangent → angle | `atan(1)` |
| `atan2(y, x)` | Arctangent of y/x | `atan2(1, 1)` |
| `pow(base, exp)` | Base to the exponent | `pow(2, 10)` |
| `sqrt(value)` | Square root | `sqrt(16)` |
| `hypot(a, b, ...)` | Euclidean distance | `hypot(3, 4)` |
| `log(value, base?)` | Logarithm | `log(100, 10)` |
| `exp(value)` | e raised to the power | `exp(2)` |
| `abs(value)` | Absolute value | `abs(-20px)` |
| `sign(value)` | Sign: -1, 0, or 1 | `sign(-5)` |
| `round(strategy, v, step)` | Round to nearest step | `round(nearest, 15px, 10px)` |
| `mod(value, modulus)` | Modulo remainder | `mod(7, 3)` |
| `rem(value, divisor)` | Remainder (sign = value) | `rem(-7, 3)` |

---

### 🔮 Filter Functions
`/filter/filter-functions.css`

| Function | Description | Example |
|---|---|---|
| `blur(radius)` | Gaussian blur | `blur(4px)` |
| `brightness(amount)` | Adjust brightness | `brightness(1.5)` |
| `contrast(amount)` | Adjust contrast | `contrast(2)` |
| `drop-shadow(x y blur color)` | Shape-aware shadow | `drop-shadow(4px 4px 8px black)` |
| `grayscale(amount)` | Convert to grayscale | `grayscale(100%)` |
| `hue-rotate(angle)` | Shift all hues | `hue-rotate(90deg)` |
| `invert(amount)` | Invert colors | `invert(100%)` |
| `opacity(amount)` | Apply transparency | `opacity(0.5)` |
| `saturate(amount)` | Adjust saturation | `saturate(2)` |
| `sepia(amount)` | Apply sepia tone | `sepia(100%)` |
| `url(#id)` | Apply SVG filter | `url('#custom-filter')` |

> All filter functions work with both `filter` and `backdrop-filter` properties.

---

### 🌈 Gradient Functions
`/gradient/gradient-functions.css`

| Function | Description | Example |
|---|---|---|
| `linear-gradient(dir, colors...)` | Straight-line gradient | `linear-gradient(to right, red, blue)` |
| `repeating-linear-gradient(...)` | Repeating linear pattern | `repeating-linear-gradient(45deg, #000 0, #000 10px, #fff 10px, #fff 20px)` |
| `radial-gradient(shape, colors...)` | Circular/elliptical gradient | `radial-gradient(circle, yellow, red)` |
| `repeating-radial-gradient(...)` | Repeating radial rings | `repeating-radial-gradient(circle, red 0, red 10px, blue 10px, blue 20px)` |
| `conic-gradient(from angle, colors...)` | Sweep-around gradient | `conic-gradient(red, yellow, green, red)` |
| `repeating-conic-gradient(...)` | Repeating conic sweep | `repeating-conic-gradient(#fff 0deg 10deg, #000 10deg 20deg)` |

---

### ✂️ Shape & Clipping Functions
`/shape/shape-functions.css`

Used with `clip-path` and `shape-outside`:

| Function | Description | Example |
|---|---|---|
| `circle(r at x y)` | Circular clip region | `circle(50%)` |
| `ellipse(rx ry at x y)` | Elliptical clip region | `ellipse(50% 30% at center)` |
| `inset(offsets round r)` | Rectangular inset clip | `inset(10px round 15px)` |
| `polygon(x1 y1, x2 y2, ...)` | Custom polygon clip | `polygon(50% 0%, 0% 100%, 100% 100%)` |
| `path(svg-path)` | SVG path clip | `path('M 10,30 A 20,20 ...')` |

---

### 📐 Sizing & Utility Functions
`/sizing/sizing-functions.css`

| Function | Description | Example |
|---|---|---|
| `minmax(min, max)` | Grid track size range | `minmax(200px, 1fr)` |
| `fit-content(limit)` | Content-fit capped at limit | `fit-content(300px)` |
| `repeat(n, tracks)` | Repeat grid tracks | `repeat(3, 1fr)` |
| `repeat(auto-fill, ...)` | Fill with as many tracks as fit | `repeat(auto-fill, minmax(200px, 1fr))` |
| `repeat(auto-fit, ...)` | Like auto-fill, collapse empty | `repeat(auto-fit, minmax(200px, 1fr))` |
| `counter(name, style?)` | Insert counter value | `counter(section)` |
| `counters(name, sep, style?)` | Nested counter | `counters(section, ".")` |
| `attr(attribute)` | Read HTML attribute | `attr(data-label)` |
| `url(path)` | Reference external resource | `url("bg.jpg")` |
| `env(variable, fallback?)` | Device environment variable | `env(safe-area-inset-top)` |

---

### 🎛️ Custom Property Functions
`/custom-properties/custom-properties.css`

| Function | Description | Example |
|---|---|---|
| `var(--prop)` | Use a custom property | `var(--color-primary)` |
| `var(--prop, fallback)` | With fallback value | `var(--card-bg, white)` |
| `@property` | Define typed custom property | `@property --progress { syntax: "<number>"; }` |

---

### ⏱️ Animation & Timing Functions
`/animation/animation-functions.css`

| Function | Description | Example |
|---|---|---|
| `linear` | Constant speed | `transition-timing-function: linear` |
| `ease` | Slow→fast→slow (default) | `ease` |
| `ease-in` | Starts slow | `ease-in` |
| `ease-out` | Ends slow | `ease-out` |
| `ease-in-out` | Slow start and end | `ease-in-out` |
| `cubic-bezier(x1,y1,x2,y2)` | Custom Bézier curve | `cubic-bezier(0.25, 0.46, 0.45, 0.94)` |
| `steps(n, direction)` | Frame-by-frame stepping | `steps(8, end)` |
| `linear(p0, p1 x%, ...)` | Multi-point linear easing | `linear(0, 0.5 50%, 1)` |

---

## 🚀 Quick Reference Cheatsheet

```css
/* ── MATH ──────────────────────────────────────── */
width: calc(100% - 2rem);
font-size: clamp(1rem, 2.5vw, 2rem);
padding: min(20px, 3%);
height: max(200px, 30vh);

/* ── TRANSFORMS ─────────────────────────────────── */
transform: translateX(50px) rotate(45deg) scale(1.2);
transform: perspective(500px) rotateY(30deg);

/* ── COLORS ─────────────────────────────────────── */
color: oklch(0.7 0.2 120);
background: color-mix(in srgb, red 40%, blue);
background: light-dark(#fff, #111);

/* ── GRADIENTS ──────────────────────────────────── */
background: linear-gradient(135deg, #667eea, #764ba2);
background: radial-gradient(circle at 30% 70%, #f093fb, #f5576c);
background: conic-gradient(red, yellow, green, blue, red);

/* ── FILTERS ────────────────────────────────────── */
filter: blur(4px) brightness(1.2) saturate(1.5);
backdrop-filter: blur(12px) saturate(1.8);

/* ── SHAPES ─────────────────────────────────────── */
clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
clip-path: circle(50%);
clip-path: inset(10px round 15px);

/* ── GRID ───────────────────────────────────────── */
grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
grid-template-columns: minmax(200px, 20%) 1fr;

/* ── VARIABLES ──────────────────────────────────── */
color: var(--color-primary);
padding: var(--spacing, 1rem);

/* ── TIMING ─────────────────────────────────────── */
transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1);
animation-timing-function: steps(8, end);
```

---

## 🌐 Browser Support Notes

| Feature | Support |
|---|---|
| `calc()`, `min()`, `max()`, `clamp()` | ✅ All modern browsers |
| Transform functions | ✅ All modern browsers |
| `filter` / `backdrop-filter` | ✅ All modern browsers (`backdrop-filter` needs `-webkit-` prefix in some) |
| Gradient functions | ✅ All modern browsers |
| `oklch()`, `oklab()`, `color-mix()` | ✅ Chrome 111+, Firefox 113+, Safari 15.4+ |
| `light-dark()` | ✅ Chrome 123+, Firefox 120+, Safari 17.5+ |
| `color()` function | ✅ Chrome 111+, Firefox 113+, Safari 15+ |
| `hwb()` | ✅ Chrome 101+, Firefox 96+, Safari 15+ |
| `sin()`, `cos()`, `tan()` etc. | ✅ Chrome 111+, Firefox 108+, Safari 15.4+ |
| `pow()`, `sqrt()`, `log()` etc. | ✅ Chrome 111+, Firefox 108+, Safari 15.4+ |
| `round()`, `mod()`, `rem()`, `abs()` | ✅ Chrome 111+, Firefox 108+, Safari 15.4+ |
| `conic-gradient()` | ✅ Chrome 69+, Firefox 83+, Safari 12.1+ |
| `@property` | ✅ Chrome 85+, Firefox 128+, Safari 16.4+ |
| `linear()` easing | ✅ Chrome 113+, Firefox 112+, Safari 17.2+ |
| `path()` in `clip-path` | ✅ Chrome 88+, Firefox 71+, Safari 13.1+ |

---

## 📚 Learning Resources

- [MDN CSS Functions Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions)
- [CSS Tricks — A Complete Guide to CSS Functions](https://css-tricks.com/)
- [Can I Use — Browser Compatibility](https://caniuse.com/)
- [Lea Verou — CSS Color Level 4](https://lea.verou.me/)
- [Josh Comeau — CSS for JavaScript Developers](https://css-for-js.dev/)
- [Easing Functions — easings.net](https://easings.net/)

---

## 🙋 About

Maintained by **Shahriar Kabir**
- GitHub: [@shahriarkabir07](https://github.com/shahriarkabir07)
- Email: shahriar.kabir.swe@gmail.com

---

*Contributions, corrections, and additions are always welcome!*
