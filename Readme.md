# ExpressJS.com

  El sitio para Express.

## Construyendo

Instalación:

```
$ npm install -g serve
$ npm install
$ make
$ serve .
$ open http://localhost:3000
```

Luego reconstruir los cambios con:

```
$ make
```

## Contribuir

Los archivos de Markdown son los archivos fuentes / originales que generan archivos HTML que son el formato de publicación. El sitio web es servido de las páginas HTML en la rama `gh-pages`. Los archivos Jade son usados para crear una página con el header, footer apropiado y uno o más archivos Markdown. Generalmente, no deberías necesitar editar los archivos Jade a menos que estés agregando una nueva página o reorganizando páginas.

  - __No__ edites el HTML directamente. En vez de eso, edita el(los) archivo(s) Markdown, luego genera los HTML usando `make` para revisar tus cambios localmente. NOTA: Debes borrar el archivo HTML existente de tal forma que `make` lo regenere. También puedes ejecutar `make clean` para borrar todos los archivos HTML, luego ejecuta `make` para reconstruir todo el sitio.  
  - En general, PRs deben contener tanto el(los) archivo(s) Markdown y el(los) HTML(s) generado(s). Sin embargo, un número muy pequeño de PRs o commits puede únicamente ser el fuente Markdown, con el entendimiento de que el HTML será generado posteriormente para incorporar numerosos cambios.
  - Para publicar un cambio, debes hacer commit de el(los) archivo(s) HTML(s).

## Mostrando tus apps

Si tienes una app que quisieras mostrar en el sitio, no abras un issue para ello.
En vez de eso, _abre un pull request_.
