# Proyecto de programacion 3
En este proyecto se manejaran conceptos de webpack
Sass y ECS6 con el manejo de web components

## Para crear y administrar un respositorio 

* Creo el repositorio en [github](https://github.com/) 
* Clono el repositorio dentro de mi pc 
    ```
    git clone url_de_mi_repo
    cd carpeta_de_mi_proyecto
    ```
* Cuanto se generen cambios en el proyecto
    ```
    git status
    git add --all
    git commit -m "mensaje del commit"
    git push
    ``` 
## Iniciar proyecto con webpack

 * Instalar el [nodeJS](https://nodejs.org/en/download/)
 * Cierro todas las ventanas de comando que tenga y el IDE
 * verifico que nodejs este instalado 
   * Abro una ventana de comandos y ejecuto 
        ```
        npm -v
        ```
* Descargo el [web packl starter](https://github.com/wbkd/webpack-starter)
  * Copio los archivos
    - package-lock.json
    - packege.json
    - /public
    - /src
    - /webpack
  * instalo los paquetes de node_modules con :
  ```
    npm install
    //corremos el pryecto con 
    npm run start
  ```  
## [Bootatrap](https://getbootstrap.com/)
* Instalar bootstrap con 
  ```
  npm install --save bootstrap jquery popper.js  
  ```
* Implementarolo en la pagina agregando al index.js  
```
import 'bootstrap';
```
* Agregamos los estiloc, adicionando la linea a index.scss
```
@import "~bootstrap/scss/bootstrap";
```

## Agregar el .gitignore
*Crean el la ruta de su proyecto un archivo .gitignore o lo abren si ya lo tienen y agregan 
node_modules/ al archivo 

  
