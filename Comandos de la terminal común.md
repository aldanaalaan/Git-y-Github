#shellComands #cmd #powershell #windows

## Carpetas y archivos

- `ls`
  Listado de carpetas y archivos dentro de la carpeta actual de la terminal.
- `pwd`
  Mostrar ruta actual de la terminal.
- `cd`
  Navegación entre carpetas desde la terminal.
  1. `cd [Nombre de la carpeta]`
     Entrar a la carpeta con ese nombre especifico, siempre y cuando este se encuentre dentro de la carpeta actual.
  2. `cd ..`
     Salir de la carpeta actual (Te lleva al nivel superior)
- `mkdir '[Nombre del directorio]'`
  Crea una carpeta vacía dentro de la carpeta actual.
- `echo > '[Nombre del archivo]'` (**touch** debido a un alias configurado en mi perfil de PoweShell, aunque está disponible en otros OS)
  Crea un archivo con el nombre indicado dentro de la carpeta actual.
- `Remove-item '[Nombre de archivo/carpeta]'` (**rm** debido a un alias configurado en mi perfil de PoweShell)
  Elimina el archivo o carpeta especificado de la carpeta actual.
- `Invoke-Item .` (**oi** debido a un alias configurado en mi perfil de PoweShell)
  Abrir el explorador de archivos en la carpeta actual.
- `clear` | `cls`
  Limpiar la terminal.

## Extra

- `code .`
  Abrir Visual Studio Code en la carpeta actual.
- `subl .`
  Abrir Sublime Text en la carpeta actual.
