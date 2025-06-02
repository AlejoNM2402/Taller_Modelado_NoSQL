# 📑Respuestas:

## ¿Qué es una base de datos NoSQL📊?
Es un sistema de bases de datos que no sigue el modelado relacional tradicional de tablas que usan las bases de datos SQL si no que usa un manejo de datos mas flexible, como por ejemplo MongoDB que usa documentos tipo Json.

### Sus caracteristicas mas importantes:
- No tiene esquemas rigidos
- Escala de manera horizontal facilmente adaptandose a sistemas distribuidos
- Ideal para bases de datos muy cambiantes
- Es mas velóz para cosas como almacenar documentos o manejar grandes volumenes de datos.


## ¿Qué es MongoDB🍃?
Es una base de datos de tipo NoSQL, que almacena dagtos en documentos tipo Json pero con un formato especial llamado Bson, normalmente se usa cuando se necesita flexibilidad al estructurar datos, trabajar en muchos servidores (escalabilidad horizontal), Almacenar datos anidados como listas y objetos dentro del mismo docuento, entre otros.

## Sus principales caracteristicas:
- no usa tablas para guardar datos, lo hace en documentos.
- No necesita esquemas rigidos, esto quiere decir que puede tener documentos con distintos campos dentro de la misma colección.
- Es flexible e ideal para manejar grandes volumenes de datos.
- Se usa mucho pasa APIs, aplicaciones web, tiendas online, entre otros usos de aplicaciones modernas.


## ¿Qué diferencia hay entre una base de datos relacional (como MySQL🐬) y una base de datos documental como MongoDB🍃?
- Mientras la estructura de MySQL se basa en tablas con filas y columnas, MongoDb usa documentos tipo Json.
- El esquema de una base de datos relacional como MySQL es rígido siguiendo todos los datos un formato una base de datos documental como MongoDB peude ser mas flexible permitiendo que cada documento pueda ser diferente.
- En las relaciones MySQL usa llaver foraneas para unir tablas mientras que en MongoDB se usan referencias o incrustraciones.
- La escalabilidad de MySQl es vertical, esto quiere decir que trabaja para mejorar un solo servidor, mientras que con MongoDB es horizontal permitiendo añadir mas servidores.
- MySQL es ideal para datos estructurados y relaciones complejas, mientras que mongoDb es mas para Datos flexibles con cambios rapidos.
- Misntras las consultas en MySQL son consultas SQL tradicionales, en MongoDB, se hacen consultas en Bson (como un Json pero mejorado y optimizado para bases de datos, especialmente para MongoDB).



## ¿Qué son documentos📑 y colecciones📒 en MongoDB?
### Documento📑:
Un documento en MongoDB es una unidad de datos parecida a un objeto Json que contiene la información que se quiera guardar, este puede tener textos, fechas, numeros, objetos anidados entre otros.

### Colección📒:
Es un conjunto de documentos que de documentos relacionados entre si mas o menos como si fuera una tabla de una base de datos relacional, pero en formato tipo Json.


## Reflexionar
### ¿Qué fue lo más difícil de imaginar sin tablas?
Lo mas dificil de imaginar sin tablas fue la organizacion del documento, ya que teniamos que ponerlo en listas objetos.
### ¿Qué les gustó del enfoque con documentos?
Es mas facil, ya que no tienes que definir las relaciones, y es mas organizado a mi gusto.
### ¿Qué dudas les surgieron al pensar en este nuevo tipo de base de datos?

