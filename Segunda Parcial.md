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
Datos de salida: sum (en for y while)
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
|#  | cont | sum=sum+cont*2 | sum|cont=cont+1|cont<=5|
| ----------- |----------- |----------- |----------- |----------- |----------- |
| 1 | 1 | sum=0+1*2 |2 | 2 |2<=5|
| 2 | 2 | sum=2+2*2 |6 | 3 |3<=5|
| 3 | 3 | sum=6+3*2 |12| 4 |4<=5|
| 4 | 4 | sum=12+4*2|20| 5 |5<=5|
| 5 |5 | sum=20+5*2|30| 6 |5<=5|


## Ejercicio 3.- Almacene en un array el número n leído del teclado. El tamaño del array es 10. 
### ANÁLISIS
Datos de entrada: num\ (en todos)\
Variables: i, num, A (en el dfd de for). cont, A, num (en el dfd de while). cont, A, num (en el dfd de do-while)\
Datos de salida: A (en todos)
### DFD
#### _For_
![3_DFD_For](https://user-images.githubusercontent.com/113320901/197297174-5f94695c-7abc-497a-80cc-384cc37c89f6.png)

#### PRUEBA DE ESCRITORIO (For)
|#  | num | i | i<=9 |A[i]=num|i++| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 | 3 | 0 | 0<=9 | A[0]=3 | 1 | 3 |
| 2 | 5 | 1 | 1<=9 | A[1]=5 | 2 | 3,5 |
| 3 | 7 | 2 | 2<=9 | A[2]=7 | 3 | 3,5,7 |
| 4 | 9 | 3 | 3<=9 | A[3]=9 | 4 | 3,5,7,9 |
| 5 | 11 | 4 | 4<=9 | A[4]=11 | 5 | 3,5,7,9,11 |
| 6 | 13 | 5 | 5<=9 | A[5]=13 | 6 | 3,5,7,9,11,13 |
| 7 | 15 | 6 | 6<=9 | A[6]=15 | 7 | 3,5,7,9,11,13,15 |
| 8 | 17 | 7 | 7<=9 | A[7]=17 | 8 | 3,5,7,9,11,13,15,17 |
| 9 | 19 | 8 | 8<=9 | A[8]=19 | 9 | 3,5,7,9,11,13,15,17,19 |
| 10 | 21 | 9 | 9<=9 | A[9]=21 | 10 | 3,5,7,9,11,13,15,17,19,21 |
#### _While_
![3_DFD_While](https://user-images.githubusercontent.com/113320901/197299189-d8e1af84-b47a-4bd1-852d-8f42cc0732cc.png)

#### PRUEBA DE ESCRITORIO (While)
|#  | num | cont | cont<10 |A[cont]=num|cont++| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 | 3 | 0 | 0<10 | A[0]=3 | 1 | 3 |
| 2 | 5 | 1 | 1<10 | A[1]=5 | 2 | 3,5 |
| 3 | 7 | 2 | 2<10 | A[2]=7 | 3 | 3,5,7 |
| 4 | 9 | 3 | 3<10 | A[3]=9 | 4 | 3,5,7,9 |
| 5 | 11 | 4 | 4<10 | A[4]=11 | 5 | 3,5,7,9,11 |
| 6 | 13 | 5 | 5<10 | A[5]=13 | 6 | 3,5,7,9,11,13 |
| 7 | 15 | 6 | 6<10 | A[6]=15 | 7 | 3,5,7,9,11,13,15 |
| 8 | 17 | 7 | 7<10 | A[7]=17 | 8 | 3,5,7,9,11,13,15,17 |
| 9 | 19 | 8 | 8<10 | A[8]=19 | 9 | 3,5,7,9,11,13,15,17,19 |
| 10 | 21 | 9 | 9<10 | A[9]=21 | 10 | 3,5,7,9,11,13,15,17,19,21 |
| 11 | 23 | 10 | 10<10 | - | - | 3,5,7,9,11,13,15,17,19,21 |
#### _Do-While_
![3_DFD_DoWhile](https://user-images.githubusercontent.com/113320901/197308348-a8f3c0ee-0692-4c27-9f61-7076e746f279.png)

#### PRUEBA DE ESCRITORIO (Do-While)
|#  | cont | num | A[cont]=num |cont++|cont<10| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 | 0 | 3 | A[0]=3 | 1 | 1<10 | 3 |
| 2 | 1 | 5 | A[1]=5 | 2 | 2<10 | 3,5 |
| 3 | 2 | 7 | A[2]=7 | 3 | 3<10 | 3,5,7 |
| 4 | 3 | 9 | A[3]=9 | 4 | 4<10 | 3,5,7,9 |
| 5 | 4 | 11 | A[4]=11 | 5 | 5<10 | 3,5,7,9,11 |
| 6 | 5 | 13 | A[5]=13 | 6 | 6<10 | 3,5,7,9,11,13 |
| 7 | 6 | 15 | A[6]=15 | 7 | 7<10 | 3,5,7,9,11,13,15 |
| 8 | 7 | 17 | A[7]=17 | 8 | 8<10 | 3,5,7,9,11,13,15,17 |
| 9 | 8 | 19 | A[8]=19 | 9 | 9<10 | 3,5,7,9,11,13,15,17,19 |
| 10 | 9 | 21 | A[9]=21 | 10 | 10<10 | 3,5,7,9,11,13,15,17,19,21 |

## Ejercicio 4.- Usando for, while y do-while almacenar n números leídos del teclado en un vector de 10 elementos. 
### ANÁLISIS
Datos de entrada: num\ (en todos)\
Variables: i, num, A (en el dfd de for). cont, A, num (en el dfd de while). cont, A, num (en el dfd de do-while)\
Datos de salida: A (en todos)
### DFD
#### _For_
![4_DFD_For](https://user-images.githubusercontent.com/113320901/197310003-bf400baf-d6f0-43d3-a0ad-003493830d22.png)
