# Manual de Buenas Prácticas para Entregas

Este manual establece los criterios mínimos para realizar entregas de proyectos en el bootcamp, asegurando calidad, profesionalismo y uso adecuado de las tecnologías.  

---

## 1. Repositorio GitHub  
- Usa un nombre descriptivo y profesional para tu repositorio.
- Evita nombres genéricos como "proyecto1". Usa algo como: gestor-tareas o app-recetas.  
- Asegúrate de configurar un archivo `.gitignore` para evitar subir archivos innecesarios, como `node_modules`.  

## 2. Commits  
- Realiza commits pequeños y frecuentes con mensajes claros y descriptivos, por ello es importante que identifiques muy bien las tareas que implica el proyecto (entre más atómicas mejor).  
  - Ejemplo:  
    - `feature: agregar validación al formulario`  
    - `fix: corregir bug en navbar`  

## 3. Estructura del Proyecto  
- Mantén una organización clara en las carpetas y archivos.  
- Usa nombres en minúsculas y sin espacios para rutas y archivos.  

## 4. Código Limpio  
- Elimina código comentado o sin uso antes de entregar.  
- Asegúrate de que tus funciones sean reutilizables y optimizadas.  
- Evita abusar de `console.log`. Usa herramientas de debugging.  

## 5. Documentación (README)  
Incluye un archivo README en tu proyecto con:  
- Descripción del proyecto.  
- Tecnologías utilizadas.  
- Instrucciones de instalación y ejecución.  
- Features principales.  
- Link a una demo o capturas de pantalla.  

    Ejemplo de estructura:  

    # Gestor de Tareas  
    Una aplicación para gestionar tareas pendientes donde el usuario puede:(...) 

    ## Tecnologías  
    - Angular  
    - Tailwind CSS  
    - Firebase  

    ## Instrucciones  
    1. Clonar el repositorio.  
    2. Ejecutar `npm install`.  
    3. Correr `ng serve` y abrir en el navegador.  

    ## Demo  
    [Demo en vivo](https://demo-app.com)  