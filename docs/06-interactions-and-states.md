# 🖱️ Interacciones y Estados

Este documento define los diferentes estados e interacciones de los componentes principales de la calculadora PhysaFlow.

---

## 📝 Input

### Default

Campo vacío que muestra un placeholder indicando el dato que debe ingresar el usuario.

### Focus

El campo muestra un indicador visual de foco para señalar que está activo y listo para recibir información.

### Filled

El valor ingresado por el usuario se muestra dentro del campo.

### Error

Cuando el valor ingresado no es válido, se muestra un estado de error acompañado de un mensaje que explica cómo corregirlo.

### Disabled

El campo no puede ser editado por el usuario y presenta un estado visual diferenciado.

---

## 🔘 Button

### Default

El botón utiliza el estilo visual principal definido en el Design System.

### Hover

El botón presenta un cambio visual para indicar que el usuario está interactuando con él.

### Active

El botón muestra un estado de interacción mientras el usuario lo presiona.

### Disabled

El botón no permite interacción y presenta una apariencia visual reducida.

---

## 🧮 Calculator

### Ready

Todos los campos obligatorios contienen valores válidos y la calculadora está lista para ejecutar el cálculo.

### Calculate Estimate

Se muestra una transición breve mientras el sistema procesa los datos ingresados.

### Estimated Annual Loss

El resultado se muestra inmediatamente después de completar el cálculo.

El resultado básico incluye:

- Capacidad varada (%).
- Capacidad varada (MW).
- Pérdida financiera anual estimada.

---

## 🧱 Visualización de Tres Capas

La visualización representa el flujo de capacidad:

```text
Facility
   ↓
IT
   ↓
Available IT
   ↓
Effective Workload

