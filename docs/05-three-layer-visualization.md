# 🧱 Visualización de las Tres Capas

## Objetivo

La visualización representa cómo se distribuye y se pierde la capacidad disponible a lo largo de las diferentes capas de un Data Center.

El flujo permite identificar de forma visual dónde se produce la pérdida de capacidad desde la instalación física hasta la capacidad efectiva disponible para el workload.

---

## 🔄 Flujo General


FACILITY
   ↓
IT CAPACITY
   ↓
AVAILABLE IT
   ↓
EFFECTIVE WORKLOAD


![](https://github.com/No-Country-simulation/S07-26-Equipo-17-Product-Design/blob/main/docs/3%20layers.png)

🎨 Representación Visual
Cada barra representa una capacidad diferente dentro del flujo.

Capacidad disponible
Se representa mediante el color principal de la visualización.

Pérdida / capacidad no aprovechada
Se representa mediante un segmento diferenciado para facilitar la identificación de la capacidad perdida.

Operational Reserve
Cuando corresponda, la reserva operacional se muestra como una categoría diferenciada para indicar capacidad disponible pero no utilizada por el workload.


