# Variables de Entorno
### ¿Qué son las variables de entorno?
# COMPLETAR
```
Las variables de entorno son valores que se almacenan en el sistema operativo que se pueden acceder por diferentes aplicaciones o procesos 
```
### Para crear un contenedor con variables de entorno

```
docker run -d --name <nombre contenedor> -e <nombre variable1>=<valor1> -e <nombre variable2>=<valor2>
```

### Crear un contenedor a partir de la imagen de nginx:alpine con las siguientes variables de entorno: username y role. Para la variable de entorno rol asignar el valor admin.
# COMPLETAR
```
docker run -d --name contenedor -e username=1234 -e role=admin nginx:alpine
```
# CAPTURA CON LA COMPROBACIÓN DE LA CREACIÓN DE LAS VARIABLES DE ENTORNO DEL CONTENEDOR ANTERIOR
<img width="1073" height="109" alt="image" src="https://github.com/user-attachments/assets/aa1a5aa6-a20a-48e3-ab23-0ddb0d7cd69d" />
### Crear un contenedor con la imagen de mysql, mapear todos los puertos
# COMPLETAR

```
docker run -P -d --name Mysql-web mysql
```

### ¿El contenedor se está ejecutando?
# COMPLETAR
```
No
```
### Identificar el problema
# COMPLETAR
<img width="1290" height="274" alt="image" src="https://github.com/user-attachments/assets/084d3a4d-de7a-4a41-950f-9178c94e4c72" />

### Para crear un contenedor con variables de entorno especificadas
- Portabilidad: Las aplicaciones se vuelven más portátiles y pueden ser desplegadas en diferentes entornos (desarrollo, pruebas, producción) simplemente cambiando el archivo de variables de entorno.
- Centralización: Todas las configuraciones importantes se centralizan en un solo lugar, lo que facilita la gestión y auditoría de las configuraciones.
- Consistencia: Asegura que todos los miembros del equipo de desarrollo o los entornos de despliegue utilicen las mismas configuraciones.
- Evitar Exposición en el Código: Mantener variables sensibles como contraseñas, claves API, y tokens fuera del código fuente reduce el riesgo de exposición accidental a través del control de versiones.
- Control de Acceso: Los archivos de variables de entorno pueden ser gestionados con permisos específicos, limitando quién puede ver o modificar la configuración sensible.

### Crear un contenedor con mysql, mapear todos los puertos y configurar las variables de entorno mediante un archivo
# COMPLETAR
# CAPTURA CON LA COMPROBACIÓN DE LA CREACIÓN DE LAS VARIABLES DE ENTORNO DEL CONTENEDOR ANTERIOR 

### ¿Qué bases de datos existen en el contenedor creado?
# COMPLETAR
```
show databases;
```  
<img width="563" height="322" alt="image" src="https://github.com/user-attachments/assets/529cd372-f868-44ee-986c-96fc3aef3fba" />


