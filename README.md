# Bitcoin Price Scraper
Extrae el histórico de Precios de Bitcoin (BTC-USD) mediante técnicas de web sracping desde Yahoo Finance. 

* Dataset Resultante: Serie Temporal del Precio Diario de Bitcoin (BTC-USD) 2014-2025

## Descripción del Dataset
Este conjunto de datos es una serie temporal univariante del precio de Bitcoin contra el dólar estadounidense (BTC-USD) desde 2014 hasta la fecha actual. Incluye los precios de apertura, cierre, máximo, mínimo, el volumen de negociación y el precio de cierre ajustado diariamente. Es ideal para la aplicación de modelos econométricos y algorítmicos de trading.

## Contenido del Dataset
| Campo           | Descripción                                         | Tipo de Dato |
| :-------------- | :-------------------------------------------------- | :----------- |
| Fecha           | Día del registro                                    | Fecha        |
| Apertura        | Precio al inicio del día                            | Numérico     |
| Máximo          | Precio más alto del día                             | Numérico     |
| Mínimo          | Precio más bajo del día                             | Numérico     |
| Cierre          | Precio al final del día                             | Numérico     |
| Cierre Ajustado | Precio de cierre ajustado (importante para splits ) | Numérico     |
| Volumen         | Volumen total de trading de BTC-USD en el día       | Numérico     |
