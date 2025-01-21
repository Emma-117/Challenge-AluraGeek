

# Proyecto AluraGeek Frontend Challenge

Este es mi proyecto para el reto de Frontend propuesto por Oracle Next Education y Alura LATAM.

## Descripción del reto

El reto consiste en crear una tienda en línea basada en el archivo [FIGMA](https://www.figma.com/file/AB8pEp5K7lo7xUYjQwdfYA/AluraGeek-(Copy)?type=design&node-id=0%3A1&mode=design&t=PGhF0WdsaFdfVfJV-1) proporcionado. Aunque se espera que sigamos el diseño del archivo FIGMA, también tenemos la libertad de personalizarlo a nuestro gusto.

Uno de los requisitos clave es implementar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) utilizando solicitudes HTTP. Esto significa que debemos poder gestionar y manipular los productos dentro de nuestra tienda, incluyendo leer, crear, eliminar y editar.

## Tecnologías utilizadas

El proyecto está construido usando JavaScript y utiliza JSON Server para simular la API para la gestión de productos.

## Empezando

Siéntete libre de clonar o modificar este proyecto para tus propios fines. Para empezar:

### 1. Clona este repositorio a tu máquina local.

   ```bash
   git clone https://github.com/SofiDevO/alura-geek.git
   ```

### 2. Explora el proyecto y realiza las personalizaciones necesarias para tus propios proyectos.

## Importante 🦉

Si deseas interactuar con la API, necesitarás cambiar la URL de Vercel a una API FALSA utilizando json-server.

Primero, necesitas instalar json-server:

```bash
npm install -g json-server
```

### 3 - Usa el archivo db.json
Debes usar el archivo ```db.json``` QUE YA HA SIDO creado, el cual actuará como la fuente de datos.

### 4 - Inicia el servidor

### Inicia el servidor JSON 

Ejecuta este comando en tu terminal: ```json-server --watch db.json.``` Esto se ejecutará por defecto en "https://localhost:3000". Puedes cambiar el puerto en el que se ejecuta especificando un número de puerto diferente al iniciar el servidor utilizando la bandera --port.

### El servidor JSON generará automáticamente endpoints RESTful basados en los datos definidos en tu archivo JSON.

Si tienes un archivo JSON con un array de "usuarios", estos son los endpoints que se generarán automáticamente por el servidor JSON:

- GET  /users - Recupera una lista de todas las entidades de usuarios.
- GET /users/:id - Recupera un usuario específico por su id.
- POST /users - Crea un nuevo usuario.
- PUT /users/:id - Actualiza un usuario basado en el id especificado.
- DELETE /users/:id - Elimina un usuario basado en el id especificado.

Este patrón facilita la interacción con la API simulada de manera RESTful, tal como se haría con una API real de backend.

4 - Reemplaza la API falsa de VERCEL con este nuevo recurso que creaste utilizando el comando ```json-server --watch db.json.``` Debería verse algo así:

![imagen](https://github.com/SofiDevO/alura-geek/assets/102200061/66f4c756-2b71-4ca2-840d-95ddc800aab6)

Ahora puedes realizar peticiones a HTTP.

## Contribuciones

Si deseas contribuir a este proyecto o informar sobre problemas, no dudes en enviar un pull request o abrir un problema en este repositorio. Agradecemos las contribuciones y comentarios de la comunidad.

## Agradecimientos

¡No olvides darle una estrella ⭐ a este repositorio si lo encuentras útil!

![Texto alternativo](image.png)
![Texto alternativo](image-1.png)
![Texto alternativo](image-2.png)
![Texto alternativo](image-3.png)
![Texto alternativo](image-4.png)
![Texto alternativo](image-5.png)
