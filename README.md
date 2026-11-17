# Pastor Psicólogo Daniel Reyes · Fundación Shalom

Sitio web oficial del **Pastor Psicólogo Daniel Reyes** y la **Fundación de Restauración Shalom** (Barranquilla, Colombia).

Es un sitio estático de un solo archivo: **`index.html`**. No requiere build ni dependencias. Vercel lo publica automáticamente en cada `push` a la rama `main`.

## Cómo editar el contenido

Todo el contenido editable (textos, WhatsApp, redes, horarios) está en el objeto **`CONFIG`**, al inicio del `<script>` dentro de `index.html`. Los campos marcados con `______` deben reemplazarse por los datos oficiales:

- Correo electrónico
- NIT / Personería jurídica de la fundación
- Horarios de servicios y del programa radial
- Cifra de personas acompañadas
- URLs de redes sociales (Facebook, Instagram, YouTube, TikTok)

## Despliegue (Vercel)

1. En Vercel: **Add New → Project → Import** este repositorio de GitHub.
2. Framework Preset: **Other** (sitio estático). Root Directory: `/`. Sin Build Command.
3. Deploy. A partir de ahí, cada `push` a `main` genera un nuevo despliegue automático.

WhatsApp de contacto: +57 304 586 9127
