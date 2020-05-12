# Proyecto Ana (or Ana's Project)

This is how a proud father teach GIT and ruby to his daugther. Hopefully, we can reuse this project to be used with my other daugther as well...

# Deliverables by version

*Dia 1 y 2*: `v1.0.0`
*TAREA*: Buscar 2 canciones de bandas que te gusten y las vayas subiendo a este repositorio. Una cancion por dia, no mas que eso. Voy a verificar dia a dia, que haya una cancion nueva, durante 2 dias.
*Conceptos GIT*: Crear branches (`git checkout -b`), Agregar archivos al versionado, `git add <archivos>`, Hacer commits`git commit -m "con mensaje"`y Subir los cambios con `git push`. Entender que es un pull request y que signfica un merge.
Al final del trabajo, modificar el archivo `VERSION` a `v1.0.1`

*Dia 3 y 4*: `v1.0.2`
*TAREA*: De esas dos canciones de la version `v1.0.1` vamos a buscar sus tradicciones al espa&ntilde;ol y vamos a poner la traduccion justo debajo de la cancion en ingles con el titulo que diga "TRADUCCION AL ESPA&NTILDE;OL".
La idea es que entiendas la idea de hacer un `git add <archivos>`, `git commit -m "con mensaje"`y `git push`.
*Conceptos GIT*: Reafirmar y practicar los conceptos anteriores (crear branches, agregar al versionado, crear pull request, hacer commits y push). Adicionalmente ver como el historial de cambios se mantiene sobre un mismo recurso `git diff`.

*Dia 5*: `v1.1.0`
*TAREA*: Aplicar markdown para que las letras tengan formato y no sean solamente texto plano.
*Conceptos GIT*: renombrar archivos con `git mv` y todos los conceptos anteriores.

# Requisitos de los entregables.
Si las letras pertenecen a distintas bandas musicales, cada banda musical debe tener su propia carpeta. Es decir la estructura de directorio (preguntarme si no se entiende que significa) deberia ser algo como:
```
proyecto-ana/
  maroon-five/
    maps.md
    animals.md
  camila-cabello/
    cancion-1.md
  README.md
  VERSION
```
