# 📱 Práctica 06: Diagrama de Secuencia de Pantallas YouTube Móvil

Este proyecto es una herramienta web interactiva orientada al modelado UX y análisis de secuencia de interfaces de usuario (*wireframes/sketches*) para la aplicación **YouTube Móvil**. Integra el mapa de flujo navegable de **17 pantallas**, simulador móvil interactivo, matriz de interacciones, modo presentación paso a paso y generador de prompts estructurados para IA (Archify / Mermaid).

---

## 🚀 Enlace Directo a la Aplicación Interactive HTML

Puedes interactuar directamente con el simulador y la documentación visual haciendo clic en el siguiente enlace:

👉 **[ACCEDER A LA APLICACIÓN INTERACTIVA (HTML) AQUÍ](https://ematias230045.github.io/Practicas_INTEGRADORA_230045/Practica06/index.html)**


---

## 📌 Datos de la Práctica Académica

* **Práctica:** Práctica 06 — Diagrama de Secuencia de Pantallas (Sketches)
* **Plataforma Estudiada:** YouTube Móvil
* **Estudiante:** Marco A. Ramírez Hernández
* **Matrícula:** 202600123
* **Valor Académico:** 20 Firmas
* **Fecha de Entrega:** Viernes, 10 de Octubre de 2026

---

## 🛠️ Módulos y Funcionalidades Principales

La aplicación HTML incluye 5 vistas y herramientas interactivas integradas en una sola interfaz responsive construida con **Tailwind CSS** y **JavaScript vanilla**:

### 1. 🗺️ Diagrama de Secuencia (Mapa de Flujo)
* Organiza las 17 pantallas en 4 fases lógicas: *Entrada & Inicio*, *Consumo Espectador*, *Interacción & Menús*, y *Suite de Creador*.
* Permite filtrado dinámico por roles: **Espectador**, **Creador** y **Pantallas Compartidas**.
* Acceso directo con un solo clic a la simulación del sketch de cada pantalla.

### 2. 📱 Simulador Interactivo de Sketches
* Incorpora un *mockup* de teléfono móvil interactivo que renderiza los componentes de la interfaz de YouTube (Header, Bottom Nav, Feed, Shorts, YouTube Studio, etc.).
* Muestra metadatos contextuales de UX: Disparador (*Trigger*), Acción del usuario, Pantallas siguientes y Conexiones directas.

### 3. 📊 Matriz Detallada de Interacción
* Tabla completa con la especificación técnica de las 17 pantallas.
* Filtro de búsqueda en tiempo real por palabra clave, rol o código de pantalla (`SCR-01` a `SCR-17`).

### 4. 🎭 Modo Presentación Guiado
* Permite realizar recorridos interactivos paso a paso para validar la lógica del ecosistema:
  * **Ruta 1:** Experiencia Espectador (*Viewer Journey*)
  * **Ruta 2:** Experiencia Creador (*Creator Studio Journey*)
  * **Ruta 3:** Flujo Completo (17 Pantallas)

### 5. 🤖 Generador de Prompt & Schema JSON para Archify AI
* Genera automáticamente una especificación estructurada en formato **Markdown / JSON Schema**.
* Diseñado para ser copiado directamente a agentes de IA como **Archify**, **Mermaid.js** o **ChatGPT** para autogenerar diagramas UML de secuencia vectoriales.

---

## 📂 Inventario de Pantallas (17 Nodos)

| Código | Nombre de la Pantalla | Rol Principal | Fase |
| :--- | :--- | :---: | :---: |
| **SCR-01** | Login / Selección de Cuenta | Compartida | 1 |
| **SCR-02** | Feed Principal / Home | Compartida | 1 |
| **SCR-03** | Búsqueda y Filtros de Video | Compartida | 1 |
| **SCR-04** | Reproductor de Video Interactivo | Espectador | 2 |
| **SCR-05** | Feed de YouTube Shorts | Espectador | 2 |
| **SCR-06** | Perfil y Menú "Tú" | Compartida | 3 |
| **SCR-07** | Centro de Notificaciones | Compartida | 3 |
| **SCR-08** | Sección / Overlay de Comentarios | Espectador | 2 |
| **SCR-09** | Feed de Suscripciones y Canales | Espectador | 2 |
| **SCR-10** | Biblioteca, Historial y Playlists | Espectador | 2 |
| **SCR-11** | Menú de Ajustes y Calidad | Compartida | 3 |
| **SCR-12** | Dashboard del Creador (YouTube Studio) | Creador | 4 |
| **SCR-13** | Pantalla de Subida / Selector | Creador | 4 |
| **SCR-14** | Editor de Metadatos y Configuración | Creador | 4 |
| **SCR-15** | Analíticas y Métricas | Creador | 4 |
| **SCR-16** | Panel de Moderación de Comentarios | Creador | 4 |
| **SCR-17** | Personalización y Branding del Canal | Creador | 4 |

---

## 💻 Tecnologías Utilizadas

* **HTML5 & CSS3:** Estructura semántica con estilos personalizados para emular la interfaz de teléfono móvil y barras de navegación.
* **Tailwind CSS (CDN):** Framework para el diseño responsive en modo oscuro inspirado en el tema de YouTube.
* **FontAwesome 6:** Librería de iconos para la interfaz gráfica y los componentes móviles.
* **JavaScript (ES6+):** Lógica reactiva para el cambio de pestañas, renderizado dinámico de maquetas SVG/HTML, filtros de búsqueda y simulador de rutas.

---

## ⚙️ Instrucciones de Ejecución Local

1. Descarga el archivo `diagrama_de_secuencia_youtube_m_vil.html`.
2. Haz doble clic sobre el archivo para abrirlo en cualquier navegador web moderno (Google Chrome, Mozilla Firefox, Edge, Safari).
3. No requiere instalación de servidores ni dependencias externas (todo se ejecuta del lado del cliente).