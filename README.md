# Comparador de Facturas y Pedidos

Esta aplicación desarrollada en Streamlit permite comparar productos de una factura con los productos pedidos en un archivo PDF con texto OCR reconocido.

## Requisitos

- El archivo PDF debe tener texto seleccionable.
- No se aceptan PDFs escaneados como imágenes (sin OCR).

## Uso

1. Suba un PDF con líneas de productos de factura y pedido.
2. El sistema extrae las líneas y compara cantidades y precios por dimensiones.
3. Se muestra el resultado y permite descargar un Excel coloreado con diferencias.
