# chess.js

chess.js es un FORK que se sustenta a partir de la versión 0.13.3 de https://github.com/jhlywa/chess.js.

## Instalación
- Incluir en package.json la librería con el tag indicado.

~~~
"chess.js": "github:smartick/chess.js#v0.13.3-smk2",
~~~


## Versión
- Para incluir una nueva versión hay que generar un tag con la forma: v0.13.3-smk{versionSMK} 


## Pruebas
- Para probar antes de subir una versión, basta con referenciar en el package.json la carpeta donde se encuentra la librería. Para ello, y para asegurarnos que se instala primero hacemos uninstall:

~~~
npm uninstall chess.js
~~~

- Instalamos la librería

~~~
npm install file:{ruta}/chess.js
~~~

NOTA: Cada cambio realizado implica repetir este proceso.