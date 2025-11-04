# Manual de comandos Git 


Repositorio: manual-git 

## Introducción

Git es un sistema de control de versiones distribuido que permite registrar los cambios realizados en los archivos de un proyecto. Es una herramienta fundamental en el desarrollo de software, ya que facilita el trabajo colaborativo, el seguimiento del historial y la integración continua.

GitHub, por su parte, es una plataforma en línea que permite alojar repositorios Git y colaborar de manera remota con otros desarrolladores.


## Objetivo 


Este documento explica el uso de los comandos básicos de Git para comprender el funcionamiento del control de versiones y cómo se trabaja con repositorios remotos en GitHub. 


## Comandos de Git


### Git init 


Este comando se utiliza al iniciar un nuevo proyecto. Una vez ejecutado, Git comenzará a realizar un seguimiento de los cambios en los archivos de la carpeta actual. Es el primer paso para comenzar a trabajar con control de versiones.


### Git clone


Se emplea cuando se desea obtener una copia idéntica de un proyecto alojado en un servidor remoto, como GitHub. Es muy útil para colaborar en proyectos existentes o descargar el código fuente de un repositorio público.


### Git add


Este comando no guarda los cambios definitivamente, solo los prepara para ser confirmados con un commit. Es ideal para revisar qué archivos se incluirán antes de guardar los cambios en el historial.


### Git commit


Guarda los cambios en el historial del repositorio. Cada commit debe incluir un mensaje descriptivo que explique qué se ha modificado. Los commits deben realizarse con frecuencia y con mensajes claros. Esto permite mantener un historial limpio y comprensible, facilitando la revisión o reversión de cambios.


### Git log


Este comando es especialmente útil para auditar el trabajo realizado en un proyecto y comprender la evolución del código. Se pueden aplicar filtros para mostrar commits de un usuario o de un rango de fechas.


### git checkout


Se usa para moverse entre ramas del proyecto o recuperar versiones anteriores de archivos. Es una herramienta esencial para probar nuevas funcionalidades sin afectar el código principal.


### Git branch


El uso de ramas permite desarrollar nuevas características o realizar pruebas sin alterar el código principal. Una buena gestión de ramas mejora la organización del trabajo en equipo.


### Git push


Es el comando que conecta el trabajo local con el repositorio remoto. Gracias a él, los demás colaboradores pueden acceder a los cambios realizados. Debe usarse después de confirmar los cambios con git commit.


### Git pull


Este comando combina dos acciones: descarga los cambios del repositorio remoto y los fusiona con la rama activa. Es recomendable ejecutarlo antes de comenzar a trabajar para evitar conflictos.


### Git merge


Permite integrar el trabajo de diferentes ramas en una sola. Si existen conflictos entre versiones, Git solicitará resolverlos manualmente antes de completar la fusión.


## Conclusión


En resumen, Git es una herramienta indispensable para cualquier desarrollador, ya que permite mantener un registro preciso de la evolución de un proyecto y facilita la colaboración en equipo.
Comprender estos comandos básicos es fundamental para trabajar de forma eficiente y profesional en entornos de desarrollo modernos.
