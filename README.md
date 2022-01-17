# TEST-API-REST
Desarrollo de un pequeño ejemplo de backend con el objeto de hacer testing con el uso de los módulos pertienentes para tal fin

 [este video de Fazt][video de fazt]
***

## Tecnologías usadas
- express: 
- supertest: Módulo que permite hacer las peticiones (hace el papel del navegador o de postman)
- jest: Es el framework encargado en si de hacer las comprobaciones
- uuid: Generador de número id


***
## Como correr el test
```
$ npm test
```
Al correr el test se espera que este entregue un reporte de cuales son aquellos test que pasan y cuales no
***


***
## Descripción detallada del proyecto y caracteristicas
Parte del desarrollo web es el testing, el cual consiste en entregar al backend algunas peticiones básicas y las salidas esperadas, las peticiones se realizan con el módulo *supertest*, mientras que las validaciones en si las realiza *jest*, los test se codifican en el archivo `index.spec.js`, es importante que el archivo tenga ese nombre. 
En el código del testing se comenta la forma de comprender el testing


***
## Descripción de la estructra del proyecto
- index.js es el que permite inciar la ejecución del desarrollo
- db.js: Encargado de toda la conexión a la base de datos
- config: Se encarga de traer el valor de la variable de entorno para el caso que se haga un despliegue en la nube
- commands.js: Es el archivo principal donde se definen los comandos de la app
- Models: carpeta con el modemlo de tareas
- Controllers, alli están las funciones encargadas de los procesos

*** 
## Por menores del proyecto
1. el uso de "type":"module" en el package.json permite el uso de la sintaxis de import sin la necesidad de babel
2. jest para que pueda soportar las sentencias import necesita de la siguiente configuración en su ejecución `set NODE_OPTIONS=--experimental-vm-modules && jest`, se usa el script test para su configuración

## Mejoras futuras
-   Diseñar mas testing
***
### Maolink software
Version. 1.0.0

Enero 2021



[video de fazt]:<https://www.youtube.com/watch?v=lZJ1mar_znk&list=PLFvTzgbYK-U7uOKvpW8kQfDF0BYzeMo3_&index=1&t=38s> 


***
# README.MD FAZT
## Jest Nodejs Supertest

Simple example of Testing a Nodejs express REST API using Jest and Supertest.

### Installation

```
git clone https://github.com/FaztWeb/nodejs-jest-supertest
cd nodejs-jest-supertest
npm install
```

### Test

```
npm test
```
