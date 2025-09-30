 Investigación – Git Intermedio

 1. ¿Qué es una rama (branch) en Git y para qué se utiliza?
Una rama es como una copia paralela del proyecto donde se pueden hacer cambios sin afectar directamente la rama principal (`main`).  
Sirve para trabajar en nuevas funciones, correcciones de errores o pruebas sin romper el código que ya funciona.

---

 2. Explica con tus palabras qué significa hacer un merge.
Hacer un *merge* significa unir los cambios de una rama con otra.  
Por ejemplo: cuando terminas una nueva funcionalidad en una rama, puedes hacer *merge* a `main` para que todo el equipo use esos cambios.

---

 3. ¿Qué es un conflicto de fusión (merge conflict) y cómo se puede resolver?
Un conflicto de fusión ocurre cuando dos ramas modifican las mismas partes de un archivo y Git no sabe cuál versión conservar.  

**Cómo resolverlo:**
1. Git marca el conflicto dentro del archivo con símbolos `<<<<<<<`, `=======`, `>>>>>>>`.  
2. El programador debe editar el archivo, elegir qué código queda o combinar ambos.  
3. Guardar, hacer `git add archivo` y luego `git commit` para confirmar la resolución.

---

 4. Diferencia entre fork y clone en GitHub.
- **Fork:** Copia de un repositorio en tu cuenta de GitHub. Se usa para proponer cambios a un proyecto que no es tuyo.  
- **Clone:** Copia local en tu computadora de un repositorio (puede ser tuyo o de otro). Se usa para trabajar en local con Git.

---

 5. ¿Qué es un pull request y para qué se usa en proyectos colaborativos?
Un *pull request (PR)* es una solicitud que haces para que los dueños de un repositorio revisen tus cambios y decidan si los aceptan.  
Se usa para colaborar en equipo, revisar el código, discutir mejoras y mantener la calidad del proyecto.

---

 6. 3 buenas prácticas para colaborar en equipo usando GitHub
1. **Usar ramas descriptivas** (ejemplo: `feature/login`, `fix/error-formulario`) para mantener el orden.  
2. **Escribir mensajes de commit claros y cortos** que expliquen qué cambió.  
3. **Revisar y comentar Pull Requests** de los compañeros antes de aprobarlos, para asegurar calidad y aprendizaje en equipo.
