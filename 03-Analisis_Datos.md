## Analisis de los dotos obtenidos en los archivos csv

#### Archivos analizados:

Se ha guardado 01-Internet_Penetracion.csv
Se ha guardado 02-Internet_Penetracion.csv
Se ha guardado 03-Internet_BAF.csv
Se ha guardado 04-Internet_BAF.csv
Se ha guardado 05-Internet_Accesos-por-tecnologia.csv
Se ha guardado 06-Internet_Accesos-por-tecnologia.csv
Se ha guardado 08-historico_velocidad_internet.csv
Se ha guardado 09-historico_velocidad_internet.csv
Se ha guardado 10-Internet_Accesos-por-velocidad.csv
Se ha guardado 11-Internet_Accesos-por-velocidad.csv
Se ha guardado 12-AccesosaInternetfijoporvelocidadbajadayprovincia
Se ha guardado 13-Internet_Ingresos.csv
Se ha guardado 14-AccesosaInternetfijoporvelocidaddebajadaylocalidad.csv
Se ha guardado 15-AccesosaInternetfijoportecnologiaylocalidad.csv
Se ha guardado 16-Listadodelocalidadesconconectividadainternet.csv
Se ha guardado indicadoresmacro.csv



- Dataframe 1 :01-CrecimientoxProvincia.csv
- Dataframe 2 :01-Internet_PenetracionxProvincia.csv
- Dataframe 3 :02-Internet_Penetracion.csv
- Dataframe 4 :03-Internet_BAF_Nacional.csv
- Dataframe 5 :04-(c)Internet_BAFxProvincia.csv
- Dataframe 6 :05-Internet_Accesos-por-tecnologia.csv
- Dataframe 7 :06-Internet_Accesos-por-tecnologiaxprovincia.csv
- Dataframe 8 :08-historico_velocidad_internet.csv
- Dataframe 9 :09-historico_velocidad_internetxprovincia.csv
- Dataframe 10 :10-Internet_Accesos-por-velocidad.csv
- Dataframe 11 :11-Internet_Accesos-por-velocidadxprovincia.csv
- Dataframe 12 :12-AccesosaInternetfijoporvelocidadbajadayprovincia.csv
- Dataframe 13 :13-Internet_Ingresos.csv
- Dataframe 14 :14-AccesosaInternetfijoporvelocidaddebajadaylocalidad.csv
- Dataframe 15 :15-AccesosaInternetfijoportecnologiaylocalidad.csv
- Dataframe 16 :16-Listadodelocalidadesconconectividadainternet.csv
- Dataframe 17 :17-ConectividadalserviciodeInternet.csv

### Dataframe 1 : 01-CrecimientoxProvincia.csv
|---|---|---|---|
|Provincia|Val_Ini|Val_Fin|	Dif %|

Este Df fue obtenido por la transformacion de 
En términos de KPIs, los valores iniciales y finales, así como la diferencia porcentual, podrían considerarse como indicadores clave de rendimiento para evaluar la calidad y el crecimiento del servicio de Internet en cada provincia

Defini un grafico de barras.

![Grafica01](\Graficas\Grafica01.jpg)




### Dataframe 2 : 01-Internet_PenetracionxProvincia.csv
|---|---|---|---|
|Año|Trimestre|Provincia|Accesos por cada 100 hogares|

Este DataFrame proporciona información sobre el acceso a Internet en diferentes provincias de Argentina, desglosada por trimestres y accesos por cada 100 hogares.

Al combinar este DataFrame con el anterior DataFrame, se pueden obtener conclusiones más completas.

* Comparando la diferencia porcentual en la calidad del servicio de Internet del primer DataFrame con los accesos por cada 100 hogares del segundo DataFrame, es posible identificar correlaciones entre la calidad y la disponibilidad de Internet en cada provincia.

Además, al agregar datos demográficos y socioeconómicos, como la densidad de población, el nivel de ingresos o el nivel de educación, se pueden obtener conclusiones más sólidas sobre las oportunidades de mercado y las fortalezas potenciales para tu cliente en el sector de las telecomunicaciones en Argentina.

