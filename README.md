# BullyingApp

Aplicacion usando Polymer para repartir puntos (negativos) Entre un grupo de personas. Esta apilicación se ha creado para el master en Ingeniería Informática de la Universidad de Almería.

## Instalación

Simplemente descargar con git:

```bash
git clone https://github.com/zerasul/BullyingApp.git
```
**Nota:** Se debe descargar los componentes básicos de Polymer, y ponerlos en el proyecto bajo la carpeta _components_.

[Página oficial del proyecto Polymer](https://www.polymer-project.org)

## Uso

Esta aplicación simplemente muestra una serie de ALumnos a los que se pueden poner puntos negativos. Cada uno tendrá un nombre y un dibujo que lo identifica.
Es necesario tener la aplicación servidor donde se usará la API REST que nos dará los datos y nos permitirá dar puntos. 
La Aplicación servidor se encuentra en [Este Repositorio]()

Para cambiar la URL a la que se conecta debe cambiar las URL en el código Javascript de las funciones ```getBullyngRanking()``` e ```insertarVoto(iduser)```.

```javascript
function getBullyngRanking(){
    var urlAPI= 'http://rpbian.ddns.net/bullyingAPI/index.php/hola';
```

```javascript
function insertarVoto(iduser){
     var urlAPI= 'http://rpbian.ddns.net/bullyingAPI/index.php/hola';
```

**Nota**: esta aplicación es solo con motivos de ejemplo y el titulo no tiene nada que ver con el Bullying Escolar.
