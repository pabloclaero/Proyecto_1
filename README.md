# Proyecto_1: Prediccion de ventas
A continuacion se encontrara informacion hacerca de la proyeccionde ventas alimenticias realizadas con arboles de regresion y graficos los cuales fueron realizados tras un proceso de limpieza de datos, analisis de datos.

Para la preparacion del aprendizage automatico se hizo una regresion lineal y un arbol de regresion.
A continuacion unos graficos.

![Grafico_De_Calor](https://user-images.githubusercontent.com/124935133/228083155-07ca3d09-a51c-44a2-bc27-74308d639924.png)

Los graficos de calor son bastantes utiles para identificar relaciones o correlaciones entre caracteristicas en un conjunto de datos, por ejemplo en este caso podemos observar que el precio de los items (Item_MRP) va casi de la mano con La venta de los itmes en tiendas (Item_Outlet_Sales), mientras que el resto de caracteristicas no tienen una gran relacion como las caracteristicas mencionadas anteriormente.

Ventas por tipo de items

![Ventas_por_tipo_de_item](https://user-images.githubusercontent.com/124935133/228085510-ff103ca2-bbca-485f-960b-1dfd71273b10.png)
![Ventas_por_tipo_de_item_Grafico_de_barras](https://user-images.githubusercontent.com/124935133/228085519-c99befe5-6780-4702-a161-d2d8dcda6b25.png)
![Ventas_de_item_por_tienda](https://user-images.githubusercontent.com/124935133/228085899-11c11e3d-1198-4802-aed6-6107f0eafc85.png)

Graficos como histogramas, graficos de barras y boxplots nos ayudan bastante para ver una comparativa entre caracteristicas seleccionadas en este caso las ventas de los items siendo que los items mas vendidos son Itmes para el hogar(household), frutas y vegetales, y snacks.

Ventas por tiendas

![Ventas_por_tienda](https://user-images.githubusercontent.com/124935133/228087971-506f8edf-9344-4dd5-a606-ffedf2e748b7.png)

En el siguiente histograma podemos observar que el tipo de supermarket 1 es el que tiene mas ventas

Precio de los items

![precio_de_los_items](https://user-images.githubusercontent.com/124935133/228088063-1a196dd9-0b46-4f33-86f8-f51292eb0ea4.png)


Modelos de aprendizage autonomo
_____________________________________________
REGRESION LINEAL

R^2 en el conjunto de entrenamiento: 0.5020802047831258

R^2 en el conjunto de prueba: 0.507657392123914

RECM en el conjunto de entrenamiento: 2067.50

RECM en el conjunto de prueba: 1165.49


ARBOL DE REGRESION

R^2 en conjunto de entrenamiento:  0.6047593730306096

R^2 en conjunto de prueba:  0.6047593730306096

RECM en conjunto de entrenamiento:  1081.525371013189

RECM en conjunto de prueba:  1133.923186895283


Recomendacion de uso de modelo de aprendizage autonomo
Mi recomendacion es que se debe utilizar el modelo de arboles de regresion debido a que la diferencia de los valores de RECM entre los datos 'train' y 'test' es menor. Y la prediccion es mejor en los datos de prueba.
