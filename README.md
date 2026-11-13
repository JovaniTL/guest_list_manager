# 🎉 GuestFlow - Gestor de Lista de Invitados

Aplicación web interactiva desarrollada con **JavaScript Vanilla** y **HTML5** para la gestión, control de asistencia y filtrado avanzado de invitados a eventos.

---

## 📌 Descripción

Este proyecto fue desarrollado como parte de la materia **Desarrollo de Aplicaciones Web Modernas** (8.° Semestre). Consiste en un sistema para administrar la lista de invitados a una fiesta o evento, permitiendo registrar nuevas personas evitando duplicados, gestionar el estado de confirmación de asistencia, y realizar operaciones avanzadas de búsqueda, filtrado y manipulación de cadenas y arreglos.

---

## ✨ Características Principales

### 📋 Gestión de Asistencia
- **Agregar Invitados**: Validación para evitar campos vacíos y nombres duplicados.
- **Confirmación de Asistencia**: Marcado de confirmación con registro del orden de llegada/confirmación (`# Confirmación`).
- **Eliminación**: Posibilidad de remover invitados de la lista de manera individual.
- **Contador en Tiempo Real**: Visualización de la cantidad total de invitados registrados.

### 🔍 Filtros y Funciones Especiales
- **5 Vocales**: Filtra y muestra aquellos nombres que contienen todas las vocales (*ej. Aurelio*).
- **Palíndromos (Al derecho y al revés)**: Detecta nombres que se leen igual en ambas direcciones (*ej. Ana*).
- **Capitalización**: Transforma los nombres a formato título (primera letra mayúscula y el resto minúsculas).
- **Orden Alfabético**: Ordena la lista completa alfabéticamente.
- **Últimos $N$ Confirmados**: Muestra los últimos $N$ invitados que confirmaron su asistencia en orden cronológico.
- **Orden Inverso**: Muestra una copia de la lista en orden inverso al registro.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica de la interfaz.
- **JavaScript (ES6+)**: Manipulación del DOM, programación funcional con métodos de arreglos (`filter`, `map`, `some`, `sort`, `slice`, `reverse`, `every`).
- **CSS3**: Hoja de estilos vinculada (`styles.css`).

---

## 📂 Estructura del Proyecto

```plaintext
ExamenDiagnostico/
│
├── index.html      # Estructura de la aplicación e interfaz de usuario
├── script.js       # Lógica del negocio, manejo del DOM y filtros
├── styles.css      # Estilos visuales
└── README.md       # Documentación del proyecto
```

---

## 🚀 Cómo Ejecutar el Proyecto

No requiere instalación de dependencias ni gestores de paquetes.

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/TU-USUARIO/NOMBRE-DEL-REPO.git
   ```
2. **Abrir el proyecto**:
   - Puedes abrir directamente el archivo [index.html](file:///c:/Users/jovas/Documents/8%20Octavo%20Semestre/Desarrollo%20de%20aplicaciones%20web%20modernas-%20Jose%20Alfredo/ExamenDiagnostico/index.html) en tu navegador preferido (doble clic).
   - O bien, si usas **VS Code**, utiliza la extensión **Live Server** haciendo clic derecho en `index.html` > *Open with Live Server*.

---

## 👨‍💻 Autor

- **José Alfredo** - Estudiante de Ingeniería / Desarrollo de Software (8.° Semestre)
- Materia: *Desarrollo de Aplicaciones Web Modernas*

