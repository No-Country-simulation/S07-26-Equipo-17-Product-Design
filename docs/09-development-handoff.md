
# 🛠️ Transferencia de Desarrollo

Este documento reúne las especificaciones necesarias para que el equipo de desarrollo pueda implementar la calculadora de PhysaFlow a partir de los diseños y prototipos definidos en Figma.

El objetivo del handoff es reducir ambigüedades y evitar que el equipo de desarrollo tenga que tomar decisiones de diseño no documentadas.

---

## 🎨 Figma

### Archivo de diseño

[INSERTAR ENLACE DE FIGMA]

### Prototipo interactivo

[INSERTAR ENLACE DEL PROTOTIPO]

---

## 🗂️ Páginas del archivo Figma

El archivo de diseño se encuentra organizado en las siguientes secciones:

- **Flujo de usuario**
- **Sistema de diseño**
- **Calculadora**
- **Visualización de tres capas**
- **Escenarios**
- **Compartir**
- **Adaptable / Responsive**
- **Componentes**

Cada sección contiene las decisiones de diseño necesarias para comprender el comportamiento de la experiencia.

---

## 🧱 Componentes

Cada componente reutilizable incluye documentación sobre:

- Variantes.
- Estados.
- Espaciado.
- Tipografía.
- Colores.
- Comportamiento de interacción.
- Uso dentro del flujo.

### Estados principales

Los componentes contemplan, según corresponda:

- Default.
- Hover.
- Focus.
- Active.
- Disabled.
- Error.
- Selected.
- Success.

---

## 🧮 Calculadora

### Entradas requeridas

La calculadora solicita tres datos principales:

1. **Tamaño de la instalación** — MW.
2. **Utilización** — %.
3. **Tipo de refrigeración** — Cooling Type.

Cada entrada cuenta con validación y estados de error documentados en Figma.

---

## 📊 Resultados

### Resultado básico

El resultado inmediato debe mostrar:

- **% de capacidad varada** (*Stranded Capacity*).
- **MW de capacidad varada**.
- **Rango estimado de pérdidas financieras anuales**.

Este resultado debe estar disponible sin solicitar el email del usuario.

### Resultado completo

El análisis ampliado incluye:

- **Capa Facility**.
- **Capa IT**.
- **Capa Workload**.
- Desglose de capacidad y pérdidas entre capas.
- Comparación de escenarios.
- Descarga del reporte en PDF.
- Opciones para compartir el resultado.

---

## 🎯 Visualización de tres capas

La visualización principal representa el flujo de capacidad:

```text
Facility
   ↓
IT
   ↓
Workload
