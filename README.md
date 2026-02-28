# Proyecto Integrador Frontend - Alquimia Literaria

---

## 📖 Descripción del Proyecto

Este repositorio contiene el frontend de "Alquimia Literaria", una plataforma digital para la compra, venta y lectura de libros en línea. Corresponde al primer hito de desarrollo, enfocado en establecer una arquitectura escalable y un flujo de trabajo colaborativo.

---

## 🛠️ Versiones de Software

- **Node.js:** v18.0.0 o superior
- **React:** v18.2.0
- **Vite:** v4.0.0
- **npm:** v9.0.0 o superior

---

## 🚀 Comandos de Instalación y Ejecución

Sigue estos pasos para ejecutar el proyecto localmente:

1. Clonar el repositorio:
   ```bash
   git clone [URL_DEL_REPOSITORIO]
   ```

2. Acceder al directorio del proyecto:
   ```bash
   cd alquimia-literaria-front
   ```

3. Instalar las dependencias:
   ```bash
   npm install
   ```

4. Ejecutar el proyecto en modo desarrollo:
   ```bash
   npm run dev
   ```
5. Abrir el navegador en la dirección que indique la terminal (generalmente http://localhost:5173)

---

## Integrantes del Equipo

| Nombre                  | Usuario GitHub     |
|-------------------------|--------------------|
| Santiago Zapata Villada | @SantiagoZVcesde   |
| [Nombre 2]              | @[usuario]         |
| [Nombre 3]              | @[usuario]         |
| [Nombre 4]              | @[usuario]         |

---

## 📁 Estructura del Proyecto

A continuación se detalla la organización de los directorios y archivos principales del frontend:

```text
src/
├── assets/          # Recursos estáticos (imágenes, logos, estilos globales)
├── components/      # Componentes UI reutilizables (Navbar, Footer)
├── helpers/         # Funciones de utilidad (validaciones, formateo)
├── pages/           # Vistas de alto nivel (Home, Login)
├── services/        # Comunicación con backend (vacío por ahora)
├── router/          # Configuración de navegación (vacío por ahora)
├── App.jsx          # Orquestador principal
└── main.jsx         # Punto de entrada de React