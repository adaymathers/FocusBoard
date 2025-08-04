# FocusBoard Landing Page

Landing page profesional para promocionar FocusBoard en GitHub Pages.

## 🚀 Características de la Landing Page

### ✅ Diseño Moderno
- Diseño responsive adaptado a móviles y desktop
- Gradientes atractivos y animaciones suaves
- Navegación sticky con scroll suave
- Efectos hover en tarjetas

### ✅ Secciones Completas
- **Hero Section**: Llamada a la acción principal
- **Features**: 6 características principales con iconos
- **Gallery**: Galería de capturas de pantalla
- **Technology Stack**: Tecnologías utilizadas
- **Download**: Sección de descarga con enlace directo
- **Footer**: Información adicional y enlaces

### ✅ SEO Optimizado
- Meta tags completos para SEO
- Open Graph tags para redes sociales
- Estructura semántica HTML5
- Contenido optimizado para buscadores

### ✅ GitHub Pages Ready
- Archivo index.html listo para publicar
- Configuración automática de galería
- Enlaces de descarga configurables
- Instrucciones de deployment incluidas

## 📁 Estructura de Archivos

```
web/
├── index.html                 # Landing page principal
├── gallery/                  # Capturas de pantalla
│   └── README.md             # Instrucciones para capturas
├── setup-github-pages.html   # Guía de configuración
└── LandingPage.txt           # Requisitos originales
```

## 🎨 Paleta de Colores

- **Primary**: Blue (#667eea → #764ba2)
- **Secondary**: Yellow (#fbbf24)
- **Background**: Gray-50 (#f9fafb)
- **Text**: Gray-900 (#111827)

## 📸 Capturas Recomendadas

Para una galería completa, agrega estas capturas en `/gallery/`:

1. `dashboard.png` - Dashboard principal
2. `tasks.png` - Gestión de tareas
3. `calendar.png` - Vista calendario
4. `subjects.png` - Gestión de materias
5. `documents.png` - Biblioteca de documentos
6. `settings.png` - Configuración

## 🔧 Personalización

### Enlaces de Descarga
Actualizar en `index.html` línea ~310:
```html
href="https://github.com/adaymathers/FocusBoard/releases/latest/download/FocusBoard-1.0.0-setup.exe"
```

### URLs del Proyecto
Ya actualizado con "adaymathers" en:
- Meta tags Open Graph
- Enlaces de GitHub
- Footer links

## 🚀 Deployment en GitHub Pages

1. **Crear repositorio público** en GitHub
2. **Subir archivos** de la carpeta `/web/`
3. **Habilitar GitHub Pages** en Settings
4. **Configurar source** como "Deploy from branch: main"
5. **Acceder** a `https://adaymathers.github.io/FocusBoard`

### Comandos Git
```bash
cd web/
git init
git add .
git commit -m "Add FocusBoard landing page"
git remote add origin https://github.com/adaymathers/FocusBoard.git
git push -u origin main
```

## 🎯 Características Destacadas

### Funcionalidades JavaScript
- Scroll suave entre secciones
- Animaciones on-scroll
- Carga dinámica de galería
- Navegación responsive

### Performance
- CSS inline para carga rápida
- Tailwind CDN optimizado
- Imágenes con lazy loading
- Código minificado

### Accesibilidad
- Navegación por teclado
- Alt tags en imágenes
- Contraste optimizado
- Estructura semántica

## 📱 Responsive Design

- **Mobile First**: Optimizado para móviles
- **Tablet**: Layout adaptado para tablets
- **Desktop**: Experiencia completa en escritorio
- **Large Screens**: Aprovecha pantallas grandes

---

**¡Tu landing page está lista para impresionar y convertir visitantes en usuarios!** 🚀
