# ❤️ Corazón Latiendo con HTML y CSS

![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![Status](https://img.shields.io/badge/Status-Activo-green)

Proyecto simple de animación web que muestra un **corazón latiendo
creado únicamente con HTML y CSS**.

Este proyecto demuestra cómo crear **animaciones visuales utilizando
CSS**, sin necesidad de JavaScript.

------------------------------------------------------------------------

# 📚 Tabla de Contenido

-   Descripción
-   Tecnologías utilizadas
-   Cómo funciona
-   Estructura del proyecto
-   Cómo ejecutar el proyecto
-   Ejemplo de código
-   Mejoras futuras
-   Autor

------------------------------------------------------------------------

# 📖 Descripción

Este proyecto consiste en una animación de un corazón que simula el
**latido del corazón utilizando CSS**.

La animación se logra mediante:

-   Transformaciones CSS
-   Animaciones con `@keyframes`
-   Propiedades como `scale()` y `rotate()`

Las animaciones CSS permiten crear efectos visuales dinámicos
directamente en el navegador sin depender de JavaScript.

------------------------------------------------------------------------

# 🛠 Tecnologías utilizadas

Este proyecto utiliza tecnologías básicas de desarrollo web:

-   HTML5
-   CSS3
-   Animaciones CSS (`@keyframes`)
-   Transformaciones (`transform`)

------------------------------------------------------------------------

# 🧠 Conceptos practicados

Este proyecto ayuda a practicar conceptos importantes como:

-   Estructura de páginas web con HTML
-   Estilos con CSS
-   Creación de formas con CSS
-   Uso de pseudoelementos (`::before`, `::after`)
-   Animaciones con `@keyframes`
-   Transformaciones (`scale`, `rotate`)

------------------------------------------------------------------------

# 📂 Estructura del proyecto

    corazon-latiendo-html-css
    │
    ├── index.html
    ├── styles.css
    └── README.md

-   **index.html** → estructura del proyecto\
-   **styles.css** → estilos y animación del corazón

------------------------------------------------------------------------

# ▶️ Cómo ejecutar el proyecto

### 1️⃣ Clonar el repositorio

``` bash
git clone https://github.com/Joseluis30c/corazon-latiendo-html-css.git
```

### 2️⃣ Entrar a la carpeta del proyecto

``` bash
cd corazon-latiendo-html-css
```

### 3️⃣ Abrir el archivo HTML

Solo abre el archivo en tu navegador:

    index.html

------------------------------------------------------------------------

# 💡 Ejemplo de código

Ejemplo de animación CSS para simular el latido:

``` css
@keyframes beat {
  0% {
    transform: scale(1) rotate(-45deg);
  }
  100% {
    transform: scale(1.1) rotate(-45deg);
  }
}

.heart {
  animation: beat 1s infinite alternate;
}
```

------------------------------------------------------------------------

# 🚀 Mejoras futuras

Posibles mejoras para este proyecto:

-   Agregar control de velocidad del latido
-   Hacer el diseño responsive
-   Agregar interacción con JavaScript
-   Agregar varios corazones animados
-   Convertirlo en un componente reutilizable

------------------------------------------------------------------------

# 👨‍💻 Autor

**Jose Luis Chavesta Rivas**

GitHub\
https://github.com/Joseluis30c

------------------------------------------------------------------------

# ⭐ Apoya el proyecto

Si este proyecto te resulta útil o interesante:

⭐ Dale una estrella al repositorio en GitHub.
