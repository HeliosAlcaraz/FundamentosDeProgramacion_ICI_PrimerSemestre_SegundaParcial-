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

#### CÓDIGO EN DART (For)
![1_DFD_For](https://user-images.githubusercontent.com/113320901/197362302-d6845409-223d-4ddb-9e7b-b3f39ab74032.png)

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

#### CÓDIGO EN DART (While)
![1_DFD_While](https://user-images.githubusercontent.com/113320901/197362552-bdfa4161-9779-40a1-846e-5b9899ac3569.png)


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

#### CÓDIGO EN DART (Do-While)
![1_DFD_DoWhile](https://user-images.githubusercontent.com/113320901/197362831-dbc0bfd1-53b5-491b-a410-cc3027b37e61.png)


## Ejercicio 2.- Obtenga la suma de los primeros cinco números pares.
### ANÁLISIS
Datos de entrada: ninguno (en todos)\
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

#### CÓDIGO EN DART (For)
![2_DFD_For](https://user-images.githubusercontent.com/113320901/197362992-204138a8-23ad-48af-9963-f4e71efb1521.png)


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

#### CÓDIGO EN DART (While)
![2_DFD_While](https://user-images.githubusercontent.com/113320901/197363206-92e7a46d-0cae-454d-b839-49205b1679d7.png)


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

#### CÓDIGO EN DART (Do-While)
![2_DFD_DoWhile](https://user-images.githubusercontent.com/113320901/197363494-3b50ddb5-376e-4698-a324-ab6b8dc3d7d0.png)


## Ejercicio 3.- Almacene en un array el número n leído del teclado. El tamaño del array es 10. 
### ANÁLISIS
Datos de entrada: num (en todos)\
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

#### CÓDIGO EN JAVA (For)
![3_DFD_For](https://user-images.githubusercontent.com/113320901/197365432-355c6241-8e02-495d-8f71-ff5d84b13202.png)

![3_DFD_For_Run](https://user-images.githubusercontent.com/113320901/197365438-b8945594-154a-4ce7-bb31-c29cba99643a.png)


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

#### CÓDIGO EN JAVA (While)
![3_DFD_While](https://user-images.githubusercontent.com/113320901/197366087-5c6d068a-b166-417d-8d2c-c4662ee53769.png)

![3_DFD_While_Run](https://user-images.githubusercontent.com/113320901/197366093-2fd456a5-1e16-4ddc-870e-cda6b4a6710f.png)


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

#### CÓDIGO EN JAVA (Do-While)
![3_DFD_DoWhile](https://user-images.githubusercontent.com/113320901/197366229-3d7e9f22-6049-45b1-9929-9e19c06dff2c.png)

![3_DFD_DoWhile_Run](https://user-images.githubusercontent.com/113320901/197366235-4b954fbd-7608-427d-8a6d-f6a339dcd6a6.png)


## Ejercicio 4.- Usando for, while y do-while almacenar n números leídos del teclado en un vector de 10 elementos. 
### ANÁLISIS
Datos de entrada: num (en todos)\
Variables: i, num, A (en el dfd de for). cont, A, num (en el dfd de while). cont, A, num (en el dfd de do-while)\
Datos de salida: A (en todos)
### DFD
#### _For_
![4_DFD_For](https://user-images.githubusercontent.com/113320901/197313611-7fe4740f-c4af-4e71-9269-73df50b9eef4.png)

#### PRUEBA DE ESCRITORIO (For)
|#  | num | i | i<10 |A[i]=num|i++| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 | 2 | 0 | 0<10 | A[0]=2 | 1 | 2 |
| 2 | 4 | 1 | 1<10 | A[1]=4 | 2 | 2,4 |
| 3 | 6 | 2 | 2<10 | A[2]=6 | 3 | 2,4,6 |
| 4 | 8 | 3 | 3<10 | A[3]=10 | 4 | 2,4,6,8 |
| 5 | 10 | 4 | 4<10 | A[4]=10 | 5 | 2,4,6,8,10 |
| 6 | 12 | 5 | 5<10 | A[5]=12 | 6 | 2,4,6,8,10,12 |
| 7 | 14 | 6 | 6<10 | A[6]=14 | 7 | 2,4,6,8,10,12,14 |
| 8 | 16 | 7 | 7<10 | A[7]=16 | 8 | 2,4,6,8,10,12,14,16 |
| 9 | 18 | 8 | 8<10 | A[8]=18 | 9 | 2,4,6,8,10,12,14,16,18 |
| 10 | 20 | 9 | 9<10 | A[9]=20 | 10 | 2,5,6,8,10,12,14,16,18,20 |
| 11 | 22 | 10 | 10<10 | - | - | 2,5,6,8,10,12,14,16,18,20 |

#### CÓDIGO EN JAVA (For)
![4_DFD_For](https://user-images.githubusercontent.com/113320901/197366857-19a05957-732d-4130-a2e2-e598900b7d3f.png)

![4_DFD_For_Run](https://user-images.githubusercontent.com/113320901/197366863-def89c30-3971-48b6-83df-ea7155eecd0c.png)


#### _While_
![4_DFD_While](https://user-images.githubusercontent.com/113320901/197314292-9b488536-9f95-4e43-8b2d-6cbed90b95aa.png)

#### PRUEBA DE ESCRITORIO (While)
|#  | num | cont | cont<=9 |A[cont]=num|cont++| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 | 2 | 0 | 0<=9 | A[0]=2 | 1 | 2 |
| 2 | 4 | 1 | 1<=9 | A[1]=4 | 2 | 2,4 |
| 3 | 6 | 2 | 2<=9 | A[2]=6 | 3 | 2,4,6 |
| 4 | 8 | 3 | 3<=9 | A[3]=8 | 4 | 2,4,6,8 |
| 5 | 10 | 4 | 4<=9 | A[4]=10 | 5 | 2,4,6,8,10 |
| 6 | 12 | 5 | 5<=9 | A[5]=12 | 6 | 2,4,6,8,10,12 |
| 7 | 14 | 6 | 6<=9 | A[6]=14 | 7 | 2,4,6,8,10,12,14 |
| 8 | 16 | 7 | 7<=9 | A[7]=16 | 8 | 2,4,6,8,10,12,14,16 |
| 9 | 18 | 8 | 8<=9 | A[8]=18 | 9 | 2,4,6,8,10,12,14,16,18 |
| 10 | 20 | 9 | 9<=9 | A[9]=20 | 10 | 2,4,6,8,10,12,14,16,18,20 |
| 11 | 22 | 10 | 10<=9 | - | - | 2,4,6,8,10,12,14,16,18,20 |

#### CÓDIGO EN JAVA (While)
![4_DFD_While](https://user-images.githubusercontent.com/113320901/197366871-378769e2-ab08-4f49-8912-cb2501c4c56b.png)

![4_DFD_While_Run](https://user-images.githubusercontent.com/113320901/197366874-7a00a724-a242-40cd-a169-0c9ac0e9c905.png)


#### _Do-While_
![4_DFD_DoWhile](https://user-images.githubusercontent.com/113320901/197314882-7f4bdb95-8ef9-416f-b9f5-bda62db2f909.png)

#### PRUEBA DE ESCRITORIO (Do-While)
|#  | cont | num | A[cont]=num |cont++|cont<=9| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 | 0 | 2 | A[0]=2 |1| 1<=9 | 2 |
| 2 | 1 | 4 | A[1]=4 |2| 2<=9 | 2,4 |
| 3 | 2 | 6 | A[2]=6 |3| 3<=9 | 2,4,6 |
| 4 | 3 | 8 | A[3]=8 |4| 4<=9 | 2,4,6,8 |
| 5 | 4 | 10 | A[4]=10 |5| 5<=9 | 2,4,6,8,10 |
| 6 | 5 | 12 | A[5]=12 |6| 6<=9 | 2,4,6,8,10,12 |
| 7 | 6 | 14 | A[6]=14 |7| 7<=9 | 2,4,6,8,10,12,14 |
| 8 | 7 | 16 | A[7]=16 |8| 8<=9 | 2,4,6,8,10,12,14,16 |
| 9 | 8 | 18 | A[8]=18 |9| 9<=9 | 2,4,6,8,10,12,14,16,18 |
| 10 | 9 | 20 | A[9]=20 |10| 10<=9 | 2,4,6,8,10,12,14,16,18,20 |

#### CÓDIGO EN JAVA (Do-While)
![4_DFD_DoWhile](https://user-images.githubusercontent.com/113320901/197366881-24408382-38fb-4432-9b79-4cbae3b2246a.png)

![4_DFD_DoWhile_Run](https://user-images.githubusercontent.com/113320901/197366885-1a146585-aac8-4224-87d0-da816a1f5433.png)


## Ejercicio 5.- Almacenar un contador regresivo en un vector. El conteo es de 10 a 0. 
### ANÁLISIS
Datos de entrada: ninguno (en todos)\
Variables: i, A, cont (en el dfd de for). cont, A, contnum (en el dfd de while). cont, contnum, A (en el dfd de do-while)\
Datos de salida: A (en todos)
### DFD
#### _For_
![5_DFD_For](https://user-images.githubusercontent.com/113320901/197315455-f0f32324-b494-4ff6-9559-a06f36d8c0d3.png)

#### PRUEBA DE ESCRITORIO (For)
| # | i  | i<11 |cont|A[i]=cont| cont--|i++| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 |  0 | 0<11 |10| A[0]=10 | 9 | 1 |10|
| 2 |  1 | 1<11 | 9| A[1]=9  | 8 | 2 |10,9|
| 3 |  2 | 2<11 | 8| A[2]=8  | 7 | 3 |10,9,8|
| 4 |  3 | 3<11 | 7| A[3]=7  | 6 | 4 |10,9,8,7|
| 5 |  4 | 4<11 | 6| A[4]=6  | 5 | 5 |10,9,8,7,6|
| 6 |  5 | 5<11 | 5| A[5]=5  | 4 | 6 |10,9,8,7,6,5|
| 7 |  6 | 6<11 | 4| A[6]=4  | 3 | 7 |10,9,8,7,6,5,4|
| 8 |  7 | 7<11 | 3| A[7]=3  | 2 | 8 |10,9,8,7,6,5,4,3|
| 9 |  8 | 8<11 | 2| A[8]=2  | 1 | 9 |10,9,8,7,6,5,4,3,2|
| 10 | 9 | 9<11 | 1| A[9]=1  | 0 | 10 |10,9,8,7,6,5,4,3,2,1|
| 11 |10 | 10<11| 0| A[10]=0 | - | 11 |10,9,8,7,6,5,4,3,2,1,0|

#### CÓDIGO EN JAVA (For)
![5_DFD_For](https://user-images.githubusercontent.com/113320901/197367181-080dc32f-8b98-41f1-af3f-f2f18fd8520a.png)

![5_DFD_For_Run](https://user-images.githubusercontent.com/113320901/197367185-002d76b9-75b5-414f-b3e3-404bcfaf465a.png)

#### _While_
![5_DFD_While](https://user-images.githubusercontent.com/113320901/197317141-91dcfdb6-5920-4f37-a41a-7869583d0eb4.png)

#### PRUEBA DE ESCRITORIO (While)
| # | cont  | cont<11 |contnum|A[cont]=contnum| contnum=contnum-1|cont++| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 |  0 | 0<11 |10| A[0]=10 | 9 | 1 |10|
| 2 |  1 | 1<11 | 9| A[1]=9  | 8 | 2 |10,9|
| 3 |  2 | 2<11 | 8| A[2]=8  | 7 | 3 |10,9,8|
| 4 |  3 | 3<11 | 7| A[3]=7  | 6 | 4 |10,9,8,7|
| 5 |  4 | 4<11 | 6| A[4]=6  | 5 | 5 |10,9,8,7,6|
| 6 |  5 | 5<11 | 5| A[5]=5  | 4 | 6 |10,9,8,7,6,5|
| 7 |  6 | 6<11 | 4| A[6]=4  | 3 | 7 |10,9,8,7,6,5,4|
| 8 |  7 | 7<11 | 3| A[7]=3  | 2 | 8 |10,9,8,7,6,5,4,3|
| 9 |  8 | 8<11 | 2| A[8]=2  | 1 | 9 |10,9,8,7,6,5,4,3,2|
| 10 | 9 | 9<11 | 1| A[9]=1  | 0 | 10 |10,9,8,7,6,5,4,3,2,1|
| 11 |10 | 10<11| 0| A[10]=0 | - | 11 |10,9,8,7,6,5,4,3,2,1,0|
#### _Do-While_
![5_DFD_DoWhile](https://user-images.githubusercontent.com/113320901/197317179-7e1bad3d-d093-4e49-b497-14bf0d5b08dc.png)

#### PRUEBA DE ESCRITORIO (Do-While)
| # | cont  | contnum |A[cont]=contnum|cont++| contnum=contnum-1|cont<11| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 |  0 | 10 |A[0]=10| 1 | 9 | 1<11 |10|
| 2 |  1 | 9 | A[1]=9| 2  | 8 | 2<11 |10,9|
| 3 |  2 | 8 | A[2]=8|  3 | 7 | 3<11 |10,9,8|
| 4 |  3 | 7 | A[3]=7|  4 | 6 | 4<11 |10,9,8,7|
| 5 |  4 | 6 | A[4]=6|  5 | 5 | 5<11 |10,9,8,7,6|
| 6 |  5 | 5 | A[5]=5|  6 | 4 | 6<11 |10,9,8,7,6,5|
| 7 |  6 | 4 | A[6]=4|  7 | 3 | 7<11 |10,9,8,7,6,5,4|
| 8 |  7 | 3 | A[7]=3|  8 | 2 | 8<11 |10,9,8,7,6,5,4,3|
| 9 |  8 | 2 | A[8]=2|  9 | 1 | 9<11 |10,9,8,7,6,5,4,3,2|
| 10 | 9 | 1 | A[9]=1| 10 | 0 | 10<11 |10,9,8,7,6,5,4,3,2,1|
| 11 |10 | 0| A[10]=0| 11 | - | 11<11 |10,9,8,7,6,5,4,3,2,1,0|


## Ejercicio 6.- Almacene en un vector de tamaño 10 todos los números pares capturados hasta completar todos. 
### ANÁLISIS
Datos de entrada: num (en todos)\
Variables: i, num, A (en el dfd de for). cont, num, A (en el dfd de while). cont, num, A (en el dfd de do-while)\
Datos de salida: A (en todos)
### DFD
#### _For_
![6_DFD_For](https://user-images.githubusercontent.com/113320901/197352813-a506281a-92a6-4346-a227-719ab7503eba.png)

#### PRUEBA DE ESCRITORIO (For)
| # | i  | i<=9 |num|n%2==0|A[i]=num|i++|i--| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 |  0 | 0<=9 | 2 |  sí  | A[0]=2 | 1 | - |2|
| 2 |  1 | 1<=9 | 2 |  sí  | A[1]=2 | 2 | - |2,2|
| 3 |  2 | 2<=9 | 1 |  no  |   -    | 3 | 2 |2,2|
| 4 |  2 | 2<=9 | 4 |  sí  | A[2]=4 | 3 | - |2,2,4|
| 5 |  3 | 3<=9 | 6 |  sí  | A[3]=6 | 4 | - |2,2,4,6|
| 6 |  4 | 4<=9 | 2 |  sí  | A[4]=2 | 5 | - |2,2,4,6,2|
| 7 |  5 | 5<=9 | 9 |  no  |   -    | 6 | 5 |2,2,4,6,2|
| 8 |  5 | 5<=9 | 4 |  sí  | A[5]=4 | 6 | - |2,2,4,6,2,4|
| 9 |  6 | 6<=9 | 2 |  sí  | A[6]=2 | 7 | - |2,2,4,6,2,4,2|
| 10 | 7 | 7<=9 | 2 |  sí  | A[7]=2 | 8 | - |2,2,4,6,2,4,2,2|
| 11 | 8 | 8<=9 | 8 |  sí  | A[8]=8 | 9 | - |2,2,4,6,2,4,2,2,8|
| 12 | 9 | 9<=9 | 5 |  no  |   -    |10 | 9 |2,2,4,6,2,4,2,2,8|
| 13 | 9 | 9<=9 |34 |  sí  | A[9]=34|10 | - |2,2,4,6,2,4,2,2,8,34|
#### _While_
![6_DFD_While](https://user-images.githubusercontent.com/113320901/197352901-c1f8105c-ecca-416d-9360-deb140979a44.png)

#### PRUEBA DE ESCRITORIO (While)
| # |cont|icont<10|num|n%2==0|A[i]=num|i++| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 |  0 |  0<10  | 2 |  sí  | A[0]=2 | 1 |2|
| 2 |  1 |  1<10  | 2 |  sí  | A[1]=2 | 2 |2,2|
| 3 |  2 |  2<10  | 1 |  no  |   -    | 2 |2,2|
| 4 |  2 |  2<10  | 4 |  sí  | A[2]=4 | 3 |2,2,4|
| 5 |  3 |  3<10  | 6 |  sí  | A[3]=6 | 4 |2,2,4,6|
| 6 |  4 |  4<10  | 2 |  sí  | A[4]=2 | 5 |2,2,4,6,2|
| 7 |  5 |  5<10  | 9 |  no  |   -    | 5 |2,2,4,6,2|
| 8 |  5 |  5<10  | 4 |  sí  | A[5]=4 | 6 |2,2,4,6,2,4|
| 9 |  6 |  6<10  | 2 |  sí  | A[6]=2 | 7 |2,2,4,6,2,4,2|
| 10 | 7 |  7<10  | 2 |  sí  | A[7]=2 | 8 |2,2,4,6,2,4,2,2|
| 11 | 8 |  8<10  | 8 |  sí  | A[8]=8 | 9 |2,2,4,6,2,4,2,2,8|
| 12 | 9 |  9<10  | 5 |  no  |   -    | 9 |2,2,4,6,2,4,2,2,8|
| 13 | 9 |  9<10  |34 |  sí  | A[9]=34|10 |2,2,4,6,2,4,2,2,8,34|
| 14 |10 | 10<10  | - |   -  |    -   | - |2,2,4,6,2,4,2,2,8,34|
#### _Do-While_
![6_DFD_DoWhile](https://user-images.githubusercontent.com/113320901/197353485-5835bdee-0910-42c2-80b9-5313fdde00fe.png)

#### PRUEBA DE ESCRITORIO (Do-While)
| # |cont| num|A[cont]=num|cont++|cont<10|num%2==0|cont--| A |
| ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| 1 |  0 | 10 |  A[0]=10  |  1 | 1<10 | sí | - |10|
| 2 |  1 |  8 |  A[1]=8   |  2 | 2<10 | sí | - |10,8|
| 3 |  2 |  6 |  A[2]=6   |  3 | 3<10 | sí | - |10,8,6|
| 4 |  3 |  7 |  A[3]=7   |  4 | 4<10 | no | 3 |10,8,6,7|
| 5 |  3 |  4 |  A[3]=4   |  4 | 4<10 | sí | - |10,8,6,4|
| 6 |  4 | 20 |  A[4]=20  |  5 | 5<10 | sí | - |10,8,6,4,20|
| 7 |  5 | 12 |  A[5]=12  |  6 | 6<10 | sí | - |10,8,6,4,20,12|
| 8 |  6 | 15 |  A[6]=15  |  7 | 7<10 | no | 6 |10,8,6,4,20,12,15|
| 9 |  6 |  2 |  A[6]=2   |  7 | 7<10 | sí | - |10,8,6,4,20,12,2|
| 10 | 7 | 24 |  A[7]=24  |  8 | 8<10 | sí | - |10,8,6,4,20,12,2,24|
| 11 | 8 |  4 |  A[8]=4   |  9 | 9<10 | sí | - |10,8,6,4,20,12,2,24,4|
| 12 | 9 | 32 |  A[9]=32  | 10 |10<10 |  - | - |10,8,6,4,20,12,2,24,4,32|
