# Proyecto Lumen — Mapa de Producto y Modelo Canvas

Este repositorio contiene la documentación visual e interactiva de **Proyecto Lumen** (*Dimatrek Studio*), una propuesta de juego de aventura isométrica y puzles centrada en el robot de reparación **M-4** y su compañero **PIP**.

El archivo principal `ModeloCanvas.html` presenta una interfaz web interactiva que sintetiza la estrategia de negocio (Business Model Canvas), el modelo 3D del personaje y la arquitectura técnica del sitio.

---

## 🚀 Características principales

- **Visor 3D Interactivo (Three.js):**
  - Renderizado en tiempo real del robot M-4 mediante WebGL.
  - Soporte para rotación interactiva (arrastrar con ratón/touch o mediante las teclas de dirección `←` `→`).
  - Iluminación cinematográfica (HemisphereLight, DirectionalLight y PointLight) y adaptación a preferencias de movimiento reducido (`prefers-reduced-motion`).
  - Imagen de respaldo en caso de que WebGL no esté disponible.

- **Business Model Canvas (Osterwalder):**
  - Matriz responsiva de 9 bloques estratégicos.
  - Diferenciación clara de niveles de certeza mediante un código de color (Premisa documentada vs. Hipótesis/Propuesta).
  - Modal interactivo con detalles expandidos, imágenes contextuales y resúmenes estratégicos.
  - Alternador de vista (*Vista compacta* vs. *Vista completa*).

- **Documentación de Arquitectura y Alcance:**
  - Desglose del stack del sitio (Frontend estático de cero dependencias de servidor).
  - Identificación clara de límites entre la web actual y el desarrollo futuro del videojuego.

- **Diseño Responsivo y Formato de Impresión:**
  - Totalmente adaptado a dispositivos móviles, tabletas y monitores de escritorio.
  - Estilos optimizados para impresión/exportación a PDF (`@media print`) limpios sin menús ni controles.

---

## 🛠️ Tecnologías utilizadas

- **HTML5 & CSS3:** Variables CSS (Custom Properties), CSS Grid, Flexbox, y diálogos nativos (`<dialog>`).
- **JavaScript (ES6+):** Código nativo ejecutable directamente en navegador.
- **Three.js (r180):** Carga modular para renderizado 3D de la unidad M-4.
- **Google Fonts:** Tipografías *Manrope* (sans-serif) y *DM Mono* (monospace).

---

## 📁 Estructura de archivos esperada

Para que la página funcione correctamente con todas sus características visuales y 3D, asegúrate de mantener la siguiente estructura de carpetas relativas:

```text
.
├── ModeloCanvas.html
├── README.md
├── assets/
│   ├── canvas/
│   │   ├── segmentos.svg
│   │   ├── relaciones.svg
│   │   ├── canales.svg
│   │   ├── propuesta-valor.svg
│   │   ├── socios.svg
│   │   ├── actividades.svg
│   │   ├── recursos.svg
│   │   ├── costos.svg
│   │   └── ingresos.svg
│   ├── documentation/
│   │   └── resources/
│   │       └── M4_turnaround.png
│   └── vendor/
│       └── three.module.js
└── docs/
    └── architecture/
        └── m4toraound-architecture.html
```

---

## ⚡ Cómo ejecutar la página

Dado que la escena 3D utiliza importaciones de módulos ES (`import('../../assets/vendor/three.module.js')`), se recomienda servir la página mediante un servidor HTTP local para evitar bloqueos por políticas CORS del navegador.

### Opción 1: VS Code (Live Server)
1. Abre el repositorio en Visual Studio Code.
2. Haz clic derecho en `ModeloCanvas.html` y selecciona **Open with Live Server**.

### Opción 2: Python (Línea de comandos)
```bash
# Ejecutar desde la raíz del proyecto
python -m http.server 8000
```
Luego abre `http://localhost:8000/ModeloCanvas.html` en tu navegador.

### Opción 3: Node.js / npx
```bash
npx serve .
```

---

## 📊 Resumen del Modelo Canvas

| Bloque | Estado | Enfoque |
| :--- | :--- | :--- |
| **01. Segmentos de clientes** | Hipótesis | Aficionados a aventuras independientes, puzles y narrativa de ciencia ficción. |
| **02. Relación con jugadores** | Propuesta | Transparencia en desarrollo, retroalimentación temprana y encuestas breves. |
| **03. Canales** | Hipótesis | Página web informativa, plataformas digitales de PC (Steam/Itch.io) y demos. |
| **04. Propuesta de valor** | **Premisa confirmada** | Aventura isométrica de exploración y reparación de mecanismos en una ciudad robótica. |
| **05. Socios clave** | Por definir | Distribución, servicios externos de audio/localización y festivales indie. |
| **06. Actividades clave** | Propuesta | Diseño de puzles, narrativa ambiental, arte 3D/2D e implementación técnica. |
| **07. Recursos clave** | Por definir | Documentación de diseño, habilidades multidisciplinarias del equipo y premisa de M-4. |
| **08. Estructura de costos** | Categorías propuestas | Desarrollo, licencias, producción de audio, localización y difusión. |
| **09. Fuentes de ingresos** | Hipótesis | Venta de copia completa a precio fijo (monetización por validar). |

---

## 📄 Licencia y créditos

- **Estudio:** Dimatrek Studio / Proyecto Lumen.
- **Documentación:** Práctica 04 — Mapa de Producto y Arquitectura.