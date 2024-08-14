# Linear-Oaxaca-Blinder-Decomposition-in-Argentina
This is the project I made to get my Economist degree. I wanted to share this simple demostration on how to apply the O-A decomposition plus an EDA in R. 

Este proyecto fue realizado para mi tesina de Licenciatura en Economía. Consiste en una demostracion de como utilizar la descomposición O-A y al mismo tiempo un análisis exploratorio en R.

Los principales usuarios podrian ser personas con intereses académicos, debido a que esta técnica está ampliamente difundida y tiene muchas aplicaciones, asi como tambien aquellos que requieran una guía de como usar la fuente de datos demográfica por excelencia de Argentina, la Encuesta Permanente de Hogares (EPH, de ahora en adelante). 

## Data Source - Fuentes de datos
La data utilizada proviene de la EPH, como se mencionó en el apartado anterior. La cual es un programa nacional de producción sistemática y permanente de indicadores sociales que lleva a cabo el Instituto Nacional de Estadística y Censos (INDEC), que permite conocer las características sociodemográficas y económicas de la población.

## Descripción del modelo


## Variables 
Las variables están codificadas, por lo que se deja un archivo xlsx que contiene todas las explicaciones. En caso de que el usuario no entienda español, puede usar AI para traducir.

Dada la disponibilidad de informacion, las variables utilizadas para explicar las diferencias salariales entre hombres y mujeres fueron: 
* Experiencia laboral: para esta variable se tomó la edad como proxy.
* Años de educación completamos
* Horas trabajadas a la semana
* Full time: variable dummy que es =1 cuando el individuo trabaja =>40hs semanales
* Empleo formal: variable dummy que es =1 cuando el individuo sufre descuentos en su salario en concepto de jubilacion.
* Empleo privado: variable dummy que es =1 cuando el individuo trabaja para el sector privado.
* Calif empleo: variable ordinal que va del 1 (menos calificado) al 4 (mas calificado).
* Subocupacion: variable dummy=1 cuando el individuo trabaja menos de 40hs semanales pero desearía trabajar mas.
* Variables sectoriales: indican a que sector de la economia pertenecen los trabajadores. 

### Warning: cualitative variables // variables cualitivativas
Dada la limitacion de este modelo para trabajar con variables cualitativas, simplemente se emplearon dummys.

## Variable transformations // Transformaciones realizadas

## Disclaimer about Insights - Conclusiones


## Contact

Whatever doubt or guidance you need, just reach me out on my personal email: talavera144@gmail.com
Cualquier duda o ayuda que necesites, consultame a mi mail.

