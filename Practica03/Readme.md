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

Para publicar este proyecto gratuitamente en internet utilizando **GitHub Pages**, sigue estos sencillos pasos:

1. **Subir el código a GitHub:**
   Asegúrate de haber subido todos los archivos a un repositorio público o privado de tu cuenta en GitHub:
   ```bash
   git add .
   git commit -m "feat: agregar Business Model Canvas interactivo de YouTube"
   git push origin main
   ```

2. **Configurar GitHub Pages:**
   * Entra a tu repositorio en GitHub.
   * Haz clic en la pestaña **Settings** (Configuración) en la parte superior.
   * En el menú lateral izquierdo, selecciona **Pages** (dentro de la sección *Code and automation*).

3. **Seleccionar la Rama de Despliegue:**
   * En la sección **Build and deployment** -> **Source**, selecciona **Deploy from a branch**.
   * En el desplegable de **Branch**, elige `main` (o `master`) y selecciona la carpeta `/ (root)`.
   * Haz clic en **Save** (Guardar).

4. **Acceder a tu sitio web:**
   * Espera de 1 a 2 minutos mientras GitHub genera la página.
   * Refresca la sección de GitHub Pages y verás un mensaje con el enlace público de tu aplicación:
     `https://ematias230045.github.io/Practicas_INTEGRADORA_230045/Practica03/Archify/`

---

## 💻 Ejecución Local

No requiere instalación de servidor ni dependencias node.js.

1. Clona o descarga este repositorio.
2. Haz doble clic en el archivo `index.html` para abrirlo directamente en tu navegador web preferido.

---

## 📝 Licencia

Este proyecto fue desarrollado como una práctica académica/educativa para el análisis de modelos de negocio interactivos.
