
# Procedimiento de instalación de Android Studio

## [Características mínimas del equipo](./requisitos.md)

## Prerequisitos

Para instalar Android Studio necesitamos intalar primero el entorno de desarrollo de Java (JDK) en su versión 7

No es suficiente con tener instalado el entorno de ejecución de Java (JRE)

### ¿Tengo Java?

Puedes ver la versión que tienes instalada con 

	javac -version

Dependiendo de la versión del sistema operativo instalado instalaremos el JDK de 32 o 64 bits.

## Instalación de Android Studio

La instalación de Android Studio es bastante sencilla, basta con ejecutarla y el paquete irá revisando si nos falta algún compomente (de no tener instalado el JDK, en este momento nos lo pediría)

## SDK de Android

El SDK de Android es el conjunto de librerías, documentación (también ejemplos), código e imágenes de emuladores necesario para poder desarrollar aplicaciones específicas para una versión dada.

Existe un SDK por cada una de las versiones de Android.

## Gestor de actualizaciones

![gestorSDK](./imagenes/OpcionesSDK.png)

Se requieren:

* Android SDK Tools: son las herramientas generales del entorno.
* Android SDK Platform Tools: la herramientas específicas para cada sistema operativo (por ejemplo el depurador)
* Al menos una de las building Tools (mejor la última). Son las encargadas de construir la aplicación.
* Al menos necesitamos una de las [versiones](./Android FAQ.md#versiones) con los sigueintes componentes obligatorios:
	* SDK Platform
	* Una imagen de emulador
Otros componentes recomendados:
	* Ejemplos (samples)
	* Documentación
