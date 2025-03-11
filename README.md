# 🎨 Aleeza Sajid - Portfolio

Este es mi portafolio personal, donde muestro mi trabajo como Web Developer.

## 🖼️ Capturas

![Portfolio](portfolio.png)

Efecto Hover en Imagen de Perfil



## 📌 Características

- **Botón "Ver Más"**: Redirige al usuario a la página `home.html` para conocer más sobre Aleeza y su trabajo.
- **Botón de Cambio de Color**: Permite cambiar aleatoriamente el color de fondo de la página al hacer clic.
- **Imagen de Perfil**: Una imagen de perfil con un estilo atractivo.
- **Diseño Responsivo**: Adaptable a dispositivos móviles, tabletas y escritorios.
- **Animaciones Sutiles**: Efectos visuales suaves para una experiencia de usuario más atractiva.

## 🖱️ Botón de Cambio de Color

El botón de cambio de color aleatorio permite una interacción divertida con la   página, cambiando el color de fondo al azar cada vez que se hace clic.
Código JavaScript para Cambio de Color:

### Código JavaScript para Cambio de Color:

document.querySelector(".change-color").addEventListener("click", function() {
    document.body.style.backgroundColor = "#" + Math.floor(Math.random()*16777215).toString(16);
});

- Este código genera un color aleatorio en formato hexadecimal y lo aplica al fondo de la página.



## 🚀 Tecnologías utilizadas

- HTML5
- CSS3 (Animaciones y Media Queries)
- JavaScript (Eventos y Dinámica de la página)

## 📂 Estructura del Proyecto
/
- |-- index.html   # Archivo principal
- |-- style.css    # Estilos de la página
- |-- script.js    # Funciones interactivas
- |-- /assets/img  # Imágenes del proyecto

## ⚙️ Instalación y Uso

Clonar el repositorio
git clone https://github.com/Aleeza951/portfolio.git

 ## Funcionalidades

- Botón "Ver Más": Redirige a la página de inicio.
- Cambio de color de fondo: Un botón cambia el color aleatoriamente.
- Animaciones y transiciones: Efectos visuales en texto e imágenes.

## 🖥️ Responsive Design

- El portafolio es totalmente responsivo y se adapta a:

✅ Móviles 
✅ Tablets 
✅ Escritorio

## 🔗 Enlaces

Portafolio en vivo: Mi Portafolio

GitHub: Aleeza Sajid