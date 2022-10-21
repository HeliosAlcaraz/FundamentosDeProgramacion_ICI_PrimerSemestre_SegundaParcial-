# Problemas resueltos en clase con Diagramas de Flujo de Datos
## Ejercicio 1.- Contar del 1 hasta el 10 y sumar los valores.
### ANÁLISIS
Datos de entrada: ninguno (en todos)\
Variables: i, sum (en dfd de for). cont, sum (en dfd de while). cont, sum (en dfd de do-while)
Datos de salida: sum (en todos)
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
|#  | cont | cont<=10 |sum=sum+cont|sum|cont=cont+1|
| ----------- |----------- |----------- |----------- |----------- |-----------|
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
#### _Do-While_
  ![1_DFD_DoWhile](https://user-images.githubusercontent.com/113320901/196837922-9aa73a7e-0117-4239-9641-8518ec8eb1c4.png)
  
  #### PRUEBA DE ESCRITORIO (Do-While)
|#  | cont | cont<=10 |sum=sum+cont|sum|cont=cont+1|
| ----------- |----------- |----------- |----------- |----------- |-----------|
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


## Ejercicio 2.- Obtenga la suma de los primeros cinco números pares.
### ANÁLISIS
Datos de entrada: ninguno\ (en todos)\
Variables: i, sum (en dfd de for). cont, sum (en dfd de while). cont, sum (en dfd de do-while)\
Datos de salida: sum (en todos)
### DFD
#### _For_
![2_DFD_For](https://user-images.githubusercontent.com/113320901/197063753-14be98bc-8b79-415b-8448-abc830c53110.png)

#### PRUEBA DE ESCRITORIO (For)
|#  | i | i<=10 |sum=sum+i|sum|i+=2|
| ----------- |----------- |----------- |----------- |----------- |----------- |
| 1 | 2 | 2<=10 | sum=0+2 | 2 | 4 |
| 2 | 4 | 4<=10 | sum=2+4 | 6 | 6 |
| 3 | 6 | 6<=10 | sum=6+6 | 12 |8 |
| 4 | 8 | 8<=10 | sum=12+8 |20|10 |
| 5 |10 | 10<=10| sum=20+10|30|12 |
#### _While_
![2_DFD_While](https://user-images.githubusercontent.com/113320901/197066700-6d292d72-fc7f-43fc-b924-60c41d1f89b0.png)

#### PRUEBA DE ESCRITORIO (While)
|#  | cont | cont<=5 |sum=sum+cont*2|sum|cont=cont+1|
| ----------- |----------- |----------- |----------- |----------- |----------- |
| 1 | 1 | 1<=5 | sum=0+1*2 | 2 | 2 |
| 2 | 2 | 2<=5 | sum=2+2*2 | 6 | 3 |
| 3 | 3 | 3<=5 | sum=6+3*2 | 12 |4 |
| 4 | 4 | 4<=5 | sum=12+4*2 |20 |5 |
| 5 |5 | 5<=5| sum=20+5*2|30|6 |
#### _Do-While_
![2_DFD_DoWhile](https://user-images.githubusercontent.com/113320901/197290650-50d2d5f6-6fc1-47f3-8287-716d7182efe1.png)

#### PRUEBA DE ESCRITORIO (Do-While)
|#  | cont | sum=sum+cont*2 | cont<=5|sum|cont=cont+1|
| ----------- |----------- |----------- |----------- |----------- |----------- |
| 1 | 1 | sum=0+1*2 | 1<=5 | 2 | 2 |
| 2 | 2 | sum=2+2*2 | 2<=5 | 6 | 3 |
| 3 | 3 | sum=6+3*2 | 3<=5 | 12 |4 |
| 4 | 4 | sum=12+4*2| 4<=5 |20 |5 |
| 5 |5 | sum=20+5*2| 5<=5|30|6 |
