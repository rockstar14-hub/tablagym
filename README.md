# tablagym
primer ejercicio de html
1. Descripción General

Este código HTML crea una tabla que muestra información sobre un grupo de personas. La tabla incluye detalles como el nombre de cada persona, su horario, estatura y peso, y la mensualidad que pagan. El código también incluye estilos CSS para mejorar la apariencia de la tabla, como colores de fondo para las columnas y bordes definidos.

2. Estructura del Documento

<!DOCTYPE html>: Declaración que define el tipo de documento como HTML5.
<html>: Etiqueta raíz del documento HTML.
<head>: Contiene metadatos e información de configuración.
<title>: Define el título de la página ("Tabla de Personas").
<style>: Contiene el código CSS para dar estilo a la tabla.
<body>: Contiene el contenido visible de la página.
<table>: Define la tabla.
<thead>: Define la sección del encabezado de la tabla.
<tr>: Define una fila en el encabezado.
<th>: Define las celdas de encabezado (títulos de las columnas).
<tbody>: Define el cuerpo principal de la tabla.
<tr>: Define las filas de datos.
<td>: Define las celdas de datos.
3. Detalles del CSS

Estilos Básicos de la Tabla:
table { border-collapse: collapse; width: 100%; }: Configura el comportamiento de los bordes y el ancho de la tabla.
th, td { border: 2px solid black; padding: 8px; text-align: left; }: Define los bordes, el relleno y la alineación del texto en las celdas.
th { background-color: #f2f2f2; }: Establece el color de fondo para las celdas de encabezado.
Colores de las Columnas:
td:nth-child(1), th:nth-child(1) { background-color: lightgreen; }: Columna "NOMBRE" en verde claro.
td:nth-child(2), th:nth-child(2) { background-color: lightblue; }: Columna "HORARIO" en azul claro.
td:nth-child(3), th:nth-child(3) { background-color: yellow; }: Columna "ESTATURA-PESO" en amarillo.
td:nth-child(4), th:nth-child(4) { background-color: lightcoral; }: Columna "MENSUALIDAD" en rojo claro.
4. Uso y Modificaciones

Personalización de Colores: Puedes cambiar los colores de fondo modificando los valores de background-color en el CSS.
Ajuste de Bordes: Modifica los valores de border en el CSS para cambiar el grosor y el color de los bordes.
Adición de Filas/Columnas: Agrega más filas (<tr>) y celdas (<td> o <th>) para incluir más datos.
CSS Externo: Para una mejor organización, puedes mover el CSS a un archivo externo y vincularlo al HTML usando la etiqueta <link>.
