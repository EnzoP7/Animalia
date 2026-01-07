GENERA UNA ESTRUCTURA COMPLETA DE UN SITIO WEB EN HTML + CSS (TAILWIND) PARA UNA VETERINARIA LOCAL LLAMADA “Animalia Veterinaria” (con enfoque en SEO y OPTIMIZACIÓN DE IMÁGENES).

1. **Objetivo del sitio web**

   - Landing page para Animalia Veterinaria diseñada para SEO local (Montevideo / Nueva Helvecia).
   - El sitio debe convertir visitantes en contactos (WhatsApp, llamada, formularios).
   - Optimizado para velocidad y móviles.

2. **Información base a usar**

   - Nombre del negocio: **Animalia Veterinaria**.
   - Descripción del negocio: clínica veterinaria que promueve el bienestar y la salud de las mascotas, con atención clínica, educación continua del equipo y publicación de información útil para dueños de mascotas (tomado de Instagram oficial de Animalia Veterinaria). :contentReference[oaicite:0]{index=0}
   - Teléfonos de contacto: **4554 4924** / **099 229 553** (según Instagram). :contentReference[oaicite:1]{index=1}
   - Horarios: Lunes a viernes de **8:00 a 13:00** y **14:00 a 18:30**, Sábados de **8:30 a 12:30** (según Instagram). :contentReference[oaicite:2]{index=2}
   - Contenidos de Instagram para extraer frases y mensajes de valor: bienestar animal, prevención de enfermedades (por ejemplo, rabia), historias y promociones. :contentReference[oaicite:3]{index=3}

3. **Estructura del sitio**

   - Header con logo y menú (Inicio, Servicios, Sobre Nosotros, Contacto, CTA WhatsApp).
   - Hero section con título H1 y llamada a la acción principal.
   - Sección “Sobre Animalia Veterinaria”.
   - Sección de **Servicios** (consultas, vacunaciones, diagnósticos, estética canina, etc.).
   - Galería optimizada con imágenes (usar imágenes comprimidas y `srcset`).
   - Sección de valor con testimonios y publicaciones recientes extraídas de Instagram.
   - Formulario de contacto + botones de WhatsApp y llamada.
   - Footer con datos estructurados.

4. **SEO On-Page**

   - Incluir meta tags (`title`, `description`) relevantes para veterinaria local.
   - Use marcado **schema.org LocalBusiness / VeterinaryCare** en JSON-LD.
   - Optimizar todas las imágenes con `alt` descriptivos y `srcset`.
   - H1 único en la página.
   - Enlaces de acción a WhatsApp y teléfono clickables.
   - Sitemap básico y archivo robots.txt sugeridos.

5. **Tailwind**

   - Incluir configuración base de Tailwind en el código.
   - Componentes responsivos.
   - Animaciones sutiles para botones CTA.

6. **Requisitos técnicos**

   - Código mínimo de JavaScript.
   - HTML semántico (header, main, section, footer).
   - Imágenes comprimidas con atributos `width` y `height`.
   - Texto amigable SEO para veterinaria en Uruguay/Montevideo.

7. **Salida esperada**
   - Un archivo principal `index.html` con Tailwind incluido.
   - Comentarios en el HTML indicando secciones.
   - Un archivo `.md` de instrucciones y checklist SEO explicando cada parte.
   Qué debe incluir el HTML final (resumen) <title>Animalia Veterinaria – Clínica y Servicios para Mascotas | Montevideo / Nueva Helvecia</title>
   <meta name="description" content="Animalia Veterinaria – cuidamos la salud y bienestar de tus mascotas. Consultas, vacunación, estética y atención profesional. Contacto: 099 229 553."> 📌 Schema LocalBusiness

<script type="application/ld+json">
{
  "@context":"https://schema.org",
  "@type":"VeterinaryCare",
  "name":"Animalia Veterinaria",
  "telephone":["+59899229553"],
  "address":{
    "@type":"PostalAddress",
    "addressLocality":"Nueva Helvecia",
    "addressCountry":"UY"
  },
  "openingHours":"Mo-Fr 08:00-18:30 Sa 08:30-12:30",
  "url":"https://tu-landing.com",
  "image":"https://scontent-eze1-2.cdninstagram.com/v/t51.2885-19/434782581_431271216056936_236236327279989544_n.jpg?efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby45MzAuYzIifQ&_nc_ht=scontent-eze1-2.cdninstagram.com&_nc_cat=108&_nc_oc=Q6cZ2QGqAJIgYh-2pDTfrMjd55eHkeZ0NFrjgdDE8MIv2a3YGb9iV5CaKPe8v5QkC2V6axQ&_nc_ohc=wu4c67TMNQkQ7kNvwHKuu0n&_nc_gid=GHcHYEBUxJY2cEzZjr8cIQ&edm=APoiHPcBAAAA&ccb=7-5&oh=00_AfrSfPm7wqzUw_AZ_rdISfx6a6HdMXjq2Dfeuz7TRUx5pA&oe=69637481&_nc_sid=22de04"
}
</script>  Hero

<h1 class="text-4xl font-bold">Bienvenido a Animalia Veterinaria – Salud y Bienestar para tu Mascota</h1>
<p class="text-lg">Atención profesional en consultas, vacunación, diagnóstico y cuidado integral de tus animales.</p>
<a href="https://wa.me/59899229553" class="btn btn-primary">Contactar por WhatsApp</a>
