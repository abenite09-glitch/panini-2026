# Álbum Panini Mundial 2026 — PWA

## Cómo publicar en Vercel (gratis, 5 minutos)

### Paso 1 — Sube el código a GitHub
1. Entra a https://github.com y crea una cuenta si no tienes
2. Crea un repositorio nuevo: "panini-2026"
3. Sube los archivos de esta carpeta (index.html, manifest.json, sw.js, icons/)

### Paso 2 — Despliega en Vercel
1. Entra a https://vercel.com y regístrate con tu cuenta de GitHub
2. Clic en "Add New Project"
3. Importa el repositorio "panini-2026"
4. Clic en "Deploy" — sin cambiar nada más
5. Vercel te da un link tipo: https://panini-2026-xyz.vercel.app

### Paso 3 — Comparte con amigos
- Manda el link por WhatsApp
- Cada persona abre el link en Safari (iPhone) o Chrome (Android)
- En iPhone: toca el botón compartir → "Agregar a pantalla de inicio"
- En Android: toca el menú → "Instalar aplicación"
- ¡Listo! Se instala como app con ícono propio

## Características
- Funciona offline (sin internet después de la primera visita)
- Cada usuario guarda sus propios datos en su celular
- Sin cuentas, sin registro
- Gratis para siempre en Vercel (hasta 100GB de tráfico/mes)

## Estructura de archivos
```
panini-pwa/
├── index.html       ← App principal
├── manifest.json    ← Configuración PWA
├── sw.js            ← Service worker (offline)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```
