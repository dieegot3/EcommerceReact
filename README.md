# Entrega del proyecto final de React en Coderhouse

## Iniciar el proyecto:

_Despues de tener el proyecto descargado de manera local se debe abrir el proyecto con el editor de código, correr la terminal e instalar las dependencias para su correcto funcionamiento con el siguiente comando:_

```
  npm i
```

## Ejecutar la app localmente:

Con el proyecto y sus dependencias ya instaladas, se debe ejecutar el siguiente comando que abrirá el proyecto en el navegador en el puerto localhost:3000

```
  npm start
```

También puede se puede visualizar el repositorio desde Vercel en la siguiente url:

```
https://ecommerce-react-diaz.vercel.app/
```

## Características del proyecto:

Este e-commerce cuenta con: Un navbar con el boton de inicio con el nombre de la web, la navegación entre las distintas categorías de los productos y la visualización del botón de carrito con la cantidad de productos agregados si es que existen.

La lista de todos los items almacenados en firestore que están disponibles en la tienda con sus imágenes almacenadas en la nube y la info correspondiente a cada item. Esta lista se modifica al hacer click en los botones del navbar filtrando los resultados.

Se puede acceder a los detalles de cada item al hacer click en un item de la lista anterior. En los detalles se muestra la info del juego más la posibilidad de seleccionar cuántas cantidades de ese juego se quieren agregar al carrito, dependiendo el stock.

Se puede navegar el carrito en caso de que haya un item o más agregado previamente y completar la compra ingresando los datos del usuario para generar una orden de compra.

## Consultas:

En caso de que la lista de juegos no aparezca se deben seguir los siguientes pasos:

1. Abrir el repositorio en el editor de código
2. Abrir una nueva terminal y ejecutar el comando npm start
3. Ir al archivo App.jsx
4. Descomentar la linea 13 que ejecuta la función createProducts
5. Checkear que le proyecto haya utilizado la función createProducts una vez
6. Volver al editor de código y comentar de nuevo la línea 13

Estos secuencia genera la subida de los juegos al servidor de firebase, el cual es leido por la App para mostrar su contenido.

También cabe mencionar que no todas las imágenes están optimizadas para su correcta visualización cuando se quiere ver el detalle de cada juego, de esta manera se evita subir imagenes que sean más pesadas y aligerar la carga de la App ya que es un proyecto simulado.
