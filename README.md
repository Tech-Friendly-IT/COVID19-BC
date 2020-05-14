# COVID-19 Baja California
Casos de COVID-19 en Baja California #opendata #data

Proyecto para la publicación de datos en formato **.CSV** y **.JSON** de la pandemia COVID-19 (coronavirus)

Los datos son extraídos del gobierno de Baja California diaramente del sitio [Gobierno de Baja California](https://www.facebook.com/BC.Gobierno).

### Municipios censados:
- Mexicali
- Tijuana
- Rosarito
- Ensenada
- Tecate
- San Quintin

Esta información es procesada y puesta en formato .CSV y .JSON para ser utilizada por cualquier persona que quiera analizarla. Podrás buscar información histórica en la carpeta **/datos**. Los datos inician el 1 de abril del 2020 hasta la fecha.

Puedes hacer uso de **covid19-bc-latest.csv** y **covid19-bc-latest.json**, estos contienen la información más reciente.

### Estructura de carpetas
- Carpeta raíz
  - datos (datos CSV y JSON)
  - graficas (gráficas)

### Gráficas
- Activos (casos acumulados meno casos recuperados y defunciones)
- Agregados (casos agregados en 24 hrs por municipio 7 dias)
- Incremental (casos acumulados por municipio 7 dias)
- Municipios (casos acumulados por municipio)
- Sumarizados (casos acumulados por estado)

## Estructura de datos
- id
- estado
- estado-slug
- municipio
- municipio-slug
- poblacion
- latitud
- longitud
- fecha (YYYY-MM-DD)
- c-negativos (casos negativos)
- c-sospechosos (casos sospechosos)
- c-confirmados (casos confirmados)
- c-defunciones (casos defunciones)
- c-recuperados (casos recuperados)
- d-negativos (diferencia 24hrs negativos)
- d-sospechosos (diferencia 24hrs sospechosos)
- d-confirmados (diferencia 24hrs confirmados)
- d-defunciones (diferencia 24hrs defunciones)
- d-recuperados (diferencia 24hrs recuperados)
- sospechosos-tasa-100k (tasa de casos x 100k habitantes)
- confirmados-tasa-100k (tasa de casos x 100k habitantes)
- activos (casos activos menos casos recuperados menos defunciones)
