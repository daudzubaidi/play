# Perbandingan Layout: Opus 4.1 vs Sonnet 4.5 vs Haiku 4.5

## Cara Melihat Examples

Buka file HTML di browser Anda:

```bash
# Opus 4.1 version (Premium)
open examples/opus-4.1/landing-page.html

# Sonnet 4.5 version (Balanced)
open examples/sonnet-4.5/landing-page.html

# Haiku 4.5 version (Fast)
open examples/haiku-4.5/landing-page.html
```

## Perbedaan Utama

### 1. **CSS Variables & Design System**

**Opus 4.1:**
- ✅✅ Comprehensive design system dengan tokens lengkap
- ✅✅ HSL color system untuk easy manipulation
- ✅✅ Multi-level shadows (xs, sm, md, lg, xl, 2xl)
- ✅✅ Advanced easing functions (spring, bounce)
- ✅✅ Z-index scale dan spacing scale
- ✅✅ Fluid typography dengan clamp()

**Sonnet 4.5:**
- ✅ Menggunakan CSS custom properties (`:root`)
- ✅ Design system yang konsisten dengan color palette
- ✅ Shadows dengan berbagai level (sm, md, lg)
- ✅ Transition yang smooth dengan cubic-bezier

**Haiku 4.5:**
- ❌ Hardcoded values
- ❌ Tidak ada design system
- ❌ Shadow sederhana
- ❌ Transition basic

### 2. **Animations & Interactivity**

**Opus 4.1:**
- ✅✅ Advanced keyframe animations dengan timing yang perfect
- ✅✅ Intersection Observer untuk scroll-based animations
- ✅✅ Performance-optimized dengan requestAnimationFrame
- ✅✅ Micro-interactions pada semua interactive elements
- ✅✅ Multi-layer hover effects (icon rotation, scale, gradient shift)
- ✅✅ Backdrop blur dengan saturate untuk glass morphism
- ✅✅ Gradient borders dengan mask-composite

**Sonnet 4.5:**
- ✅ Keyframe animations (fadeInLeft, fadeInRight)
- ✅ Navbar scroll effect yang smooth
- ✅ Hover states yang sophisticated
- ✅ Transform & translateY effects
- ✅ Backdrop blur untuk modern glass effect

**Haiku 4.5:**
- ❌ Tidak ada animations
- ❌ Tidak ada JavaScript interactions
- ❌ Hover states basic
- ❌ Tidak ada transform effects

### 3. **Accessibility**

**Opus 4.1:**
- ✅✅ Complete ARIA labels dan roles
- ✅✅ prefers-reduced-motion support
- ✅✅ prefers-contrast: high support
- ✅✅ Advanced focus-visible states
- ✅✅ Semantic HTML5 elements
- ✅✅ Keyboard navigation optimized
- ✅✅ Screen reader friendly

**Sonnet 4.5:**
- ✅ Focus states dengan outline
- ✅ prefers-reduced-motion support
- ✅ Semantic HTML
- ✅ ARIA-friendly structure

**Haiku 4.5:**
- ⚠️ Basic accessibility
- ❌ Tidak ada prefers-reduced-motion
- ✅ Semantic HTML
- ⚠️ Minimal focus states

### 4. **Responsive Design**

**Opus 4.1:**
- ✅✅ Fluid typography dengan clamp() functions
- ✅✅ Advanced grid dengan auto-fit & minmax
- ✅✅ Container queries ready
- ✅✅ Mobile-first approach
- ✅✅ Responsive spacing dan sizing
- ✅✅ Thoughtful breakpoints strategy

**Sonnet 4.5:**
- ✅ Grid yang lebih flexible (auto-fit, minmax)
- ✅ Responsive typography (rem units)
- ✅ Better mobile experience
- ✅ Thoughtful breakpoints

**Haiku 4.5:**
- ✅ Basic responsive layout
- ⚠️ Simple media queries
- ⚠️ Fixed typography scaling
- ⚠️ Limited breakpoints

### 5. **Code Quality**

**Opus 4.1:**
- ✅✅ Extremely well-organized dengan sections
- ✅✅ BEM naming conventions
- ✅✅ Highly maintainable architecture
- ✅✅ Performance-optimized JavaScript
- ✅✅ CSS custom properties untuk theming
- ✅✅ Scalable design system
- ✅✅ Production-ready code quality

**Sonnet 4.5:**
- ✅ Well-organized CSS
- ✅ BEM-like naming conventions
- ✅ Maintainable code structure
- ✅ Performance optimized
- ✅ Modern CSS features (Grid, Flexbox advanced)

**Haiku 4.5:**
- ✅ Clean and simple
- ✅ Easy to understand
- ⚠️ Basic structure
- ⚠️ Limited use of modern features

## Perbandingan Ukuran File

| Version | HTML Size | CSS Lines | JS Lines | Complexity |
|---------|-----------|-----------|----------|------------|
| Opus 4.1 | ~15KB | ~650 lines | ~30 lines | Very High |
| Sonnet 4.5 | ~7KB | ~400 lines | ~10 lines | High |
| Haiku 4.5 | ~4KB | ~200 lines | 0 lines | Low |

## Kesimpulan Visual

### Opus 4.1 menghasilkan:
- 🏆 Desain paling sophisticated dan premium
- 🎨 Complete design system dengan tokens
- ⚡ Advanced animations dengan Intersection Observer
- 🎯 Exceptional UX dengan micro-interactions
- 📱 Fluid typography dan responsive excellence
- ♿ Full WCAG compliance
- 🔧 Highly maintainable architecture

### Sonnet 4.5 menghasilkan:
- 🎨 Desain yang polished dan professional
- ⚡ Animasi yang smooth dan modern
- 🎯 Better UX dengan micro-interactions
- 📱 Responsive design yang thoughtful
- ♿ Accessibility yang baik

### Haiku 4.5 menghasilkan:
- 📦 Kode yang simple dan compact
- ⚡ Quick to implement
- 📚 Easy to understand dan modify
- 💰 Efficient untuk prototyping

## Rekomendasi

**Gunakan Opus 4.1** untuk flagship projects yang membutuhkan:
- Premium design quality
- Complete design systems
- Advanced interactions & animations
- Full accessibility compliance
- Scalable architecture
- When budget allows

**Gunakan Sonnet 4.5** untuk most production layouts yang membutuhkan:
- Professional appearance
- Modern interactions
- Best practices implementation
- Good accessibility
- Best value for money

**Gunakan Haiku 4.5** untuk:
- Quick prototypes
- Simple internal tools
- Learning projects
- Budget-constrained MVP
- When speed matters most
