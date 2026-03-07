🌐 CMCV Trader — Bio & Portfolio Web
Página personal de enlaces, proyectos y servicios. Diseñada como una mobile-first link-in-bio con estética editorial y acceso directo a todos los canales y productos digitales.

🚀 Demo
URL pública: cmcvtrader.github.io

✨ Características

Diseño mobile-first optimizado para móvil
Foto de perfil servida desde Cloudinary CDN
Anillo animado + indicador de disponibilidad
Links de redes sociales con iconos SVG oficiales
Cards de servicios destacadas con efecto hover
Cards de proyectos con barra lateral animada
Animaciones de entrada en cascada al cargar
Sin dependencias — HTML, CSS y JS puro


🗂️ Estructura del proyecto
cmcvtrader.github.io/
│
├── index.html          # Bio web principal (este archivo)
│
└── herramientas/
    └── h.html          # App Gestión de Turnos — 

🛠️ Stack
CapaTecnologíaUsoFrontendHTML · CSS · JSPágina estáticaHostingGitHub PagesDeploy automático desde rama mainImágenesCloudinaryFoto de perfil y media futuraTiendaPayhipProductos digitalesBD (otros proyectos)SupabasePostgreSQL + Auth

🖼️ Imagen de perfil
Alojada en Cloudinary bajo la carpeta /cmcvtrader/:
https://res.cloudinary.com/dnmbqinb4/image/upload/v.../cmcvtrader/fotomaxis_f68257.jpg

Para actualizar la foto, sube la nueva imagen a Cloudinary y reemplaza la URL en el src del <img id="profile-img">.


📦 Deploy
Este sitio se despliega automáticamente con GitHub Pages al hacer push a main.
bashgit add .
git commit -m "update bio"
git push origin main
La URL pública queda activa en https://cmcvtrader.github.io en menos de 60 segundos.

✏️ Personalización rápida
Qué cambiarDóndeNombre / bio<h1 class="name"> y <p class="bio">Foto de perfilsrc del <img id="profile-img">Links de redesAtributo href de cada .social-btnCards de proyectosSección Proyectos — editar href, título y descripciónCards de serviciosSección Servicios — editar href y badgeColoresVariables CSS en :root

🔗 Links relacionados

CMCV Store — Payhip
GitHub — cmcvtrader
Cloudinary Console


📄 Licencia
Proyecto personal — uso privado. No reutilizar sin autorización.

© 2026 CMCV Trader
