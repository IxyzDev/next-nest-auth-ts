# NextNestAuthTS

Este proyecto es una guía completa para implementar autenticación de usuarios utilizando **Next.js**, **NestJS**, y **TypeScript**. Está diseñado para desarrolladores que desean comprender cómo funcionan las configuraciones de autenticación en un entorno full-stack utilizando tecnologías modernas de JavaScript.

🚧 PROXIMAMENTE

## 🚀 Características

<!-- - Autenticación con JWT
- Protección de rutas en Next.js
- Integración completa con API de NestJS
- Validación de usuarios y manejo de errores
- Desarrollo en TypeScript para una mayor robustez -->



## 🛠 Tecnologías Utilizadas
<!-- 
- **Next.js**: para la interfaz de usuario y protección de rutas del lado del cliente
- **NestJS**: para manejar la API del lado del servidor y la autenticación
- **TypeScript**: para una tipificación estática y mejor desarrollo de código
- **JWT (JSON Web Tokens)**: para la gestión de autenticación segura
 -->


## 📋 Pre-requisitos
<!-- 
Antes de comenzar, asegúrate de tener instalado:

- Node.js (>= 14.x)
- Yarn o NPM
- Docker (opcional para bases de datos) -->

## 📂 Estructura del Proyecto
<!-- 
```
next-nest-auth-ts/
├── client/                 # Aplicación Next.js
│   ├── pages/              # Páginas de Next.js
│   ├── components/         # Componentes compartidos
│   ├── utils/              # Utilidades (auth, helpers, etc.)
│   └── services/           # Lógica de autenticación
├── server/                 # API con NestJS
│   ├── src/
│   │   ├── auth/           # Módulo de autenticación
│   │   ├── users/          # Módulo de usuarios
│   │   └── common/         # Utilidades y guardas
└── README.md
``` -->

## ⚙️ Instalación y Configuración
<!-- 


1. **Clona el repositorio**:
    ```bash
    git clone https://github.com/tuusuario/next-nest-auth-ts.git
    cd next-nest-auth-ts
    ```

2. **Instala las dependencias para el cliente y servidor**:
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

3. **Configura las variables de entorno**:

    Crea un archivo `.env` tanto en `client/` como en `server/`:

    ```bash
    # server/.env
    JWT_SECRET=tu_secreto_jwt
    DATABASE_URL=tudatabaseurl

    # client/.env.local
    NEXT_PUBLIC_API_URL=http://localhost:3001
    ```

4. **Ejecuta el proyecto**:
     -->

## 🚧 Uso y Ejemplos

<!-- 1. **Registro de Usuarios**: Visita `/register` en el cliente para crear una cuenta.
2. **Iniciar Sesión**: Accede a `/login` para iniciar sesión. Un JWT se almacenará en las cookies para futuras autenticaciones.
3. **Protección de Rutas**: Accede a rutas protegidas como `/dashboard` solo si estás autenticado.
4. **API NestJS**: Prueba la API en `http://localhost:3001/api` para verificar las respuestas de autenticación. -->
