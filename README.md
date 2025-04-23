# 🧠 Editor de Preguntas Interactivas - Backend  
Sistema de gestión para preguntas educativas interactivas con validaciones y control de usuarios.

Este repositorio contiene la parte del servidor del proyecto, encargada de manejar la lógica de negocio, validaciones, autenticación y persistencia de datos.

---

## 🚀 Características principales

📦 API RESTful construida con NestJS  
🧩 Arquitectura escalable y modular  
🔐 Soporte para autenticación, autorización y roles  
📊 Prisma ORM con MySQL  

---

## 🎓 Roles de usuario

- **Profesor / Autor**  
  Crear preguntas interactivas y tradicionales.  
  Compartir contenido fácilmente.  
  Exportar preguntas como archivos HTML o XML con recursos incluidos (imágenes, PDFs, etc).

- **Administrador**  
  Gestión general del sistema y usuarios.

---

## ❓ Tipos de Preguntas

🔸 Interactivas: Arrastrar, ordenar, puzzles  
🔸 Tradicionales: Múltiple opción, respuesta corta  
🔸 Recursos: Imágenes, PDF  

---

## 🛠️ Tecnologías

- ⚙️ NestJS 
- 🔗 Prisma ORM
- 🐬 MySQL

---

## 📋 Requisitos Previos

- Node.js   
- PNPM (gestor de paquetes rápido y moderno)  
  Si no lo tienes instalado, ejecutar:

  ```bash
  npm install -g pnpm

## ⚙️ Instalación y Configuración Inicial

```bash
# Clonar el repositorio
git clone https://github.com/Jhosephcaceres19/pWeb-backend.git
cd pWeb-backend

# Instalar dependencias
pnpm install

# Iniciar el servidor en modo desarrollo
pnpm start:dev
```