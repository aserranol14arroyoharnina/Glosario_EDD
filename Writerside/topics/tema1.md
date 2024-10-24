# Tema 1. Sistemas de control de versiones. Git

* <tooltip term="Git">**Git**</tooltip>: Es un sistema de control de versiones distribuido. Esto significa que cada desarrollador tiene una copia completa del historial del proyecto en su máquina local. Esto permite trabajar sin conexión y facilita la colaboración, ya que los cambios se pueden fusionar fácilmente de diferentes fuentes. Git rastrea los cambios en el código fuente durante el desarrollo de software, permitiendo a los desarrolladores volver a versiones anteriores, experimentar con nuevas funciones y trabajar simultáneamente en diferentes partes del proyecto sin interferir entre sí.

* <tooltip term="Repositorio">**Repositorio**</tooltip>: Un repositorio es donde Git almacena todos los archivos de un proyecto, incluyendo el código fuente, la documentación, las imágenes, etc.  También contiene el historial completo de todos los cambios realizados en el proyecto.  Hay dos tipos principales de repositorios:

* <tooltip term="Repositorio local">**Repositorio local**</tooltip>:
Reside en tu propia máquina. Aquí es donde haces tu trabajo diario, como editar archivos y confirmar cambios.

* <tooltip term="Repositorio remoto">**Repositorio remoto**</tooltip>:
Se almacena en un servidor, como GitHub, GitLab o Bitbucket. Sirve como un punto centralizado para que varios desarrolladores compartan su trabajo y colaboren.

* <tooltip term="Commit">**Commit**</tooltip>:
Un commit es una instantánea de los cambios realizados en el repositorio en un momento dado. Cada commit tiene un mensaje asociado que describe los cambios realizados. Los commits son la unidad básica del historial de un proyecto en Git. Permiten rastrear el progreso del desarrollo, identificar quién hizo qué cambios y cuándo, y revertir a versiones anteriores si es necesario.
<tooltip term="Fork">**Fork**</tooltip>:
Es una copia de un repositorio que se crea en tu cuenta. Esta copia te permite hacer cambios y experimentar sin afectar el repositorio original. Es especialmente útil para colaborar en proyectos de código abierto. Aquí tienes un desglose más detallado:

Copia independiente: Un fork es una copia completa del repositorio original, incluyendo todo su historial de commits.
Desarrollo paralelo: Puedes trabajar en tu fork de manera independiente, añadiendo nuevas características, corrigiendo errores o experimentando con el código.
Contribuciones: Si haces cambios que crees que pueden beneficiar al proyecto original, puedes enviar un “Pull Request” para que los mantenedores del repositorio original revisen y, si lo consideran adecuado, integren tus cambios.