# Desaf-o_TelecomX_1
En este repositorio se comparten los archivos utilizados para llevar a cabo el desafío de TelecomX_1

Se tiene una compañia telefonica que quiere analizar el comportameitno de la evasión del pago de os clientes, para ello se proporciona una tabla con formato JSON con datos agrupados en diccionarios internos, 
para poder tabajar con los datos primero se requirió de coloarlos todos sn una tabla, esto se hizo con la lectura, nirmalización y agrupamiento de los datos.

Una vez que se tuvo la tabla "aplanada" con todos los datos proporcionados, se nalizaron los tipos de variable y como los acomodo la biblioteca JSON y pandas, se noto que algunas de las columas se clasificaron
como objeto pero en relaida se podian tratar como núimero, así que se cambio el tipo de dato, se notó que en la columna de totales habian 11 celadas vacias, se visualizaron y se rellenaron con datos de "cero" 
para tratar de afectar lo maneo sposible el analisis de los mismos. Una vez que se tiene la tabla arregada de inconsistencias, se proceió a cmabiar tambein el tipo de varibales booleanas a ceros y unos, 
para así ya poser hacer una visualización de los datos y realizar su analisis corespondinte. PAra visualizar y analizar el comprtamiento de los datos, primero se analizaron las varibales categoricas y se correlacionaron 
con le evasión para ello se utilzairon diferetnes tipos de gráficos, y de igual manera al final se analizó el comportamiento de las variables numericas de gasto y tiempo de contrato haciendo uso de graficos de caja.

Se tiene una mayor evasión en clientes que tienen poco tiempo de contrato comparados con aquellos que ya tienen más periodo con el servicio. También es notorio que los clientes que eligen un plazo de contrato
mas corto son los que evanden más.

En el caso del genero no se presta evidencia que alguno de ellos sea mas evasor que otro, el comportameitno es el mismo.

También es de destacar que los senir aunque son menos clientes respecto a los que no son senior estos presentan una tasa de evasión mas alta.
