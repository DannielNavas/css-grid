# CSS GRID

 - Contenedor es el elemento que se convierte en una linearGradient
 - los items son los elementos que estan dentro del contenedor
 - las lineas limitan o dividen los elementos de las grids 
 - las filas de arriba hacia abajo
 - rows y colums
 - celdas es la unidad minima que puede tener una grid 
 - se pueden crear grupos de celdas  pueden ser track o areas 
 - los tracks son los grupos de celdas que estan en una misma fila o misma columna
 - las areas pueden usuar varias filas y varias columnas a la vez


## Propiedades del contenedor 
    - Display grid
    - grid-template
    - gaps
    - grid-auto

nos permiten crear una grid definir la cantidad de columnas y filas y definir los espaciados entre las filas y columnas


## propiedades de alineación de los items
    - justify-items
    - align-items
    - place-items

    - justify-self
    - align-self
    - place-self

## propiedades de alineación del contenedor
    - justify-content
    - align-content
    - place-content


## propiedades de ubicación
    - grid-column-start
    - grid-column-end
    - grid-column

    - grid-row-start
    - grid-row-end
    - grid-row

    - grid-area
        donde inicia y donde termina la fila y la columna


## Funciones especiales
    - minmax
        tamaño minimo y maximo de una celda
    - repeat
        
## keywords especiales 
    - fr
        fraccion para darle alto o ancho a filas y columnas es una fracción de la grid se declara la cantidad de fracciones que se van a usar
    - min-content
        ajusta el ancho de la celda para que se tenga la columna lo mas fina que se pueda sin romperla
    - max-content
        enzanchar la columna o crecer las filas
    - auto-fill/ auto-fit
        ayudan para que la grid ocupen el 100% del tamaño que tienen 
