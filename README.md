# novaretail_analisis
Un análisis realizado a partir de una base de datos ficticia de una empresa de ventas en línea realizado en el sprint 7 del curso de análisis de datos de la academia TripleTen

# ¡Bienvenid@!
## Aquí te dejo el trabajo realizado. No dudes en contactarme si tienes alguna duda :) ¡Espero que te sirva este proyecto!

# Acerca del dataframe

## El presente análisis fue realizado a partir de un dataframe con los siguientes campos: 

1. id_cliente: La identificación de cada cliente
2. edad: La edad correspondente a cada cliente
3. nivel_ingreso: El nivel de ingreso de cada cliente
4. visitas_mes: Las visitas al mes realizadas por el cliente
5. compras_mes: La cantidad de compras realizadas por el cliente
6. gasto_publicidad_dirigida: El gasto que se realizó en la publicidad dirigida al cliente
7. satisfaccion: El grado de satisfaccíón del cliente en una escala del 0 al 5
8. miembro_premium: Variable binaria que identifica a los miembros con suscripción premium
9. abandono: Variable binaria que identifica a los miembros que han abandonado el sistema
10. tipo_dispositivo: Tipo de dispositivo desde el que se realiza la compra ('movil', 'escritorio' o 'tablet')
11. region: Región del usuario ('norte', 'sur', 'este' u 'oeste')
12. ingreso_anual: Ingreso anual del usuario

El dataset cuenta con 15,000 registros sin valores nulos. Es decir, este análisis se realiza con una base de datos de 15,000 usuarios. 
Es importante especificar que se trata de un dataframe de una empresa ficticia llamada 'Novaretail', que fue proporcionado en la séptima etapa del curso de análisis de datos de la academia TripleTen. 

# Objetivos

El objetivo de este análisis es generar hipótesis a partir de este set de datos que tras un mayor análisis permitan tomar decisiones informadas para el crecimiento de la empresa y el aprovechamiento de los recursos como la inversión en publicidad, aumentando las compras y la satisfacción de los clientes. 

# Metodología

## Primera revisión y limpieza de datos: 
Para cumplir este objetivo, se inició realizando una revisión del dataframe para verificar que no existieran valores nulos y que los datos correspondieran a los formatos esperados. 

## Visualización de correlaciones
Para visualizar la correlación entre los campos y generar hipótesis que guíen el análisis, se hicieron heatmaps y scatterplots.

## Coeficientes de correlación y evidencia numérica
Para confirmar las hipótesis generadas a partir de la visualización de estas correlaciones, se calcularon coeficientes con el método Spearman y Pearson. Así mismo, se calcularon correlaciones con el método de la V de Cramér y el método de punto-biserial. 

## Interpretación de resultados
A partir de estos análisis se interpretaron los resultados para informar al negocio acerca de los descubrimientos y las hipótesis generadas. 

## Próximos pasos
Es importante recalcar que este análisis no es definitivo ni demuestra causalidad, sino únicamente correlación entre variables que puede servir para guiar un análisis de mayor profundidad, por lo que se proponen una serie de pasos para continuar. 

# Resumen
En resumen, este análisis cumple la función de generar hipótesis de negocio a partir del estudio de correlaciones de un dataset de la empresa ficticia Novaretail con el objetivo de incrementar las ganancias y la efectividad de los recursos. 

# ¡Gracias por leer!
