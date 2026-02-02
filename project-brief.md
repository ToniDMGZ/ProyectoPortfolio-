# Project Brief

**Student:** [Your Name]  
**Handle:** @[your-github-username]  
**Course:** Web Design 2025 · Fall  
**Date:** [Fill in date - Week 2]

---

## Project Concept

### What are you building?

<!-- Describe your project in 2-3 sentences -->

### Who is it for?

<!-- Define your target audience -->

### Why does it matter?

<!-- Explain the purpose and value of your project -->

---

## Technical Approach

### Core Technologies

- [ ] HTML5 (semantic markup)
- [ ] CSS3 (responsive design)
- [ ] JavaScript (if applicable)
- [ ] Other: ****\_\_\_****

### Accessibility Goals

- [ ] Semantic HTML structure
- [ ] Proper heading hierarchy
- [ ] Alt text for images
- [ ] Keyboard navigation support
- [ ] Color contrast compliance
- [ ] Screen reader compatibility

### Responsive Design Strategy

- [ ] Mobile-first approach
- [ ] Flexible grid system
- [ ] Scalable typography
- [ ] Optimized images
- [ ] Touch-friendly interactions

---

## Content Strategy

### Key Sections/Pages

1. **Galería Principal** - Grid masonry responsivo (3 cols desktop → 2 cols tablet → 1 col mobile) por series temáticas
   - Cada obra: imagen + título + año + técnica
   - Click → detail modal/slide con descripción expandida
   - Filtros opcionales (por serie, técnica, año) si >30 obras

2. **Sobre el Artista** - Bio resumida + técnicas utilizadas + inspiraciones
   - Humanizar el proceso creativo
   - Enlaces a secciones principales

3. **Contacto/Colaboraciones** - CTAs claros (formulario, social media, email)
   - Profesionalismo + accesibilidad

### Content Sources

<!-- Where will your content come from? -->

### Multilingual Considerations

- Primary language:
- Secondary language (optional):
- Translation strategy:

---

## Design Direction

### Visual Style

<!-- Describe your aesthetic approach -->

### Color Palette

<!-- List your main colors -->

### Typography

<!-- What fonts/typeface approach will you use? -->

### Design Decisions (from Pattern Analysis Feb 2026)

#### Decisión 1: Layout de Galería - Masonry Grid Temático
- **Patrón:** Grid responsivo (3 cols desktop → 2 cols tablet → 1 col mobile)
- **Justificación:** Combina minimalismo visual (Martin Campos) con profesionalismo (Veta Galería); respeta `--max-width` y `--container-padding` de `_variables.css`
- **Implementación:** Cada obra muestra imagen + título + año + técnica; click abre detail modal/slide
- **Rationale:** Secciones temáticas (por serie, técnica) vs cronológico mejora exploración sin sobrecargar
- **Respeta brief:** Facilita descubrimiento, accesible, escalable para >30 obras con filtros opcionales

#### Decisión 2: Contenido + Contexto Expandible
- **Patrón:** Minimalismo en grid + contexto completo en detail page
- **Justificación:** Balance entre estética limpia y suficiente metadato; UI profesional sin ruido visual
- **Implementación:** 
  - Grid: Imagen + Título + Año + Técnica (metadata mínimo)
  - Detail page: Descripción expandida + proceso + serie completa + contexto del artista
- **Rationale:** Reduce fricción de scroll (mobile-friendly) mientras permite profundidad (desktop engagement)
- **Respeta brief:** Humaniza proceso creativo (About) + información completa por proyecto

### Inspiration/References

<!-- List 2-3 websites or designs that inspire your approach -->
- https://www.awwwards.com/inspiration/desktop-grit-pictures 
- https://www.awwwards.com/sites/lady-gaga-official-website
- https://www.awwwards.com/sites/la-tatuajeria-tattoo-studio
- https://www.martin-campos.com/ 
- https://vetagaleria.com/es/artists/44-matias-sanchez/

**Análisis detallado:** Ver `docs/prompt-analisis-galerias.md` 
---

## Success Metrics

### Week 4 Goals

- [ ] Functional homepage
- [ ] Basic responsive layout
- [ ] Core content in place
- [ ] Accessible markup

### Final Project Goals

- [ ] Fully responsive across devices
- [ ] Meets WCAG 2.1 AA standards
- [ ] Fast loading performance
- [ ] Complete content
- [ ] Polished visual design

---

## Reflection Questions

### What excites you most about this project?

### What challenges do you anticipate?

### How does this project connect to your learning goals?

---

_This brief will evolve as your project develops. Update it as needed and reference it in your weekly commits._
