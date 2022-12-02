----
# MEDIA (PROMEDIO) ($\bar x$)
## Media aritmética (MA)
### Media aritmética para datos no agrupados
Cual es la formula para el promedio o media aritmética para datos no agrupados ($M.A$.) ?
$$\overline{x}=\overline{MA}=\dfrac{\sum_{i=1}^n x_i}{n}=\dfrac{x_1+x_2+x_3+...+x_n}{n}$$
Compara tu respuesta con la formula anterior, y califícate honestamente.

### Media aritmética para datos agrupados
Cual es la formula para el promedio o media aritmética para datos agrupados ($M.A$.) ?
$$\overline{x}=\overline{MA}=\dfrac{\sum_{i=1}^n(x_i \cdot f_i )}{n} = \sum_{i=1}^n x_ih_i$$
Compara tu respuesta con la formula anterior, y califícate honestamente.
### Media aritmética ponderada (PP)
$$PP=\dfrac{\sum_{i=1}^{n}x_i \cdot p_i}{\sum_{i=1}^{n} p _i}= \dfrac{x_1 \cdot p_1 + x_2 \cdot p_2 + x_3 \cdot p_3 + ... + x_n \cdot p_n}{p_1+p_2+p_3+...+p_n}$$
## Media geométrica (MG)
$$\bar  x = \overline{MG} = \left( \prod _{i=1}^n \right) ^{\dfrac{1}{n}} = \sqrt[n]{\prod _{i=1}^n} = \sqrt[n]{x_1 \cdot x_2 \cdot x_3 \cdot \cdot \cdot x_n}$$
## Media armónica (MH)
$$\bar x = \overline{MH} = n \left( \sum_{i=1}^n \cfrac{1}{x_i} \right)^{-1} \cfrac{n}{\sum_{i=1}^n \dfrac{1}{x_i}} = \cfrac{n}{\dfrac{1}{x_1}+ \dfrac{1}{x_2}+ \dfrac{1}{x_3} +\cdots+\dfrac{1}{x_n}}$$

## Propiedades de Promedios
+ Cuando todos los datos son siempre positivos, se cumple:
$$MH \leq MG \leq MA$$
+ Para dos números a y b (a > b > 0), se cumple:
$$MG^2 = MA \cdot MH$$

----

# MEDIANA
## Mediana para datos no agrupados
### Mediana (cantidad de datos impar)
Cual es la formula para el promedio o media aritmética para datos no agrupados ($M.A$.) ?
**revisar teoría de otras fuentes**
Compara tu respuesta con la formula anterior, y califícate honestamente.

### Mediana (cantidad de datos par)
Cual es la formula para el promedio o media aritmética para datos no agrupados ($M.A$.) ?
**revisar teoría de otras fuentes**
Compara tu respuesta con la formula anterior, y califícate honestamente.
## Mediana para datos agrupados
Cual es la formula para calcular la mediana de un conjunto de datos agrupados ($Me$) ?
$$Me = L_i + c \left( \dfrac{\dfrac{n}{2}-F_{i-1}}{f_i} \right)$$
donde:
+ $L_i$: límite inferior de la clase de la mediana
+ $f_i$: frecuencia absoluta de la clase de la mediana
+ $n$: cantidad de datos
+ $c$: ancho de clase
+ $F_{i-1}$: frecuencia absoluta acumulada de la clase anterior al intervalo de la mediana.

Compara tu respuesta con la formula anterior, y califícate honestamente.

-----

# MODA (Mo)
## Moda para datos no agrupados
**Que es la moda ?**
La moda es el dato que tiene mayor frecuencia, es decir, es el dato que más veces se repite.

## Moda para datos agrupados
**Cual es la fórmula para calcular la moda de un conjunto de datos agrupado?**
$$Mo = L_i + c\left(  \dfrac{d_1}{d_1+d_2} \right)$$
donde:
+ $L_i$: límite inferior de la clase de la moda
+ $c$: ancho de clase
+ $d_1 = f_i - f_{i-1}$: diferencia entre las frecuencias de la clase modal con la clase anterior.
+ $d_2 = f_i - f_{i+1}$: diferencia entre las frecuencias de la clase modal con la clase siguiente.

Compara tu respuesta con la formula anterior, y califícate honestamente.
