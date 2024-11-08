# Mapa Interactivo de Hoteles a Nivel Mundial 🌍

Este proyecto utiliza `folium` y `pandas` para crear un mapa interactivo de hoteles a nivel mundial, diferenciando los hoteles de 4 y 5 estrellas con distintos colores en los marcadores. El archivo `listadomaestro.xlsx` contiene la información de los hoteles, incluyendo nombre, coordenadas y categoría de estrellas.

## Descripción del Proyecto

El mapa generado muestra la ubicación de los hoteles de 4 y 5 estrellas en diferentes partes del mundo. Los hoteles se diferencian visualmente de la siguiente manera:
- **Hoteles de 4 estrellas**: Marcadores azules
- **Hoteles de 5 estrellas**: Marcadores dorados

Al hacer clic en un marcador, se puede ver el nombre del hotel y la categoría de estrellas.

## Archivos

- `listadomaestro.xlsx`: Archivo Excel con los datos de los hoteles.
  - Columnas esperadas:
    - `Nombre del hotel`: Nombre del hotel
    - `Ubicación (coordenadas)`: Coordenadas en formato `latitud, longitud`
    - `Estrellas`: Número de estrellas (4 o 5)
- `mapa_mundial_hoteles.html`: Archivo HTML generado que contiene el mapa interactivo.

## Uso

Para crear el mapa interactivo:

1. Clona este repositorio y asegúrate de que el archivo `listadomaestro.xlsx` esté en la misma carpeta que el código Python.
2. Instala las dependencias si aún no lo has hecho:
   ```bash
   pip install folium pandas
