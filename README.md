# Gestor de tiempos

Una aplicación para estudiantes y docentes con el objetivo de facilitar la monitorización y asignación de tareas.

# Instalación

La aplicación requiere de [Node.js](https://nodejs.org/) para funcioar.

Clonar el repositorio e instalar todas las dependencias.

```sh
$ git clone https://github.com/BZaldua/odsi18-firebase
$ cd odsi18-firebase/functions
$ npm i firebase-functions --save
$ npm i firebase-admin --save
$ npm i express --save
$ npm i ejs --save
$ npm i view-engine --save
```
Y se ejecuta el servidor local.

```sh
$ firebase serve
```
Comprobamos que está funcionando en el navegador.
```sh
localhost:5000
```
Notas: tarda un poco en iniciar.

### Interfaces

La aplicación tendrá distintas interfaces implementadas. A continuación una lista de la dirección que hay que poner para cada una (localhost:5000/[DIRECCION])

| Interfaz | Dirección |
| ------ | ------ |
| Inicio | / |
| Registro | /registro |
| Inicio usuarios | /inicioUsuarios |
| Inicio profesores | /inicioProfesor |
| Tareas de asignatura | /tareas |