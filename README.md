# Predicting-Movie-Rental-Durations
# Predicción de Alquiler de DVD - Proyecto DataCamp

## Visión General
¡Una empresa de alquiler de DVD necesita tu ayuda! Quieren determinar cuántos días un cliente alquilará un DVD basándose en algunas características y te han solicitado ayuda. Quieren que pruebes algunos modelos de regresión que ayuden a predecir la cantidad de días que un cliente alquilará un DVD. La empresa busca un modelo que genere un Error Cuadrático Medio (MSE) de 3 o menos en un conjunto de prueba. El modelo que desarrolles ayudará a la empresa a ser más eficiente en la planificación de inventario.

## Conjunto de Datos
Los datos proporcionados por la empresa se encuentran en el archivo CSV `rental_info.csv`. Contiene las siguientes características:
- `"rental_date"`: La fecha (y hora) en que el cliente alquila el DVD.
- `"return_date"`: La fecha (y hora) en que el cliente devuelve el DVD.
- `"amount"`: La cantidad pagada por el cliente por alquilar el DVD.
- `"amount_2"`: El cuadrado de `"amount"`.
- `"rental_rate"`: La tarifa a la que se alquila el DVD.
- `"rental_rate_2"`: El cuadrado de `"rental_rate"`.
- `"release_year"`: El año en que se lanzó la película que se está alquilando.
- `"length"`: Duración de la película que se está alquilando, en minutos.
- `"length_2"`: El cuadrado de `"length"`.
- `"replacement_cost"`: El costo que tendrá la empresa reemplazar el DVD.
- `"special_features"`: Cualquier característica especial, como tráilers/escenas eliminadas que también tenga el DVD.
- `"NC-17"`, `"PG"`, `"PG-13"`, `"R"`: Estas columnas son variables dummy de la clasificación de la película. Toman el valor 1 si la película está clasificada como el nombre de la columna y 0 de lo contrario. Para tu conveniencia, la variable dummy de referencia ya ha sido eliminada.

