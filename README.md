# Análisis de rendimiento en campañas de marketing digital (Meta, TikTok y Google Ads)

## Objetivo
Este proyecto busca responder a las siguientes preguntas clave del negocio:
* ¿Qué plataforma tuvo más éxito?
* ¿Qué tipo de campaña obtiene mejor resultado?
* ¿Que país genera más conversiones?
* ¿Cómo evolucionó el ROAS mes a mes?
* ¿Qué industria tiene mayores y menores ingresos?
* ¿En cuál plataforma hubo mayor inversión?
* ¿Qué plataforma tiene mayores y menores impresiones?
* ¿Cómo cae el volumen de impresiones a clicks y conversiones?

## Proceso
1. Carga y traducción de columnas.
2. Problema detectado: el ROAS, el CTR y CT venían mal calculados.
3. Solución: medidas con DIVIDE sobre sumas, no columnas por fila.
   (Utilización de la función DIVIDE para recalcular el ROAS (Ingresos / Coste), la corrección del CTR (Clics / Impresiones) y la creación de la métrica de Tasa de Conversión (CT))
4. Construcción del dashboard.

## Visualización e Insights Clave

*(<img width="1302" height="754" alt="dashboard1" src="https://github.com/user-attachments/assets/ae114853-779c-4434-9beb-e0abec5a7248" />
<img width="1297" height="750" alt="dashboard2" src="https://github.com/user-attachments/assets/591fe52f-2141-4b14-8f77-683a112f96b6" />
)*

## Hallazgos
**TikTok Ads lidera el retorno:** A pesar de tener el menor volumen de impresiones (47 millones), generó el mejor ROAS de la campaña (9,3).
**Google Ads concentra el gasto:** Fue la plataforma con mayor inversión ($0,49 mil M) y mayor alcance (74 millones de impresiones), pero presentó el ROAS más bajo (4,2).
**Dominio de SaaS:** La industria de *Software as a Service* fue la más rentable, generando los mayores ingresos globales ($1,09 mil M).
**Embudo de conversión:** Solo el 0,2% del total de las impresiones logra convertirse en una compra final, ocurriendo la mayor pérdida en el paso previo al clic.

## Herramientas
- **Excel / CSV:** formato del dataset original.
- **Power BI Desktop:**
  - Power Query: carga de datos y traducción de nombres de columnas.
  - DAX (nivel básico): medidas con DIVIDE para ROAS, CPC medio, CTR y tasa de conversión.
  - Visualización: diseño del dashboard de dos páginas, con versión para móvil.

---
**Autor:** Matías Silva Bustos
