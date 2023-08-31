# Comandos de Git

#shellComands

## Repositorio

- `git init`
  Inicializar un repositorio de Git en la carpeta actual.
- `git status`
  Muestra el estado actual del repositorio.
- `git add [Nombre de archivos]`
  Añade los archivos especificados al área de preparación, para añadirlos a la base de datos próximamente (Usar '.' añadirá _todos_ los archivos)
- `git commit -m "[Mensaje]"`
  Agrega todas las modificaciones de los archivos preparados con `git add` a la base de datos y guarda el mensaje.
- `git log`
  Muestra los commits del repositorio, del mas reciente al mas antiguo.
  Se pueden agregar parámetros adicionales como:
  - `-n [Numero]`
    Limitar el numero de commits agregados.
  - `--grep='[Palabra]'`
    Para mostrar commits que contengan esa palabra.
- `git restore [Nombre del archivo]`
  Indicando o no algún archivo en especifico, puedes restaurar los cambios no confirmados en un repositorio.
- `git diff`
  Nos permite visualizar las diferencias entre la versión actual del código, y el ultimo commit, sin la necesidad de crear un nuevo commit
