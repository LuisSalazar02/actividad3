# Manual de uso pacman.py

## tiles

El array tiles es una estructura de datos que representa cada uno de los puntos del mapa de juego. Dentro de este array los 1 representan un espacio azul con un punto, mientras que los 0 representan una pared con un recuadro de color negro.

## Control de velocidad fantasmas

Dentro de la función move se usa el array options para describir el posible movimiento que tendrán los fantasmas dentro del juego.

Ejemplo:

```python
options = [
    vector(10, 0),
    vector(-10, 0),
    vector(0, 10),
    vector(0, -10),
]
```

Al cambiar los valores en el array los fantasmas tendrán movimientos más ágiles a través del mapa.
