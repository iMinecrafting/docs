# iMinecrafting Docs
Este repositorio contiene toda la documentación de [docs.iminecrafting.com](https://docs.iminecrafting.com)
en archivos `.md` (formato Markdown).

## Contribuciones
Toda contribución a nuestra página de documentación es bienvenida siempre y cuando se aliñe con el
objetivo del sitio.
Para realizar un aporte es necesario:
1. **Hacer un fork al repositorio.**
1. **Realizar los cambios en el repositorio forkeado.**
1. **Crear una Pull Request contra el repositorio de iMinecrafting** para que lo revisemos.  
   _Nota: Al crear una Pull Request, hay un enlace que te permite comparar a través de forks.
   El enlace directo sería algo así:  
   `https://github.com/iMinecrafting/docs/compare/master...<tu usuario>:master`_

## Entorno local
La documentación se puede correr localmente para ver como se visualiza el contenido de dos maneras
distintas.
### #1 Recomendada
- Requisitos: [Node.js](https://nodejs.org/) junto a NPM.

La primera vez se tiene que instalar `docsify-cli`:
```
npm i docsify-cli -g
```
Y luego ya se puede correr desde la carpeta del proyecto:
```
docsify serve ./docs
``` 

http://localhost:3000

### #2 Manual
- Requisitos: Python

Dentro de la carpeta `docs/` del proyecto se puede correr:
```bash
# Con Python 2.x
python -m SimpleHTTPServer 3000

# Con Python 3.x
python -m http.server 3000
``` 

http://localhost:3000

## Avanzado
### Markdown Spec
El parsing de los archivos `.md` se realiza con [marked.js](https://marked.js.org/) que
[soporta varias espcificaciones](https://marked.js.org/#/README.md#specifications) de Markdown.
Todas las opciones de formato más populares están soportadas, pero si se quiere probar con algo
más particular, recomendamos correr el proyecto locamente para ver si los cambios se visualizan
correctamente o probar en [marked.js.org/demo](https://marked.js.org/demo). 
