# DOCUMENTACIÓN DEL MODELO 

# PROCESO DE DESCARGA: 
Para la descarga de los pallets, se requiere de 8 sources, 1 por cada proveedor, los cuales están programados con la distribución de probabilidad del tiempo de arribo para cada uno. Esta decisión fue tomada por el equipo consultor teniendo en cuenta que cada source está etiquetado con un label del cual depende todo, es decir, la cantidad de pallets y cajas que contiene cada tipo de camión, tiempo de preparación, descarga y el destino del producto.
# PROCESO DE DESPALETIZADO:
En este proceso se tienen dos sources, el primero en donde cada pallet es separado del producto y el segundo separa el producto en el número de cajas que trae cada pallet (con respecto a su distribución), las cuales se clasifican con respecto a la tienda de destino, información que es suministrada desde el source inicial que provee de los camiones con un label por porcentaje.
# PROCESO DE PALETIZADO: 
Debido a que hay 10 zonas de paletizado, se programa una zona específica para cada tienda de destino, en las cuales mediante un combiner, son paletizadas de a 70 unidades por Pallet los cuales se dirigen a la estación de caga para ser enviados a su destino.
