1.Revisa el contenido de las carpetas del proyecto, ¿qué carpetas se han creado y para qué sirve cada una?

*  angular/  → Código web compilado.
*  node_modules/ → Módulos y dependencias instaladas de Ionic.
*  src/ → Código fuente principal de nuestra aplicación.
* App: Contiene el código de la aplicación:
 – Páginas
 - Servicios (o proveedores de contenido)
 - Componentes
 - Directivas
 - Módulo y componente principal de la app
 * assets: Recursos de la aplicación: imágenes, vídeos, etc.
 * environments:Gestiona configuraciones especificas segun el entorno de desarrollo(desarrollo,producción,etc)
 * theme:  Temas y estilos de la aplicación.


2.Revisa el contenido de la carpeta "src" y busca el contenido de la página que se incluye por defecto (llamada home).
home.page.html: Archivo de la plantilla HTML.
home.page.scss: Archivo de estilos específicos para la página.
home.page.ts: Archivo TypeScript que contiene la lógica y configuración de la página.
home.page.spec.ts: Archivo de pruebas unitarias para la página.

3.¿Cómo se carga la página por defecto? Busca si se hace referencia a la página "home" desde algún fichero y cómo se indica que se cargue como página principal.
El archivo app-routing.module.ts es el responsable de definir las rutas de la aplicación y establecer cuál será la página principal, en este caso seria home.
