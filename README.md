# Herramientasbasicas-dupre-guadalupe
Herramientas básicas para el Análisis de Datos
# Análisis de Ocupación, Tarifas y Cancelaciones en la Industria Hotelera

**Autor:** [Guadalupe Dupre]  
**Curso:** Herramientas Básicas para el Análisis de Datos  
**Institución:** Centro de e-Learning UTN.BA  
**Cohorte:** 2026  

---

## 1. Descripción del Proyecto y Objetivo
El presente proyecto end-to-end tiene como objetivo principal analizar los factores determinantes en la demanda, las tarifas diarias promedio (ADR) y la tasa de cancelación en reservas hoteleras (City Hotel vs. Resort Hotel). A través de este análisis se busca proveer insights accionables para optimizar las políticas de reserva y la estrategia de revenue management.

---

## 2. Dataset Utilizado
* **Fuente:** [Hotel Booking Demand Dataset en Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) (Jesse Mostipak).
* **Dimensiones procesadas:** 87,396 registros únicos y 32 columnas tras la depuración de duplicados exactos y tratamiento de nulos.

---

## 3. Metodología y Herramientas
1. **Python (pandas, matplotlib, seaborn):** Ingesta, auditoría estructural, imputación de nulos (`agent`, `company`, `country`), estandarización de tipos y análisis exploratorio (EDA).
2. **Power BI:** Modelado de datos, creación de medidas en DAX (`Reservas Concretadas`, `Tasa Cancelacion`, `ADR Promedio`) y diseño de un dashboard interactivo con segmentadores temporales y por tipo de hotel.
3. **GitHub:** Control de versiones y documentación formal del proyecto.

---

## 4. Hallazgos Principales (Insights)
* **Anticipación y Cancelación:** Las reservas canceladas registran una mediana de anticipación (*lead time*) significativamente superior (~80 días) frente a las concretadas (~40 días), evidenciando que el riesgo de cancelación se incrementa con el tiempo de reserva previa.
* **Rendimiento por Canal:** El segmento de venta **Direct** genera la tarifa diaria promedio más alta ($115.3 USD), seguido muy de cerca por **Online TA** ($114.7 USD).
* **Estacionalidad:** Ambos establecimientos alcanzan su pico máximo de ocupación en la temporada estival europea (julio y agosto), con una demanda más estable y sostenida a lo largo del año en el **City Hotel**.

---

## 5. Estructura del Repositorio y Enlaces
* `/notebooks/`: Cuaderno Jupyter/Colab con el EDA completo.
* `/dashboard/`: Archivo interactivo `.pbix` y capturas visuales.
* `/data/`: Enlace a la fuente original de datos.