### Dataframe 3 : 02-Internet_Penetracion.csv
|---|---|---|---|
Año|Trimestre|	Accesos por cada 100 hogares	Accesos por cada 100 hab|	Periodo|

Utilizando los datos proporcionados de : 01-CrecimientoxProvincia.csv, 01-Internet_PenetracionxProvincia.csv e 01-Internet_PenetracionxProvincia.csv construimos un nuevo DataFrame que contenga las siguientes columnas de información:
|---|---|---|---|---|---|---|---|---|---|---|
|Año|Trimestre|Provincia|Val_Ini|Val_Fin|Dif %|Accesos por cada 100 hogares|Accesos por cada 100 habitantes|

Al comparar los valores iniciales y finales, las diferencias porcentuales y los accesos por hogar y por habitante, podremos evaluar el crecimiento, la calidad y la disponibilidad de Internet en cada provincia a lo largo del tiempo.

### Dataframe 4 : 03-Internet_BAF_Nacional.csv
|---|---|---|---|---|---|
|Año|Trimestre|Banda ancha fija|Dial up|Total|Periodo|

Con estos datos podemos analizar la evolución de las conexiones de banda ancha fija y acceso telefónico a lo largo de los trimestres y años. 
- Observar el aumento o disminución en el número de conexiones de banda ancha fija y acceso telefónico por trimestre.
- Podemos tener un calculo de la proporción de conexiones de banda ancha fija y acceso telefónico en relación con el total de conexiones de Internet y con esto podemos obtener información sobre la preferencia de los usuarios por diferentes tipos de conexión y la adopción de tecnologías más avanzadas.

- Calcular la proporción de conexiones de banda ancha fija y acceso telefónico en relación con el total de conexiones de Internet. Esto puede proporcionar información sobre la preferencia de los usuarios por diferentes tipos de conexión y la adopción de tecnologías más avanzadas.

### Dataframe 5 : 03-Internet_BAF_Nacional.csv
|---|---|---|---|---|
|Año|Provincia|Banda ancha fija|Dial up|Fecha|

Con estos datos podemos analizar la distribución de las conexiones de banda ancha fija y acceso telefónico en cada provincia durante los diferentes años, tambien comparar el número de conexiones entre las provincias y evaluar la adopción de tecnologías de Internet en cada región.


### Dataframe 6 : 04-(c)Internet_BAFxProvincia.csv
|---|---|---|---|---|
|Año|Provincia|Banda ancha fija|Dial up|Fecha|

Este es una modificacion de 04-Internet_BAFxProvincia.csv, solo quitando el total.

Nos permite analizar la distribución de las conexiones de banda ancha fija y acceso telefónico en cada provincia durante los diferentes años, comparando el número de conexiones entre las provincias y evaluar la adopción de tecnologías de Internet en cada región.

### Dataframe 7 : 04-(c)Internet_BAFxProvincia.csv
|---|---|---|---|---|---|---|---|---|
|Año|	Trimestre|	ADSL|	Cablemodem|	Fibra óptica|	Wireless|	Otros|	Total|	Periodo|

Podemos obtener la distribución de los diferentes tipos de conexiones de Internet (ADSL, cablemodem, fibra óptica, inalámbricas, otros) durante cada trimestre. Tambien puedes evaluar la preferencia de los usuarios en cuanto a los tipos de conexión utilizados y ver si hay cambios o tendencias en la adopción de diferentes tecnologías a lo largo del tiempo.

Además, al considerar el total de conexiones de Internet, puedes tener una idea general del crecimiento y la evolución de la penetración de Internet en cada trimestre.

### Dataframe 8 : 05-Internet_Accesos-por-tecnologia.csv
|---|---|---|---|---|---|---|---|---|
|Año|Trimestre|Provincia|ADSL|Cablemodem|Fibra óptica|	Wireless|Otros|Total|

Podemos analizar la distribución de los diferentes tipos de conexiones de Internet (ADSL, cablemodem, fibra óptica, inalámbricas y otros) en cada provincia y trimestralmente. Tambien se puede identificar las provincias con mayor adopción de cada tipo de conexión y evaluar la penetración de tecnologías específicas en diferentes regiones.

