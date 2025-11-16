# TechPro Solutions - Portafolio Profesional

Sitio web portafolio profesional desarrollado con HTML5, CSS3 y diseño responsivo moderno.

## 📋 Descripción del Proyecto

Portafolio web que presenta los servicios, experiencia y habilidades de un equipo de desarrollo tecnológico especializado en:
- Desarrollo Web Full Stack
- Soporte Técnico IT
- Análisis de Sistemas
- Automatización de Procesos

## 🚀 Estructura del Proyecto

```
proyecto/
│
├── index.html          # Página principal
├── about.html          # Página sobre el equipo
├── portfolio.html      # Página de proyectos y experiencia
├── contact.html        # Página de contacto
├── styles.css          # Hoja de estilos principal
└── README.md          # Documentación
```

## 💻 Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Diseño moderno con gradientes, animaciones y grid layout
- **Diseño Responsivo**: Adaptable a dispositivos móviles, tablets y escritorio

## 🎨 Características del Diseño

### Paleta de Colores
- **Principal**: #1a1a2e (Azul oscuro)
- **Acento**: #00d4ff (Cyan brillante)
- **Fondo**: #ffffff (Blanco)
- **Texto**: #333333 (Gris oscuro)

### Elementos Visuales
- Navegación fija (sticky navbar)
- Gradientes modernos en secciones destacadas
- Animaciones suaves en hover
- Tarjetas con sombras y efectos de elevación
- Tabla comparativa de tecnologías
- Formulario de contacto completo

## 📱 Diseño Responsivo

El sitio se adapta perfectamente a diferentes tamaños de pantalla:
- **Desktop**: > 768px - Layout completo con grids de 3 columnas
- **Tablet**: 481px - 768px - Layout de 2 columnas
- **Mobile**: < 480px - Layout de 1 columna

## 📄 Páginas del Sitio

### 1. Inicio (index.html)
- Hero section con call-to-action
- Servicios destacados en tarjetas
- Estadísticas del equipo
- Tecnologías dominadas
- Sección CTA final

### 2. Nosotros (about.html)
- Presentación del equipo
- Perfiles profesionales detallados con:
  - Experiencia laboral
  - Formación académica
  - Habilidades técnicas
- Valores corporativos

### 3. Experiencia (portfolio.html)
- Proyectos destacados
- Grid de proyectos realizados
- Tabla comparativa de tecnologías
- Logros y certificaciones

### 4. Contacto (contact.html)
- Formulario de contacto completo
- Información de contacto
- Redes sociales
- Preguntas frecuentes (FAQ)

## 🌐 Despliegue en GitHub Pages

### Paso 1: Crear Repositorio en GitHub
1. Ir a [github.com](https://github.com) e iniciar sesión
2. Hacer clic en "New repository"
3. Nombrar el repositorio: `mi-portafolio` o el nombre que prefieras
4. Marcar como "Public"
5. Hacer clic en "Create repository"

### Paso 2: Subir los Archivos

**Opción A: Desde la interfaz web de GitHub**
1. En tu repositorio, hacer clic en "Add file" > "Upload files"
2. Arrastrar todos los archivos del proyecto (index.html, about.html, portfolio.html, contact.html, styles.css)
3. Hacer clic en "Commit changes"

**Opción B: Usando Git (línea de comandos)**
```bash
# Inicializar repositorio local
git init

# Agregar todos los archivos
git add .

# Hacer commit
git commit -m "Primer commit: Portafolio completo"

# Conectar con repositorio remoto
git remote add origin https://github.com/TU-USUARIO/mi-portafolio.git

# Subir archivos
git push -u origin main
```

### Paso 3: Activar GitHub Pages
1. Ir a "Settings" en tu repositorio
2. Seleccionar "Pages" en el menú lateral
3. En "Source", seleccionar "main" como rama
4. Hacer clic en "Save"
5. Esperar unos minutos y tu sitio estará disponible en:
   `https://TU-USUARIO.github.io/mi-portafolio/`

## 🔧 Personalización

### Cambiar Información Personal
1. Editar **about.html** para actualizar los perfiles del equipo
2. Modificar nombre, experiencia, formación y habilidades

### Cambiar Colores
En **styles.css**, buscar y reemplazar:
- `#1a1a2e` - Color principal
- `#00d4ff` - Color de acento
- `#16213e` - Color secundario

### Agregar Proyectos
En **portfolio.html**, agregar nuevas tarjetas siguiendo la estructura:
```html
<div class="project-card">
    <h3>Nombre del Proyecto</h3>
    <p class="project-category">Categoría</p>
    <p class="project-description">Descripción...</p>
    <div class="tech-tags">
        <span>Tecnología 1</span>
        <span>Tecnología 2</span>
    </div>
</div>
```

## 📊 Elementos Destacados

### Tabla Comparativa
Tabla HTML completa con estilos personalizados que muestra tecnologías, niveles de dominio y casos de uso.

### Formulario de Contacto
Formulario completo con campos para:
- Nombre
- Email
- Teléfono
- Empresa
- Servicio de interés
- Mensaje

### Sistema de Navegación
Menú de navegación sticky con indicador de página activa y transiciones suaves.

## 🎯 Elementos Requeridos por la Actividad

✅ Texto con diferentes énfasis (negrita, cursiva, tamaños)
✅ Estructuras divisorias (div, section)
✅ Tablas (tabla comparativa de tecnologías)
✅ Imágenes (placeholders para fotos de perfil)
✅ Propiedades de visualización (display: flex, grid, inline-block)
✅ Archivos separados (HTML y CSS)
✅ Enlaces entre páginas
✅ Diseño responsivo
✅ Repositorio en GitHub

## 📝 Notas Técnicas

### Archivos Separados
- **HTML**: Estructura y contenido semántico
- **CSS**: Todos los estilos en archivo independiente
- Sin JavaScript inline ni estilos inline

### Buenas Prácticas
- Código semántico y bien estructurado
- Comentarios descriptivos en CSS
- Nombres de clases descriptivos
- Estructura de carpetas organizada
- Diseño mobile-first

### Accesibilidad
- Etiquetas semánticas apropiadas
- Contraste de colores adecuado
- Navegación por teclado funcional
- Formularios con labels asociados

## 🚀 Mejoras Futuras

- Agregar JavaScript para interactividad del formulario
- Implementar lightbox para imágenes de proyectos
- Agregar animaciones con scroll
- Integrar con backend para formulario funcional
- Agregar blog o sección de artículos

## 📞 Soporte

Para consultas o sugerencias sobre el proyecto, contactar a través del formulario en la página de contacto.

---

**Desarrollado con 💙 por TechPro Solutions - 2024**
