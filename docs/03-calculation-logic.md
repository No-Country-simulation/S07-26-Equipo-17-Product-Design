# 🧮 Lógica de cálculo

## Entradas

La calculadora requiere tres entradas principales:

| Entrada | Unidad | Obligatorio |
| :--- | :---: | :---: |
| Tamaño de la instalación | MW | Sí |
| Utilización | % | Sí |
| Tipo de refrigeración | Tipo | Sí |

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



```text

![](https://github.com/No-Country-simulation/S07-26-Equipo-17-Product-Design/blob/main/docs/calculo.png)