Además, al considerar el total de conexiones de Internet en cada provincia y trimestre, puedes comparar el nivel de conectividad en diferentes regiones y evaluar las diferencias en la infraestructura de Internet.

### Dataframe 9 : 06-Internet_Accesos-por-tecnologiaxprovincia.csv
|---|---|---|---|---|
|Año|Trimestre|Mbps (Media de bajada)|Trimestre.1|

Se puede analizar la evolución de la velocidad media de bajada de Internet en trimestres. También se puede evaluar las diferencias en la velocidad promedio de Internet en cada período y considerar cómo esto puede afectar la calidad y la experiencia del usuario.

### Dataframe 10 : 08-historico_velocidad_internet.csv
|---|---|---|---|---|
|Año|Trimestre|Provincia|Mbps (Media de bajada)|

Con este df se puede analizar la velocidad media de bajada de Internet en cada provincia durante cada trimestre. Tambien comparar las velocidades entre las provincias y evaluar si hay diferencias significativas en el rendimiento del Internet.

### Dataframe 11 : 09-historico_velocidad_internetxprovincia.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Año|Trimestre|Hasta 512 kbps|Entre 512 Kbps y 1 Mbps|Entre 1 Mbps y 6 Mbps|Entre 6 Mbps y 10 Mbps|Entre 10 Mbps y 20 Mbps|	Entre 20 Mbps y 30 Mbps|Más de 30 Mbps|OTROS|Total|

Podemos analizar la distribución de las conexiones de Internet en diferentes rangos de velocidad en periodos trimestrales. Tambien se puede evaluar las tendencias y cambios en la adopción de diferentes rangos de velocidad a lo largo del tiempo.

### Dataframe 12 : 10-Internet_Accesos-por-velocidad.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Anio|Trimestre|Provincia|HASTA 512 kbps|V+ 512 Kbps - 1 Mbps|V+ 1 Mbps - 6 Mbps|V+ 6 Mbps - 10 Mbps|V+ 10 Mbps - 20 Mbps|V+ 20 Mbps - 30 Mbps|V+ 30 Mbps|OTROS|Total|

Es el mismo que el anterior pero ahora se puede analizar por provincia

### Dataframe 13 : 1-Internet_Accesos-por-velocidadxprovincia.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Año|Trimestre|Provincia|Otros|0,256 Mbps|0,375 Mbps|0,625 Mbps	|0,5 Mbps|0,512 Mbps|0,75 Mbps|70 Mbps|71 Mbps|75 Mbps|77 Mbps|78 Mbps|80 Mbps|81 Mbps|83 Mbps|82 Mbps|86 Mbps|

Se puedes analizar la distribución de las conexiones de Internet en diferentes velocidades en cada provincia y trimestre. Puedes identificar las velocidades más comunes y evaluar la adopción de velocidades más altas en comparación con velocidades más bajas.

No lo voy a usar creo que las velocidades estan muy segmentadas.

### Dataframe 14 : 12-AccesosaInternetfijoporvelocidadbajadayprovincia.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Anio|Trimestre|Provincia|HASTA 512 kbps|V+ 512 Kbps - 1 Mbps|V+ 1 Mbps - 6 Mbps|V+ 6 Mbps - 10 Mbps|V+ 10 Mbps - 20 Mbps|V+ 20 Mbps - 30 Mbps|V+ 30 Mbps|OTROS|Total|

### Dataframe 15 : 13-Internet_Ingresos.csv
|---|---|---|---|---|
|Año|Trimestre|Ingresos (miles de pesos)|Periodo|

Nos permite analizar los ingresos generados en el sector de las telecomunicaciones trimestralmente. Puedes evaluar las tendencias y cambios en los ingresos a lo largo del tiempo y considerar cómo esto puede reflejar el estado de la industria de las telecomunicaciones en Argentina.


