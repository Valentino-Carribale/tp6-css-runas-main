# 🏰 Dungeons & Dragons – Demostración de Layouts en CSS

### 21/07-28/07 | Valentino Carribale 4to Informático
### Funcionamiento de Sistemas Digitales | Prof. Roberto Argumedo

## 📖 Descripción

Este proyecto consiste en una página web temática inspirada en **Dungeons & Dragons**, diseñada para demostrar y comparar las tres principales técnicas de posicionamiento en CSS:

- Position
- Flexbox
- CSS Grid

Cada sección explica una técnica de diseño diferente e incluye una tarjeta con información sobre criaturas u objetos inspirados en la **Casa Cannith**. El objetivo es comprender el funcionamiento de cada sistema de posicionamiento utilizándolo exclusivamente en cada tarjeta.

---

## 🎯 Objetivos

- Comprender las diferencias entre **Position**, **Flexbox** y **CSS Grid**.
- Uso de Ingeniería Inversa en HTML.

---

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- Google Fonts
  - MedievalSharp
  - Respaldo en *sans-serif*

---

## 📂 Estructura del proyecto

```TP6
tp6-css-runas-main/
│
├── index.html
├── style.css
│
├── img/
│   ├── centinela.jpg
│   ├── goblin.jpg
│   ├── logo.jpg
│   └── matriz.jpg
│
└── README.md (este archivo)
```

---

## 🎨 Características

- Diseño inspirado en la estética medieval fantástica.
- Fondo oscuro con múltiples degradados radiales.
- Tipografía temática mediante Google Fonts.
- Diseño responsivo utilizando unidades relativas (`vw` y `vh`) en posiciones críticas.
- Uso de HTML con ingeniería inversa y CSS propio.
- Tarjetas con información de criaturas y artefactos.
- Práctica de sistemas de posicionamiento principales *(position, flexbox, grid)*.

---

## 💡 Decisiones de Diseño

- Tipografía personalizada obtenida en Google Fonts, ya que no encontré alguna integrada al 100% que cumpliera lo que quería, *sans-serif* de respaldo.
- Fondos con gradientes para simular luces en un castillo oscuro, sin tener que incluir una imagen en HTML.
- Bordes punteados y lineados con color de contraste.
- Espaciado para legibilidad óptima.
- Efectos *hover* en los *img* para darles contorno brillante.

---

## 🚀 Cómo ejecutar el proyecto

1. Descargar el archivo comprimido y descomprimirlo.

2. Abrir la carpeta del proyecto.

3. Ejecutar el archivo `index.html` en el navegador.

---

## 📖 Técnicas y Dificultades

Personalmente *Position* me pareció lo más sencillo, porque con una simple declaración ya es fácil moverlo con *top, bottom, left, right*. En los otros, Flex y Grid, hay que pensar un poco más en cuanto a ejes, cuadrículas, espaciado, etc.

- Tuve que jugar mucho con los márgenes para posicionar bloques de teoría y tarjetas, para asimilarlo lo más posible a la imagen de referencia.
- En varias ocasiones, como en *.header__logo*, la imagen se me deformaba en cuanto a ancho y alto, intenté arreglarlo poniendo el *height* en automático pero al final apliqué *align-items: center;*.

---

## 👤 Autor

**Valentino Carribale**

Proyecto educativo desarrollado para practicar y comparar las principales técnicas de posicionamiento en CSS mediante una interfaz inspirada en el universo de **Dungeons & Dragons**.