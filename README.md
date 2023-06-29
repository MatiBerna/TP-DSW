# Propuesta TP DSW

## Grupo
### Integrantes
* 48777 - Bernardi, Matias
* 49810 - Gaggiotti, Gabriele

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
*2 a 6 líneas describiendo el negocio (menos es más)*
Sistema de gestión de eventos organizados desde la comuna "nombre". Los mismos son organizados para feriados y celebraciones (como día del niño, dia de la madre, dia del padre, etc). Los eventos pueden extenderse en varios días y dentro de los mismos pueden llevarse a cabo espectaculos en vivo y/o competencias. 

Manejaremos dos tipos de usuarios: Una persona que podrá registrarse para participar de una competencia, y persona administrativa que organice y registre los eventos a realizar.

### Modelo
![image](https://github.com/MatiBerna/TP-DSW/assets/128424988/e2f43240-98a2-420c-8bd5-854814e43c42)


## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Persona<br>2. CRUD Evento<br>3. CRUD Competencia<br>4. CRUD Participante|
|CRUD dependiente|1. CRUD Espectaculo {depende de} CRUD Evento<br>2. CRUD Valor_diario {depende de} CRUD Recurso|
|Listado<br>+<br>detalle| 1. Listado de participantes filtrado por competencia, muestra nombre del participante y el puesto del mismo => detalle CRUD Participante<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente(CAMBIAR POR UNO DE NUESTRO SISTEMA)| 
|CUU/Epic|1. Registrar participación de una persona en una competencia<br>2. Registrar un espectaculo para un determinado evento|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|
