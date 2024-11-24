# tarea_repaso_nov24
Mi repositorio de prueba para el examen

Primeero clono el respositorio en local para poder empezar a trabajar en el
  - Busco el directorio donde quiero clonarlo
  - `git init` --> iniciar la conexión del directorio con git
  - `git clone <clave-ssh>` --> clono el repo en local

Creo estructura de directorios con:
- `mkdir`

Creo archivos dentro de los directorios con:
- `touch` NomArchivo.tipofichero
- `echo` "contenido del fichero" > NomArchivo.tipofichero
- `cd` NomArchivo.tipofichero --> `echo` "el contenido que quiero meter en el fichero"

Verificamos contenido de algún fichero:
- `cat` NomArchivo.tipofichero

Recordemos que `>` sobrescribe y `>>` añade.

Abro el archivo ".gitignore" en Visual Studio Code con `code .` (esto me abre todo el repo).

Incluyo dentro los elementos a ignorar por git:
```plaintext
# Ignorar esta carpeta
local_config/
# Ignorar archivos
*.tmp
*.env
```
* Compruebo que git detecta los cambios con `git status`.
* Añado los archivos al stage con `git add .`.
* Compruebo que están correctamente preparados nuevamente con `git status`.
* Hago commit con `git commit`, añadiendo una descripción con `-m "..."`.
  
