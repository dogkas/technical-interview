# Dogkas: Prueba técnica
> Prueba técnica para Senior Software Developer

## Objetivos de la prueba técnica
- Revisar la capacidad del candidato de interpretar los requerimientos expresados en la prueba técnica
- Revisar la capacidad de solución de problemas del candidato
- Revisar la capacidad del candidato de plantear soluciones tecnológicas acordes y eficientes.
- Manejo y validación de formularios

## Recomendaciones para trabajar con esta prueba técnica
- Tener instalado Angular version 14 o superior
- Tener instalado Node v18 o superior (se recomienda tener instalado NVM)
- Tener instalado MySQL

## Requerimientos y condiciones
- Plazo de entrega son 92hrs hábiles desde la fecha de entrega de la prueba.
- Se debe entregar la prueba técnica finalizada en un repositorio público otorgado al candidato.
- La API Key para Google Maps será provista en un correo al momento de entregar la dirección del repositorio de esta prueba técnica.
- Debes entregar el archivo backup .sql para su evaluación.
- No es necesario desplegar estos artefactos en ningun lugar, sin embargo se considerará como 10 puntos extras.

## Descripción de la prueba
    El objetivo de esta prueba es construir una aplicación básica para guardar clientes con su geolocalización en una base de datos. 
    
#### Back-end
    - Debes crear una API REST con NodeJS 
    - Debe permitir un CRUD de clientes con su geolocalización
    - Debe obtener la latitud y longitud basados en una dirección
    - Crear la base de datos para almacenar los datos del CRUD con MySQL

#### Front-end
    - Se debe generar una aplicación con Ionic y Angular dentro de la carpeta `frontend` que permita mostrar un mapa de Google Maps. Debe funcionar de la siguiente manera
    - Se debe crear un service llamado `ApiService` que permita realizar las llamadas al único endpoint disponible en el backend creado previamente.
    - El componente debe mostrar un mapa utilizando la librería oficial de [Google Maps de Angular](https://www.npmjs.com/package/@angular/google-maps).
    - Se debe ver a los clientes creados como una lista respetando el formato de la imagen. El mapa debe verse en el apartado *image cap* ![image](https://github.com/user-attachments/assets/4cafe624-1548-416c-971d-453a0ab526f0)
    

## Criterios de evaluación
- Creación de API rest
- Creacion de base de datos
- Creación de app Angular con Ionic
- Resolución de problemas

## Preguntas
Las preguntas sobre esta prueba técnica puedes realizarlas a contacto@dogkas.cl y a tu reclutador.
