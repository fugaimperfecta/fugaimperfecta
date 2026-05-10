````markdown name=README.md
# Fotografía Minimalista

Una página web de portafolio fotográfico con diseño minimalista en escala de grises. Atractiva, elegante y completamente funcional.

## 🎨 Características

- **Diseño Minimalista**: Paleta de colores en escala de grises (blanco, grises y negro)
- **Responsivo**: Compatible con dispositivos móviles, tablets y desktop
- **Galería Interactiva**: Sistema de lightbox con navegación por teclado
- **Navegación Suave**: Scroll suave y menú sticky
- **Formulario de Contacto**: Validación de formularios integrada
- **Rendimiento Optimizado**: CSS puro, JavaScript vanilla, sin dependencias externas
- **Accesible**: Semántica HTML5 y atributos ARIA

## 📁 Estructura del Proyecto

```
.
├── index.html        # Estructura HTML principal
├── styles.css        # Estilos CSS minimalistas
├── script.js         # Funcionalidad JavaScript interactiva
└── README.md         # Este archivo
```

## 🚀 Características Principales

### 1. **Header & Navegación**
- Navbar sticky con logo minimalista
- Menú responsive con hamburger menu para móviles
- Enlaces con efecto hover elegante

### 2. **Sección Hero**
- Título atractivo con call-to-action
- Gradiente sutil en escala de grises
- Botón con efecto hover

### 3. **Galería de Imágenes**
- Grid responsivo de 6 imágenes
- Overlay con título al pasar el mouse
- Lightbox modal con navegación:
  - Click en imágenes
  - Botones siguiente/anterior
  - Flechas del teclado (← →)
  - Tecla ESC para cerrar

### 4. **Sección Acerca de**
- Descripción del enfoque fotográfico
- Fondo en tono gris claro
- Texto centrado y legible

### 5. **Formulario de Contacto**
- Validación de campos
- Validación de email
- Respuesta al usuario
- Diseño limpio y minimalista

### 6. **Footer**
- Enlaces a redes sociales
- Copyright
- Fondo oscuro elegante

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Diseño responsivo con variables CSS
- **JavaScript Vanilla**: Sin frameworks externos
- **Grid & Flexbox**: Layout moderno

## 📱 Responsividad

- **Desktop**: Experiencia completa con navegación clásica
- **Tablet**: Grid adaptado, navegación completa
- **Móvil**: Hamburger menu, galería en una columna, formulario optimizado

### Breakpoints
- `768px`: Cambio a navegación móvil
- `480px`: Optimización para pantallas muy pequeñas

## 🎯 Paleta de Colores

```css
--color-black: #0a0a0a
--color-dark-gray: #1a1a1a
--color-gray: #4a4a4a
--color-light-gray: #d0d0d0
--color-white: #f5f5f5
--color-accent: #7a7a7a
```

## ⌨️ Controles del Lightbox

| Tecla/Acción | Función |
|--------------|---------|
| Click en imagen | Abrir lightbox |
| Flecha Derecha | Siguiente imagen |
| Flecha Izquierda | Imagen anterior |
| ESC | Cerrar lightbox |
| Click fuera | Cerrar lightbox |

## 🚀 Cómo Usar

### 1. **Clonar el repositorio**
```bash
git clone https://github.com/fugaimperfecta/fugaimperfecta.git
cd fugaimperfecta
```

### 2. **Abrir en navegador**
```bash
# Opción 1: Doble click en index.html
# Opción 2: Usar un servidor local
python -m http.server 8000
# Luego abre: http://localhost:8000
```

### 3. **Personalizar**

#### Cambiar imágenes
Reemplaza las URLs de las imágenes en `index.html`:
```html
<img src="tu-imagen.jpg" alt="Descripción">
```

#### Modificar textos
- Logo: Cambia "FOTOGRAFÍA" en el `<h1>` del header
- Sobre ti: Edita el contenido en la sección `#acerca`
- Enlaces sociales: Actualiza los enlaces en el footer

#### Ajustar colores
En `styles.css`, modifica las variables CSS en `:root`:
```css
:root {
    --color-black: #0a0a0a;
    --color-white: #f5f5f5;
    /* ... etc */
}
```

## 📝 Formulario de Contacto

El formulario incluye:
- Validación de campos vacíos
- Validación de formato de email
- Mensaje de confirmación
- Reset del formulario al enviar

**Nota**: Actualmente es un formulario local. Para funcionalidad completa, integra con:
- Formspree
- EmailJS
- Backend personalizado

## 🌐 Despliegue

### GitHub Pages
```bash
# 1. Ve a Settings > Pages
# 2. Selecciona "Deploy from a branch"
# 3. Elige rama "main"
# 4. Guarda
# Tu sitio estará en: https://fugaimperfecta.github.io/fugaimperfecta
```

### Otras opciones
- Netlify
- Vercel
- Firebase Hosting
- Cualquier servidor web

## 📊 Optimizaciones Realizadas

- ✅ CSS minimalista sin frameworks
- ✅ JavaScript vanilla sin dependencias
- ✅ Imágenes con placeholders responsivos
- ✅ Carga rápida y renderizado eficiente
- ✅ Accesibilidad mejorada
- ✅ SEO friendly

## 🔧 Mejoras Futuras

- [ ] Filtrado de galería por categorías
- [ ] Animaciones más avanzadas con Intersection Observer
- [ ] Backend para gestionar imágenes
- [ ] Sistema de comentarios
- [ ] Blog de fotografía
- [ ] Galería con lazy loading
- [ ] Dark mode toggle

## 📄 Licencia

Este proyecto es de código abierto. Siéntete libre de usarlo como base para tu propio portafolio.

## 👤 Autor

**fugaimperfecta** - Fotografía minimalista en escala de grises

## 📧 Contacto

¿Preguntas o sugerencias? Abre un issue o usa el formulario de contacto en la web.

---

**Hecho con ❤️ y minimalismo**
````
