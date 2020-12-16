# TAREA #1

Primera tarea real. Fácil. Son pocas cosas que agregar.

## DETALLES

Basado en el proyecto realizado en clase, debe **crear 3 nuevas secciones** (<section>).

## Especificaciones / Requerimientos

- Crear 3 sections nuevos. (abajo del que ya está hecho, no borre nada)
- Cada section tendrá un color de fondo diferente y único (no se pueden repetir).
- Cada section va a tener un (1) *ÚNICO .container <div>*
- Cada *container* va a teber *una (1) ÚNICA fila (.row)*.
- **No puede cambiar el padding de ningún row**, en ningún section. Todos tienen el mismo padding.
- Cada *row* de cada section tendrá una **cantidad de columnas diferente** a las demás.
- Los **cols de cada row-section**, tendrán un **margin diferente** a las otras rows-sections. (Ver detalles de cada section abajo)
- Los cols de todos los rows **deben calzar exacto al 100% del ancho del row**
- Todas las medidas deben ser en pixeles (px).

## Detalles de cada section a crear

1. Hacer 1 section con *2 columnas*, *cada una* de esas 2 columnas tendrá *margin: 0 40px*. (El HTML ya está agregado para referencia, el CSS no)
2. Hacer 1 section con *4 columnas*, *cada una* de esas 4 columnas tendrá un *margin: 0 10px*
3. Hacer 1 section con *6 columnas*, *cada una* de esas 6 columnas tendrá un *margin: 0 5px* (tricky, no es un número exacto el resultado)

### Notas

- En el CSS, la tarea empieza en la línea 67.
- No puede cambiar nada del código ya existente para el container, ni para los rows.
- Si necesita agregar algo, debe crear una nueva clase.
- El contenido adentro de cada columna (en todas) es irrelevante. Puede copiar y pegar los .card en todas las columnas.

### Tips

- Lo único que debería tener que cambiar es agregar una clase adicional a las columnas, dependiendo de su tamaño (one-third, one-fourth, one-half, one-sixth).
- A esas clases de columna nuevas sobreescribirle el ancho y el margin (basado en los detalles descritos anteriormente)
- Hacer los calculos necesarios para que calcen exacto dentro de la fila, basados en la cantidad de columnas y el margin de cada una.
