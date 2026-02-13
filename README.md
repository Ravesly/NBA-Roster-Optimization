# NBA Roster Optimization  


<p align="center">
  <img src="https://images.unsplash.com/photo-1519861531473-9200262188bf" width="800"/>
</p>

---

## Objetivo

Desarrollar un modelo predictivo orientado a optimizar la rentabilidad de las franquicias de la NBA mediante:

- Evaluación del potencial físico
- Optimización del Retorno de Inversión (ROI) en contratos.
- Optimizar decisiones estratégicas en el Draft
---
## Diagrama de Entidad Relación
https://github.com/Ravesly/NBA-Roster-Optimization/blob/main/DER%20DRAFT%20NBA.png

## Contexto

La NBA moderna opera bajo un entorno altamente competitivo y financieramente exigente.  
Cada selección del Draft y cada contrato representan una inversión estratégica.

Para garantizar un modelo con alta capacidad de generalización y relevancia económica, el análisis se segmentó entre los años **2004 y 2023**, debido a:

- Estandarización del mercado.
- Consolidación del formato moderno de 2 rondas del Draft.
- Mayor precisión en la variable de inactividad.
- Profesionalización en la captura de métricas físicas y estadísticas avanzadas.

---

## Desarrollo del Proyecto

El proyecto se organiza bajo metodología de sprints y control de versiones mediante ramas:

- `main` → Versión estable del proyecto.
- `sprint_1` → Limpieza y estructuración inicial de datasets.

> Las ramas podrán actualizarse conforme avance el desarrollo del proyecto.

---

## Datasets Utilizados

Los datasets limpios utilizados en este proyecto pueden consultarse en la siguiente rama:

**[Acceder a la rama CSV](https://github.com/Ravesly/NBA-Roster-Optimization/tree/main/csv)**

## Tecnologías Empleadas

- Python  
- Pandas  
- NumPy  
- Machine Learning  
- Git & GitHub  

---
## Flujo de Datos

<p align="center">
  <img src="assets/arquitectura_datos.png" width="100%"/>
</p>

### Descripción

La arquitectura implementada permite un flujo de datos seguro, automatizado y escalable desde la ingesta hasta la visualización analítica.

- **Seguridad:** IAM, KMS, VPC y Security Groups garantizan control de accesos y cifrado.
- **Ingesta:** Los datos crudos se almacenan en AWS S3 (Bucket RAW).
- **Procesamiento:** AWS Lambda y Python ejecutan procesos ETL y limpieza.
- **Almacenamiento:** AWS RDS (SQL Server) consolida datos estructurados.
- **Visualización:** Power BI permite análisis e insights estratégicos.
- **Escalabilidad:** Athena y Redshift soportan consultas y almacenamiento a gran escala.
- 
## Presentación
**Link de presentación:**  
**[Haz click para ir a la presentación](https://www.canva.com/design/DAHBGv9sZuc/FmPbbLb9jVUZOnrIoFRxKg/edit?utm_content=DAHBGv9sZuc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)**


---

## Proyecto Integrador 

**[Ve a este link para ver el proyecto](https://docs.google.com/document/d/1FU2Nm4tVonkBbrriwm5wt-3XUIiFiJobLnINLZZMhEc/edit?usp=sharing)**


## Impacto Esperado

- Reducción de costos asociados a contratos de bajo rendimiento.
- Optimización estratégica del talento en rosters.
- Mejora en la toma de decisiones financieras.
- Incremento del ROI en procesos de Draft y contratación.
