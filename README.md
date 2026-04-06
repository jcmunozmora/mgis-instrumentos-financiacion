# Nuevos Instrumentos de Financiación del Sector Social

Sitio web del curso para la Maestría en Gerencia e Innovación Social (MGIS) — Universidad EAFIT.

## Estructura

```
04_web/
├── _quarto.yml          # Configuración del sitio
├── index.qmd            # Página de inicio
├── syllabus.qmd         # Syllabus completo
├── unidades/
│   ├── unidad-01.qmd   # Ecosistema del financiamiento de impacto
│   ├── unidad-02.qmd   # Instrumentos de financiamiento social
│   └── unidad-03.qmd   # Estructuración e implementación
├── recursos/
│   ├── bibliografia.qmd
│   ├── glosario.qmd
│   ├── herramientas.qmd
│   └── styles.css
└── .github/workflows/
    └── publish.yml      # Deploy automático a GitHub Pages
```

## Uso local

```bash
# Previsualizar el sitio
quarto preview

# Renderizar el sitio completo
quarto render

# Publicar en GitHub Pages (manual)
quarto publish gh-pages
```

## Publicación automática

El sitio se publica automáticamente en GitHub Pages cuando se hace push a la rama `main`, usando el workflow de GitHub Actions en `.github/workflows/publish.yml`.

## Información del curso

- **Programa:** Maestría en Gerencia e Innovación Social (MGIS)
- **Escuela:** Finanzas, Economía y Gobierno — EAFIT
- **Semestre:** III | 2 créditos | 24 horas
- **Profesor:** Juan Carlos Muñoz Mora (jcmunoz@eafit.edu.co)
