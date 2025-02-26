# README - Proyecto de Página Web para Aprendizaje de Programación

## Descripción del Proyecto

Este proyecto consiste en una página web diseñada para facilitar el aprendizaje de programación, proporcionando recursos educativos, ejercicios prácticos y una interfaz intuitiva para los usuarios.

---

## 1. Diseño de la Página

La página web ha sido diseñada siguiendo las mejores prácticas de desarrollo web:

- **Front-end:** Utiliza **HTML, CSS y JavaScript** junto con **React.js** para una experiencia de usuario dinámica e interactiva.
- **Estilos:** Se ha implementado **Tailwind CSS** para un diseño moderno y responsivo.
- **Back-end:** Se basa en **Node.js con Express.js** para gestionar la lógica del servidor y la API.
- **Base de Datos:** Utiliza **MongoDB** para almacenar información de usuarios y contenido educativo.
- **Autenticación:** Se implementó **JWT (JSON Web Token)** para una autenticación segura.
- **API REST:** Se construyó una API para la gestión de usuarios y el acceso a los recursos educativos.
- **Despliegue:** Se puede alojar en plataformas como **Vercel, Netlify o Heroku**.

---

## 2. Configuración y Ejecución Local

Para ejecutar la página web en tu entorno local, sigue estos pasos:

### **2.1 Requisitos Previos**

Asegúrate de tener instalados los siguientes programas:

- **Node.js** ([https://nodejs.org/](https://nodejs.org/))
- **Git** ([https://git-scm.com/](https://git-scm.com/))
- **MongoDB** (si se usa localmente, de lo contrario, puedes usar un servicio en la nube como MongoDB Atlas)

### **2.2 Clonar el Repositorio**

Abre la terminal y clona el repositorio con el siguiente comando:

```sh
 git clone https://github.com/usuario/repositorio.git
 cd repositorio
```

### **2.3 Instalación de Dependencias**

Ejecuta el siguiente comando para instalar las dependencias:

```sh
 npm install
```

### **2.4 Configurar Variables de Entorno**

Crea un archivo **.env** en la raíz del proyecto y agrega las siguientes variables:

```
PORT=5000
MONGO_URI=mongodb+srv://usuario:contraseña@cluster.mongodb.net/baseDeDatos
JWT_SECRET=tu_secreto_jwt
```

### **2.5 Ejecutar el Servidor**

Para iniciar el servidor, usa el siguiente comando:

```sh
 npm start
```

Si estás trabajando con el entorno de desarrollo, puedes usar:

```sh
 npm run dev
```

Esto iniciará el servidor en **[http://localhost:5000](http://localhost:5000)**.

### **2.6 Iniciar el Cliente (Front-end)**

Dirígete al directorio del frontend:

```sh
 cd frontend
 npm install
 npm start
```

Esto iniciará la aplicación en **[http://localhost:3000](http://localhost:3000)**.

---

## 3. Contribuir al Proyecto

Si deseas contribuir, sigue estos pasos:

1. **Fork** al repositorio.
2. Crea una rama nueva: `git checkout -b mi-rama`.
3. Realiza tus cambios y confirma los cambios: `git commit -m "Mi mejora"`.
4. Sube los cambios: `git push origin mi-rama`.
5. Abre un **Pull Request** en GitHub.

---

## 4. Contacto

Si tienes dudas o sugerencias, puedes contactarnos en **[ccuzco.p@gmail.com](mailto\:ccuzco.p@gmail.com)** o crear un **issue** en el repositorio de GitHub.

---

**Autor:** Carla Cuzco **Licencia:** MIT


