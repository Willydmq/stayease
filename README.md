# Nombre del Proyecto 📋

"**StayEase:** enfatizar la experiencia relajante y cómoda que se busca al alojarse en un lugar". 😀

<div style="text-align: center; padding: 10px; display:flex flex-direction:column">
    <h1 style="font-size:25px; text-decoration-line: underline;">Version Escritorio 💻</h1>
    <h2>1. Home/Login/User</h2>
    <div style="display:flex; flex-wrap: wrap; gap:5px; justify-content: center;">
      <img src="/client/public/Home.png" width="300px" style="border: 3px solid #f5385d;">
      <img src="/client/public/Login.png" width="300px" style="border: 3px solid #f5385d;">
      <img src="/client/public/User.png" width="300px" style="border: 3px solid #f5385d;">
    </div>
    <h2>2. Accommodation/Bookings</h2>
    <div style="display:flex; flex-wrap: wrap; gap:5px; justify-content: center;">
      <img src="/client/public/Accommodation_1.png" width="300px" style="border: 3px solid #f5385d;">
      <img src="/client/public/Accommodation_2.png" width="300px" style="border: 3px solid #f5385d;">
      <img src="/client/public/Bookings.png" width="300px" style="border: 3px solid #f5385d;">
    </div>
</div>

# Link Proyecto

<div style="display: flex; flex-direction: column; align-items: center;">
    <img src="../airbn/client/public/StayEase.png" width="50px">
    <a style="color: blue; font-size: 20px; display: block; text-align: center;" href="#" target="_blank">StayEase</a>
</div>

## Instalación ⚙️

<strong>A. Instalación del proyecto Frontend</strong>

1. Asegúrese de tener instalado Node.js y Yarn en su computadora. Si no lo tiene instalado, puede descargar e instalar **Node.js y Yarn** en el sitio web oficial.

2. Descargar o clonar el repositorio del proyecto desde GitHub (carpeta client).

3. Abrir una terminal o línea de comandos en la carpeta raíz del proyecto.
4. Inicializar un nuevo proyecto de Node.js ejecutando el siguiente comando:

   ```
   yarn init
   ```

5. Ejecutar el comando `yarn add` para instalar todas las dependencias necesarias del proyecto, incluyendo:

   ```
   yarn add react react-dom react-router-dom axios date-fns postcss autoprefixer tailwindcss
   ```

   Esto instalará las siguientes dependencias:

   - react: biblioteca para construir interfaces de usuario.
   - react-dom: paquete de enlace DOM específico para React.
   - react-router-dom: paquete para manejar la navegación y el enrutamiento en una aplicación React.
   - axios: cliente HTTP basado en promesas para el navegador y Node.js.
   - date-fns: biblioteca para manipular, formatear y mostrar fechas.
   - postcss: herramienta de procesamiento de CSS.
   - autoprefixer: plugin de PostCSS para agregar prefijos de proveedor a las reglas CSS.
   - tailwindcss: biblioteca de CSS utilitario para diseñar interfaces de usuario.

6. Después de instalar las dependencias, para iniciar el proyecto frontend se puede ejecutar el siguiente comando:

   ```
   yarn dev
   ```

   Este comando iniciará el servidor de desarrollo y abrirá la aplicación en el navegador.

   Es **_importante_** mencionar que el comando yarn dev puede variar dependiendo de cómo se haya configurado el entorno de desarrollo y el servidor de desarrollo que se esté utilizando. En algunos casos, se puede utilizar el comando yarn start o yarn serve para iniciar el servidor de desarrollo.

<strong>B. Instalación del proyecto Backend</strong>

7. Asegúrese de tener instalado Node.js y Yarn en su computadora. Si no lo tiene instalado, puede descargar e instalar **Node.js y Yarn** en el sitio web oficial.

8. Descargar o clonar el repositorio del proyecto desde GitHub (carpeta api).

9. Abrir una terminal o línea de comandos en la carpeta raíz del proyecto.
10. Inicializar un nuevo proyecto de Node.js ejecutando el siguiente comando:

```
yarn init
```

11. Ejecutar el comando `yarn add` para instalar todas las dependencias necesarias del proyecto, incluyendo:

```
yarn add bcryptjs cookie-parser cors dotenv express image-downloader jsonwebtoken mongoose multer
```

Esto instalará las siguientes dependencias:

