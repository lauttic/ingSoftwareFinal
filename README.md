# Final Ingeniería de Software

Proyecto final de la materia **Ingeniería de Software**.

La aplicación muestra los datos del alumno y se ejecuta dentro de un contenedor Docker.

## Ejecución del proyecto

### 1. Construir la imagen Docker

Desde la carpeta del proyecto ejecutar:

docker build -t final-ingsoft .

### 2. Ejecutar el contenedor

docker run -d -p 8080:80 --name final-ingsoft-container final-ingsoft


### 3. Acceder a la aplicación

Abrir el navegador y acceder a:

http://localhost:8080

## Control de versiones

El proyecto utiliza Git para el control de versiones y fue subido a un repositorio remoto en la rama **main**, realizando múltiples commits durante el desarrollo.

## Autor

- Nombre y Apellido: Lautaro Nahuel Corceiro  
- Materia: Ingeniería de Software
- Fecha: 17 de Diciembre de 2025

