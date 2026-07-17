## Integrantes del proyecto:

- Luis-Felipe Guajardo Torres
- Pablo Morales Carvallo
- Francisco Bahamondes Castro
- Gabriel Lafertte Cárcamo \# \* Diego Meléndez Córdova

## Instalación de paquetes

Este proyecto usa renv para manejar los paquetes de R. Al clonar el repo, abre el proyecto en RStudio con el archivo .Rproj y ejecuta renv::restore() en la consola (NO la terminal): eso instala automáticamente todos los paquetes en las versiones correctas, sin tener que instalarlos a mano.

Si más adelante alguien agrega un paquete, debe correr renv::snapshot() para registrarlo, y el resto solo vuelve a ejecutar renv::restore() después de hacer ungit pull.
