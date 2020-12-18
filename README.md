# DOCUMENTACIÓN DEL MODELO CASO EMPRESA OLIMPOS

# OBJETIVO:

Simular un sistema Cross-docking evaluando dos alternativas diferentes, con el fin de identificar cuál es la más conveniente para aplicar en la empresa objeto de estudio "Olimpos". 

# FUNCIONAMIENTO:

# Poceso de descarga: 
Para la descarga de los pallets, se requiere de 8 sources, 1 por cada proveedor, los cuales están programados con la distribución de probabilidad del tiempo de arribo para cada uno. Esta decisión fue tomada por el equipo consultor teniendo en cuenta que cada source está etiquetado con un label del cual depende todo, es decir, la cantidad de pallets y cajas que contiene cada tipo de camión, tiempo de preparación, descarga y el destino del producto.

# Proceso de despaletizado:
En este proceso se tienen dos separator, el primero en donde cada pallet es separado del producto y el segundo separa el producto en el número de cajas que trae cada pallet (con respecto a su distribución), las cuales se clasifican con respecto a la tienda de destino, información que es suministrada desde el source inicial que provee de los camiones con un label por porcentaje.

# Proceso de paletizado: 
Debido a que hay 10 zonas de paletizado, se programa una zona específica para cada tienda de destino, en las cuales mediante un combiner, son paletizadas de a 70 unidades por Pallet los cuales se dirigen a la estación de caga para ser enviados a su destino.

"Ver anexo 2 y 3 archivo Informe"

# SUPUESTOS: 

# - Alternativa 1: 
- Se trabaja con 4 operarios para el proceso de descarga, 20 para clasificar el producto de acuerdo a su origen, para un total de 24 operarios en sistema. 
- Se hace uso se 4 transpalet eléctricos, los cuales transportan los pallets de la estación de descarga a la zona P.
- Dependiendo el tipo de camión llega a una fuente distinta.
- Los pallets a utilizar para paletizar el producto, son los mismos que se obtuvieron en el proceso de despaletización.
- Se estima que en promedio llegan 31 estibas y 70 cajas por cada una de ellas, para un total de 2.201 en cada camión, las cuales son utilizadas para el calculo de la proporción de las salidas y llegadas al sistema. 
# - Alternativa 2:
- Dependiendo el tipo de camión llega a una fuente distinta.
- Se trabaja con 4 operarios para el proceso de descarga.
- Los pallets a utilizar para paletizar el producto, son los mismos que se obtuvieron en el proceso de despaletización.
- Se estima que en promedio llegan 31 estibas y 70 cajas por cada una de ellas, para un total de 2.201 en cada camión, las cuales son utilizadas para el calculo de la proporción de las salidas y llegadas al sistema. 

# RESULTADOS:

# - Alternativa 1: 
- Llegan 36 camiones lo que equivale aproximadamente a 79.236 cajas, a su vez salen 205 pallets que equivalen a 14.350 cajas; para un porcentaje de salida respecto a las llegadas de 18.11%.
# - Alternativa 2:
- Llegan 33 camiones lo que equivale aproximadamente a 72.633 cajas, a su vez salen 204 pallets que equivalen a 14.280 cajas; para un porcentaje de salida respecto a las llegadas de 19.66%.



