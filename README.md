# PROYECTOCD_M8_R2
Repositorio para el reto 2 del módulo 8 del Máster en Behavioral Data Science.

## Objetivos del proyecto

El objetivo general del presente proyecto de ciencia de datos comportamentales es examinar **las relaciones entre variables demográficas (edad, género, años de educación formal y país) y el comportamiento relacionado con el uso de medios (tiempo dedicado a las noticias y política, frecuencia de uso de Internet y tiempo de uso de Internet)**, para comprender mejor el comportamiento de los usuarios de medios digitales y de comunicación en función de sus características demográficas.

De forma más específica, los objetivos concretos del poryecto son los siguientes:

* Estudiar las posibles diferencias en el uso de medios en función del género.
* Comprobar si existe una relación entre la edad y el tiempo y frecuencia de uso de medios.
* Estudiar la posible relación entre los años de educación formal completados y el uso de medios.
* Examinar si hay diferencias en el tiempo y frecuencia de uso de medios en distintos países europeos.

## Datos del proyecto
El presente proyecto trabajará con la base de datos de la **11.ª oleada de la Encuesta Social Europea** (ESS round 11 - 2023. Social inequalities in health, Gender in contemporary Europe). La Encuesta Social Europea es un proyecto de investigación paneuropeo cuyo objetivo es recopilar datos sobre las actitudes, creencias y comportamientos de la población en Europa. Se distingue por su rigor metodológico y la calidad de sus datos, que se obtienen mediante encuestas bien diseñadas y representativas de la población adulta de cada país participante (en esta oleada, hay recogidos datos de 13 países). La documentación sobre el conjunto de datos (alcance, fecha, licencia, etc.) se puede consultar [aquí](https://ess.sikt.no/en/study/412db4fe-c77a-4e98-8ea4-6c19007f551b/83).

Este conjunto de datos incluye un total de 558 variables que abarcan diferentes aspectos sociales, que se agrupan en los diferentes bloques de contenido (demografía, bienestar, política, religión, sociedad, medios de comunicación, etc.). La relación completa de variables incluidas en el conjunto, junto con su descripción y valores, se puede consultar [aquí](https://ess.sikt.no/en/datafile/242aaa39-3bbb-40f5-98bf-bfb1ce53d8ef/93?tab=0).

Para este proyecto, se trabajará con siete variables incluidas en la base de datos: la edad (*agea*), el género (*gndr*), los años de educación formal completados (*eduyrs*), el país (*cntry*), el tiempo dedicado a las noticias y la política (*nwspol*), la frecuencia de uso de Internet (*netusoft*) y el tiempo de uso de Internet (*netustm*).

## Descripción de las variables del proyecto

* **Edad (*agea*):** esta variable numérica se refiere a la edad de la persona encuestada, expresada en años, con un rango de valores desde 15 hasta 90 años.

* **Género (*gndr*):** esta variable se refiere al género de la persona encuestada. Es un dato de tipo categórico nominal y su codificación numérica abarca dos valores: 1 (Varón) y 2 (Mujer).

* **Años de educación completados (*eduyrs*):** esta variable numérica se refiere al número de años de educación formal que ha completado la persona encuestada, con un rango de valores desde 0 hasta 47.

* **País (*cntry*):** esta variable se refiere al país de origen de la persona encuestada. Es un dato de tipo categórico nominal y abarca 13 valores de tipo carácter: AT (Austria), CH (Suiza), DE (Alemania), FI (Finlandia), GB (Reino Unido), HR (Croacia), HU (Hungría), IE (Irlanda), LT (Lituania), NL (Países Bajos), NO (Noruega), SI (Eslovenia) y SK (Eslovaquia).

* **Tiempo dedicado a las noticias y la política (*nwspol*):** esta variable numérica se refiere al tiempo que dedica la persona encuestada a ver, leer o escuchar noticias sobre la actualidad o la política en un día, expresado en minutos, con un rango de valores desde 0 hasta 1439 minutos.

* **Frecuencia de uso de internet (*netusoft*):** esta variable se refiere a la frecuencia habitual con que la persona encuestada utiliza Internet. Es un dato de tipo categórico ordinal y abarca 5 valores, en una escala ordinal de frecuencia, que va desde 1 (Nunca) hasta 5 (Todos los días).

* **Tiempo de uso de Internet (*netustm*):** esta variable numérica se refiere al tiempo que dedica la persona encuestada al uso de Internet en un día, expresado en minutos, con un rango de valores desde 0 hasta 1440.

## Información sobre el repositorio

Este repositoriose organiza del siguiente modo:

* **Datos:** contiene la base de datos original (ESS11.csv), así como la base de datos depurada (ESS11 depurada.csv) y el código para llevar a cabo la depuración de la base original.

* **Dashboard:** contiene el código necesario para realizar un *dashboard* con la visualización de los gráficos y datos para estudiar las relaciones entre las variables, así como el HTML con el *dashboard* generado con dicho código.

* **Informe:** contiene el código necesario para realizar un informe con los resultados de las relaciones entre las variables estudiadas en el proyecto, así como el PDF del informe generado con dicho código.

* **Presentación:** contiene el código necesario para realizar una presentación con los resultados de las relaciones entre las variables estudiadas en el proyecto, así como el PDF de la presentación generada con dicho código.

## Información adicional

Todos los análisis, informes y visualizaciones han sido realizados utilizando el *software* estadístico R. Los detalles del programa son los siguientes:

```R
platform       x86_64-w64-mingw32               
arch           x86_64                           
os             mingw32                          
crt            ucrt                             
system         x86_64, mingw32                  
status                                          
major          4                                
minor          2.1                              
year           2022                             
month          06                               
day            23                               
svn rev        82513                            
language       R                                
version.string R version 4.2.1 (2022-06-23 ucrt)
nickname       Funny-Looking Kid 
```
