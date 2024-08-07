# Propuesta TP DSW

## Grupo
### Integrantes
* 48777 - Bernardi, Matias

### Repositorios
* [frontend app](https://github.com/MatiBerna/frontend-comuna)
* [backend app](https://github.com/MatiBerna/comuna-backend)

### Deploy
* [página web](https://comunavillafucsia.vercel.app/home) (El backend cae por inactividad, se vuelve a abrir luego de unos segundos)

## Tema
### Descripción

Sistema de gestión de eventos organizados desde la comuna "Villa Fucsia". Los mismos son organizados para feriados y celebraciones (como día del niño, dia de la madre, dia del padre, etc). Los eventos pueden extenderse en varios días y dentro de los mismos pueden llevarse a cabo competencias. 

Manejaremos dos tipos de usuarios: Una persona que podrá registrarse para participar de una competencia o postularse como jurado, y persona administrativa que organice y registre los eventos a realizar.

### Modelo
![TP DSW](https://github.com/MatiBerna/TP-DSW/assets/128424988/00128af9-d975-492e-803c-ae9f31b9cba5)


## Alcance Funcional 

### Alcance Mínimo
 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Persona<br>2. CRUD Evento<br>3. CRUD Tipo Competencia<br>4. CRUD Participante|
|CRUD dependiente|1. CRUD Competencia {depende de} CRUD Evento y TipoCompetencia|
|Listado<br>+<br>detalle| 1. Listado de participantes filtrado por competencia, muestra nombre del participante y el puesto del mismo => detalle CRUD Participante<br> 2. Listado de competencias para un evento especifico => detalle CRUD evento| 
|CUU/Epic|1. Registrar participación de una persona en una competencia<br>2. Registrar jurado de una competencia|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD <br>4. CRUD Participante {depende de} CRUD Competencia y CRUD persona|
|CUU/Epic|1. Participación de eventos<br>


### Alcance Adicional Voluntario



|Req|Detalle|
|:-|:-|

