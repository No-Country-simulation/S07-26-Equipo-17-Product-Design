# 📊 PhysaFlow — Calculadora de Stranded Capacity
> **S07-26-Equipo-17-Product-Design**

Proyecto colaborativo para el diseño de una calculadora interactiva que permite estimar la capacidad desperdiciada y su impacto económico en centros de datos.

---

## 💡 Objetivo

Facilitar a operadores de Data Centers una estimación precisa del desperdicio de capacidad (*Stranded Capacity*) y su impacto financiero anual en menos de 3 minutos, mediante una experiencia fluida, sin fricción y orientada a la generación de valor inmediato y la viralidad.

## 👤 Equipo

| Nombre | Rol | Perfil de GitHub |
| :--- | :--- | :--- |
| **Ismael Miranda** | Product Designer | [@Ismael-ArMiranda](https://github.com/Ismael-ArMiranda) |
| **Romina Rao** | UX/UI Designer | [@RomiRao](https://github.com/RomiRao) |
| **Javiana Altuve** | UX/UI Designer | [@javialtuve](https://github.com/javialtuve) |
| **Estefania Parra** | UX/UI Designer | [@estefaniaparzon](https://github.com/estefaniaparzon) |
| **Vanesa Roshanaj Gamarra** | UX Researcher | [@VanesaRGamarra](https://github.com/VanesaRGamarra) |

## 🔎 Enlaces del Proyecto

| Recurso | Enlace |
| :--- | :--- |
| 🎨 **Figma** — Flujo completo y UI Kit | [Ver archivo en Figma](https://www.figma.com/design/1XEQQgMIuC2ICZ8xW9tEbn/PhysaFlow-Calculator?node-id=12234-1143&t=810HaKFtPOgtSn68-1) |
| 📊 **FigJam** — User Journey & User Flow | [Ver pizarra de investigación](https://www.figma.com/board/3D9qyDhZ1Yr7ZFOs1oK7yo/SO7-26-TEAM-17?node-id=0-1&t=t1OHxQQ9Yt7iAZDP-1) |
| 📁 **Prototipo Interactivo** — Momentos 1, 2 y 3 | [Ver prototipo navegable](https://www.figma.com/proto/1XEQQgMIuC2ICZ8xW9tEbn/PhysaFlow-Calculator?node-id=12234-1424&p=f&t=P2pYA1iHtPX7uG13-1&scaling=min-zoom&content-scaling=fixed&page-id=12234%3A1143&starting-point-node-id=12234%3A1424) |

## 🗂️ Estructura del archivo Figma

| Página | Contenido | Estado |
| :--- | :--- | :---: |
| **Cover** | Portada del proyecto y presentación principal | ✅ |
| **Style Guide (UI)** | Tokens de diseño, paleta de colores, tipografía y reglas UI | ✅ |
| **Icons** | Set de íconos vectoriales del sistema | ✅ |
| **Research** | User Journey, Persona (Mario Gómez) e investigación de mercado | ✅ |
| **Componentes** | UI Kit con botones, inputs, cards y elementos interactivos | ✅ |
| **Low-Fidelity** | Wireframes de baja fidelidad y validación de flujos | ✅ |
| **High-Fidelity** | Diseños finales de UI correspondientes a los Momentos 1, 2 y 3 | ✅ |
| **Prototyping** | Prototipo interactivo navegable y especificación de flujos | ✅ |

## ⚙️ Arquitectura de la Experiencia — 3 Momentos

### Momento 1 — Input
Formulario rápido con los datos necesarios para realizar la estimación:
* **Facility Size** en MW
* **Utilización actual** (%)
* **Tipo de Cooling** con PUE sugerido
* **Costo de energía** (opcional)

### Momento 2 — Resultado Básico
Visualización pública e inmediata, sin bloqueo por email. Presenta:
* Capacidad desperdiciada estimada en MW.
* Impacto financiero estimado en $/año.
* Resultados presentados de forma clara y fácil de interpretar.

### Momento 3 — Profundidad & Loop Viral
Intercambio de valor mediante email para desbloquear información avanzada:
* Desglose en 3 capas: *Facility, IT y Workload*.
* Tabla comparativa de escenarios (*Scenario Comparison*).
* Reinicio del cálculo.
* Compartir resultados (*Share Results*).

## 🧱 Componentes Construidos

| Componente | Variantes / Descripción | Estado |
| :--- | :--- | :---: |
| **Selector de Cooling** | 4 tipos: Air PUE 1.55, Free/Evap PUE 1.35, Liquid PUE 1.25, Immersion PUE 1.10 | ✅ |
| **Campos de Entrada** | Inputs numéricos con unidades fijas (MW, %, USD/kW) | ✅ |
| **Gráfico de Dona** | Visualización interactiva de uso vs. pérdida (*Lost %*) | ✅ |
| **Capacity Breakdown Flow** | Visualizador de barras de 3 capas: Facility, IT y Workload | ✅ |
| **Scenario Comparison** | Tabla de auditoría capa por capa (MW, Loss, Optimized) | ✅ |
| **Botones / CTAs** | Estados de hover, activo y deshabilitado en tono Gold (`#C49A45`) | ✅ |

## ✦ Principios de Diseño

* **Velocidad sin Fricción:** Cálculo rápido en menos de 3 minutos, sin formularios extensos ni bloqueos innecesarios.
* **Progresión de Valor:** Entrega de información general en el primer impacto y acceso a información avanzada mediante un intercambio consciente de valor.
* **Credibilidad Técnica:** Uso de estándares de la industria, como PUE, presentados de forma clara tanto para perfiles técnicos como ejecutivos.
* **Diseño para la Viralidad:** Resultados visualmente impactantes y fáciles de compartir con superiores o colegas.

## 🔄 Metodología de Trabajo

El proyecto se desarrolló utilizando metodologías ágiles centradas en el usuario:
* **Lean UX:** Para validar rápidamente hipótesis, necesidades y soluciones mediante ciclos de diseño, feedback e iteración.
* **Scrum:** Para organizar el trabajo colaborativo del equipo mediante sprints, distribución de tareas y seguimiento continuo del progreso.

## 📍 Estado del Proyecto

**Fase Actual:** Finalización de Handoff & Documentación UI

* ✅ **Fase 1 — Investigación & Empatía:** Research, User Persona (Mario Gómez) y definición del problema técnico-financiero.
* ✅ **Fase 2 — Arquitectura de Experiencia:** Definición del User Flow en 3 momentos y User Journey Map.
* ✅ **Fase 3 — Wireframing Lo-Fi:** Estructuración de baja fidelidad y validación de la lógica matemática.
* ✅ **Fase 4 — Design System Hi-Fi:** Creación de UI Kit, tokens (`#16422F`, `#C49A45`, `#9DB5A9`) y tipografía *Inter*.
* ✅ **Fase 5 — Handoff:** Documentación de estados, componentes e interacciones de la visualización de 3 capas.

---

## ✨ Resultado

PhysaFlow transforma un problema técnico complejo —la capacidad desperdiciada en un Data Center— en una experiencia de cálculo rápida, visual y comprensible.

El objetivo es que un operador pueda obtener un resultado inicial en menos de 3 minutos, comprender su impacto económico y compartirlo fácilmente para impulsar nuevas oportunidades de análisis.
