# Modelos de Prediccion de Cancer de Mama

![](https://dam.ngenespanol.com/wp-content/uploads/2018/10/Cancer-mama-America-P.png)

Introduccion:

Mediante el siguiente trabajo, vamos a crear un modelo de prediccion que ayude a detectar de manera oprotuna a el diagnostico de cancer de mama, para ello seguimos los siguientes pasos.

Procedimiento:

1.- En primer lugar cargamos las liberia a utilizar en el modelo, las cuales las veremos en el proyecto.

2.- Como segundo paso leemos el archivo y colocamos y añadimos las cabeceras como lo detalla la imagen.

![image](https://user-images.githubusercontent.com/114968090/194793590-65f148e2-d532-4bbb-bf60-5f952b2ff8d8.png)

3.- Como parte del tratamiento de datos para trabajar con los modelos remplazamos en la columna diagnosisi M =1 y B = 0

![image](https://user-images.githubusercontent.com/114968090/194793750-23f22d26-4568-4c1d-8e57-c38d178284b6.png)

4.- Dentro de la limpieza de datos se valido si exiten null o algun dato adicional el cual no fue ejecutado.}}

![image](https://user-images.githubusercontent.com/114968090/194793861-39e8ba46-b565-4af9-94d1-2c774d0b70e1.png)

5.- Transformamos los todo el df en intero con la siguiente sentencia.

![image](https://user-images.githubusercontent.com/114968090/194793987-3b838d9f-51a3-45d8-bd7d-e8e8f5cb008a.png)

6.-  Corremos los modelos los cuales se detallan en el archivo y vemos como resultado lo siguiente:

el modelo numero uno nos arroja el siguiente resultado

![image](https://user-images.githubusercontent.com/114968090/194794208-0f1a0ab8-30d9-4760-8e77-f100646d04bf.png)

con el segundo modelo tenemos el siguiente resultado:

![image](https://user-images.githubusercontent.com/114968090/194794351-2885c615-1f14-4a01-ab77-13316a9ca72b.png)

El modelo tres Nos arroja el Siguiente resultado:

![image](https://user-images.githubusercontent.com/114968090/194794475-56bf87c3-b487-4ece-92dd-fb5dfd44ae1d.png)

Y por ultimo el cuarto modelo nos arroja el siguiente resultado:

![image](https://user-images.githubusercontent.com/114968090/194794843-a267b193-2030-4699-86ff-1e0bb697355a.png)

Resultado Final

Como vimos en los resultados de los modelos se podria mencionar que el modelo mas acertivo en base a las variable tratadas, es el modelo numero tres debido a que dentro de la matriz de confucion tenemos pronosticados

245 Verdaderos Positivos detectados

0 Falsos Positivos detectados

0 Falsos negativos detectados

245 Verdaderos negativos detectado

y deacuerdo al accuracy tienen un 0.94 a comparacion a los modelos anteriores.

Por lo que este seria el modelo mas optimo a utilizar.








