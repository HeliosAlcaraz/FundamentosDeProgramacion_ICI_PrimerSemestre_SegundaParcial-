# Problemas resueltos en clase con Diagramas de Flujo de Datos
## Ejercicio 1.- Contar del 1 hasta el 10 y sumar los valores.
### ANÁLISIS
Datos de entrada: ninguno\
Variables: i, sum
Datos de salida: sum
### DFD
#### _For_
![1_DFD_For](https://user-images.githubusercontent.com/113320901/196837617-f0126e35-87bf-4851-8b36-8f878bbcadce.png)

#### PRUEBA DE ESCRITORIO (For)
|#  | i | i<=10 |sum=sum+i|sum|i+1|
| ----------- |----------- |----------- |----------- |----------- |----------- |
| 1 | 1 | 1<=10 | sum=0+1 | 1 | 2 |
| 2 | 2 | 2<=10 | sum=1+2 | 3 | 3 |
| 3 | 3 | 3<=10 | sum=3+3 | 6 | 4 |
| 4 | 4 | 4<=10 | sum=6+4 | 10| 5 |
| 5 | 5 | 5<=10 | sum=10+5| 15| 6 |
| 6 | 6 | 6<=10 | sum=15+6| 21| 7 |
| 7 | 7 | 7<=10 | sum=21+7| 28| 8 |
| 8 | 8 | 8<=10 | sum=28+8| 36| 9 |
| 9 | 9 | 9<=10 | sum=36+9| 45| 10 |
| 10 | 10 | 10<=10 | sum=45+10| 55| 11 |
#### _While_
![1_DFD_While](https://user-images.githubusercontent.com/113320901/196837834-bc9d2655-ff1f-4f41-bad2-26c8c3579729.png)

#### PRUEBA DE ESCRITORIO (While)
| | | |
| ----------- |----------- |----------- |
|  |  |  |
#### _Do-While_
  ![1_DFD_DoWhile](https://user-images.githubusercontent.com/113320901/196837922-9aa73a7e-0117-4239-9641-8518ec8eb1c4.png)
  
  #### PRUEBA DE ESCRITORIO
| | | |
| ----------- |----------- |----------- |
|  |  |  |
