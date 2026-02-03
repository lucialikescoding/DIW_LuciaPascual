# Folclore: El origen de las hadas
## Versión Bootstrap con diseño original preservado

---

## 🎨 Colores exactos del proyecto

### Modo Claro
```css
--color-fondo: #FCF2CE;    /* Fondo principal - beige claro */
--color-header: #CF9788;    /* Header y footer - rosa pálido */
--color-caja: #D1E5A0;      /* Secciones y cajas - verde pastel */
--color-texto: #333;        /* Texto principal - gris oscuro */
```

### Modo Oscuro
```css
--darkmode-fondo: #342929;  /* Fondo oscuro - marrón oscuro */
--darkmode-caja: #705D3A;   /* Cajas oscuras - marrón medio */
--darkmode-acento: #D1E5A0; /* Acento - verde pastel (mismo que modo claro) */
```

---

## 🔤 Tipografías

- **Títulos (h1, h2, h3)**: `Princess Sofia` (cursive)
- **Texto del cuerpo**: `Cormorant Upright` (serif)

Ambas fuentes se cargan desde Google Fonts automáticamente.

---

## 📐 Tamaños de imágenes

### Artículos (lista principal)
- **Ancho**: clamp(80px, 15vw, 120px) - adaptativo
- **Alto**: clamp(120px, 20vw, 180px) - adaptativo
- **Formato**: Rectangular vertical
- **Object-fit**: cover (recorta y centra)

### Galería lateral
- **Ancho**: 50% del contenedor (2 columnas)
- **Alto**: clamp(180px, 30vw, 250px) - adaptativo
- **Object-fit**: cover

### Logo
- **Dimensiones**: 87px × 80px
- **Forma**: Circular (border-radius: 50%)

---

## 📁 Estructura del proyecto

```
proyecto/
├── index.html              # Página principal con Bootstrap 5
├── styles.css              # Estilos personalizados
├── README.md              # Este archivo
└── imagenes/              # Carpeta de imágenes
    ├── logo.png           # Logo circular 87x80px
    ├── intro.jpg          # Imagen introducción
    ├── historia.jpg       # Imagen historia
    ├── tipos1.jpg         # Imagen tipos de hadas
    ├── fairy1.jpg         # Galería imagen 1
    ├── fairy2.jpg         # Galería imagen 2
    ├── fairy3.jpg         # Galería imagen 3
    └── fairyring.jpg      # Galería imagen 4
```

---

## 🎯 Componentes Bootstrap utilizados

1. **Navbar** (`navbar`, `container-fluid`)
   - Logo, título y botones de acción
   - Botón hamburguesa para menú lateral

2. **Offcanvas** (panel lateral)
   - Menú de navegación deslizable
   - Se cierra al hacer clic en los enlaces

3. **Grid System**
   - `row` y `col-lg-8` / `col-lg-4`
   - Responsive automático

4. **Cards** 
   - Artículos clicables con imagen y texto
   - Diseño horizontal con `row g-0`

5. **Table**
   - Tabla responsive con `table-responsive`
   - Clases: `table-bordered`, `table-hover`

6. **Utilidades**
   - Spacing: `p-3`, `mb-3`, `gap-2`, etc.
   - Display: `d-flex`, `align-items-center`
   - Border: `rounded-4` (15px de border-radius)

---

## ✨ Características

### Funcionalidad JavaScript
- ✅ Cambio entre vista lista y detalle
- ✅ Modo oscuro con checkbox oculto (CSS puro)
- ✅ Panel lateral con Offcanvas de Bootstrap
- ✅ Scroll automático al cambiar de vista
- ✅ Navegación intuitiva

### Diseño Responsive
- 📱 **Móvil** (< 576px): Diseño vertical, imágenes centradas
- 📱 **Tablet** (576px - 900px): Columna única
- 💻 **Desktop** (> 900px): Dos columnas (8-4)

### Animaciones
- Hover en artículos (transform + box-shadow)
- Transiciones suaves en modo oscuro (300ms)
- Efectos en botones

---

## 🚀 Instalación y uso

1. **Descargar el proyecto**
   - Extrae todos los archivos en una carpeta

2. **Verificar estructura**
   - Asegúrate de que la carpeta `imagenes/` contiene todas las imágenes
   - El archivo `index.html` debe estar en la raíz

3. **Abrir en el navegador**
   - Doble clic en `index.html`
   - O arrastra el archivo al navegador

**No requiere servidor local** - funciona directamente desde el sistema de archivos.

---

## 🔧 Dependencias externas

Todas las dependencias se cargan desde CDN:
- **Bootstrap 5.3.2** - jsDelivr
- **Google Fonts** - Princess Sofia + Cormorant Upright

---

## 🌐 Compatibilidad

✅ Chrome / Edge / Opera (Chromium)  
✅ Firefox  
✅ Safari  
✅ Navegadores móviles

---

## 📝 Notas técnicas

### Modo oscuro
El modo oscuro se implementa con CSS puro usando un checkbox oculto:
```css
#modo-toggle:checked ~ .site { ... }
```

### Responsive
Se utilizan funciones CSS modernas:
- `clamp()` para tamaños adaptables
- `@media queries` para breakpoints
- Grid de Bootstrap para columnas

### Preservación del diseño original
- ✅ Colores exactos mantenidos
- ✅ Fuentes originales preservadas
- ✅ Tamaños de imagen adaptables pero proporcionales
- ✅ Funcionalidad idéntica
- ✅ Solo cambia la estructura HTML (Bootstrap)

---

## 👤 Autor

**Lucía Pascual López-Roca**  
© 2025

### Enlaces
- 🔗 [GitHub](https://github.com/lucialikescoding/DIW_LuciaPascual.git)
- 🔗 [LinkedIn](www.linkedin.com/in/lucía-pascual-lópez-roca-8680b3185)

---

## 📄 Licencia

Proyecto educativo - Desarrollo de Interfaces Web (DIW)

---

**Desarrollado con ❤️ usando Bootstrap 5.3.2**
