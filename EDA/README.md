# Exploratory Data Analysis (EDA)

## NBA Roster Optimization

---

## Objetivo

El objetivo del EDA es analizar las variables clave que determinan la rentabilidad de los jugadores seleccionados en el Draft de la NBA.

Este análisis permite identificar patrones que ayuden a construir un modelo predictivo para optimizar el ROI de las franquicias.

---

## Análisis Greatest 75 Players

La columna `greatest_75_flag` identifica si el jugador pertenece al Top 75 histórico de la NBA.

Resultados:

* 20 jugadores identificados
* Representan el 1.13% del total

Transformación:

| Original | Nuevo |
| -------- | ----- |
| Y        | 1     |
| N        | 0     |

Esta variable permite identificar talento élite.

---

## Creación Variable ROI

Se creó una variable de rentabilidad basada en la duración de la carrera.

Definición:

Jugador rentable:

≥ 5 temporadas

Jugador no rentable:

< 5 temporadas

Justificación:

Los contratos rookie duran aproximadamente 4 años.

# Cantidad de jugadores rentables vs no rentables

<p align="center">
  <img src="graficas/cantidad de jugadores rentables.png" width="600">
</p>

*Figura 1. Cantidad de jugadores rentables vs no rentables**

La gráfica muestra la distribución de jugadores clasificados como rentables y no rentables, según el criterio de al menos 5 temporadas jugadas en la NBA.

Se observa que una proporción importante de jugadores no alcanza el umbral de rentabilidad, lo que confirma que el Draft representa una inversión con riesgo.

Esta variable constituye el objetivo principal del modelo predictivo.

## 📉 Distribución Duración Carrera

Hallazgo:

La mayoría de jugadores no supera los 5 años.

Esto confirma que el Draft es una inversión de alto riesgo.

---

## Experiencia vs Rentabilidad

Promedios:

No rentables:

2 años

Rentables:

10 años

Esto valida la variable ROI.

---

## Rentabilidad vs Draft Pick

Conclusión:

Picks altos tienen mayor probabilidad de éxito.

---

## Rentabilidad basada en partidos

Definición:

Rentable:

≥ 200 partidos

No rentable:

< 200 partidos

---

## Métricas de eficiencia utilizadas

Variables:

pts_home
pts_away

fgm
fga

fg3m
fg3a

ftm
fta

---

## Conclusiones

✔ La duración de la carrera predice el ROI

✔ Picks altos tienen mayor probabilidad de éxito

✔ El talento élite es escaso

