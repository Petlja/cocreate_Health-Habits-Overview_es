# ¿Cómo crear una tabla dinámica?

```{infonote}
**Cuatro elementos básicos de una tabla dinámica**

- **Filas (*Rows*)** - Categorías que se muestran en el lado izquierdo de la tabla.
- **Columnas (*Columns*)** - Categorías que se muestran en la parte superior de la tabla.
- **Valores (*Values*)** - Números que se calculan (suma, conteo, promedio…).
- **Filtros (*Filters*)** - Permiten mostrar solo una parte de los datos.
```

## Crear una tabla dinámica: paso a paso

### Paso 1: Seleccione la tabla con los datos
Haga clic en cualquier celda de la tabla y en el teclado presione la combinación de teclas *Ctrl + A*

![Paso 1](images/pivot1_sr.png)

### Paso 2: Inicie la creación de la tabla dinámica
Haga clic en *Insert* (1), *PivotTable* (2) y elija la opción *From Table/Range* (3)

![Paso 2](images/pivot2_sr.png)

### Paso 3: Elija dónde desea que se ubique su tabla dinámica
Puede elegir una nueva hoja de trabajo (*New Worksheet*) o una ubicación en la misma hoja (*Existing Worksheet*) (4) (en ese caso debe hacer clic en la celda en la que se ubicará la esquina superior izquierda de su tabla dinámica) (5). Confirme con un clic en *Ok*. (6)

![Paso 3](images/pivot3_sr.png)

### Paso 4: Conozca el editor de tablas dinámicas
Ajusta la tabla dinámica arrastrando los campos (7) a las zonas correspondientes (8).

![Paso 4](images/pivot4_sr.png)

### Paso 5: Agregue filas (*Rows*) y valores (*Values*)
Para el primer ejemplo de la introducción, arrastramos el campo *воће* a la zona *Rows*. A la zona *Values* arrastramos el campo *количина [kg]*

![Paso 5](images/pivot5_sr.png)


```{infonote}
Podemos cambiar el modo de cálculo en el área Values mediante la opción Value Field Settings. Además de la suma predeterminada (Sum), también están disponibles Average (promedio), Count (número de registros), Min y Max. Es importante saber que, si se coloca un campo de texto en el área Values, la tabla dinámica mostrará automáticamente el número de apariciones de ese texto (Count) en lugar de la suma.
```

### Paso 6: Agregue columnas (opcional)
La tabla en la que también se ve de qué manera pagaron los clientes se obtuvo agregando el campo *начин плаћања* a la zona Columnas (*Columns*) (10)

![Paso 6](images/pivot6_sr.png)

```{infonote}
Si ocurre que se cerró la ventana de la derecha que permite configurar la vista de la tabla dinámica, puede volver a abrirla haciendo clic en cualquier celda de la tabla dinámica y seleccionando la opción Show field list.
```
### Paso 7: Agregue filtros (opcional)
Agregar filtros le permitirá seleccionar rápidamente de una gran cantidad de datos y mostrar solo aquellos valores que necesita en ese momento, sin modificar la tabla original ni hacer cálculos adicionales. 

```{infonote}
Aunque la tabla dinámica está vinculada a la tabla original, los cambios en ella no se actualizan automáticamente. Después de cada modificación es necesario hacer clic derecho sobre la tabla dinámica y elegir la opción Refresh para actualizar todos los resultados.
```
## Gráfico dinámico

Los datos de la tabla dinámica también se pueden mostrar de forma gráfica. De este modo, los resultados son más claros y las diferencias y relaciones se observan con mayor facilidad.

El gráfico dinámico se crea de la siguiente manera:

Haga clic dentro de la tabla dinámica y, en el menú, elija la opción *PivotChart*. Seleccione el tipo de gráfico y confirme la elección.

![Gráfico dinámico](images/chart1_sr.png)

```{infonote}
El gráfico está vinculado a la tabla dinámica, lo que significa que cualquier cambio en la tabla se refleja automáticamente también en el gráfico. Al presentar los datos gráficamente, las ventajas de aplicar filtros se hacen especialmente evidentes.
```

![Gráfico dinámico](images/chart2_sr.png)