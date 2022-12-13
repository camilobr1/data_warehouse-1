# Data Warehouse

Este proyecto consiste en la creación de herramienta que permite a una compañía de Marketing administrar todos los contactos de sus clientes para sus campañas.

## Construido con 

- HTML
- CSS
- JavaScript
- Node JS
- Express js
- Sequelize
- MySQL
- JWT
- Postman
- Swagger

## Documentación 

Archivo `spec.yaml` Para verlo mejor, puede copiarlo y abrirlo con [Swagger](https://editor.swagger.io/)

## Instalación ⚙

Clonar el repositorio de [GitHub](https://github.com/camilobr1/data_warehouse.git)

```
git clone https://github.com/camilobr1/data_warehouse.git
```

## Dependencias 🟢

Instalar las dependencias requeridas para el correcto funcionamiento de la aplicación

```
npm install express
npm install sequelize
npm install mysql2
npm install body-parcer
npm install jsonwebtoken
npm install cors
npm install nodemon
```

## Base de datos SQL 

1. Instalar [Xamp](https://www.apachefriends.org/es/index.html) y abrir el panel de control, iniciando MySQL y Apache.
2. Abrir el navegador con localhost, phpmyadmin y en sql crear el schema "data_warehouse".
3. Replicar las tablas del documento.

## Inicio del servidor 

En package.json reemplazar la linea:

```
"scripts": {"test": "echo \"Error: no test specified\" && exit 1"},
```

Por esta linea:

```
"scripts": {"start": "node index","dev": "nodemon index"},
```

Posicionarse en la carpeta _Backend_ en una terminal y ejecutar el siguiente comando:

```
npm run dev
```

## Autores 

- **Conrado Vargas** - _Desarrolo web_ - [Camilo Bravi](https://github.com/camilobr1)
- **Acámica** - _Recursos y UI_ - [Acámica](https://github.com/acamica)

## Repositorio 

- [GitHub](https://github.com/camilobr1/data_warehouse.git)
