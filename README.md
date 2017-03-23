# Ejercicio, análisis de correlación

## Bases de Datos
Para realizar el análisis de correlación vamos a emplear los siguientes ejemplos provenientes de Vincent Arel-Bundock (University of Michigan) e-mail: varel@umich.edu

+ Political Economic Risk Data from 62 Countries in 1987:
	+ https://vincentarelbundock.github.io/Rdatasets/csv/Zelig/PErisk.csv
	+ https://vincentarelbundock.github.io/Rdatasets/doc/Zelig/PErisk.html
  
+ Level of Calculus Attained for Students Taking Advanced Micro–economics:
	+ https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/Mathlevel.csv
	+ https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/Mathlevel.html
	
### Importación de datos
Vamos a importar los datos directamente desde internet. Es, quizás, uno de los casos más sencillos pero debe tenerse en cuenta la extensión que se está empleando. Para el ejemplo es CSV  (del inglés comma-separated values), luego trabajaremos en exploración en bases html y xml.

Llamaremos "datos" a la base con la que trabajaremos, con esto, la sintaxis es:

```{r}
datos<-read.csv("https://vincentarelbundock.github.io/Rdatasets/csv/Zelig/PErisk.csv")
```
