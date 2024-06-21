
# Expreso Arequipa

## Descripción
Este proyecto fue desarrolado por un grupo de 5 jovenes Universitarios de la carrera de Ing. Informatica de la Universidad Autonoma Juan Misael Saracho.
El proyecto consiste en una aplicación Android y un backend desarrollado en Node.js/NestJS, junto con los esquemas de bases de datos necesarios. La aplicación permite la reserva de voletos para un empresa de de buses interprovinciales "Expreso Arequipa"

## Requisitos
- [Android Studio](https://developer.android.com/studio)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [PostgreSQL](https://www.postgresql.org/) 

## Instalación

### Clonar el Repositorio
Primero, clona el repositorio en tu máquina local:
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio

### Configuración del Backend

1. Navega al directorio del backend:
    
    cd Sistema_Backend

2. Configura las variables de entorno creando un archivo `.env` en el directorio `backend` con el siguiente contenido 

    type: "postgres",
    host: "localhost",
    port: 5432,// cambiar puerto de acuerdo al puerto de su compilador de base de datos
    username: "postgres",//cambiar de acuerdo al nombre de sus usuario de postgres
    password: "contraseña de tu base de datos",
    database: "transportedb",// crea esta base de datos de tu postgres 
    logging: true,

4. Inicia el servidor:

    npm start

### Configuración de la Aplicación Android

1. Abre Android Studio.
2. Selecciona `File > Open` y navega a `tu-repositorio/android`.
3. Permite que Android Studio configure el proyecto y descargue las dependencias necesarias.
4. Conecta un dispositivo Android o inicia un emulador.
5. Compila y ejecuta la aplicación.

### Configuración de la Base de Datos

1. Asegúrate de tener PostgreSQL instalado y en funcionamiento.
2. Navega al directorio `database`:

    cd ../Base_datos


3. Visualizar la base de datos de manera mas espeficica:

    habre script.sql

### Ejecución del Proyecto

Con el backend en funcionamiento y la aplicación Android compilada y ejecutándose, deberías poder interactuar con la aplicación. Asegúrate de que tu dispositivo Android está conectado a la misma red local que el servidor backend o ajusta las configuraciones de red según sea necesario.

## Uso

1. Al entrar al Sistema podras crear tu cuenta con un usuario y tu correro electronico para despues loguearte con ese mismo usuario y contraseña de tu correro.
2. Una ves dentro podras visualizar los diferntes viajes disponibles o cercanos de la empresa y podras reservarlos

## Problemas Comunes

- **Error de conexión con la base de datos**: Asegúrate de que las credenciales y la URL de la base de datos en el archivo `.env` son correctas.
- **Error de compilación en Android Studio**: Verifica que todas las dependencias están instaladas y que tu SDK de Android está actualizado.

## Contribuir

Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (\`git checkout -b feature/nueva-caracteristica\`).
3. Realiza tus cambios y haz un commit (\`git commit -m 'Añadir nueva característica'\`).
4. Sube tus cambios (\`git push origin feature/nueva-caracteristica\`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo demanda de los siguientes jovenes.

Desarrollado por:
- Antonio Fernandez Tapia
- Jorge Eduardo Arequipa Cruz
- Dante Tolaba Coronel
- Fabian Lopez
- Leonel Fernando Villca Ortega
- Felix Ancasi 