- bcryptjs: biblioteca para cifrar contraseñas y verificar contraseñas cifradas.
- cookie-parser: middleware para manejar cookies en Express.
- cors: middleware de Express para habilitar CORS en una aplicación Express.
- dotenv: biblioteca para cargar variables de entorno desdeun archivo .env.
- express: framework de servidor web para Node.js.
- image-downloader: biblioteca para descargar imágenes desde una URL.
- jsonwebtoken: implementación de JSON Web Tokens (JWT) en JavaScript.
- mongoose: biblioteca para modelar objetos de MongoDB.
- multer: middleware para manejar cargas de archivos en Express.

12. Después de instalar las dependencias, para iniciar el proyecto frontend se puede ejecutar el siguiente comando:

```
nodemon index.js
```

Este comando iniciará el servidor backend y escuchará las peticiones en el puerto configurado en el archivo index.js.

13. Es importante mencionar que para utilizar **_nodemon_**, primero se debe instalar globalmente en el sistema ejecutando el siguiente comando:

```
yarn global add nodemon
```

Una vez instalado globalmente, se puede utilizar el comando nodemon para iniciar el servidor backend.

### Requisitos 📄

1. Conocimientos: en HTML, CSS, JavaScript, **Vite ReactJS y MongoDB**.

2. Conocimientos de Git: La aplicación utiliza Git para el control de versiones, por lo que necesitará conocimientos básicos de Git para clonar el repositorio del proyecto, crear ramas, fusionar cambios y enviar solicitudes de extracción.

## Uso 💪

StayEase aplicación que hemos desarrollado, similar a Airbnb, puede ser utilizada por personas que buscan alojamiento temporal en un lugar específico, ya sea para vacaciones, trabajo o cualquier otra actividad. Los usuarios pueden buscar alojamientos que se ajusten a sus necesidades y presupuesto, y reservarlos directamente a través de la aplicación. La aplicación también puede ser utilizada por anfitriones que desean ofrecer alojamiento a los huéspedes y ganar dinero extra. Los anfitriones pueden publicar sus alojamientos en la aplicación y recibir reservas de los usuarios interesados. Además, la aplicación puede ofrecer servicios adicionales como guías turísticos, transporte, recomendaciones de restaurantes y actividades locales para mejorar la experiencia de los usuarios..

## Construido con 🛠️

<div style="text-align: center; padding: 10px;">
    <img src="/client/public/mongo.png" width="100px">
    <img src="/client/public/express.png" width="100px">
    <img src="/client/public/reactjs.png" width="100px">
    <img src="/client/public/nodejs.png" width="100px">
</div>

## Deployment 🚀

La arquitectura de nuestra aplicación consta de dos partes principales: el frontend y el backend. El frontend está construido con React y utiliza un enfoque de arquitectura de componentes para organizar y reutilizar el código. Utilizamos **React Router** para manejar la navegación en la aplicación y **Axios** para comunicarnos con el backend. El frontend también utiliza **TailwindCSS** para estilos y **PostCSS** para procesamiento de CSS.

El backend está construido con **Node.js y Express**, y utiliza una arquitectura de API RESTful para manejar las solicitudes de los usuarios. Utilizamos **MongoDB y Mongoose** para almacenar y recuperar datos, y **JSON Web Tokens (JWT)** para la autenticación y autorización de los usuarios. También utilizamos **bcrypt** para cifrar contraseñas, **multer** para manejar cargas de archivos y **dotenv** para cargar variables de entorno.

## Autores ✒️

- **William Maldonado** - _Challenge: Build a Fullstack Booking App using MERN_ - [Willydmq](https://github.com/Willydmq)

## Expresiones de Gratitud

- Me gustaría expresar mi más sincero agradecimiento a **[Coding With Dawid](https://github.com/dejwid)** por todo el esfuerzo y dedicación que ha puesto en el Challenge. 🤓.
- Gracias a sus enseñanzas y el video tutorial de **[YouTube](https://www.youtube.com/watch?v=MpQbwtSiZ7E)**, pude aprender nuevas habilidades y poner en práctica mis conocimientos para construir una aplicación similar a Airbnb. 📢.
- Estoy muy agradecido por la oportunidad de aprender de un tutor tan talentoso y dedicado, y espero seguir aprendiendo de él en el futuro. ¡Gracias de nuevo, **[Coding With Dawid](https://github.com/dejwid)**! 🌟.

---

⌨️ con ❤️ por [William Maldonado](https://github.com/Willydmq) 😊

---
