# PV-TP-1

Plataforma Educativa — Trabajo Práctico de Programación Visual

Integrantes del Grupo

| Nombre Completo        | Usuario de GitHub | Rol en el Proyecto                    |
| ---------------------- | ----------------- | ------------------------------------- |
| Gabriel Ortega         | Gabo506           | Analista — index.html (Dashboard)     |
| Lucas Alvaro Flores    | LucasAFlores      | Explorador — proyectos.html           |
| Federico Rios Marcial  | Fede-Marcial      | Documentador — detalle.html           |
| Mauro Arcangel Chauque | Mauro006          | Integrador — perfil.html y Navegación |
| Vega Brian Agustin     | mitisbroken-debug | Auditor — README.md y Validación W3C  |

---

Descripción de las Páginas

index.html — Dashboard Principal
Desarrollado por Gabriel Ortega (Gabo506)

Página de inicio de la plataforma. Tiene un encabezado con el nombre del sitio y una bienvenida al usuario. Se agregó una sección de estadísticas con tres bloques de datos (proyectos totales, tareas del día y mensajes pendientes) y una sección de novedades con las últimas acciones realizadas en el sistema, mostradas en forma de lista.

---

proyectos.html — Explorador de Proyectos
Desarrollado por Lucas Alvaro Flores (LucasAFlores)

Página para explorar los proyectos de la plataforma. Incluye una barra de filtros para ordenar por categoría, año y estado (En curso / Finalizado). Se listan 5 proyectos, cada uno con título, imagen, descripción breve, categoría y un enlace para ver el detalle.

Se introdujo un menú de navegación: Con la etiqueta <nav>, se colocó una barra superior que permite saltar entre las distintas páginas del sitio sin complicaciones.

Se incluyó una zona de filtros: Se utilizó un <aside> para separar la barra de búsqueda del contenido principal. Dentro de esta parte, se agregaron selectores (<select>) para que se pueda filtrar la información por materia, año o estado del proyecto.

Se organizaron los proyectos en fichas: Para cada uno de los 5 proyectos, se usó la etiqueta <article>. De esta manera, cada trabajo quedó contenido en su propia "tarjeta" con su título, descripción y foto.

Se incorporaron imágenes con descripción: En cada ficha se insertó una imagen representativa. Se agrego el atributo alt, donde se describió qué hay en cada foto para que la página sea más accesible.

Se vincularon las páginas: Al final de cada proyecto, se puso un enlace que lleva directamente a la página de detalles, logrando que todo el sitio esté conectado entre sí.

---

detalle.html — Detalle de Proyecto
Desarrollado por Federico Rios Marcial (Fede-Marcial)

Vista individual de un proyecto. Muestra el título, la fecha de inicio y los autores en el encabezado. Tiene una descripción extendida en dos párrafos con los objetivos del proyecto, una lista con enlaces a recursos como PDFs, Drive y GitHub, y una sección con los integrantes del equipo y sus roles.

---

perfil.html — Perfil de Usuario y Navegación Global
Desarrollado por Mauro Arcangel Chauque (Mauro006)

Página de perfil personal con imagen, nombre y rol del usuario (Docente o Alumno). Además, Mauro se encargó de armar el menú de navegación global y vincular todos los archivos del proyecto entre sí mediante etiquetas a.

---

Validación W3C
Realizada por Vega Brian Agustin (mitisbroken-debug)

Se tomó el código HTML de cada página y se validó en https://validator.w3.org/ usando la opción Validate by Direct Input, verificando que el HTML cumpla con los estándares del W3C.

---

Tecnologías utilizadas: HTML5 y CSS3.
