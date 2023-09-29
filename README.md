# MovieApp-180247
![Banner-de-Twitch-Nubes-Gamer-Chica-Morado.png](https://i.postimg.cc/15q3LFXF/Banner-de-Twitch-Nubes-Gamer-Chica-Morado.png)
## Información General

- **Creado por:** Lesly Yareth Hernández Bonilla 
- **Asignatura:** Desarrollo Movil Integral
- **Grado:** 10
- **Grupo:** A
- **Docente:** MTI. Marco Antonio Ramirez Hernandez

## Descripción del Proyecto

Se desarrollo una aplicación que muestra una página de inicio que contiene un catálogo de películas que se encuentran en el cine a punto de estrenar o bien que ya fueron estrenadas.  La aplicación cuenta con los siguientes puntos:

### 1. Barra de Navegación Superior

La AppBar muestra el título "MovieApp" en el centro y un icono de búsqueda en la esquina derecha. 

### 2. Menú Lateral (Drawer)

El menú lateral se abre deslizando desde el borde izquierdo de la pantalla o tocando el icono de menú en la AppBar. Contiene las siguientes opciones:

- **"peliculas"**
- **"Television"**
- **"Cerrar"**

### 3. Barra de Navegación Inferior (BottomNavigationBar)

La barra de navegación inferior contiene tres elementos:

- **"populares"**: Muestra películas populares y tiene un ícono de pulgar hacia arriba.

- **"Proximamente"**: Muestra películas próximas a estrenarse y tiene un ícono de actualización.

- **"Mejor valorados"**: Muestra películas mejor valoradas y tiene un ícono de estrella.

### `media_list.dart`

Este archivo contiene la definición de la clase `MediaList`, que es un StatefulWidget que representa una lista de medios. Actualmente, en el método `build`, devuelve un contenedor vacío. Puedes personalizar esta parte para mostrar la lista de medios.

### `HttpHandler.dart`

El archivo `HttpHandler.dart` contiene la lógica para realizar solicitudes HTTP y obtener datos de películas desde una API. Define la clase `HttpHandler`, que tiene métodos para obtener datos JSON y `fetchMovies`.

### `Constants.dart`

El archivo `Constants.dart` define una constante `API_KEY`, que se utiliza en `HttpHandler.dart` para autenticar las solicitudes a la API.

## Uso de Fuente Personalizada

La aplicación utiliza un estilo de fuente personalizado (`customTextStyle`) que se define en el código. Esta fuente personalizada se especifica en el archivo `pubspec.yaml` y se aplica a los elementos de texto en la aplicación para darle un aspecto distintivo.

<!-- ## Capturas de Pantalla

[![Captura de Pantalla 1](./assets/1.jpeg)](./assets/1.jpeg)
[![Captura de Pantalla 2](./assets/2.jpeg)](./assets/2.jpeg)
[![Captura de Pantalla 3](./assets/3.jpeg)](./assets/3.jpeg) -->

## Instalación

Para ejecutar esta aplicación en tu entorno de desarrollo, sigue estos pasos:

1. Asegúrate de tener Flutter y Dart instalados en tu sistema.

2. Clona este repositorio o descarga el código fuente.

3. Abre una terminal en la carpeta del proyecto.

4. Ejecuta `flutter pub get` para obtener las dependencias.

5. Ejecuta `flutter run` para iniciar la aplicación en un emulador o dispositivo físico.


Este proyecto es un ejemplo sólido de una página de inicio en Flutter que utiliza elementos de interfaz de usuario personalizados y estilos de fuente únicos. Si tienes alguna pregunta o necesitas ayuda ad
