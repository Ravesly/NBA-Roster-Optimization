## Índice

1. [Estructura General del Dataset](#estructura-general-del-dataset)  
2. [Información de Jugadores](#información-de-jugadores)  
3. [Información de Partidos](#información-de-partidos)  
4. [Información de Equipos](#información-de-equipos)  
5. [Dataset Más Importante](#dataset-más-importante)  
6. [Decisiones Clave de Limpieza](#decisiones-clave-de-limpieza)  
7. [Conclusión](#conclusión)

---

# Estructura General del Dataset

El ecosistema de datos se divide en tres bloques principales:

- Información de jugadores  
- Información de partidos  
- Información de equipos  

Cada bloque cumple una función específica dentro del análisis.

---

# Información de Jugadores

## common_player_info

### Propósito

Tabla base estructural del proyecto. Permite identificar y caracterizar a cada jugador.

### Información incluida

- Identificación: `person_id`, nombres  
- Datos físicos: `height`, `weight`  
- Estado profesional: `rosterstatus`  
- Trayectoria: `from_year`, `to_year`, `season_exp`  
- Equipo actual: `team_id`, `team_name`  
- Información de draft  

---

## draft_combine_stats

### Propósito

Contiene métricas físicas y técnicas obtenidas en el NBA Draft Combine.

### Información incluida

- Medidas físicas (altura, peso, envergadura)  
- Pruebas atléticas (vertical, sprint, agilidad)  
- Pruebas técnicas de tiro (`spot_*`, `off_drib_*`, `on_move_*`)  

---

# Información de Partidos

## game

Tabla principal de rendimiento en competencia.

Incluye:

- Puntos  
- Rebotes  
- Asistencias  
- Porcentajes de tiro  
- Resultado del partido  

---

# Información de Equipos

## team

Información básica del equipo:

- Nombre  
- Ciudad  
- Año de fundación  

---
