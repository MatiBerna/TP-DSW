# Propuesta TP DSW

## Grupo
### Integrantes
* 48777 - Bernardi, Matias
* 49810 - Gaggiotti, Gabriele

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](https://github.com/MatiBerna/comuna-backend)


## Tema
### Descripción

Sistema de gestión de eventos organizados desde la comuna "nombre". Los mismos son organizados para feriados y celebraciones (como día del niño, dia de la madre, dia del padre, etc). Los eventos pueden extenderse en varios días y dentro de los mismos pueden llevarse a cabo espectaculos en vivo y/o competencias. 

Manejaremos dos tipos de usuarios: Una persona que podrá registrarse para participar de una competencia, y persona administrativa que organice y registre los eventos a realizar.

### Modelo
![image](https://github.com/MatiBerna/TP-DSW/assets/128424988/e2f43240-98a2-420c-8bd5-854814e43c42)


## Alcance Funcional 

### Alcance Mínimo
 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Persona<br>2. CRUD Evento<br>3. CRUD Competencia<br>4. CRUD Participante|
|CRUD dependiente|1. CRUD Espectaculo {depende de} CRUD Evento<br>2. CRUD Valor_diario {depende de} CRUD Recurso|
|Listado<br>+<br>detalle| 1. Listado de participantes filtrado por competencia, muestra nombre del participante y el puesto del mismo => detalle CRUD Participante<br> 2. Listado de competencias para un evento especifico => detalle CRUD evento| 
|CUU/Epic|1. Registrar participación de una persona en una competencia<br>2. Registrar un espectaculo para un determinado evento|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Lugar<br>2. CRUD Espectaculo<br>3. CRUD Artista<br>4. CRUD Persona<br>5. CRUD Evento<br>6. CRUD Recurso<br>7. CRUD Tipo_competencia<br>8. CRUD Jurado<br>9. CRUD Valor_diario|
|CUU/Epic|1. Programación de eventos<br>2. Gestión de recursos para el evento


### Alcance Adicional Voluntario



|Req|Detalle|
|:-|:-|

