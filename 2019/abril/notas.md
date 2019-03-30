# Notas:
## Tablero de Ludo, toma 1:
Explicación: Dibujo un solo cuadrado "Dibujar cuadrado de color Rojo"
### Preguntas: 
 1. Para dibujar solamente el cuadrado de color Rojo, 
 . ¿Cuantos procedimientos definí? 5 (1 para la tarea principal y 4 para las subtareas)
 . ¿Cuáles?  `DibujarCuadradoDeColorRojo()`, `DibujarLíneaRojaHaciaElNorte()`, `DibujarLíneaRojaHaciaElEste()`,`DibujarLíneaRojaHaciaElSur()`, `DibujarLíneaRojaHaciaElOeste()`
 2. Para dibujar los cuadrados de color Rojo y Negro
 . ¿Cuantos procedimientos definí? 10
 . ¿Cuáles? `DibujarCuadradoDeColorRojo()`, `DibujarCuadradoDeColorNegro()`, `DibujarLíneaRojaHaciaElNorte()`, `DibujarLíneaNegraHaciaElNorte()`, `DibujarLíneaRojaHaciaElEste()`,`DibujarLíneaNegraHaciaElEste()`,`DibujarLíneaRojaHaciaElSur()`,`DibujarLíneaNegraHaciaElSur()`, `DibujarLíneaRojaHaciaElOeste()`,`DibujarLíneaNegraHaciaElOeste()`,  `
3. Para dibujar los cuadrados de color Rojo, Negro, Verde y Azul
 . ¿Cuantos procedimientos definí? 20

2. Tablero de Ludo, toma 2: lo explicaría de la siguiente forma:
### Explicación
1. 1ro: 
``` javascript
procedure DibujarCuadrado(colorDelCuadrado) {
  DibujarLíneaNorte(colorDelCuadrado)
  DibujarLíneaEste(colorDelCuadrado)
  DibujarLíneaSur(colorDelCuadrado)
  DibujarLíneaOeste(colorDelCuadrado)
}
```


2. 2do:
``` javascript
procedure DibujarCuadrado(colorDelCuadrado) {
  DibujarLínea(colorDelCuadrado, Norte)
  DibujarLínea(colorDelCuadrado, Este)
  DibujarLínea(colorDelCuadrado, Sur)
  DibujarLínea(colorDelCuadrado, Oeste)
}
```

### Preguntas
1. Para dibujar solamente el cuadrado de color Rojo, 
. ¿Cuantos procedimientos definí? 5 (1 para la tarea principal y 4 para las subtareas)
. ¿Cuáles?  `DibujarCuadrado(colorDelCuadrado)`, `DibujarLínea(colorDeLaLinea, direcciónDeLaLinea)`
2. Para dibujar los cuadrados de color Rojo, Negro
 . ¿Cuantos procedimientos definí? 2 (1 para tarea principal y otro para subtarea)
 . ¿Cuáles?  `DibujarCuadrado(colorDelCuadrado)`, `DibujarLínea(colorDeLaLinea, direcciónDeLaLinea)`
3. Para dibujar los cuadrados de color Rojo, Negro, Azul y Negro
 . ¿Cuantos procedimientos definí? 2 (1 para tarea principal y otro para subtarea)
 . ¿Cuáles?  `DibujarCuadrado(colorDelCuadrado)`, `DibujarLínea(colorDeLaLinea, direcciónDeLaLinea)`

