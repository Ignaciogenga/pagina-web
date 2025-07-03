# AlteraCode - Página Web Profesional

Una página web moderna y responsiva para una empresa de tecnología especializada en desarrollo de software y soluciones digitales.

## 🚀 Características

### Diseño y UX
- **Diseño moderno y profesional** con paleta de colores personalizada
- **Completamente responsivo** - se adapta a todos los dispositivos
- **Navegación suave** con scroll automático a secciones
- **Animaciones fluidas** y efectos visuales atractivos
- **Tipografía optimizada** (Inter) para mejor legibilidad

### Secciones Principales
- **Inicio** - Hero section con llamada a la acción
- **Quiénes Somos** - Información de la empresa y estadísticas
- **Servicios** - Desarrollo web, apps móviles, consultoría y automatización
- **Casos de Éxito** - Proyectos destacados con métricas
- **Testimonios** - Slider interactivo con opiniones de clientes
- **Contacto** - Formulario funcional y información de contacto

### Funcionalidades
- **Formulario de contacto** con validación en tiempo real
- **Botón de WhatsApp** flotante para contacto directo
- **Mapa de Google Maps** integrado
- **Slider de testimonios** con navegación automática
- **Navegación móvil** con menú hamburguesa
- **Botón "Volver arriba"** para mejor UX
- **Sistema de notificaciones** para feedback del usuario

### Optimización
- **SEO optimizado** con meta tags apropiados
- **Rendimiento optimizado** con lazy loading
- **Accesibilidad** mejorada
- **Código limpio** y bien estructurado

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con Grid y Flexbox
- **JavaScript ES6+** - Funcionalidades interactivas
- **Font Awesome** - Iconografía
- **Google Fonts** - Tipografía Inter
- **Google Maps** - Integración de mapas

## 📁 Estructura del Proyecto

```
proyecto-pagina-web/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidades JavaScript
├── README.md           # Documentación
└── favicon.ico         # Icono del sitio (opcional)
```

## 🚀 Instalación y Uso

### Opción 1: Uso Directo
1. Descarga todos los archivos en una carpeta
2. Abre `index.html` en tu navegador web
3. ¡Listo! La página está funcionando

### Opción 2: Servidor Local
Para desarrollo, puedes usar un servidor local:

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (si tienes http-server instalado)
npx http-server

# Con PHP
php -S localhost:8000
```

Luego visita `http://localhost:8000` en tu navegador.

### Opción 3: Hosting Web
Para subir a un hosting:
1. Sube todos los archivos a tu servidor web
2. Asegúrate de que `index.html` esté en la raíz
3. La página estará disponible en tu dominio

## 🎨 Personalización

### Colores
Los colores están definidos como variables CSS en `styles.css`:

```css
:root {
    --primary-color: #0A192F;    /* Azul oscuro */
    --secondary-color: #64FFDA;  /* Verde lima */
    --accent-color: #ECEFF1;     /* Gris claro */
    --white: #ffffff;
}
```

### Contenido
- **Empresa**: Cambia "AlteraCode" por el nombre de tu empresa
- **Servicios**: Modifica los servicios en la sección correspondiente
- **Casos de éxito**: Actualiza con tus proyectos reales
- **Testimonios**: Reemplaza con testimonios reales de clientes
- **Contacto**: Actualiza información de contacto y redes sociales

### Imágenes
- Reemplaza los placeholders con imágenes reales de tu empresa
- Optimiza las imágenes para web (formato WebP recomendado)
- Mantén proporciones consistentes

## 📱 Responsive Design

La página está optimizada para:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🔧 Configuración Avanzada

### Formulario de Contacto
Para hacer funcional el formulario, necesitas:

1. **Backend**: Configurar un servidor para procesar el formulario
2. **Email**: Integrar servicio de envío de emails (SendGrid, Mailgun, etc.)
3. **Validación**: El JavaScript ya incluye validación básica

Ejemplo con PHP:
```php
<?php
if ($_POST) {
    $name = $_POST['name'];
    $email = $_POST['email'];
    $message = $_POST['message'];
    
    // Enviar email
    mail('tu@email.com', 'Nuevo contacto', $message);
}
?>
```

### Google Maps
Para personalizar el mapa:
1. Ve a [Google Maps Platform](https://developers.google.com/maps)
2. Crea un proyecto y obtén una API key
3. Reemplaza la URL del iframe en `index.html`

### WhatsApp
Para personalizar el botón de WhatsApp:
1. Cambia el número en el enlace: `https://wa.me/TU_NUMERO`
2. Personaliza el mensaje predeterminado

## 📊 SEO y Analytics

### Meta Tags
La página incluye meta tags básicos para SEO:
- Title optimizado
- Description descriptiva
- Keywords relevantes
- Open Graph tags

### Google Analytics
Para agregar Google Analytics:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🚀 Despliegue

### Opciones de Hosting
- **Netlify**: Drag & drop de archivos
- **Vercel**: Integración con Git
- **GitHub Pages**: Gratuito para proyectos públicos
- **Hosting tradicional**: cPanel, FTP, etc.

### Optimización para Producción
1. **Minificar** CSS y JavaScript
2. **Comprimir** imágenes
3. **Habilitar** compresión GZIP
4. **Configurar** cache headers
5. **Implementar** CDN para assets

## 🐛 Solución de Problemas

### Problemas Comunes
1. **Formulario no funciona**: Verifica que el backend esté configurado
2. **Mapa no se muestra**: Revisa la API key de Google Maps
3. **WhatsApp no abre**: Verifica el número de teléfono
4. **Estilos no cargan**: Verifica las rutas de los archivos CSS

### Debug
- Abre las herramientas de desarrollador (F12)
- Revisa la consola para errores JavaScript
- Verifica la pestaña Network para problemas de carga

## 📞 Soporte

Si necesitas ayuda:
1. Revisa la documentación
2. Verifica la consola del navegador
3. Asegúrate de que todos los archivos estén presentes

## 📄 Licencia

Este proyecto está disponible para uso personal y comercial. Puedes modificarlo y adaptarlo a tus necesidades.

---

**AlteraCode** - Transformamos ideas en soluciones digitales 