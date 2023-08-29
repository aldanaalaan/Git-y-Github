#development #basicConcepts #controlVersions 
# Introducción
## ¿Qué es?
Git es un sistema de control de versiones (**CVS**) distribuido que ayuda a gestionar y seguir los cambios realizados en un proyecto, comúnmente de software, que permite manejar de manera efectiva y eficiente el historial de versiones.
## Características
- Rastrear los cambios.
- Colaborar.
- Versionado.
- Revertir cambios.
- Auditoria y seguimiento.
- Desarrollo experimental.
- Despliegue seguro.
## Conceptos básicos
1. **Repositorio.** Una base de datos donde se almacena todo lo necesario para el control del proyecto, como cambios, historial y archivos. Puede ser local o remoto.
2. **Commit.** Un registro de cambios en un repositorio, Git, almacena la nueva versión de los archivos que hayan sido modificados y enlaza los que no, a esta nueva versión, en lugar de guardar únicamente los cambios.
3. **Branch.** Líneas independientes y alternativas de los repositorios, permitiendo modificar una rama sin afectar otra.
4. **Merge.** Permite incorporar los cambios entre ramas de un repositorio.
5. **Clone.** Crear una copia de un repositorio, permitiéndote trabajar en el de forma local, y después sincronizarla con el repositorio remoto.
## Los tres estados.

| Estado | Descripción | Sección |
|:-:|-|-:|
|**Modified** |Cuando se realizó una modificación pero aún no se prepara para agregarlo a la base de datos.| Directorio de trabajo|
|**Staged** |Se agrega un archivo modificado, donde se prepara para agregarlo a la base de datos próximamente.|Area de preparación|
|**Merged** |Ya se han confirmado los cambios y se agrega a la base de datos |Directorio de Git|
