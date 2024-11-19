# UNI_Ingresantes
En el presente análisis, exploramos dos bases de datos: La primera "df_admision" es un listado de postulantes al Concurso de Admisión de la Universidad Nacional de Ingeniería desde 2021-1 al 2024-1 y la segunda "df_cepre" es un listado de alumnos del Centro Pre Universitario de la Universidad Nacional de Ingeniería desde 2016 al 2023. 

Ambos data sets se encuentran en la plataforma de datos abiertos del Gobierno Peruano: https://www.datosabiertos.gob.pe/

df_admision: https://www.datosabiertos.gob.pe/dataset/postulantes-al-concurso-de-admisi%C3%B3n-de-la-universidad-nacional-de-ingenier%C3%ADa-uni

df_cepre: https://www.datosabiertos.gob.pe/dataset/alumnos-del-centro-pre-universitario-de-la-universidad-nacional-de-ingenier%C3%ADa-uni

En el cuaderno 1: Se aplico fuzzywuzzy con la finalidad de corregir errores de texto, por ejemplo: 0025 San Martin de Porres y 0025 San Martín de Porras son considerados dos colegios distintos, a pesar de que se debió a un error humano, a fin de no corregir los miles de valores manualmente, se aplico fuzzywuzzy para que agrupe las palabras con cierta familiaridad y las agrupe. 

En el cuaderno 2: Se realizo el merge y se analizó las bases de datos conjuntas. 
