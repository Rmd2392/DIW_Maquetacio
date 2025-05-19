# Proyecto Web - Bar Oliva Cafetería

Este proyecto web forma parte del módulo **DIW (Diseño de Interfaces Web)** del Grado Superior en Desarrollo de Aplicaciones Web (DAW) del **Institut TIC de Barcelona**. A lo largo de las prácticas 10, 11 y 12 se ha desarrollado un sitio web estructurado, responsive y multimedia.

---

##  Estructura del Repositorio

- `main` → **Práctica 10**: Maquetación base con HTML y CSS.
- `responsive` → **Práctica 11**: Adaptación responsive mediante `@media queries`.
- `multimedia` → **Práctica 12**: Transiciones, animaciones y contenido multimedia.

---

##  Tecnologías utilizadas

- HTML5 semántico
- CSS3 con Flexbox y Grid
- Responsive Design (`@media queries`)
- Transiciones y animaciones CSS
- Google Fonts & Material Icons
- JavaScript (para control de vídeo)
- Multimedia en `.mp4` y `.webm`

---

##  Visualización del Proyecto

1. Clona el repositorio.
2. Abre el archivo `index.html` para ver el proyecto completo con:
   - Efectos multimedia
   - Controles personalizados sobre vídeo
   - Animaciones y transiciones
3. Para el **ejercicio 3** de la práctica 12 (vídeo con controles nativos), abre `index_ex3.html`.

---

##  Detalle de prácticas

###  Práctica 10 – Maquetación

- Estructura web en HTML semántico.
- Secciones maquetadas:
  - **Sobre nosotros** → con **Flexbox**.
  - **Carta del menú**, **Formulario** → con **Grid Layout**.
  - **Galería** → con imágenes optimizadas y estilo hover.
- Código limpio y bien comentado.

---

###  Práctica 11 – Responsive Design

- Uso de **media queries** para adaptar el diseño a tablets y móviles.
- Cambios aplicados a:
  - Cabecera (alineación y visibilidad).
  - Menú de navegación (estructura vertical en móviles).
  - Galería (paso de 4 a 2 o 1 columnas según resolución).
  - Formulario (estructura más compacta y amigable).
  - Footer adaptado y reorganizado.

---

###  Práctica 12 – Multimedia, Transiciones y Animaciones

####  Ejercicio 1 – Transiciones

- Hover en imágenes de la galería:
  - **Zoom**, **rotación** y efecto `grayscale`.
- Hover en botón "Reservar":
  - Cambio de color, sombra y escala.

####  Ejercicio 2 – Animaciones

- Animación `fadeUpColor` al cargar la página:
  - Aplica a la cabecera.
  - Cambios progresivos de color, opacidad y posición.

####  Ejercicio 3 – Vídeo con controles nativos

- Se utiliza un archivo independiente: **`index_ex3.html`**.
- El vídeo:
  - Está silenciado y en pausa por defecto.
  - Se muestran los **controles nativos del navegador**.
- Esta separación es necesaria porque los requisitos de este ejercicio son **incompatibles** con los del siguiente (ejercicio 4).

####  Ejercicio 4 – Controles personalizados

- Se ocultan los controles nativos.
- Se implementan **iconos de Google Material** como controles:
  - Play, Pause, Mute, Unmute.
- Se añade un script en JavaScript para controlar el comportamiento del vídeo.

---

## ✅ Observaciones finales

- Todo el código CSS está unificado en **`style.css`** y **organizado por secciones y ejercicios**.
- Se han seguido buenas prácticas de codificación, comentarios explicativos y semántica.
- El uso de ramas permite distinguir claramente el desarrollo de cada práctica:
  - `main`: base estática.
  - `responsive`: diseño adaptativo.
  - `multimedia`: efectos dinámicos.

---

**Desarrollado por**: Ricardo Martín  
**Módulo**: Diseño de Interfaces Web (DIW)  
**Curso**: 2024–2025  
**Centro**: Institut TIC de Barcelona  

---
