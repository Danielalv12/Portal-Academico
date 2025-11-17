# Portal Académico Seguro con Autenticación Multifactor (MFA)

# Realizado por:
Carlos Daniel Alvarez Quintero - 1099734902
Rusbell Oveymar Endes - 1116868419
Wilson Parada Gelvez - 1094275964

## Descripción del proyecto
Este proyecto consiste en el desarrollo de un portal académico web que integra un sistema de autenticación multifactor (MFA), combinando el uso de una contraseña tradicional y un código OTP temporal. El objetivo principal es fortalecer la seguridad en el acceso a información sensible perteneciente a estudiantes, docentes y administradores, mitigando riesgos como el phishing, el robo de credenciales y los accesos no autorizados.

## Tecnologías utilizadas

### Frontend
- React
- HTML, CSS, JavaScript

### Backend
- Node.js + Express

### Base de datos
- MySQL o PostgreSQL

### Seguridad
- JWT (gestión de sesiones)
- Bcrypt (hash de contraseñas)
- Generación y verificación de OTP (correo o app autenticadora)

---

## Estructura del proyecto

portal-academico-mfa/
├── backend/
│   ├── src/
│   │   ├── config/          # Configuración del servidor y base de datos
│   │   ├── controllers/     # Controladores de autenticación y usuarios
│   │   ├── routes/          # Rutas de la API (auth, otp, roles)
│   │   ├── models/          # Modelos de la base de datos (usuarios, logs)
│   │   ├── middlewares/     # Middlewares de seguridad (JWT, validaciones)
│   │   └── app.js           # Archivo principal de configuración de Express
│   ├── package.json         # Dependencias y scripts del backend
│   └── README.md            # Información técnica específica del backend
│
├── frontend/
│   ├── src/
│   │   ├── components/      # Componentes reutilizables (input OTP, formularios)
│   │   ├── pages/           # Páginas principales (Login, MFA, Dashboard)
│   │   ├── services/        # Conexiones con la API del backend
│   │   └── App.jsx          # Componente principal del frontend
│   ├── package.json         # Dependencias y scripts del frontend
│   └── README.md            # Información técnica específica del frontend
│
├── docs/
│   ├── informe.pdf          # Documento final del proyecto (8–10 páginas)
│   └── diagramas/           # Diagramas y material de apoyo
│
├── .gitignore               # Archivos ignorados por Git
└── README.md                # README técnico principal del repositorio

## Requisitos previos
Para ejecutar el proyecto es necesario contar con:

- Node.js instalado (versión recomendada: LTS)
- npm o yarn
- Motor de base de datos (MySQL o PostgreSQL)
- Git para clonar el repositorio