### Dataframe 16 : 14-AccesosaInternetfijoporvelocidaddebajadaylocalidad.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Provincia|	Partido|Localidad|Link Indec|Otros|0,256 mbps|0,375 mbps|0,5 mbps|0,512 mbps|0,625 mbps|...|75 mbps	|78 mbps|80 mbps|82 mbps|83 mbps|85 mbps|90 mbps|92 mbps|95 mbps|100 mbps|

Muy Segmentado y no voy a analizar a nivel localidad

### Dataframe 17 : 15-AccesosaInternetfijoportecnologiaylocalidad.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Provincia|	Partido|Localidad|Link Indec|ADSL|CABLEMODEM|	DIAL UP|FIBRA OPTICA|OTROS|SATELITAL|WIMAX|	WIRELESS|Total general|	

No voy a analizar a nivel localidad


### Dataframe 18 : 16-Listadodelocalidadesconconectividadainternet.csv
|---|---|---|---|---|---|---|---|---|---|
|Partido|Localidad|ADSL|DIALUP|FIBRAOPTICA|4G|TELEFONIAFIJA|SATELITAL|

No voy a analizar a nivel localidad

### Dataframe 19 : 17-ConectividadalserviciodeInternet.csv
|---|---|---|---|---|---|---|---|---|---|
|Partido|Localidad|CABLEMODEM|WIRELESS|TELEFONIAFIJA|link|

No voy a analizar a nivel localidadLatitud	

**************************************
**************************************
*************************************
#### Resumen:

### Dataframe 1 : 01-CrecimientoxProvincia.csv
|---|---|---|---|
|Provincia|Val_Ini|Val_Fin|	Dif %|

Este Df fue obtenido por la transformacion de 
En términos de KPIs, los valores iniciales y finales, así como la diferencia porcentual, podrían considerarse como indicadores clave de rendimiento para evaluar la calidad y el crecimiento del servicio de Internet en cada provincia


### Dataframe 2 : 01-Internet_PenetracionxProvincia.csv
|---|---|---|---|
|Año|Trimestre|Provincia|Accesos por cada 100 hogares|

Este DataFrame proporciona información sobre el acceso a Internet en diferentes provincias de Argentina, desglosada por trimestres y accesos por cada 100 hogares.

Al combinar este DataFrame con el anterior DataFrame, se pueden obtener conclusiones más completas.

* Comparando la diferencia porcentual en la calidad del servicio de Internet del primer DataFrame con los accesos por cada 100 hogares del segundo DataFrame, es posible identificar correlaciones entre la calidad y la disponibilidad de Internet en cada provincia.

Además, al agregar datos demográficos y socioeconómicos, como la densidad de población, el nivel de ingresos o el nivel de educación, se pueden obtener conclusiones más sólidas sobre las oportunidades de mercado y las fortalezas potenciales para tu cliente en el sector de las telecomunicaciones en Argentina.

### Dataframe 3 : 02-Internet_Penetracion.csv
|---|---|---|---|
Año|Trimestre|	Accesos por cada 100 hogares	Accesos por cada 100 hab|	Periodo|

Utilizando los datos proporcionados de : 01-CrecimientoxProvincia.csv, 01-Internet_PenetracionxProvincia.csv e 01-Internet_PenetracionxProvincia.csv construimos un nuevo DataFrame que contenga las siguientes columnas de información:
|---|---|---|---|---|---|---|---|---|---|---|
|Año|Trimestre|Provincia|Val_Ini|Val_Fin|Dif %|Accesos por cada 100 hogares|Accesos por cada 100 habitantes|

Al comparar los valores iniciales y finales, las diferencias porcentuales y los accesos por hogar y por habitante, podremos evaluar el crecimiento, la calidad y la disponibilidad de Internet en cada provincia a lo largo del tiempo.

### Dataframe 4 : 03-Internet_BAF_Nacional.csv
|---|---|---|---|---|---|
|Año|Trimestre|Banda ancha fija|Dial up|Total|Periodo|

