# PRECAMPO TPZ COLOMBIA
# Predio Formal

# Georeferenciación: 

Utilizando las capas de: nombre_geográfico, Cercas, Construcción_R, Drenaje_R, Drenaje_L, Límite_vía y Muro Vía_Ferrea ([INSUMOS](https://drive.google.com/drive/folders/1PZ154pDtyj1r31IeuHY7DkVniptOmTHE))


# LEYENDAS PARA DERIVADOS: 

1.En caso de identificar la misma cantidad de derivados: Se identifican por fotointerpretación una cantidad de derivados coincidente con la
indicada por Jurídico, se realizan predios informales para su verificación e investigación de FMI en campo.

2. En caso de no identificar la misma cantidad de derivados: Se identifican por fotointerpretación una _cantidad de derivados diferente_ con la
indicada por Jurídico, se realizan predios informales para su verificación e investigación de FMI en campo.

3. En caso de no identificar ningún derivado: No se identifican por fotointerpretación derivados indicados por Jurídico, se requiere verificación e investigación en campo.

4. En caso de identificar los derivados en base: Se identifican los derivados por FMI en la base catastral

5. Sí en la pestaña de novedades y observaciones encontramos que tiene FMI DERIVADOS debemos buscarlos en la capa *cca_terrenos* en el espacio
t_matricula inmobiliaria, si no se encuentran y el predio se le identifican divisiones con los insumos e indica área de FMI DERIVADO y se ubica el área. Se creará un nuevo número provisional con una I_ Debe informar de la creación de un nuevo provisional para corroborar que el código
esté correcto y que siga con el consecutivo cuando es rural Colocar el área operativa Condición de predio: Informal Copiar el número provisional en la etiqueta cuando generemos el terreno. Sin derecho interesado fuente.

# MARCAS Y NOVEDADES

Se realiza la revisión de las marcas y novedades Destinación económica sin unidad de construcción (se solventa con las construcciones) 

El predio tiene la marca: Diferencia de área en porcentaje : Posee área registral : Modificado con el fin de llevar el área que posee el terreno en el QGIS lo más próxima al área que tenemos en la información registral. Predios URT no se debe modificar el área.

> Formato ajuste marca componente SIG:

>  1- En caso de modificar y solventar marca: Posterior al análisis de fotointerpretación se modifica el área del terreno ajustando los linderos a la ortofoto, el área modificada es coincidente con el área registral, requiere validación en campo para solventar marca.

> 2- En caso de modificar y no solventar marca: Posterior al análisis de fotointerpretación se modifica el área del terreno ajustando los linderos a la ortofoto e insumos base, el área modificada no es coincidente con el área registral, no se solventa la marca y se requiere verificación en campo.

> 2.1 En caso de modificar y no solventar la marca, por no alterar terrenos contiguos: Posterior al análisis de fotointerpretación, se modifica el área del terreno
ajustando a los linderos a los predios colindantes según la ortofoto, sin embargo, el área modificada no es coincidente por que alteraría la de los terrenos contiguos, se requiere verificación en campo.

> 3- En caso de no modificar: Posterior al análisis de fotointerpretación no es posible identificar linderos consistentes para modificar el área del terreno, se requiere verificación en campo para solventar la marca.

>  4- En caso de no tener área registral, ni en cavida y linderos: No se indica área registral que por lo que no se solventa la marca de área

# TIPO DE CAPTURA DE LA INFORMACIÓN : Siempre directo

# DIRECCIÓN : Generarle la geometría debe generarse donde está el acceso del predio o de las construcciones.


## URBANA 
Con la información existente en el campo complemento debe llenarse los cambios de la dirección estructurada y si la información está incompleta debe terminar de llenarse con el recurso de Open Street Maps o Bing

## RURAL 
Cuando la dirección es rural Tipo de dirección: No estructurada Y se debe cambiar la información que existe en complemento y pegarla en Nombre predio


# CORRECCIONES TOPOLÓGICAS 
## REGLAS: 
cca_terreno, cca_unidad construcción. No debe superponer. No debe tener saltos. No debe tener geometrías multiparte.No debe superponer con cca_unidadconstrucción con cca_terreno.No debe tener geometrías no válidas.

# Herramienta comprobación de topologías
# Códigos de revisión 
> 01 Autointersecciones
> 02 Revisar Construcciones
> 03 Revisar Nodos
> 04.1 CCA_Terreno sin puntos CCA_Direccion_2.0
> 04.2 CCA_Direccion se encuentra fuera de CCA_Terreno (LIN)_2.0
> 04.2 CCA_Direccion se encuentra fuera de CCA_Terreno (PTO)_2.0


# Informal

# Georeferenciación: 

Utilizando las capas de: nombre_geográfico, Cercas, Construcción_R, Drenaje_R, Drenaje_L, Límite_vía y Muro Vía_Ferrea ([INSUMOS](https://drive.google.com/drive/folders/1PZ154pDtyj1r31IeuHY7DkVniptOmTHE))

> Verificación del predio para conocer si debe ser creado otra informalidad utilizando el insumo de cercas, ortoimágen
y en su defecto streetview.
> Sí el predio es rural y en el mismo se identifican multiples construcciones como zonas urbanizas se debe dar aviso al supervisor.




   > "**" (Claerbout, 1992)

([FDA]( https://www.fda.gov/)) 


![](https://github.com/09StevenG/notas-investigacion-reproducible/blob/master/img/ZiemannEtAlFig1.png)

