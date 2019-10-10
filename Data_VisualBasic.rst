Data En Visual Basic 
===========================


DataSet
-------

Lugar donde se almacenan datos en memoria solamente, independiente de la conexion si esta abierta o cerrada.

Se pueden agregar datos desde varias fuentes tambien

Existen dos tipos: tipado y no tipado

**Tipado**

- En un DataSet Tipado puedes meter todos tus métodos y graficamente verlos como estan organizados, además de que le da un sentido organizacional y mas profesional a tu proyecto

- Posee una estructura grafica mas robusta y más facil de entender además de que un dataset no tipado, permite un ambiente amigable con la conexion a la base de datos. 

- En un dataset tipado puedo hacer la conexion directamente y poner los métodos que voy a utilizar, Insert,Update,Delete,Edit ……etc, etc

**No Tipado**

- Un DataSet No tipado es crear un dataset con puro codigo, desde 0. Es un poco más seguro en cuanto a control pero, como la mayoría de los métodos casi siempre son los mismos, a veces es mejor hacer las cosas más rapido.


DataTable
---------

Un DataTable es igual que el dataset solo que con una sola tabla, comunmente se utiliza para volcar el dataset sobre el y trabajar el datarow.


DataVIew
--------

El DataVIew es una vista del datatable y es utilizada para darle una vista personalizada al datatable como filtrar, buscar, navegar,etc.