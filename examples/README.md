# Perbandingan Layout: Sonnet 4.5 vs Haiku 4.5

## Cara Melihat Examples

Buka file HTML di browser Anda:

```bash
# Sonnet 4.5 version
open examples/sonnet-4.5/landing-page.html

# Haiku 4.5 version
open examples/haiku-4.5/landing-page.html
```

## Perbedaan Utama

### 1. **CSS Variables & Design System**

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

| Version | HTML Size | CSS Lines | Complexity |
|---------|-----------|-----------|------------|
| Sonnet 4.5 | ~7KB | ~400 lines | High |
| Haiku 4.5 | ~4KB | ~200 lines | Low |

## Kesimpulan Visual

### Sonnet 4.5 menghasilkan:
- 🎨 Desain yang lebih polished dan professional
- ⚡ Animasi yang smooth dan modern
- 🎯 Better UX dengan micro-interactions
- 📱 Responsive design yang lebih thoughtful
- ♿ Accessibility yang lebih baik

### Haiku 4.5 menghasilkan:
- 📦 Kode yang lebih simple dan compact
- ⚡ Quick to implement
- 📚 Easy to understand dan modify
- 💰 Efficient untuk prototyping

## Rekomendasi

**Gunakan Sonnet 4.5** untuk production-ready layouts yang membutuhkan:
- Professional appearance
- Modern interactions
- Best practices implementation
- Accessibility compliance

**Gunakan Haiku 4.5** untuk:
- Quick prototypes
- Simple internal tools
- Learning projects
- Budget-constrained MVP
