# LMSGI EXAMEN UNIDAD 4 - 17/04/2024

## Indicaciones generales
Lee atentamente estas indicaciones generales antes de realizar esta prueba:
* Crea una carpeta que se llame TUSINICIALES_EX_UD_4.
* Dentro de dicha carpeta ve creando y/o modificando los diversos archivos .xml, .dtd o .xsd que se pidan durante el examen.
* Debes subir a la tarea de classroom dicha carpeta como .zip: Click derecho en la carpeta, Click en "Enviar a", Click en "Carpeta comprimida (en zip)".
* Realiza cada apartado siguiendo las indicaciones al pie de la letra.
* Puedes acceder a los apuntes, diapositivas, ejercicios resueltos, internet y consultar cualquier cosa <b>exceptuando la IA</b>, que queda prohibida.
* Revisa el tiempo, la entrega se cierra 5 minutos antes de que termine la clase - 🕙 11:10.
* Acuérdate de ir guardando constantemente. En caso de no visualizarse algun archivo, dicho apartado o ejercicio contará como un 0 <b>no revisable. También si haces uso de la IA. </b>


## **Ejercicios XML básico - 2 puntos**

### Ejercicio 1 - 1 punto
Creación de un Documento XML sobre un Libro. Escribe un documento XML que represente la información detallada de un libro. Este contiene un atributo ISBN para identificar de manera única el libro. Para representar la información completa de un libro se necesita conocer el título, autor del cual queremos saber nombre, apellidos y fecha de nacimiento, publicación que se compone de la fecha de publicación y editorial. También almacenaremos el género y este a su vez se compone de principal, subgénero. También de libro queremos seguir conociendo el idioma y el precio, que presenta un atributo moneda que expresa el precio.

### Ejercicio 2 - 1 punto
En este ejercicio, crearás un documento XML que represente un catálogo de productos de una cadena de tiendas. Este catálogo tendrá una fecha de publicación, un listado con las tiendas en el que está disponible, de las que se indicará la provincia y la ciudad. Este catálogo también contendrá información sobre varios productos, cada uno con un atributo que indique la cantidad adquirida y también se indicará como elementos su nombre, descripción, precio (con un atributo que indique la divisa) y disponibilidad en stock.

## **Ejercicios DTD - 2 puntos**
### Ejercicio 3 - 1 punto
Realiza un DTD para el ejercicio 1 que valide el documento XML que has creado.

### Ejercicio 4 - 1 punto
Realiza un DTD para el ejercicio 2 que valide el documento XML que has creado.

## **Ejercicios XML Schema - 6 puntos**
### Ejercicio 5 - 1,5 puntos
Realiza un XML Schema para el ejercicio 1 que valide el documento XML que has creado.

### Ejercicio 6 - 1,5 puntos
Realiza un XML Schema para el ejercicio 2 que valide el documento XML que has creado.

### Ejercicio 7 - 3 puntos
En este ejercicio, tu tarea es crear un esquema XML (XSD) que valide documentos XML que contienen información sobre un sistema de gestión de pacientes de un hospital. El esquema debe definir la estructura y las restricciones que deben cumplir los documentos XML para ser considerados válidos.

Instrucciones:

Define un elemento raíz llamado hospital que puede contener uno o más elementos <paciente>.
Cada elemento <paciente> debe contener elementos para el nombre, el apellido, la fecha de nacimiento, el sexo, el número de seguro social y una lista de consultas médicas del paciente.
Define un elemento <consulta> para representar una consulta médica. Cada consulta debe tener elementos para la fecha de la consulta, el médico que realizó la consulta, el motivo de la consulta y el diagnóstico.
Aplica las siguientes restricciones adicionales:
El nombre y el apellido del paciente no pueden estar vacíos.
La fecha de nacimiento del paciente debe estar en el formato "AAAA-MM-DD".
El sexo del paciente debe ser "Masculino" o "Femenino".
El número de seguro social del paciente debe ser una cadena de 9 dígitos.
La fecha de la consulta médica debe estar en el formato "AAAA-MM-DD".
El motivo de la consulta médica y el diagnóstico no pueden estar vacíos.

Define un elemento <hospitalizacion> para registrar las hospitalizaciones de los pacientes. Cada hospitalización debe tener elementos para la fecha de ingreso, la fecha de alta, la habitación asignada y el motivo de la hospitalización.
Aplica restricciones adicionales según lo consideres necesario para garantizar la validez de los documentos XML de las hospitalizaciones.
