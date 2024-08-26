# Linear-Oaxaca-Blinder-Decomposition-in-Argentina
EN: This is the project I made to get my Economist degree. I wanted to share this simple demostration on how to apply the O-A decomposition plus an EDA in R. 
The main users could be people with academic interests, as this technique is widely known and has many applications, as well as those who need a guide on how to use Argentina's foremost demographic data source, the Permanent Household Survey (EPH, from now on).


ES: Este proyecto fue realizado para mi tesina de Licenciatura en Economía. Consiste en una demostracion de como utilizar la descomposición O-A y al mismo tiempo un análisis exploratorio en R.

Los principales usuarios podrian ser personas con intereses académicos, debido a que esta técnica está ampliamente difundida y tiene muchas aplicaciones, asi como tambien aquellos que requieran una guía de como usar la fuente de datos demográfica por excelencia de Argentina, la Encuesta Permanente de Hogares (EPH, de ahora en adelante). 

To access the full project visit the link // Para acceder al trabajo completo haga click en el siguiente link: 

## Structure - Estructura 
EN:
The following work is composed by:

* An xlsx file with the composition of the EPH and the meaning of each variable.
* The raw data of the four quarters of 2022 used in this study, in txt format.
* An xlsx file with the RIPTE index.

//
ES:
El siguiente trabajo está compuesto por:
* Un xlsx con la composicion de la EPH y el significado de cada variable.
* La raw data de los 4 trimestres del año 2022 empleados en este estudio en formato txt.
* Un xlsx con el RIPTE.

## Study's Delimitation // Alcances y definiciones
En:
In this study, the population was limited to young people between 16 and 30 years old from Gran Resistencia (one of the provinces in Northeast Argentina).
Gender is limited by the EPH, defined by biological sex at birth.

//
ES:
Para el presente estudio la población quedó limitada a los jovenes entre 16 y 30 años del aglomerado Gran Resistencia (una de las provincias del Noreste argentino).
El género queda limitada a la EPH, definido por el sexo biológico al momento del nacimiento.


## Data Source - Fuentes de datos
EN: The data used comes from the Permanent Household Survey (EPH), as mentioned in the previous section. This is a national program for the systematic and ongoing production of social indicators conducted by the National Institute of Statistics and Censuses (INDEC), which provides insights into the sociodemographic and economic characteristics of the population

//

ES: La data utilizada proviene de la EPH, como se mencionó en el apartado anterior. La cual es un programa nacional de producción sistemática y permanente de indicadores sociales que lleva a cabo el Instituto Nacional de Estadística y Censos (INDEC), que permite conocer las características sociodemográficas y económicas de la población.

## Variables 
EN:
The variables are coded, so an xlsx file containing all the explanations is provided. If the user does not understand Spanish, AI can be used to translate.

Given the availability of information, the variables used to explain the wage differences between men and women were:

* Work Experience: Age was used as a proxy for this variable.
* Years of Education Completed
* Weekly Working Hours
* Full-Time: Dummy variable that equals 1 when the individual works 40 or more hours per week.
* Formal Employment: Dummy variable that equals 1 when the individual has salary deductions for retirement contributions.
* Private Employment: Dummy variable that equals 1 when the individual works in the private sector.
* Job Qualification: Ordinal variable ranging from 1 (least qualified) to 4 (most qualified).
* Underemployment: Dummy variable equals 1 when the individual works less than 40 hours per week but wishes to work more.
* Sectoral Variables: Indicate the sector of the economy to which the workers belong.

On the other hand, the dependent variable in question, salary, undergoes two transformations:
* Logarithmic Transformation: Salary is converted to a logarithmic scale because this allows for the observation of percentage differences when studying the wage gap, making the results more intuitive.
* Deflation by RIPTE: Salary is deflated by RIPTE (average taxable income of stable workers) to eliminate the effect of inflation and make periods comparable."

//
ES:
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

Por otro lado, la variable explicada en cuestión, el salario, pasa por dos transformaciones:
* Se lo convierte en log debido a que esto permite ver la diferencia porcentual a la hora de estudiar la brecha, siendo mas intuitivo el resultado.
* Se deflacta por RIPTE (remuneración imponible promedio de los  trabajadores estables), para eliminar el efecto de la inflacion y hacer comparables los periodos.

## Conclusion - Insights
EN:
Using the three-fold decomposition, the one that split de gap among endowments - coefficients - interaction effects we can see that a 4.18% aggregate difference in real hourly wages was found in favor of women. This could be influenced by the fact that hourly wages tend to be higher in part-time jobs, and since a larger percentage of women work under this condition, it may be influencing the wage gap in favor of this group, as shown by the decomposition model. Furthermore, there is a clear difference in job market share, with a 26% of the participation gap in favour of men. Additionally, it is notable that women have an almost negligible presence in the industry and construction sectors

On the other hand, due to the magnitude of the variables' standard errors (SE), it seems that the existing differences are not statistically significant. However, this does not mean that in a different context, these variables couldn't be key to explaining this phenomenon.

//
ES:
Usando la descomposicion en tres partes, vemos que se encontró una diferencia agregada del 4.18% en el salario real por hora a favor de las mujeres. Esto podría estar influenciado por el hecho de que los salarios por hora suelen ser más altos en trabajos a tiempo parcial, y dado que un porcentaje mayor de mujeres trabaja bajo esta condición, podría estar influyendo en la brecha salarial en favor de este grupo, tal como lo muestra el modelo de descomposición. Por otro lado, hay una clara diferencia en la participación en el mercado laboral, con una ventaja del 26% a favor de los hombres. Ademas, es notable la poca presencia de las mujeres en industria y construcción.

Por otro lado, debido a la magnitud de los errores estándar (SE) de las variables, parece que las diferencias existentes no son estadísticamente significativas. Sin embargo, esto no significa que en otro contexto estas variables no puedan ser clave para explicar este fenómeno.

## Contact

Whatever doubt or guidance you need, just reach me out on my personal email: talavera144@gmail.com

Cualquier duda o ayuda que necesites, consultame a mi mail!

