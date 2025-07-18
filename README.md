# PRECAMPO TPZ COLOMBIA
# Predio Formal

## Georeferenciación: 

Utilizando las capas de: nombre_geográfico, Cercas, Construcción_R, Drenaje_R, Drenaje_L, Límite_vía y Muro Vía_Ferrea ([INSUMOS](https://drive.google.com/drive/folders/1PZ154pDtyj1r31IeuHY7DkVniptOmTHE))


## LEYENDAS PARA DERIVADOS: 

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

>  4- En caso de no tener área registral, ni en cavida y linderos: No se indica área registral por lo que no se solventa la marca de área

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

## Predios URT no se debe modificar el área.

# Informal

# Georeferenciación: 

Utilizando las capas de: nombre_geográfico, Cercas, Construcción_R, Drenaje_R, Drenaje_L, Límite_vía y Muro Vía_Ferrea ([INSUMOS](https://drive.google.com/drive/folders/1PZ154pDtyj1r31IeuHY7DkVniptOmTHE))

> Verificación del predio para conocer si debe ser creado otra informalidad utilizando el insumo de cercas, ortoimágen
y en su defecto streetview.

*Se genera la informalidad del predio Colocar en el Identificador único de operación I_A001, se debe verificar con el supervisor que el provisional a crear esté correcto según
la numeración y el consecutivo. Copiar el número provisional en la etiqueta y colocar el área operativa, la condición de predio sería Informal Al espacio restante del terreno original *NO* se le genera una nueva informalidad*

> Sí el predio es rural y en el mismo se identifican multiples construcciones como zonas urbanizas se debe dar aviso al supervisor.

# CONSTRUCCIONES
Se generan las construcciones a partir de ortofoto apoyado de servicios de mapas base web de cada uno de las informalidades. Tipo de planta: Piso planta de ubicación: 1

Se ajusta la construcción a la ortofoto. *Si hay construcciones en el terreno base se queda en el base y si se generan nuevas construcciones si se
le ingresan a la nueva informalidad*

# TIPO DE CAPTURA DE LA INFORMACIÓN : Siempre directo

# DIRECCIÓN : Generarle la geometría debe generarse donde está el acceso del predio o de las construcciones.

## URBANA 
Con la información existente en el campo complemento debe llenarse los cambios de la dirección estructurada y si la información está incompleta debe terminar de llenarse con el recurso de Open Street Maps o Bing

## RURAL 
Cuando la dirección es rural Tipo de dirección: No estructurada Y se debe cambiar la información que existe en complemento y pegarla en Nombre predio

# AREA CATASTRAL : Se actualiza el dato de área catastral a todos los terrenos creados

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


# Mejora

# Georeferenciación: 

Utilizando las capas de: nombre_geográfico, Cercas, Construcción_R, Drenaje_R, Drenaje_L, Límite_vía y Muro Vía_Ferrea ([INSUMOS](https://drive.google.com/drive/folders/1PZ154pDtyj1r31IeuHY7DkVniptOmTHE))


> La mejora se puede extender en un terreno siempre y cuando se encuentre una división material utilizando los recursos de la ortoimágen, la capa de cercas y cuando se
cuente con la herramienta streetview
>  Cuando es una mejora en un terreno NUNCA se debe extender a la totalidad del terreno
> Cuando no es posible interpretar en la ortoimagen una división material en el terreno se deja la mejora tal cual como se encuentra


# CONSTRUCCIONES
Se generan las construcciones a la mejora si esta se extiendea partir de ortofoto apoyado de servicios de mapas base web. Tipo de planta: Piso
planta de ubicación: 1 Se ajusta la construcción a la ortofoto

# NOVEDADES (IMPORTANTE)

Se le debe generar una novedad en el apartado de novedad número predial: 1. Nueva novedad número predial 2. Copiar el mismo número predial de la marca 3. Tipo novedad: Cambio número predial mejora a informal 4.En la pestaña de Información catastral se cambia el número predial Se genera como número provisional como si fuera un informal

# TIPO DE CAPTURA DE LA INFORMACIÓN: Siempre directo

# DIRECCIÓN : Generarle la geometría debe generarse donde está el acceso del predio o de las construcciones.

## URBANA 
Con la información existente en el campo complemento debe llenarse los cambios de la dirección estructurada y si la información está incompleta debe terminar de llenarse con el recurso de Open Street Maps o Bing

## RURAL 
Cuando la dirección es rural Tipo de dirección: No estructurada Y se debe cambiar la información que existe en complemento y pegarla en Nombre predio

# AREA CATASTRAL : Se actualiza el dato de área catastral a todos los terrenos creados

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


# Grupo de informalidades 

Predio o un grupo de predios informales, que en el apartado de derecho interesado fuente encontramos que es una persona particular *diferente* de La Nación
o el Municipio

GENERACIÓN DE FORMALIDAD
Se creará un nuevo número provisional con una F_A00# Debe informar de la creación de un nuevo provisional para corroborar que el código
esté correcto y que siga con el consecutivo

En área urbana y En área rural (comportamiento urbano) : El consecutivo del terreno es en seguimiento de la última informalidad trabajada y se cambia el 2 (de informalidad) del campo 22 por 0. 

Rural (comportamiento rural) : Se genera una F por terreno. F_npn se cambia el 2 (de informalidad) del campo 22 por 0

Cuando es rural Poner los 30 dígitos del provisional que se encuentran despues de la F_ en el espacio de número predial 
Colocar el área operativa Condición de predio: No propiedad horizontal Tipo: Presunto Baldio
En derecho interesado fuente Tipo de derecho = Dominio Urbano = Municipio Rural = LA NACION

# Fecha de inicio de tenencia: Urbanos 31/12/1959 Rurales: 04/12/1936 

Cuando es la nación el NIT=0

Fuente administrativa=Sin documento Copiar el número provisional en la etiqueta del nuevo terreno creado

# NIT MUNICIPIOS: 

- alcaldía de Zambrano: 890481177-7
-  alcaldía de San Estanislao: 890481310-0 
- alcaldía de Los Palmitos: 892201287-6 
- alcaldía de Morroa: 892201296-2 
- alcaldía de Chalan: 892200740-7

# TIPO DE CAPTURA DE LA INFORMACIÓN Siempre directo

# DIRECCIÓN: Generarle la geometría

# URBANA 
Con la información existente en el campo complemento debe llenarse los cambios de la dirección estructurada y si la información está incompleta debe terminar de llenarse con el recurso de Open Street Maps o Bing

# RURAL
Cuando la dirección es rural en el espacio Nombre de Predio se pone LA NACION

# Y el punto se añade dentro del polígono en los accesos al terreno

# CORRECCIONES TOPOLÓGICAS 
## REGLAS: 
cca_terreno, cca_unidad construcción. No debe superponer. No debe tener saltos. No debe tener geometrías multiparte.No debe superponer con cca_unidadconstrucción con cca_terreno.No debe tener geometrías no válidas.


# Espacios Vacios

## GENERACIÓN DE INFORMALIDAD

Se creará un nuevo número provisional con una I_A00# 
Debe informar de la creación de un nuevo provisional para corroborar que el código
esté correcto y que siga con el consecutivo cuando es rural Poner los 30 dígitos del provisional que se encuentran despues de la I_ en el espacio de número predial Colocar el área operativa Condición de predio: Informal Copiar el número provisional en la etiqueta

En derecho interesado fuente Tipo de derecho = Dominio Urbano = Municipio Rural = LA NACION
Cuando es la nación el NIT=0




