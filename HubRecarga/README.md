# El Hub de Recarga Ibérico

Gemelo digital de una electrolinera de autopista: simulo cuántos coches llegan, qué cargan y cuánto ganan, y decido si conviene **instalar una batería o ampliar el transformador**.

Proyecto de *Ciencia de Datos e IA* (UMH) · Python · Simulación Monte Carlo

## Qué hace

| Parte | Pregunta | Método |
|---|---|---|
| 1. Llegadas | ¿Cuántos coches llegan cada hora? | Distribución de Poisson por franja horaria |
| 2. Tipos de coche | ¿Qué coches llegan? | Distribución multinomial |
| 3. Consumo y beneficio | ¿Cuánta energía piden y cuánto se gana? | Ajuste de distribuciones + simulación |
| 4. Riesgo | ¿Batería o transformador más grande? | Percentil 99, Monte Carlo e intervalos de confianza |

## Resultados

- Las llegadas por hora siguen una **Poisson** en las 6 franjas.
- Mezcla de coches: 14.9% AC/PHEV · 35.0% DC Estándar · 40.3% HPC 150 · 9.8% HPC 350.
- Una campaña de marketing con +25% de llegadas llevaría la estación a superar los 50 coches/hora en el 61.1% de las horas (hoy, el 45.8%).

## Tecnologías

Python · pandas · NumPy · SciPy · Matplotlib · seaborn · plotnine

## ▶️ Cómo ejecutarlo

1. Abre el cuaderno en Google Colab.
2. Ejecuta todas las celdas en orden.
