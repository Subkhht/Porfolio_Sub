# 🎮 Portfolio con Estética PlayStation 2

Portfolio profesional con diseño inspirado en la icónica consola PlayStation 2. Construido con Astro y TypeScript, este proyecto combina nostalgia retro con tecnología moderna.

## ✨ Características

- 🎨 **Diseño PS2 Auténtico**: Paleta de colores azul característico, efectos de brillo y estética de memoria card
- 💾 **Proyectos como Memory Cards**: Cada proyecto se presenta como un save de PS2
- ⚡ **Rendimiento Optimizado**: Construido con Astro para máxima velocidad
- � **Totalmente Responsive**: Se adapta perfectamente a todos los dispositivos
- 🎯 **Animaciones Suaves**: Transiciones y efectos visuales inspirados en el XMB de PS2
- ♿ **Accesible**: Diseño pensado para todos los usuarios

## 🚀 Inicio Rápido

### Requisitos Previos

- Node.js 18+ instalado
- npm o pnpm

### Instalación

1. **Las dependencias ya están instaladas** (el proyecto ya tiene `node_modules/`)

2. **Iniciar el servidor de desarrollo:**
   ```bash
   npm run dev
   ```
   
   El sitio estará disponible en `http://localhost:4321/`

## 📁 Estructura del Proyecto

```
/
├── public/              # Archivos estáticos
├── src/
│   ├── components/      # Componentes de Astro
│   │   ├── Header.astro      # Navegación con estilo PS2
│   │   ├── Hero.astro        # Sección hero con memory card
│   │   ├── Projects.astro    # Grid de proyectos como saves
│   │   ├── About.astro       # Información personal y skills
│   │   ├── Contact.astro     # Formulario de contacto
│   │   └── Footer.astro      # Pie de página
│   ├── layouts/
│   │   └── Layout.astro      # Layout principal
│   ├── pages/
│   │   └── index.astro       # Página principal
│   └── styles/
│       └── global.css        # Estilos globales con tema PS2
├── .github/
│   └── copilot-instructions.md
├── astro.config.mjs
├── package.json
└── README.md
```

## 🎨 Personalización

### Colores PS2

Los colores están definidos como variables CSS en `src/styles/global.css`:

```css
--ps2-blue-dark: #001f3f;
--ps2-blue-primary: #0047ab;
--ps2-blue-light: #4d94ff;
--ps2-blue-glow: #6bb6ff;
```

### Añadir Proyectos

Edita el archivo `src/components/Projects.astro` y modifica el array de proyectos:

```typescript
const projects = [
  {
    title: "Tu Proyecto",
    description: "Descripción del proyecto",
    technologies: ["React", "Node.js", "MongoDB"],
    link: "https://tu-proyecto.com",
    github: "https://github.com/tu-usuario/proyecto"
  }
]
```

### Información Personal

Actualiza tu información en:
- `src/components/Hero.astro` - Título y descripción
- `src/components/About.astro` - Sobre mí y habilidades
- `src/components/Contact.astro` - Información de contacto

## 🛠️ Scripts Disponibles

```bash
# Desarrollo
npm run dev          # Inicia servidor de desarrollo en localhost:4321

# Producción
npm run build        # Construye el sitio para producción
npm run preview      # Previsualiza el build de producción

# Otros
npm run astro        # Ejecuta comandos de Astro CLI
```

## 🌐 Despliegue

### Vercel (Recomendado)

1. Sube tu proyecto a GitHub
2. Importa el repositorio en [Vercel](https://vercel.com)
3. Vercel detectará Astro automáticamente
4. ¡Despliega!

### Netlify

1. Sube tu proyecto a GitHub
2. Importa en [Netlify](https://netlify.com)
3. Build command: `npm run build`
4. Publish directory: `dist`

### GitHub Pages

```bash
npm run build
# Sube la carpeta dist/ a tu rama gh-pages
```

## 🎯 Características del Diseño

### Componentes Principales

- **Header**: Navegación fija con menú hamburguesa responsive
- **Hero**: Sección principal con animación y memory card 3D
- **Projects**: Grid de tarjetas que simulan saves de PS2
- **About**: Información personal con estadísticas
- **Contact**: Formulario funcional con validación
- **Footer**: Enlaces y créditos

### Efectos Visuales

- Efectos de brillo (glow) en elementos interactivos
- Animaciones de fade-in escalonadas
- Hover states con transformaciones 3D
- Scrollbar personalizada con tema PS2
- Fondo con gradiente y efecto de líneas de escaneo

## 🔧 Tecnologías

- [Astro](https://astro.build) - Framework web
- TypeScript - Tipado estático
- CSS3 - Estilos modernos y animaciones
- Diseño responsive sin frameworks CSS

## 📝 Licencia

Este proyecto es de código abierto. Siéntete libre de usarlo para tu propio portfolio.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si tienes ideas para mejorar el diseño PS2 o añadir nuevas características, ¡abre un issue o pull request!

## � Inspiración

Este proyecto está inspirado en la interfaz XMB (XrossMediaBar) de PlayStation 2, una de las consolas más icónicas de la historia de los videojuegos.

---

**Hecho con ❤️ y nostalgia por la PS2**

¿Tienes preguntas? Abre un issue en GitHub o contáctame directamente.