Con estos datos podemos analizar la evolución de las conexiones de banda ancha fija y acceso telefónico a lo largo de los trimestres y años. 
- Observar el aumento o disminución en el número de conexiones de banda ancha fija y acceso telefónico por trimestre.
- Podemos tener un calculo de la proporción de conexiones de banda ancha fija y acceso telefónico en relación con el total de conexiones de Internet y con esto podemos obtener información sobre la preferencia de los usuarios por diferentes tipos de conexión y la adopción de tecnologías más avanzadas.

- Calcular la proporción de conexiones de banda ancha fija y acceso telefónico en relación con el total de conexiones de Internet. Esto puede proporcionar información sobre la preferencia de los usuarios por diferentes tipos de conexión y la adopción de tecnologías más avanzadas.

### Dataframe 5 : 03-Internet_BAF_Nacional.csv
|---|---|---|---|---|
|Año|Provincia|Banda ancha fija|Dial up|Fecha|

Con estos datos podemos analizar la distribución de las conexiones de banda ancha fija y acceso telefónico en cada provincia durante los diferentes años, tambien comparar el número de conexiones entre las provincias y evaluar la adopción de tecnologías de Internet en cada región.


### Dataframe 6 : 04-(c)Internet_BAFxProvincia.csv
|---|---|---|---|---|
|Año|Provincia|Banda ancha fija|Dial up|Fecha|

Este es una modificacion de 04-Internet_BAFxProvincia.csv, solo quitando el total.

Nos permite analizar la distribución de las conexiones de banda ancha fija y acceso telefónico en cada provincia durante los diferentes años, comparando el número de conexiones entre las provincias y evaluar la adopción de tecnologías de Internet en cada región.

### Dataframe 7 : 04-(c)Internet_BAFxProvincia.csv
|---|---|---|---|---|---|---|---|---|
|Año|	Trimestre|	ADSL|	Cablemodem|	Fibra óptica|	Wireless|	Otros|	Total|	Periodo|

Podemos obtener la distribución de los diferentes tipos de conexiones de Internet (ADSL, cablemodem, fibra óptica, inalámbricas, otros) durante cada trimestre. Tambien puedes evaluar la preferencia de los usuarios en cuanto a los tipos de conexión utilizados y ver si hay cambios o tendencias en la adopción de diferentes tecnologías a lo largo del tiempo.

Además, al considerar el total de conexiones de Internet, puedes tener una idea general del crecimiento y la evolución de la penetración de Internet en cada trimestre.

### Dataframe 8 : 05-Internet_Accesos-por-tecnologia.csv
|---|---|---|---|---|---|---|---|---|
|Año|Trimestre|Provincia|ADSL|Cablemodem|Fibra óptica|	Wireless|Otros|Total|

Podemos analizar la distribución de los diferentes tipos de conexiones de Internet (ADSL, cablemodem, fibra óptica, inalámbricas y otros) en cada provincia y trimestralmente. Tambien se puede identificar las provincias con mayor adopción de cada tipo de conexión y evaluar la penetración de tecnologías específicas en diferentes regiones.

Además, al considerar el total de conexiones de Internet en cada provincia y trimestre, puedes comparar el nivel de conectividad en diferentes regiones y evaluar las diferencias en la infraestructura de Internet.

### Dataframe 9 : 06-Internet_Accesos-por-tecnologiaxprovincia.csv
|---|---|---|---|---|
|Año|Trimestre|Mbps (Media de bajada)|Trimestre.1|

Se puede analizar la evolución de la velocidad media de bajada de Internet en trimestres. También se puede evaluar las diferencias en la velocidad promedio de Internet en cada período y considerar cómo esto puede afectar la calidad y la experiencia del usuario.

### Dataframe 10 : 08-historico_velocidad_internet.csv
|---|---|---|---|---|
|Año|Trimestre|Provincia|Mbps (Media de bajada)|

Con este df se puede analizar la velocidad media de bajada de Internet en cada provincia durante cada trimestre. Tambien comparar las velocidades entre las provincias y evaluar si hay diferencias significativas en el rendimiento del Internet.

