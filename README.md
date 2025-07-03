# TodoList

## Sprint 1: Devops Sprint [ EN PROCESO ]

### Duración

- Inicio: 1 Julio
- Finalizó: 3 Julio 
- Duración: 3 días

### Objetivo
Este sprint tiene como objetivo facilitar el deployment de los distintos contenedores y limitar el trabajo manual que se hace al descargar los contenedores.

### Tareas

### Script de descarga en el bucket de admin:
- [x] Descargar automáticamente los modelos voz de VOSK
- [x] Descargar automáticamente las imágenes de cada personaje
- [x] Descargar automáticamente el pth e index de cada personaje ( descomprir el zip )
- [x] Descargar automáticamente los gameplays al bucket de gameplays.

### Docker Compose
- [x] Hacer que todos los contenedores se reinicien automáticamente si se caen  (restart: unless-stopped)

### Testeo General
- [ ] Testear que el docker compose funcione sin intervención manual para arreglar errores en una máquina nueva que nunca ejecutó los contenedores. [ No sabemos cómo replicar el error, quedá abierto ]

## Sprint 2: Errores Generales [PLANEACIÓN]

Inicio: 3 Julio
Finalizó: 
Duración: 

### Objetivo
Este sprint tiene como objetivo corregir errores que hacen que el sistema falle o se rompa.

- [ ] Cuando se envían cero o menos imágenes no se debe renderizar nada, también hay que hacer un catch de ZeroDivisionError
- [ ] Subtitle generator no renderiza si el nombre es muy largo
- [ ] Agregar un limite de imágenes a los videos
- [ ] Parsear los datos que se ponen en el frontend para que solo devuelva ASCII válido.

## Sprint 3: Eliminar valores hardcodeados [PLANEACIÓN]

### Objetivo
El objetivo de este sprint es que en el frontend el usuario tenga opciones en base a los datos que psoee el servidor y que no esten hardcodeadas. Esto evitaría muchos errores en el backend cuando algún microservicio no encuentre un archivo especifico. 

- [ ] Agregar un endpoint de modelos de AI disponibles
- [ ] Agregar un endpoint de los gameplays disponibles
- [ ] Agregar un endpoint de las imágenes disponibles
- [ ] Agregar un endpoint de los personajes disponibles (Homero, Peter Griffin)
- [ ] Agregar un endpoint de los idiomas disponibles

## Sprint 4: Hostear el servidor de manera robusta [PLANEACIÓN]

## Sprint 4: Reescribir video Creator en GO lang! [PLANEACIÓN]
