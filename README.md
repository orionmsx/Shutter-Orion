# Shutter-Orion

Simple juego matamarcianos para MSX con fines educativos. Está escrito en MSX-Basic, y se trata de una pequeña evolución del original 
de Raúl Portales, incluido en su libro "[Desarrollo moderno de juegos en MSX-Basic](https://github.com/plattysoft/Modern-MSX-BASIC-Game-Dev)".

![Pantalla de inicio](https://github.com/orionmsx/Shutter-Orion/blob/master/inicial.png)
![Pantalla de juego](https://github.com/orionmsx/Shutter-Orion/blob/master/juego.png)

## Controles
Cursores y barra espaciadora para disparar

## Funcionalidades añadidas al original
- Pantalla de inicio
- Vidas
- Marcador
- Record de puntuación
- Explosión de la nave con sonido
- Marco de la pantalla de juego

## Notas sobre el código
Para el desarrollo he usado el plugin [Basic Dignified Suite](https://github.com/farique1/basic-dignified) para Sublime Text, por lo que hay que tener en cuenta:
- Los archivos .amx son código MSX-Basic normal y corriente, como si se tratara de un .BAS cualquiera.
- Los archivos .bmx son código MSX-Basic tokenizado, para que corra más rápido. Son los que vamos a invocar.

Por otra parte, al igual que Raúl, he usado MSX Kun Basic para acelerar.