### Dataframe 11 : 09-historico_velocidad_internetxprovincia.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Año|Trimestre|Hasta 512 kbps|Entre 512 Kbps y 1 Mbps|Entre 1 Mbps y 6 Mbps|Entre 6 Mbps y 10 Mbps|Entre 10 Mbps y 20 Mbps|	Entre 20 Mbps y 30 Mbps|Más de 30 Mbps|OTROS|Total|

Podemos analizar la distribución de las conexiones de Internet en diferentes rangos de velocidad en periodos trimestrales. Tambien se puede evaluar las tendencias y cambios en la adopción de diferentes rangos de velocidad a lo largo del tiempo.

### Dataframe 12 : 10-Internet_Accesos-por-velocidad.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Anio|Trimestre|Provincia|HASTA 512 kbps|V+ 512 Kbps - 1 Mbps|V+ 1 Mbps - 6 Mbps|V+ 6 Mbps - 10 Mbps|V+ 10 Mbps - 20 Mbps|V+ 20 Mbps - 30 Mbps|V+ 30 Mbps|OTROS|Total|

Es el mismo que el anterior pero ahora se puede analizar por provincia

### Dataframe 13 : 1-Internet_Accesos-por-velocidadxprovincia.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Año|Trimestre|Provincia|Otros|0,256 Mbps|0,375 Mbps|0,625 Mbps	|0,5 Mbps|0,512 Mbps|0,75 Mbps|70 Mbps|71 Mbps|75 Mbps|77 Mbps|78 Mbps|80 Mbps|81 Mbps|83 Mbps|82 Mbps|86 Mbps|

Se puedes analizar la distribución de las conexiones de Internet en diferentes velocidades en cada provincia y trimestre. Puedes identificar las velocidades más comunes y evaluar la adopción de velocidades más altas en comparación con velocidades más bajas.

No lo voy a usar creo que las velocidades estan muy segmentadas.

### Dataframe 14 : 12-AccesosaInternetfijoporvelocidadbajadayprovincia.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Anio|Trimestre|Provincia|HASTA 512 kbps|V+ 512 Kbps - 1 Mbps|V+ 1 Mbps - 6 Mbps|V+ 6 Mbps - 10 Mbps|V+ 10 Mbps - 20 Mbps|V+ 20 Mbps - 30 Mbps|V+ 30 Mbps|OTROS|Total|

### Dataframe 15 : 13-Internet_Ingresos.csv
|---|---|---|---|---|
|Año|Trimestre|Ingresos (miles de pesos)|Periodo|

Nos permite analizar los ingresos generados en el sector de las telecomunicaciones trimestralmente. Puedes evaluar las tendencias y cambios en los ingresos a lo largo del tiempo y considerar cómo esto puede reflejar el estado de la industria de las telecomunicaciones en Argentina.


### Dataframe 16 : 14-AccesosaInternetfijoporvelocidaddebajadaylocalidad.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Provincia|	Partido|Localidad|Link Indec|Otros|0,256 mbps|0,375 mbps|0,5 mbps|0,512 mbps|0,625 mbps|...|75 mbps	|78 mbps|80 mbps|82 mbps|83 mbps|85 mbps|90 mbps|92 mbps|95 mbps|100 mbps|

Muy Segmentado y no voy a analizar a nivel localidad

### Dataframe 17 : 15-AccesosaInternetfijoportecnologiaylocalidad.csv
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Provincia|	Partido|Localidad|Link Indec|ADSL|CABLEMODEM|	DIAL UP|FIBRA OPTICA|OTROS|SATELITAL|WIMAX|	WIRELESS|Total general|	

No voy a analizar a nivel localidad


### Dataframe 18 : 16-Listadodelocalidadesconconectividadainternet.csv
|---|---|---|---|---|---|---|---|---|---|
|Partido|Localidad|ADSL|DIALUP|FIBRAOPTICA|4G|TELEFONIAFIJA|SATELITAL|

No voy a analizar a nivel localidad

### Dataframe 19 : 17-ConectividadalserviciodeInternet.csv
|---|---|---|---|---|---|---|---|---|---|
|Partido|Localidad|CABLEMODEM|WIRELESS|TELEFONIAFIJA|link|

No voy a analizar a nivel localidadLatitud



