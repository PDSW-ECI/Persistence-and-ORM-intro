-   [English (en)](https://campusvirtual.escuelaing.edu.co/moodle/mod/assign/view.php?id=114476# "Language")

## Laboratorio 7

## Escuela Colombiana de Ingeniería

## Ciclos de vida del Desarrollo de Software

## Sección I. - Introducción a JDBC

1.  Clonar el proyecto [MyBatis\_Introduction\_VideoRental de GitHub](https://github.com/PDSW-ECI/MyBatis_Introduction_VideoRental) donde se realizará la implementación completa del laboratorio.
2.  Descargue el archivo [JDBCExample.java](https://campusvirtual.escuelaing.edu.co/moodle/pluginfile.php/191340/mod_assign/intro/JDBCExample.java) y agreguelo en el paquete "edu.eci.cvds.sampleprj.jdbc.example".
3.  Desde esta clase se realizará una conexión a una base de datos MySQL por medio de JDBC y sus "_Prepared Statements_".
4.  En un motor de base de datos SQL se tiene un esquema con el siguiente modelo de base de datos (para registrar pedidos sobre productos):![Model.png](https://raw.githubusercontent.com/PDSW-ECI/JDBC_Intro/master/img/RMODEL.png)
5.  Revise la documentación de ‘[PreparedStatement](http://docs.oracle.com/javase/tutorial/jdbc/basics/prepared.html)’, del API JDBC.
6.  En la clase **JDBCExample** juste los parámetros de conexión a la base de datos con los datos reales:
    -   ```
        Url: jdbc:mysql://desarrollo.is.escuelaing.edu.co:3306/bdpruebaDriver: com.mysql.jdbc.DriverUsuario: bdpruebaContraseña: prueba2019
        ```
        
7.  Implemente las operaciones faltantes:
    1.  nombresProductosPedido
    2.  valorTotalPedido - El resultado final lo debe retornar la base de datos, no se deben hacer operaciones en memoria.
    3.  registrarNuevoProducto - Use su código de estudiante para evitar colisiones.
8.  Verifique por medio de un cliente SQL, que la información retornada por el programa coincide con la que se encuentra almacenada en base de datos.

## Sección II. - Introducción a MyBatis

1.  Revise la [documentación básica de MyBatis](http://www.mybatis.org/mybatis-3/es/) de forma que entienda para qué sirve y el uso básico que se le puede dar al framework.
2.  Seguir las instrucciones que se encuentran en el repositorio de forma que en la clase **MyBatisExample.java** se creen los mappers necesarios y sea posible realizar la ejecución de diferentes sentencias SQL en la base de datos de pruebas.

## Entrega

-   Agregar la URL del repositorio donde se cargó el proyecto.

### Grading summary

<table><tbody><tr><th scope="row">Hidden from students</th><td>Yes</td></tr><tr><th scope="row">Participants</th><td>0</td></tr><tr><th scope="row">Submitted</th><td>0</td></tr><tr><th scope="row">Needs grading</th><td>0</td></tr><tr><th scope="row">Due date</th><td>Saturday, 19 March 2022, 10:00 AM</td></tr><tr><th scope="row">Time remaining</th><td>Assignment is due</td></tr><tr><th scope="row">Late submissions</th><td>Only allowed for participants who have been granted an extension</td></tr></tbody></table>

[Get the mobile app](https://download.moodle.org/mobile?version=2020061513.05&lang=en&iosappid=633359593&androidappid=com.moodle.moodlemobile)