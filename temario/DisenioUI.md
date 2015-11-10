# Proyecto 1: Calculadora

Vamos a comenzar diseñando el interfaz de una calculadora como la siguiente

![calc](./imagenes/AppCalculadora.png)

# Analizando

En primer lugar vamos a analizar los tipos de controles que usaremos:

* Una caja de texto, donde el usuario podrá leer los números. No es necesario que el usuario pueda editar los contenidos.

* Un conjunto de botones con los escribiremos los números y con los que indicamos las operaciones a realizar.

Viendo la disposición de los botones podemos pensar que lo más adecuado es usar una disposición tabular. Eso lo podemos conseguir con el TableLayout

# Layout:

Una Layout es una forma de disponer los controles. Existe diferentes tipos:

* FrameLayout
* AbsoluteLayout
* RelatveLayout
* LinearLayout
* TableLayout

## TableLayout
Está constituido por filas que contienen otros elementos. Dentro de ellas los controles se colocan unos a continuación de los otros