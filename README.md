# 💻 Digitalizame - Frontend

Este es el **frontend del proyecto Digitalizame**, una plataforma de apoyo a la transformación digital de pequeñas empresas y emprendedores. La interfaz está desarrollada con tecnologías web puras: **HTML, CSS y JavaScript**, conectada a un backend hecho en Spring Boot con persistencia en base de datos **MySQL**.

---

## 🚀 Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- Consumo de API REST
- Arquitectura desacoplada (Frontend ↔ Backend)

---

## 📂 Estructura del proyecto

```bash
digitalizame-frontend/
├── index.html               # Página principal
├── about.html               # Página sobre el proyecto
├── contact.html             # Página de contacto
├── css/
│   └── styles.css           # Estilos generales
├── js/
│   ├── main.js              # JS principal de interacción
│   └── api.js               # Conexión con backend (fetch)
├── components/
│   ├── header.html          # Encabezado reutilizable
│   ├── footer.html          # Pie de página reutilizable
│   └── navbar.html          # Barra de navegación
├── assets/
│   ├── images/              # Logos e imágenes
│   └── icons/               # Íconos (SVG, PNG)
└── README.md                # Documentación del frontend

🌐 Conexión con backend

El frontend se conecta al siguiente backend:

🔗 Repositorio del backend (Spring Boot)

Base de datos usada: MySQL
Puerto por defecto del backend: http://localhost:8080

Ejemplo de una llamada desde api.js:

fetch('http://localhost:8080/api/usuarios')
  .then(response => response.json())
  .then(data => console.log(data));

📌 Recomendaciones para desarrollo

    Ejecuta el backend localmente antes de cargar el frontend.

    Asegúrate de que CORS esté habilitado en el backend si usas HTML local.

    Puedes usar extensiones como Live Server en VSCode para simular entorno de producción local.

🧪 Próximas funcionalidades

    Formulario de contacto funcional (POST al backend)

    Login y dashboard para usuarios registrados

    Registro dinámico de necesidades de digitalización

✨ Autores

    Proyecto académico Digitalizame

    Desarrollo por: @Cuoralex

📜 Licencia

Este proyecto se distribuye bajo la Licencia MIT.


---

¿Quieres que también te genere la estructura y contenido inicial para `index.html`, `styles.css` y `api.js` conectados al backend?

