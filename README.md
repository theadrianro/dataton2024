# Modelo de Optimización espacial

Integrantes:
* Rojas Rivas, Adrian Andres
* Silva Paucar, Stefany Dennis

## Data 📊
Registro de campañas veterinarias de la Municipalidad Distrital de Chorrillos [Ver fuente](https://www.datosabiertos.gob.pe/dataset/registro-de-campa%C3%B1as-veterinarias-de-la-municipalidad-distrital-del-chorrillos-mdch)

La propuesta incluye la aplicación de web scraping para la búsqueda de datasets que tenga información geoespacial, lenguaje de programación Python para la creación del diagrama de Voronoi, el desarrollo de coberturas con coordenadas exactas y el despliegue sencillo en html que brinda acceso total a cualquier usuario con internet.

## Impacto ✅
Se ha identificado una distribución desigual de los puntos de atención, dejando algunas zonas sin acceso cercano a estos servicios o campañas. Para resolver este problema de cobertura, se utilizaron herramientas tecnológicas como web scraping para la detección de bases de datos con información geoespacial disponible, para luego usar un lenguaje de programación como Python para la creación del diagrama de Voronoi.

❗️ ¿Sabías que la metodología Voronoi ayudó a prevenir la expansión de una plaga de cólera en el siglo XIX?
En 1854, el médico John Snow utilizó un concepto similar al de Voronoi para mapear casos de cólera en Londres, lo que le permitió identificar y aislar una fuente de agua contaminada, deteniendo la propagación de la enfermedad.

## Resultados 🚀
Los marcadores representan las campañas realizadas, organizadas por colores de acuerdo al trimestre y año en que se llevaron a cabo. Las áreas sombreadas en verde indican una estimación de la población beneficiada por cada campaña, considerando que muchas personas suelen caminar con sus mascotas para asistir. El área destacada en gris corresponde al distrito de Chorrillos.

Es evidente que hay zonas del distrito que aún no han sido alcanzadas por las campañas, lo que subraya la importancia estratégica de este proyecto: ampliar la cobertura para beneficiar a la mayor cantidad posible de ciudadanos.
![Mapa 1](https://github.com/user-attachments/assets/8af0c2d8-2b7b-45ee-9817-49e220c97e03)

El uso de diagramas de Voronoi permite identificar las áreas geográficas más cercanas a cada campaña, representando las zonas desde las cuales los ciudadanos pueden acceder fácilmente a la más cercana. Sin embargo, el análisis revela que en algunas zonas, las distancias son considerables, lo que aumenta la probabilidad de que los ciudadanos no asistan a las campañas debido a la lejanía.
![Mapa 2](https://github.com/user-attachments/assets/639b5bb1-59ad-41c3-8417-448f8a8ddb04)

## Despliegue ⚡️
* [Ver PDF](https://theadrianro.github.io/dataton2024/modelo.pdf) Ver documento de trabajo.
* [Ver Mapa 1](https://theadrianro.github.io/dataton2024/map1.html) Identificación de zonas con cobertura insuficiente en campañas debido a la lejanía para algunos ciudadanos.
* [Ver Mapa 2](https://theadrianro.github.io/dataton2024/map2.html) Metodología Voronoi para la determinación estratégica y óptima de ubicaciones para nuevas campañas.

## Próximos pasos 🧠
La metodología basada en diagramas de Voronoi tiene múltiples aplicaciones en la optimización de recursos y servicios. Por ejemplo, puede emplearse para:
* Optimizar la ubicación de campañas de salud, como aquellas destinadas a prevenir plagas o enfermedades, asegurando un mayor alcance y eficiencia.
* Determinar el lugar óptimo para movilizar los llamados TAMBOS a fin de facilitar el acceso a zonas rurales remotas.
* Identificar las mejores ubicaciones para implementar campañas nutricionales en áreas de difícil acceso, mejorando la cobertura en comunidades vulnerables.
* Ubicar estratégicamente centros educativos para reducir los tiempos de viaje de los estudiantes, permitiendo un acceso más equitativo a la educación.
Estas son solo algunas de las infinitas posibilidades que esta metodología ofrece, abriendo oportunidades para mejorar la calidad de vida y el acceso a servicios esenciales en diversas áreas.

