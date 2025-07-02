# TodoList

## Sprint 1: Devops Sprint [ EN PROCESO ]

### Objetivo
Este sprint tiene como objetivo facilitar el deployment de los distintos contenedores y limitar el trabajo manual que se hace al descargar los contenedores.

### Tareas

### Script de descarga en el bucket de admin:
- [ ] Descargar automáticamente los modelos voz de VOSK
- [ ] Descargar automáticamente las imágenes de cada personaje
- [ ] Descargar automáticamente el pth e index de cada personaje ( descomprir el zip )
- [ ] Descargar automáticamente los gameplays al bucket de gameplays.

### Docker Compose
- [ ] Hacer que todos los contenedores se reinicien automáticamente si se caen  (restart: unless-stopped)

### Testeo General
- [ ] Testear que el docker compose funcione sin intervención manual para arreglar errores en una máquina nueva que nunca ejecutó los contenedores.

## Sprint 2: Errores Generales [PLANEACIÓN]

### Objetivo
Este sprint tiene como objetivo corregir errores que hacen que el sistema falle o se rompa.

- [ ] Cuando se envían cero o menos imágenes no se debe renderizar nada, también hay que hacer un catch de ZeroDivisionError
- [ ] Subtitle generator no renderiza si el nombre es muy largo
- [ ] Agregar un limite de imágenes a los videos
- [ ] Parsear los datos que se ponen en el frontend para que solo devuelva ASCII válido.

