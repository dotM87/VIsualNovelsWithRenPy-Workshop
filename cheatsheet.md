# Cheatsheet de Ren'Py - Sintaxis Básica

## Etiquetas:

```renpy
label inicio:
    "Este es el comienzo del juego."
    jump siguiente_etiqueta
```
## Saltos condicionales:
```renpy
if variable >= 5:
    "La variable es mayor o igual a 5."
else:
    "La variable es menor que 5."
```
## Mostrar texto:
```renpy
"Hola, ¿cómo estás?"
"¡Bienvenido al juego!"
```
## Asignación de variables:
```renpy
$ nombre = "John Doe"
$ edad = 25
```
## Condicionales en línea:
```renpy
"¡Eres mayor de edad!" if edad >= 18 else "Eres menor de edad."
```
## Opciones:
```renpy
menu:
    "Elige una opción:"
    "Opción 1" [jump etiqueta_opcion_1]
    "Opción 2" [jump etiqueta_opcion_2]
end
```
## Reproducir música:
```renpy
play music "musica_fondo.ogg"
```
## Reproducir sonidos:
```renpy
play sound "efecto_sonido.ogg"
```
