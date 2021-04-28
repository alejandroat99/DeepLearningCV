# Desarrollo de Herramientas Formativas sobre Redes Neuronales aplicadas a la Visión por Computador

Este proyecto tiene como objetivo proporcionar una labor formativa en el ámbito del Deep Learning enfocándose
en el área de la Visión por Computador. En este repositorio se encuentran los cuadernos de trabajo desarrollados
que contienen todos los conceptos y fundamentos teóricos necesarios para comprender esta área, así como actividades
prácticas planteadas para aplicar los conocimientos obtenidos.

## Estructura
Los cuadernos se encuentran clasificados en tres grandes bloques:
1. Bloque de Fundamentos
2. Bloque de Aplicaciones Prácticas
3. Bloque de Proyectos

### Bloque de Fundamentos
Este bloque está centrado en explicar los conceptos y fundamentos teóricos de las redes neuronales y el Deep Learning,
se realizarán activades sencillas para mostrar ilustrar los conocimientos proporcionados y se desarrollarán redes
neuronales básicas para solucionar los problemas genéricos de esta área: clasificación binaria, clasificación multiclase
y regresión.

### Bloque de Aplicaciones Prácticas
Este bloque se centrará más en el uso de las redes neuronales en la resolución de problemas de Visión por Computador. Los
problemas a resolver estarán basados en redes neuronales convolucionales y aplicados desde el procesamiento de la imagen
hasta la detección de objetos.

### Bloque de Proyectos
Este bloque propone algunos proyectos interesantes a realizar que aplican todo lo aprendido en los bloque anteriores,
centrándose en el encadenamiento de técnicas para resolver los problemas planteados.

## Requisitos Técnicos
- Docker

## Ejecución
Los siguientes pasos a siguientes pasos son para la primera ejecución del contenedor docker

1. Descargar el contenido del repositorio
2. Construir la imagen docker desde la carpeta del repositorio: `docker build -t <image-name> .`.
3. Ejecutar la imagen docker: `docker run -d -v <path-absoluto-repositorio>:/home/appuser/src -p <port>:8888 <image-name>`.
4. Acceder a la dirección: `127.0.0.1:<port>` y consultar en la consola de docker el token de acceso.
5. Ejecutar `docker ps` para ver el nombre del contenedor que se está ejecutanto

Para ejecuciones posteriores tan solo debemos volver a ejecutar el contendor docker que se creo con los pasos anteriores.
Esto se puede hacer desde la aplicación _Docker Desktop_ o desde la consola del equipo con el comando
`docker start <container-name>`.