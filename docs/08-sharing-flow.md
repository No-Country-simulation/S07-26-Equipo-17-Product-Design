# 📤 Flujo para Compartir

## Objetivo

Permitir que los operadores compartan fácilmente sus resultados con sus compañeros y generar un loop de crecimiento que incentive a nuevos usuarios a realizar su propio cálculo.

---

## 🔄 Recorrido del Usuario

```text
Calcular
   ↓
Ver resultado
   ↓
Compartir
   ↓
Previsualizar tarjeta para compartir
   ↓
Compartir / Descargar
   ↓
El compañero recibe el resultado
   ↓
El compañero calcula su propio resultado
```
El flujo debe ser rápido y requerir la menor cantidad de pasos posible.

🖼️ Contenido para Compartir
El resultado compartible debe incluir la información esencial para que un usuario pueda comprender el resultado sin necesidad de acceder nuevamente al dashboard.

Debe incluir:

Marca PhysaFlow.
% de capacidad ociosa.
Capacidad ociosa en MW.
Impacto financiero anual estimado.
Visualización de las tres capas:
Facility.
IT.
Workload.

Llamada a la acción (CTA) para calcular su propio resultado.

📊 Ejemplo de Resultado Compartible
Capacidad ociosa
3,2 MW

Impacto anual estimado
$420 000 – $680 000

Desglose
```text
Facility → IT → Workload

CTA
Calcula el tuyo →
```


🎯 Objetivo de Diseño
El resultado compartido debe generar curiosidad y motivar al receptor a conocer su propia situación.

La pieza debe provocar una pregunta como:

"¿Cuánta capacidad estoy desperdiciando?"

El contenido debe ser suficientemente claro para comprender el resultado rápidamente y suficientemente atractivo para incentivar al compañero a realizar su propio cálculo.

🔁 Loop de Crecimiento
El sistema de compartir debe contribuir a generar un ciclo de adquisición orgánica:

```text
Usuario calcula
      ↓
Obtiene resultado
      ↓
Comparte con un compañero
      ↓
El compañero descubre PhysaFlow
      ↓
El compañero realiza su cálculo
      ↓
Obtiene su resultado
      ↓
Comparte nuevamente

```
Este loop convierte el resultado en un mecanismo de crecimiento del producto.

🖼️ Share Card
La tarjeta compartible debe mantener una composición visual consistente con la identidad de PhysaFlow.

Relación de aspecto
1:1

Tamaño recomendado
1080 × 1080 px

Nota: Las dimensiones son una decisión de diseño inicial y pueden modificarse según el canal de distribución o plataforma donde se vaya a compartir.

🎨 Consideraciones Visuales
La tarjeta debe priorizar:

Resultado principal — Capacidad ociosa.
Impacto financiero — Pérdida anual estimada.
Visualización de tres capas — Elemento visual distintivo de PhysaFlow.
Marca — Identificación clara de PhysaFlow.
CTA — Invitación directa a realizar el cálculo.
La información secundaria no debe competir visualmente con el resultado principal.

📱 Canales de Compartir
El diseño debe contemplar la posibilidad de:

Descargar la tarjeta como imagen.
Compartir mediante el mecanismo nativo del dispositivo.
Copiar o compartir un enlace al resultado.
Compartir el resultado directamente con un colega, cuando la plataforma lo permita.
El mecanismo técnico definitivo de compartir debe validarse durante la etapa de desarrollo.

✅ Criterio de Éxito
El flujo de compartir se considera exitoso cuando un usuario puede pasar de su resultado a una pieza compartible de forma rápida y comprender, sin contexto adicional:

Cuánta capacidad está desperdiciando.
Cuál es el impacto financiero estimado.
Dónde ocurre la pérdida.
Cómo puede calcular su propio resultado.
El resultado compartido debe funcionar como una pieza de valor independiente y como una puerta de entrada hacia la calculadora de PhysaFlow.
