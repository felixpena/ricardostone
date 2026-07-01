# Ricardo Stone — Landing Page

Fecha inicio: 2025 (aprox.)
Última sesión: 2026-07-02

## Qué es
Landing page para Ricardo Stone, analista Bitcoin privado en Chile desde 2017.
Consultoría privada, sin redes sociales, sin afiliaciones.

## Etapa actual
[x] MVP en construcción → **Producto operando**

## Stack
- HTML/CSS/JS puro, sin framework, sin build tool
- Formspree para el formulario (action: https://formspree.io/f/mpqgyzwr)
- Google Analytics 4: G-70L6Y0K48S
- GitHub: https://github.com/felixpena/ricardostone.git (branch master)
- Dominio: ricardostone.com (.com, no .cl)
- Hosting: GitHub Pages (o equivalente)

## Estado actual
- **Tema claro** implementado: fondo blanco #FFFFFF, crema #F5F3EF, bronce oscuro #7A5C1E
- Marco Analítico mantiene fondo oscuro (#111110) como contraste deliberado
- Footer oscuro (#111110) — cierre limpio
- Botón negro, JetBrains Mono eliminado (reemplazado por DM Sans con tracking)
- Tono copy alineado: sin disclaimers, sin defensivos, sin narrativa personal
- SEO optimizado: H1 semántico, Schema.org @graph (Person+ProfessionalService+FAQPage)
- Meta tags completas, canonical, geo tags, OG, Twitter Cards
- GA4 integrado + conversión en /gracias
- Formulario con redirect a /gracias (Formspree async)
- Cambios de esta sesión: pendiente commit + deploy a GitHub

## Secciones del sitio (en orden)
1. Nav (sticky, backdrop-blur)
2. Hero — headline "Todos entran. Pocos saben cuándo."
3. Insight — quote grande + 2 columnas de texto
4. Sobre Ricardo — grid texto + pullquote
5. Marco Analítico — 3 capas: onchain / precio / macro
6. Proceso — 3 pasos numerados
7. FAQ — accordion JS, 5 preguntas
8. Formulario — 3 campos + redirect
9. Footer

## Decisiones importantes
- Sin redes sociales (cliente es agente privado)
- Sin testimonios (propuesta rechazada por riesgo legal Ley 19.628)
- No mencionar métricas técnicas por nombre (MVRV, SOPR, Realized Price)
- No usar el término "ciclo" en texto visible (solo en meta keywords SEO)
- "Ciclo bitcoin 2025" mantenido en keywords para SEO
- Dominio .com elegido sobre .cl
- Formulario tercer campo: "Tu situación en dos líneas" (texto abierto)
- Tema claro elegido sobre oscuro: dark theme leía como "crypto/exchange", no como consultor senior
- Sin badge "30 min · sin costo · sin compromiso" — la escasez habla sola
- Sin narrativa personal en "Sobre Ricardo" — consultor senior no justifica su expertise
- Pregunta Ethereum eliminada del FAQ — no se defiende el alcance del servicio
- Gold oscuro (#7A5C1E) para fondos claros, gold original (#C4963A) solo en sección oscura

## Pendiente
- [ ] sitemap.xml
- [ ] robots.txt
- [ ] Política de privacidad (Ley 19.628 Chile)
- [ ] Registrar en Google Search Console (acción manual del cliente)
- [ ] Verificar dominio ricardostone.com apunta al hosting correcto

## Problemas encontrados y soluciones
- Edit tool encoding error en caracteres ñ/á: usar contexto circundante para match único
- Hero demasiado vacío en desktop: resuelto con 2 columnas en insight/sobre, secciones alternas, ancho 960px
