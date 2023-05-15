# INTRODUCCIÓN A REACT PARA PRINCIPIANTES

## Sobre el proyecto

Empezaremos a crear una aplicación web desde cero desde los conceptos basicos hasta el despliegue de la aplicacioón en Github Pages
___
## Conceptos que aprenderás en el camino
- Crear proyecto de React con Create-React-App
- Estructura del proyecto
- Hola Mundo en React
- Componentes en React
- Tu primer componente
- JSX
- EcmaScript - Javascript Modules
- Extensión jsx
- React Props
- PropTypes y default Props
- Estilos
- Tipos de componentes
- Event Handlers
- Fetch API
- Third Party modules - React Icons
- Array en React
- React Hooks
- useState
- useEffect
- React con Vitejs
- Mostrar lista de tareas
- Añadir tareas al formulario
- Separar componentes
- Eliminar Tarea
- Crear Contexto
- useContext
- TailwindCSS
- Despliegue Github Pages
___
## Sección 1 : Crear proyecto de React con create-react-app

Este proyecto se inició con [Create React App](https://github.com/facebook/create-react-app).

### Requisitos Previos
- [NodeJs](https://nodejs.org/en) 14.0 o posterior
- [VSCode](https://code.visualstudio.com/)

### Primeros pasos
1. Abrir la consola de comandos (CMD) sobre la carpeta de desarrollo

2. Crear una aplicación con  `create-react-app`:

```sh
npx create-react-app nombreProyecto
```
+ Creará un directorio llamado `nombreProyecto`dentro de la carpeta de desarrollo.\
Dentro de este directorio, generará la estructura inicial del proyecto e instalará las dependencias:
```
nombreProyecto
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
|   ├── logo192.png
|   ├── logo512.png
|   ├── manifest.json
│   └── robots.txt
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── reportWebVitals.js
    └── setupTests.js
```

+ Una vez finalizada la instalación puedes abrir la carpeta de tu proyecto React con VSCode :
```
code .
```

<details><summary>Primeros Pasos con Create React App</summary>
<p>
### Comandos habilitados

En el directorio del proyecto, puedes ejecutar:

### `npm start`

Ejecuta la aplicación en el modo desarrollo.\
Abrir [http://localhost:3000](http://localhost:3000) para verlo en el navegador.

La página se volverá a cargar cuando realice cambios.\

### `npm test`

Inicia el corredor de prueba en el modo de reloj interactivo.\
Consulte [running tests](https://facebook.github.io/create-react-app/docs/running-tests) para más información.

### `npm run build`

Construye la aplicación para producción en la carpeta `build`.\
Empaqueta correctamente React en modo de producción y optimiza la compilación para obtener el mejor rendimiento.

¡Tu aplicación está lista para ser implementada!

Consulte la sección [deployment](https://facebook.github.io/create-react-app/docs/deployment) para más información.\

</p>
</details>