# Funvalor - Sitio Web Estático

Este es el sitio web completo de Fundación Valores y Raíces (Funvalor) compilado como archivos estáticos HTML, CSS y JavaScript.

## Contenido

- `index.html` - Página principal (contiene todo el HTML)
- `assets/` - Carpeta con archivos CSS y JavaScript compilados
- `images/` - Carpeta con imágenes del sitio
- `README.md` - Este archivo

## Cómo Hospedar

### Opción 1: Servidor Web Local (Python)
```bash
# En la carpeta del sitio
python3 -m http.server 8000
# Luego accede a http://localhost:8000
```

### Opción 2: Servidor Web Local (Node.js)
```bash
# Instala http-server globalmente
npm install -g http-server

# En la carpeta del sitio
http-server
```

### Opción 3: Hosting en la Nube
Puedes subir estos archivos a cualquier servicio de hosting estático:

- **Netlify** (Gratuito): Arrastra la carpeta a netlify.com
- **Vercel** (Gratuito): Sube a vercel.com
- **GitHub Pages** (Gratuito): Sube a un repositorio GitHub
- **AWS S3** (Pago): Configura un bucket S3
- **Hosting tradicional**: Sube vía FTP a tu servidor web

### Opción 4: Servidor Apache/Nginx
Copia todos los archivos a la carpeta `public_html` o `www` de tu servidor web.

## Características

✓ Completamente estático (HTML + CSS + JavaScript)
✓ Almacenamiento local de fotos en el navegador
✓ Responsive y compatible con todos los navegadores
✓ Sin dependencias externas
✓ Rápido y seguro

## Almacenamiento de Fotos

Las fotos que agregues a cada actividad se guardan en el almacenamiento local del navegador (localStorage). Esto significa:

- Las fotos persisten aunque cierres el navegador
- Cada navegador/dispositivo tiene su propio almacenamiento
- Capacidad aproximada: 5-10 MB por navegador
- Las fotos se guardan automáticamente al cargarlas

## Estructura de Archivos

```
funvalor-web-export/
├── index.html              # Página principal
├── assets/
│   ├── index-[hash].css   # Estilos compilados
│   └── index-[hash].js    # JavaScript compilado
├── images/
│   └── funvalor-logo.png  # Logo de la fundación
└── README.md              # Este archivo
```

## Notas Importantes

1. El archivo `index.html` contiene TODO el contenido del sitio
2. Los archivos en `assets/` son referencias desde el HTML
3. No necesitas instalar nada para usar este sitio
4. Funciona offline una vez que se carga en el navegador

## Soporte

Si tienes preguntas o problemas, contacta a Funvalor.

---

**Generado:** Enero 2026
**Versión:** 1.0
