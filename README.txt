# Akira Café — TP1 Frontend II

##  Propósito
Landing responsive para **Akira Café**, desarrollada en el marco de la materia *Frontend II (UADE)*.  
Incluye secciones de servicios, navbar responsive y un formulario de contacto funcional (Formspree).  

##  Estructura de carpetas
- `docs/` → documentación del proyecto  
  - `brief.md` → objetivo, público, alcance, restricciones, riesgos y supuestos  
  - `user-stories.md` → historias de usuario con criterios y priorización  
  - `trazabilidad.md` → matriz de trazabilidad (user stories ↔ secciones del sitio)  
- `src/` → sitio web  
  - `index.html`  
  - `css/` (estilos principales)  
  - `js/` (scripts: nav, form)  
  - `img/` (imágenes optimizadas)  
- `README.md` → este archivo

##  Cómo ver el proyecto
1. Descargar y abrir `src/index.html` en un navegador moderno.  

##  Accesibilidad
- Todas las imágenes cuentan con `alt`.  
- Formularios con `label for`.  
- Contraste AA en textos principales.  
- Estados de foco visibles en enlaces y botones.  

##  Formulario de contacto (Formspree)
- Campos obligatorios: **nombre, email, mensaje**.  
- Validación de email en cliente.  
- Flujo de estados: *enviando…*, *éxito*, *error*. 
