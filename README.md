# angular-ghpages
_Angular | GitHub Pages_  
Proyecto inicial de Angular desplegado sobre GitHub Pages.  
  
Comandos.  
Sobre la ruta local del proyecto Angular, vincula el proyecto local al repositorio remoto:  
git remote add origin URL_repo  
Sube los cambios del proyecto local al repositorio remoto (master es la rama por defecto del .git del proyecto de Angular):  
git push -u origin master  
Desde el repositorio dentro del navegador establecemos la rama master por defecto y eliminamos la rama main.  
ng add angular-cli-ghpages  
ng deploy --base-href=https://luisvalles92.github.io/nombre-del-repositorio-gh/  
Terminamos con un commit y un push desde VSC para guardar los cambios provocados por el npmjs.
  
[Enlace](https://luisvalles92.github.io/angular-ghpages/) | [Tutorial](https://www.youtube.com/watch?v=lM4A6SBK1uQ) | [npmjs](https://www.npmjs.com/package/angular-cli-ghpages) | [Repositorio](https://github.com/LuisValles92/angular-ghpages)
  
# ProyectoGHPages

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
