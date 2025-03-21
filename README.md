# Documento de Visión Inicial

## Índice

- [**Integrantes**](#integrantes)
- [**Tema**](#tema)
- [**Desarrollo**](#desarrollo)
- [**Tareas**](#tareas)
- [**Clases**](#clases)
- [**Tecnologías y Librerías**](#tecnologías-y-librerías)
- [**Funciones**](#funciones)
- [**Estructura**](#estructura)

## Integrantes

- **Ronald Sardiñas González**
- **Christopher Lázaro Sablón Suárez**
- **Guillermo León Rodríguez**
- **Brian Ramírez Enríquez**
- **Dassiel Ernesto Quintero Rubido**

## Tema

``Lechugas del Caos: El Jardín de los Enigmas``

## Desarrollo

>Basándonos en el desarrollo incremental, o sea, construir el programa en pequeñas partes hasta obtener la versión completa, crearemos un juego simple y le iremos añadiendo mecánicas y funciones hasta obtener el resultado deseado.

## Tareas

- ``Ronald``: Creación de los personajes y todo lo relacionado a ellos.
- ``Christopher``: Creación de los enemigos, peligos y todo lo relacionado a ellos.
- ``Guillermo``: Creación de los mundos con sus mapas y acertijos.
- ``Brian``: Creación de toda la UI de los menúes.
- ``Dasiel``: Creación de los sprites y las animaciones.

## Clases

- ``Main``: Añade los elementos (personajes, mapas, etc.) a la ventana del juego y lanza esta última.
- ``Character``: Usada para crear un personaje con sus distintas características.
- ``Hero``: Extiende de Character y añade los atributos específicos de un héroe.
- ``Enemy``: Extiende de Character y añade los atributos específicos de un enemigo.
- ``WorldMap``: Crea el mapa del mundo.
- ``Options``: Crea el menú de opciones del juego.
- ``MainMenu``: Crea el menu de inicio del juego que permite elegir el nivel e iniciar el juego.

## Tecnologías y Librerías

- ``JavaFX``: Librería de Java para crear interfaces gráficas.
- ``SceneBuilder``: Programa que permite crear interfaces de JavaFX arrastrando y soltando elementos.
- ``Gradle``: Herramienta de Java que permite construir el proyecto para su distribución.
- ``VS Code``: IDE multipropósito que permite programar de manera esficiente en Java.
- ``Gimp``: Software Open Source que permite la edición y creación de imágenes, en este caso, sprites.

## Funciones

- Movimiento en 4 direcciones (arriba, abajo, derecha e izquierda).
- Multijugador con hasta 5 jugadores simultáneos.
- Varios personajes  y enemigos con habilidades y ataques únicos.
- Enigmas en cada mundo.
- Movimientos por turno.
- Gráficos 2D, con barra de habilidades, minimapa y animaciones.

## Estructura

``` plaintext
LechugasDelCaos/
│── src/
│   ├─ main/
│      ├── java/
│      │   ├── com/lechugasdelcaos/
│      │       ├── app/  
│      │       ├── controllers/
│      │       ├── models/       
│      │       ├── views/
│      ├── resources/
│── build.gradle
│── README.md
│── .gitignore
```

- ``app``: Punto de entrada del juego.
- ``controllers``: Lógica de la UI y el juego.
- ``models``: Clases del juego (personajes, enemigos, tablero).
- ``views``: Renderización de la UI.
- ``resources``: Recursos gráficos.
- ``build.gradle``: Configuración de gradle.
- ``README.md``: Descripción del proyecto.
- ``.gitignore``: Archivos a excluir en Git.
