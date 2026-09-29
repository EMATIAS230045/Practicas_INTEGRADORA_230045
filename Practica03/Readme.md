# 📊 Business Model Canvas Interactivo - YouTube

Una aplicación web interactiva y autocontenida que presenta el **Business Model Canvas (Lienzo de Modelo de Negocio)** para **YouTube**. Diseñada con un enfoque moderno, responsivo y dinámico que permite explorar los aspectos clave del negocio a diferentes niveles de profundidad.

---

## 📸 Capturas de Pantalla

A continuación se muestra la interfaz del proyecto y sus principales funcionalidades:

### 1. Vista General del Canvas
![Vista General](/Practica03/Evidencias/Vista%20inicial.png)
*Estructura general de los 9 bloques del Business Model Canvas estilizados con la paleta de colores oficial de YouTube.*

### 2. Alternancia de Perspectiva (Vista Simplificada vs. Extendida)
| Vista Simplificada | Vista Extendida |
| :---: | :---: |
| ![Vista Simplificada](./Evidencias/Vista%20del%20Model%20simple.png) | ![Vista Extendida](./Evidencias/Vista%20modelo%20extenso.png) |
| *Muestra hitos y puntos clave esenciales.* | *Detalla métricas, datos financieros y aspectos técnicos.* |

### 3. Modal Detallado e Interacción
![Modal Detallado](./Evidencias/Vista%20emergente.png)
*Ventana modal desplegada al hacer clic en un bloque. Permanece abierta hasta cerrar de forma explícita mediante la "X" o al hacer clic fuera del cuadro.*

---

## ✨ Características Principales

* **9 Bloques del Canvas:** Análisis completo del modelo de negocio real de YouTube (Socios clave, Actividades clave, Propuesta de valor, Fuentes de ingresos, etc.).
* **Modo Doble de Perspectiva:** Botón en la cabecera que permite cambiar instantáneamente entre una **Vista Simplificada** y una **Vista Extendida**.
* **Interacción Hover & Click:**
  * **Hover:** Vista previa rápida al pasar el cursor sobre los elementos.
  * **Click:** Apertura de modal con desglose exhaustivo y persistente.
* **Exportación a PDF:** Botón integrado que descarga la vista actual del lienzo en formato PDF utilizando `html2pdf.js`.
* **Diseño Standalone:** Todo el código HTML, CSS (Tailwind CSS) y JavaScript está autocontenido dentro de un solo archivo `index.html`.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica.
* **Tailwind CSS (CDN):** Estilizado responsivo y paleta de colores personalizada (YouTube Red & Dark theme).
* **JavaScript (Vanilla):** Lógica interactiva para la alternancia de vistas, controles del modal y tooltips.
* **html2pdf.js (CDN):** Renderizado y exportación en formato PDF directamente desde el navegador.

---

## 📁 Estructura del Proyecto

```text
.
├── index.html              # Archivo principal autocontenido (HTML + CSS + JS)
├── README.md               # Documentación del proyecto
└── assets/
    └── screenshots/        # Capturas de pantalla para el README
        ├── vista-general.png
        ├── vista-simplificada.png
        ├── vista-extendida.png
        └── modal-detalle.png
```

---

## 🚀 Despliegue en GitHub Pages

👉 **[Ver Práctica 03 en GitHub Pages](https://ematias230045.github.io/Practicas_INTEGRADORA_230045/Practica03/Archify/)**

---

## 💻 Ejecución Local

No requiere instalación de servidor ni dependencias node.js.

1. Clona o descarga este repositorio.
2. Haz doble clic en el archivo `index.html` para abrirlo directamente en tu navegador web preferido.

---

## 📝 Licencia

Este proyecto fue desarrollado como una práctica académica/educativa para el análisis de modelos de negocio interactivos.
