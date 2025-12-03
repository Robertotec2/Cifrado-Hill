# Cifrado-Hill
Esta tarea tiene como objetivo evaluar sus habilidades de programación, gestión de versiones utilizando Git/GitHub, y documentación de proyectos. Deberán implementar el algoritmo de Cifrado Hill en un repositorio de GitHub, personalizar su diseño y funcionalidad, y presentar el proyecto en una página web.


##Nombre Completo del Alumno: Roberto Balmes Solis
##Grupo: 1C
##Materia: Álgebra



## Cómo ejecutar (desarrollo)
### Requisitos
- Java 11+ y Maven (para el backend)
- Node.js 16+ y npm (para el frontend/server)

### Backend (Java)
1. Ir a la carpeta `backend` y compilar:
   ```bash
   cd backend
   mvn clean package
   java -jar target/tu-app.jar




   Cómo funciona:

Eliges una matriz clave, por ejemplo:

3	3
2	5

Convierte cada letra a número:

A = 0

B = 1

…

Z = 25

Tomas el mensaje de dos en dos (si tu matriz es 2×2).

Multiplicas la matriz por cada par de números.

Al resultado le aplicas módulo 26 (para que vuelva a ser una letra).
