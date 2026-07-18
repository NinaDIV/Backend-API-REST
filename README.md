# Backend API REST — Servidor base con Node.js y Express

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

Backend minimalista que expone endpoints REST y sirve como base para proyectos de servidor. Implementado en JavaScript sobre Node.js con Express, con una estructura simple lista para extender con nuevas rutas y lógica de negocio.

## ✨ Características

- API REST básica lista para usar como punto de partida.
- Servidor Express en un único archivo (`server.js`), fácil de leer y extender.
- Manejo de respuestas HTTP estándar.
- Sin configuración adicional: instalar dependencias y arrancar.

## 🛠️ Tecnologías

| Tecnología | Rol |
|---|---|
| Node.js | Entorno de ejecución de JavaScript en el servidor |
| Express | Framework web minimalista para las rutas y respuestas HTTP |
| npm | Gestión de dependencias y scripts |

## 📋 Requisitos previos

Antes de ejecutar el proyecto necesitas tener instalado:

- **Node.js** (se recomienda la versión LTS, 18 o superior) — incluye **npm**. Verifica con:

  ```bash
  node --version
  npm --version
  ```

- **Git** para clonar el repositorio.

No se requieren variables de entorno ni base de datos.

## 🚀 Instalación y ejecución

1. Clona el repositorio y entra a la carpeta:

   ```bash
   git clone https://github.com/NinaDIV/Backend-API-REST.git
   cd Backend-API-REST
   ```

2. Instala las dependencias:

   ```bash
   npm install
   ```

3. Arranca el servidor:

   ```bash
   npm start
   ```

4. La API estará disponible en `http://localhost:3000`. Puedes comprobarlo abriendo esa URL en el navegador o con `curl http://localhost:3000`.

## 📁 Estructura del proyecto

```
Backend-API-REST/
├── server.js          # Punto de entrada: configura Express y define las rutas
├── package.json       # Dependencias y scripts (npm start)
├── package-lock.json  # Versiones exactas de las dependencias
└── README.md
```
