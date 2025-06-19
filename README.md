# Comparador de Facturas y Pedidos

Aplicación web desarrollada con Streamlit para comparar líneas de productos entre una factura y un pedido, a partir de un archivo PDF que contenga texto (no imagen escaneada).

## Características

- Extrae productos, cantidades, precios unitarios y dimensiones.
- Agrupa por dimensión.
- Compara las líneas entre factura y pedido.
- Genera un archivo Excel resaltando las diferencias.

## Uso

1. Sube el PDF con las líneas de factura y pedido (en texto).
2. La app detecta y compara los datos.
3. Descarga el Excel generado.

## Requisitos

- El PDF debe contener texto seleccionable (no imagen).
- Puedes desplegar esta app en [Streamlit Cloud](https://streamlit.io/cloud).
