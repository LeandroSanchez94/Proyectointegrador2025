🛍️ Evidencia 1 - Catálogo de Productos
📌 Descripción

Este proyecto es un catálogo interactivo de productos que consume datos de la API DummyJSON. Desarrollado con:

    ⚛️ React + Vite

    🎨 Tailwind CSS

    🔄 Axios

    📱 Diseño responsive

🚀 Cómo ejecutar el proyecto
Requisitos previos

    Node.js (versión 16 o superior)

    npm (viene con Node.js)

    Git (opcional)

Pasos de instalación

    Clonar el repositorio (o descargar como ZIP):

// Escribir en terminal (en caso de querer hacerlo por git)

git clone https://github.com/LeandroSanchez94/Proyectointegrador2025.git
cd Proyectointegrador2025

    Instalar dependencias:

// Escribir en terminal

npm install

Nota: El repositorio no incluye la carpeta node_modules (es normal en proyectos Node.js). Se creará automáticamente al ejecutar este comando.

    Iniciar la aplicación:

// Escribir en terminal

npm run dev

    Abrir en el navegador:
    La aplicación estará disponible en:
    👉 http://localhost:5173

🛠️ Estructura del proyecto

Proyectointegrador2025/
├── src/
│   ├── components/
│   │   └── ProductCard.jsx  # Componente reutilizable de producto
│   ├── App.jsx              # Componente principal
│   ├── main.jsx             # Punto de entrada
│   └── App.css              # Estilos base
├── public/                  # Assets estáticos
├── .gitignore               # Archivos excluidos de Git
└── package.json             # Dependencias y scripts

🔍 Características principales

✅ Listado de productos con paginación
✅ Diseño responsive (mobile, tablet, desktop)
✅ Animaciones al hacer hover
✅ Indicador de carga
✅ Manejo de errores
📌 Notas importantes

    No subir node_modules: Esta carpeta debe regenerarse con npm install

    Variables de entorno: Si necesitas configurar API keys, crear un archivo .env

    Problemas comunes:

        Si falla la instalación, intenta borrar node_modules y package-lock.json y reinstalar

        Verifica que tengas la última versión de Node.js

📚 Documentación útil

    React Docs (https://react.dev/)

    Tailwind CSS (https://tailwindcss.com/docs/installation/using-vite)

    DummyJSON API (https://dummyjson.com/docs)
    