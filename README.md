# Project4_DA_Ironhack

![img](https://i.pinimg.com/originals/02/37/32/02373230148ce4fde8b3fac5960745cf.png)

## Introducción y proceso

Este repositorio contiene el trabajo realizado para el cuarto proyecto del Bootcamp de Data Analystics (Julio 2022). Durante esta semana, visualización y explicación de datos ha sido enseñado. Esto significa que el proyecto de la semana contiene: proceso ETL completo, carga en base de datos, y visualicación y explicación de los datos mediante Tableau y PowerBI:

1. **Extracción de los datos mediante Web Scrapping (He usado Beautiful Soup).***  -- El proceso ha consistido en extraer datos de las 9 ediciones de Masterchef España (sexo, procedencia, edad, pruebas en equipo ganadas y perdidas, ranking y posición, etc) de todos los concursantes.

1. **Limpieza y transformación de datos**

1. **Creación base de datos, introducir tablas y relaciones**


## Objetivo del análisis (EDA).
Masterchef España ha llegado a su décima edición en 2022. Esto significa que el talent show de cocina ha sido un éxito de la televisión española. Pero...

        REALMENTE SE TRATA DE UN TALENT SHOW, O MÁS BIEN PODRÍAMOS DECIR QUE ES UN REALITY SHOW?

Mi objetivo en este proyecto es demostrar que con los años el programa de cocina se ha vuelto cada vez más en un programa de entretenimiento tipo reality show. Es por este motivo que el casting desde inicio tiene peculiaridades:
- Representación de toda españa (diferentes ciudades a lo largo de la geografía española)
- Representación de todas las edades.
- Paridad en cuanto a género.


No obstante, conforme va avanzando el programa, se suele ver, como espectador, una tendencia a acabar con 4 finalistas tipo(edad aprox 28 años, oficios variados, procedencias diferentes cada año, genero variado, etc.)



## Visualización.
Para poder comprobar dichas aafirmaciones, he realizado un análisis mediante la herramienta PowerBI. En este análisis he comparado las siguientes variables para todos los concursantes de todas las ediciones, y para los ganadores de todas ellas:
- Edad
- Procedencia
- Género
- Ranking
- Número de veces en equipo ganador durante la prueba por equipos
- Número de veces en equipo perdedor durante la prueba por equipos



## Conclusión.
Una vez analizados los datos de las nueve ediciones, afloran las siguientes conclusiones:
- La edad media de los concursantes se situa entorno a los 30 años, mientras que la media de ganadores se situa en los 28 años. ***INSIGHT Nº1: El concursante ganador de la edición 10 debe tender a edad 28-30 años.***



- Ha habido un 52% de concursantes de género femenino y un 48% de concursantes masculinos. No obstante, ha habido 5 hombres ganadores y 4 mujeres. Además el patrón ha sido el siguiente: ***M-F-M-F-M-F-M-F-M   --> INSIGHT Nº2: El ganador de la edición 10 debe ser género Femenino***



- Existe representación de todas las cidudades españolas a lo largo de la historia, pero solamente hay ganadores de: Barcelona, Madrid, Toledo, Cádiz, Granada, ALmería y Palma de Mallorca. ***INSIGHT Nº3: Si el reality quiere que haya representación de toda España, esta edición debería de ganar alguien procedente de una ciudad sin ganadores en la hsitoria***



- Las ocupaciones previas al concurso han sido muy diversas, así como las ocupaciones de los ganadores. ***INSIGHT Nº4: El ganador de la 10ª edición no debería de coincidir en profesión con otros ganadores anteriores***



- De media, los ganadores han estado 5 veces en Equipos Perdodres durante la prueba de equipos y 4 veces en Equipos Ganadores. ***INSIGHT Nº5: Se espera que la combinación de pruebas ganadas y perdidas en equipo del ganador de la edición 10 sea similar***


--> Con todos estos insights he generado una expectativa numérica con probabilidades en cada aspecto de 0 a 1 para los 6 concursantes finalistas a día 04/07/2022. El objetivo: PREDECIR AL GANADOR DE LA 10º EDICIÓN.

Proyecto 4 finalizado!!
