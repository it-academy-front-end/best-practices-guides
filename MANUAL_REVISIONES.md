# Manual de Criterios para Revisiones de Pares

Este manual establece el proceso y los criterios para realizar revisiones de proyectos entre compañeros de manera efectiva y profesional.  

---

## 1. Proceso de Revisión  
1. Descarga el proyecto del compañero y pruébalo en tu entorno local.  
2. Crea una **issue** en el repositorio del compañero con el título:  
   - `Revisión Sprint [Número] - Feedback`.  
3. Documenta tu revisión siguiendo los criterios detallados a continuación.  

---

## 2. Criterios de Revisión  
### **Funcionalidad**  
- ¿Todas las características descritas en el README funcionan correctamente?  
- ¿Existen errores visibles o casos no manejados?  

### **Código y Clean Code**  
- ¿El código sigue principios de **Clean Code**?  
  - ¿Está bien estructurado y es fácil de entender?  
  - ¿Se evita la duplicación de código?  
  - ¿Se usan nombres significativos para variables, funciones y clases?  
  - ¿Se eliminó código comentado o sin uso?  
- ¿Se emplea modularización para mejorar la mantenibilidad?  

### **Git y Gitflow**  
- ¿Se utilizaron **commits descriptivos** y pequeños?  
- ¿La rama principal (`main` o `master`) contiene la versión estable? 
- ¿Existe una rama de trabajo (`develop` o `dev`)?
- ¿Se respetó la estructura de Gitflow (ramas de desarrollo y features separadas)?  
- ¿El archivo `.gitignore` está configurado correctamente?  

### **Documentación (README)**  
- ¿El README describe claramente el propósito del proyecto?  
- ¿Incluye tecnologías utilizadas, instrucciones de instalación y ejecución?  
- ¿Se agregaron capturas de pantalla, demos o diagramas si son necesarios?  
- ¿Es fácil de seguir para alguien que no conoce el proyecto?  

### **Estilo y Usabilidad**  
- ¿El diseño es responsive y atractivo?  
- ¿El manejo de errores es claro y funcional para el usuario?  
- ¿Los estilos están bien organizados y no hay redundancia?  

---

## 3. Cómo Dar Feedback  
- Usa un lenguaje constructivo:  
  - Ejemplo: "Me gusta cómo organizaste las rutas, pero podrías considerar dividir las funciones para mayor claridad."  
- Divide tu feedback en:  
  - **Fortalezas:** ¿Qué está bien hecho?  
  - **Áreas de mejora:** ¿Qué podría mejorarse?  
  - **Sugerencias:** ¿Qué podrías recomendar?  

---

## 4. Formato de la Issue  

### Revisión de Proyecto  

**1. Funcionalidad:**  
- Todas las características descritas en el README funcionan correctamente.  
- El formulario no maneja errores al enviar datos vacíos.  

**2. Código y Clean Code:**  
- El código es fácil de entender y sigue principios de Clean Code.  
- Encontré duplicación de código en las funciones `calculateTotal` y `calculateTax`.  
- Los nombres de las variables son significativos y autoexplicativos.  

**3. Git y Gitflow:**  
- Los commits son descriptivos y claros.  
- No se respetó la separación de ramas para features específicas.  
- El archivo `.gitignore` está bien configurado y evita subir archivos innecesarios.  

**4. Documentación (README):**  
- El README es completo y útil.  
- Falta incluir capturas de pantalla del proyecto.  

**5. Estilo y Usabilidad:**  
- El diseño es responsive y atractivo.  
- Los estilos CSS contienen algunas reglas redundantes que podrían refactorizarse.  

### Feedback General  
¡Gran trabajo! El proyecto es funcional y tiene un diseño muy limpio. Sin embargo, recomendaría modularizar el código para mejorar la mantenibilidad y evitar duplicación. Además, sería ideal respetar la estructura de Gitflow para un flujo de trabajo más profesional.  
