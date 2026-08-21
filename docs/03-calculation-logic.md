# 🧮 Lógica de cálculo

## Entradas

La calculadora requiere tres entradas principales:

| Entrada | Unidad | Obligatorio |
| :--- | :---: | :---: |
| Tamaño de la instalación | MW | Sí |
| Utilización | % | Sí |
| Tipo de refrigeración | Tipo | Sí |

---
## PUE y eficiencia energética del centro de datos

El PUE (Power Usage Effectiveness) mide la eficiencia energética de un centro de datos: cuanto más cercano a 1.0, mejor aprovecha el centro de datos la energía para cómputo real frente a la energía destinada a servicios de soporte, como el enfriamiento.

Definiciones para integrar al motor de la calculadora:

### 1. Aire — PUE ~1.55

Definición:
Enfriamiento mecánico tradicional que utiliza unidades de aire acondicionado (CRAC/CRAH) para mover grandes volúmenes de aire frío a través de pasillos organizados o pisos falsos.

Por qué tiene ese PUE:
Es el sistema menos eficiente porque el aire transporta mal el calor y los compresores, junto con los ventiladores, consumen mucha energía eléctrica de forma continua.

### 2. Free / Evap — PUE ~1.35

Definición:
Sistemas de enfriamiento libre (Free Cooling) o evaporativo/adiabático que aprovechan el aire exterior natural o la evaporación de agua para reducir la temperatura de la sala sin encender compresores mecánicos durante la mayor parte del año.

Por qué tiene ese PUE:
Reduce drásticamente el consumo eléctrico del centro de datos, aunque depende fuertemente de las condiciones climáticas y de la humedad de la zona geográfica.

### 3. Líquido — PUE ~1.25

Definición:
Enfriamiento directo al chip (Direct-to-Chip) donde se bombea un fluido refrigerante o agua helada a través de bloques metálicos montados directamente sobre los procesadores y GPUs.

Por qué tiene ese PUE:
El líquido transporta el calor de forma miles de veces más eficiente que el aire. Reduce casi por completo la necesidad de ventiladores de alta potencia en la sala de servidores.

### 4. Inmersión — PUE ~1.10

Definición:
Los servidores se sumergen por completo en tanques llenos de un líquido dieléctrico (que no conduce electricidad), de forma monofásica o bifásica, para remover el calor directamente de todos los componentes.

Por qué tiene ese PUE:
Es la tecnología más eficiente del mercado. Elimina al 100 % los ventiladores de los servidores y el flujo de aire en el edificio, requiriendo energía casi exclusivamente para pequeñas bombas de circulación y disipación externa.

---

![](https://github.com/No-Country-simulation/S07-26-Equipo-17-Product-Design/blob/main/docs/calculo.png)


## Salidas

### Resultado básico

El usuario recibe inmediatamente:

- Capacidad varada (*Stranded Capacity*) (%).
- Capacidad varada (*Stranded Capacity*) (MW).
- Pérdida financiera anual estimada ($).

### Resultado completo

El análisis ampliado incluye:

- Capacidad total de la instalación (*Facility*).
- Capacidad de IT.
- Capacidad de *Workload*.
- Pérdida de capacidad entre cada capa.
- Comparación de diferentes escenarios.

---

## 📐 Modelo de cálculo

El modelo de cálculo exacto debe ser proporcionado y validado por **PhysaFlow**.

El diseño no debe asumir ni definir coeficientes financieros, energéticos o de capacidad que no hayan sido previamente aprobados.

La fórmula definitiva deberá contemplar, como mínimo:

- Tamaño de la instalación.
- Porcentaje de utilización.
- Tipo de refrigeración.
- Capacidad disponible en cada capa.
- Capacidad varada resultante.
- Impacto financiero anual estimado.

> **Nota:** Los valores y fórmulas utilizados en el prototipo deben considerarse ilustrativos hasta que el modelo matemático oficial sea proporcionado y validado por PhysaFlow.

---

## 🧪 Ejemplo ilustrativo

> Los siguientes valores son únicamente de referencia y no representan resultados reales.

| Parámetro | Valor |
| :--- | :--- |
| Instalación | 10 MW |
| Utilización | 65% |
| Refrigeración | Aire |

### Resultado


Capacidad varada: [valor calculado]
Pérdida anual estimada: [rango calculado]



