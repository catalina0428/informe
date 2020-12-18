# DOCUMENTACIÓN DEL MODELO 

# OBJETIVO:

Simular un sistema Cross-docking evaluando dos alternativas diferentes, con el fin de identificar cual es la mas conveniente para aplicar en la empresa objeto de estudio. 

# FUNCIONAMIENTO:

# Poceso de descarga: 
Para la descarga de los pallets, se requiere de 8 sources, 1 por cada proveedor, los cuales están programados con la distribución de probabilidad del tiempo de arribo para cada uno. Esta decisión fue tomada por el equipo consultor teniendo en cuenta que cada source está etiquetado con un label del cual depende todo, es decir, la cantidad de pallets y cajas que contiene cada tipo de camión, tiempo de preparación, descarga y el destino del producto.

# Proceso de despaletizado:
En este proceso se tienen dos sources, el primero en donde cada pallet es separado del producto y el segundo separa el producto en el número de cajas que trae cada pallet (con respecto a su distribución), las cuales se clasifican con respecto a la tienda de destino, información que es suministrada desde el source inicial que provee de los camiones con un label por porcentaje.

# Proceso de paletizado: 
Debido a que hay 10 zonas de paletizado, se programa una zona específica para cada tienda de destino, en las cuales mediante un combiner, son paletizadas de a 70 unidades por Pallet los cuales se dirigen a la estación de caga para ser enviados a su destino.

# SUPUESTOS: 

# - Alternativa 1: 
- Se trabaja con 4 operarios para el proceso de descarga, 20 para clasificar el producto de acuerdo a su origen, para un total de 24 operarios en sistema. 
- Se hace uso se 4 transpalet eléctricos, los cuales transportan los pallets de la estación de descarga a la zona P.
- Dependiendo el tipo de camión llega a una fuente distinta.
- Los pallets a utilizar para paletizar el producto, son los mismos que se obtuvieron en el proceso de despaletización.

# - Alternativa 2:
- Dependiendo el tipo de camión llega a una fuente distinta.
- Se trabaja con 4 operarios para el proceso de descarga.
- Los pallets a utilizar para paletizar el producto, son los mismos que se obtuvieron en el proceso de despaletización.

# RESULTADOS:


