# Animalia Veterinaria - Checklist SEO e Instrucciones

## Archivos Creados

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Landing page principal con todas las secciones |
| `robots.txt` | Instrucciones para bots de búsqueda |
| `sitemap.xml` | Mapa del sitio para indexación |
| `images/` | Carpeta para imágenes (necesita agregar imágenes) |

---

## Checklist SEO On-Page

### Meta Tags
- [x] `<title>` optimizado con keywords locales (Montevideo / Nueva Helvecia)
- [x] `<meta description>` con llamada a la acción y teléfono
- [x] `<meta keywords>` con términos relevantes
- [x] `<meta robots>` permitiendo indexación
- [x] URL canónica definida
- [x] Open Graph tags para redes sociales
- [x] Twitter Card tags

### Estructura HTML
- [x] HTML5 semántico (header, main, section, footer, article, nav)
- [x] Un único H1 en la página
- [x] Jerarquía de encabezados correcta (H1 > H2 > H3)
- [x] Atributos `lang="es"` en el HTML
- [x] Enlaces con `rel="noopener noreferrer"` para externos

### Schema.org (Datos Estructurados)
- [x] Schema tipo `VeterinaryCare` implementado
- [x] Nombre del negocio
- [x] Teléfonos de contacto
- [x] Dirección (Nueva Helvecia, Uruguay)
- [x] Horarios de apertura
- [x] Redes sociales (sameAs)

### Imágenes
- [x] Atributos `width` y `height` definidos
- [x] Atributos `alt` descriptivos con keywords
- [x] `loading="lazy"` para imágenes no críticas
- [x] `srcset` preparado para imágenes responsivas

### Accesibilidad
- [x] Labels en formularios
- [x] `aria-label` en botones de iconos
- [x] Contraste de colores adecuado
- [x] Navegación por teclado funcional

### Performance
- [x] Tailwind CSS via CDN (considerar compilar para producción)
- [x] JavaScript mínimo
- [x] CSS animaciones optimizadas

---

## Imágenes Necesarias

Debes agregar las siguientes imágenes en la carpeta `images/`:

| Nombre del archivo | Dimensiones recomendadas | Descripción |
|--------------------|--------------------------|-------------|
| `animalia-logo.png` | 200x200 px | Logo principal del negocio |
| `animalia-logo-white.png` | 200x200 px | Logo en blanco para footer |
| `favicon.png` | 32x32 px | Favicon del sitio |
| `hero-veterinaria.jpg` | 1200x1000 px | Imagen principal del hero |
| `equipo-veterinario.jpg` | 800x600 px | Foto del equipo o clínica |
| `equipo-veterinario-400.jpg` | 400x300 px | Versión pequeña (srcset) |
| `equipo-veterinario-600.jpg` | 600x450 px | Versión mediana (srcset) |
| `equipo-veterinario-800.jpg` | 800x600 px | Versión grande (srcset) |
| `galeria-1.jpg` | 600x600 px | Foto de mascota/paciente 1 |
| `galeria-2.jpg` | 600x600 px | Foto de mascota/paciente 2 |
| `galeria-3.jpg` | 600x600 px | Foto de mascota/paciente 3 |
| `galeria-4.jpg` | 600x600 px | Foto de mascota/paciente 4 |
| `og-image.jpg` | 1200x630 px | Imagen para compartir en redes |

### Recomendaciones para imágenes:
1. **Comprimir** todas las imágenes antes de subir (usar TinyPNG, Squoosh, etc.)
2. **Formato WebP** es preferible para mejor rendimiento
3. **Nombres descriptivos** ayudan al SEO (ej: `veterinario-atendiendo-perro.jpg`)
4. **Alt text** ya está configurado en el HTML

---

## Acciones Post-Lanzamiento

### Google Search Console
1. Verificar propiedad del dominio
2. Enviar sitemap.xml
3. Solicitar indexación de la página principal

### Google Business Profile
1. Crear/reclamar perfil de Google Business
2. Completar toda la información del negocio
3. Agregar fotos de la clínica
4. Vincular con el sitio web

### Analíticas
1. Instalar Google Analytics 4
2. Configurar objetivos de conversión:
   - Clics en WhatsApp
   - Clics en teléfono
   - Envíos de formulario

---

## Configuración del Dominio

Actualizar estos valores cuando tengas el dominio final:

1. En `index.html`:
   - `<link rel="canonical" href="https://TU-DOMINIO.com/">`
   - `<meta property="og:url" content="https://TU-DOMINIO.com/">`
   - En el Schema.org: `"url": "https://TU-DOMINIO.com"`

2. En `robots.txt`:
   - `Sitemap: https://TU-DOMINIO.com/sitemap.xml`

3. En `sitemap.xml`:
   - Cambiar todas las URLs a tu dominio real

---

## Estructura Final del Proyecto

```
Animalia/
├── index.html          # Página principal
├── robots.txt          # Configuración para bots
├── sitemap.xml         # Mapa del sitio
├── SEO-CHECKLIST.md    # Este archivo
├── Reglas.md           # Especificaciones originales
└── images/
    ├── animalia-logo.png
    ├── animalia-logo-white.png
    ├── favicon.png
    ├── hero-veterinaria.jpg
    ├── equipo-veterinario.jpg
    ├── equipo-veterinario-400.jpg
    ├── equipo-veterinario-600.jpg
    ├── equipo-veterinario-800.jpg
    ├── galeria-1.jpg
    ├── galeria-2.jpg
    ├── galeria-3.jpg
    ├── galeria-4.jpg
    └── og-image.jpg
```

---

## Contacto del Negocio (Referencia)

- **Nombre:** Animalia Veterinaria
- **Teléfono fijo:** 4554 4924
- **Celular/WhatsApp:** 099 229 553
- **Horarios:** Lun-Vie 8:00-13:00 y 14:00-18:30 | Sáb 8:30-12:30
- **Ubicación:** Nueva Helvecia, Colonia, Uruguay
- **Instagram:** @animalia.veterinaria
