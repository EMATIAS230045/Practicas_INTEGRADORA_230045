# Proyecto Lumen — Diagrama de Roles y Permisos

Este repositorio contiene la herramienta interactiva de visualización de **Roles, Actores y Permisos de Proyecto Lumen** (`AFTERLIGHT · Diagrama de roles y permisos.html`). 

El objetivo de este módulo (correspondiente a la **Práctica 05**) es mapear tanto a las entidades narrativas que habitan la metrópolis de Lumen como a los perfiles técnicos y plataformas propuestas para el ecosistema del juego.

👉 **[ACCEDER A LA APLICACIÓN INTERACTIVA (HTML) AQUÍ](https://ematias230045.github.io/Practicas_INTEGRADORA_230045/Practica05/index.html)**

---

## 🚀 Características principales

* **Mapa de Conexiones Interactivo (SVG + Canvas CSS):**
  * Estructura *Hub & Spoke* centrada en el núcleo del sistema **LUMEN**.
  * Trazado dinámico de líneas SVG con animaciones de flujo de datos (*dash animation* y partículas en movimiento).
  * Resaltado visual de relaciones al seleccionar o pasar el cursor sobre cualquier actor.

* **Panel Lateral de Detalles (Drawer):**
  * Desglose completo de responsabilidades ("Qué puede hacer") y límites ("Qué no puede hacer").
  * Mapeo de relaciones directas entre roles con botones de navegación rápida.
  * Matriz individualizada de permisos CRUD para roles técnicos.

* **Matriz de Permisos por Módulo:**
  * Tabla interactiva de permisos con sistema de filtrado por módulo (*Partida local*, *Progreso propio*, *Logros*, *Configuración*, *Cuentas*, etc.).
  * Nomenclatura estandarizada **LCME** (*Consultar*, *Crear*, *Modificar*, *Eliminar*) con indicadores de estado (*Propuesto*, *Denegado*, *No aplica*).

* **Diferenciación de Certeza Técnica vs. Lore:**
  * **Documentados en las fuentes (d):** Entidades y personajes de la narrativa oficial (M-4, PIP, CORE, etc.).
  * **Propuestas de arquitectura (* / p):** Perfiles y clientes de software conceptuales pendientes de implementación y validación técnica.

* **Accesibilidad y Personalización:**
  * Conmutador de tema **Claro / Oscuro** (`data-theme`).
  * Soporte para navegación completa por teclado (`Tab`, `Enter`, `Space`, `Escape`).
  * Respeto a preferencias de usuario como `prefers-reduced-motion`.

---

## 👥 Clasificación de Actores y Roles

### 1. Actores Narrativos (Documentados)
| Actor | Ícono | Descripción / Función Principal |
| :--- | :---: | :--- |
| **Jugador** | 🎮 | Controla a M-4, descubre registros de memoria y avanza en la historia. |
| **M-4 (Protagonista)** | 🤖 | Unidad de reparación que explora Lumen, resuelve puzles y restaura sistemas. |
| **PIP (Compañero)** | 📨 | Unidad mensajera que guía a M-4, otorga pistas y transmite misiones. |
| **CORE (IA de Lumen)** | 🧠 | Inteligencia Central que administra la ciudad y ejecuta el protocolo RESTORE. |
| **Robots del mundo** | 🦾 | Habitantes autómatas (rutinarios, defectuosos o reiniciados) de la metrópolis. |
| **Jefes** | 👁️ | Enfrontamientos principales (*The Gardener*, *The Conductor*, *The Watcher*). |

### 2. Perfiles Técnicos (Propuestos *)
| Perfil | Ícono | Alcance Propuesto |
| :--- | :---: | :--- |
| **Jugador invitado** | 👤 | Acceso sin registro, almacenamiento de progreso exclusivamente local. |
| **Jugador registrado** | 🔑 | Sincronización de progreso remoto, desbloqueo de logros y acceso al perfil. |
| **Admin técnico** | 🛡️ | Gestión conceptual de cuentas, supervisión de plataforma y registros. |

### 3. Plataformas y Clientes (Propuestos *)
| Cliente | Ícono | Rol en la Red |
| :--- | :---: | :--- |
| **Cliente Unity** | 🕹️ | Motor del juego; ejecuta la partida local y envía estados de progreso/logros. |
| **Terminal PWA** | 🖥️ | Aplicación web para consultar enciclopedia, mapas y progreso. |
| **App móvil** | 📱 | Cliente ligero para consultar el codex y estado del jugador. |

---

## 🛠️ Especificaciones Técnicas

* **Formato:** Archivo único ejecutable HTML5 estático (sin necesidad de servidor backend activo).
* **Estilos:** Custom CSS Variables, Flexbox, CSS Grid, `color-mix()` y animaciones de keyframes nativas.
* **Scripting:** Vanilla JavaScript (ES6+) con manipulación DOM y SVG nativos.
* **Fuentes:** Google Fonts (*Manrope* y *DM Mono*).

---

## ⚡ Cómo Visualizar

1. Descarga o clona el repositorio.
2. Abre el archivo `AFTERLIGHT · Diagrama de roles y permisos.html` directamente en cualquier navegador web moderno (Chrome, Firefox, Edge, Safari).
3. No requiere instalación de dependencias ni servidores `Node.js` / `Python`.

---

## 🔐 Convención de Permisos (Matriz LCME)

En la matriz de permisos por módulo se utilizan las siguientes convenciones:

* **L (Consultar):** Permiso de lectura.
* **C (Crear):** Permiso de escritura o creación.
* **M (Modificar):** Permiso de edición.
* **E (Eliminar):** Permiso de borrado o destrucción.

**Estados:**
* <b style="color:#eccb91">◐ Propuesto:</b> Funcionalidad deseada en la arquitectura futura.
* <b style="color:#ff876d">✖ Denegado:</b> Restricción explícita por seguridad o lógica de negocio.
* **— (Gris / N/D):** Operación no definida o no aplicable al contexto.

---

## 📄 Créditos y Contexto

* **Estudio:** Dimatrek Studio
* **Proyecto:** LUMEN / AFTERLIGHT
* **Documento:** Práctica 05 — Sistema de Roles, Actores y Permisos