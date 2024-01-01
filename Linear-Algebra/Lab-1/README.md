## <a id='toc1_1_'></a>[Objetivos](#toc0_)

Con esta actividad reforzarás tus conceptos aprendidos hasta el momento en el curso y comenzarás a explorar una de las herramientas para la computación cuántica.

## <a id='toc1_2_'></a>[Pautas de elaboración](#toc0_)

La actividad consiste en familiarizarse con el entorno de Python y con librerías como Numpy. Adicionalmente, usaremos Qiskit, una de las herramientas para la computación cuántica, por lo que la actividad se dividirá en dos partes:

- La primera, en la que hacemos uso de NumPy.
- La segunda, en la que, además, utilizaremos Qiskit.

Para ello, vamos a realizar las operaciones que se han aprendido hasta el momento durante la primera parte del curso, entre ellas: identificar una matriz normal, hermitiana, unitaria y el producto tensorial entre matrices y vectores.

## <a id='toc1_3_'></a>[Operaciones con Matrices](#toc0_)

### <a id='toc1_3_1_'></a>[Utilizando NumPy, Cmath y Math](#toc0_)

Considere las siguientes matrices:

$ A = \begin{bmatrix} 9i & 2+i & 6-2i \\ -2+i & 4i & -7+7i \\ -6-2i & 7+7i & -2i \end{bmatrix} $

$ B = \begin{bmatrix} 1+i & 1+2i & 1+3i \\ 2+i & 2+2i & 2+3i \\ 3+i & 3+2i & 3+3i \end{bmatrix} $

$ C = \begin{bmatrix} 2i & 1+i & 4+i & -2i 
                 \\ -1+i & 3i & 4+7i & 1-i 
                 \\ -4+i & -4+7i & -9i & 3-4i 
                 \\ 2i & -1+i & -3-4i & -5i \end{bmatrix} $

$ D = \begin{bmatrix} i & 0 \\ 0 & 3-5i \end{bmatrix} $

### <a id='toc1_3_2_'></a>[Resultados a Obtener](#toc0_)

1. Forma polar de cada determinante y traza de cada matriz.
2. $2i(\text{det}(D) + \text{tr}(C))AB - (1+i)\det(C)\text{tr}(D)BA$.
3. La inversa de cada matriz, si existe.
4. Usando la definición y, al mismo tiempo, las propiedades de los valores propios, clasifica cada una de las matrices en normales, hermitianas o unitarias.

### <a id='toc1_3_3_'></a>[Utilizando NumPy y Qiskit](#toc0_)

### <a id='toc1_3_4_'></a>[Vectores Estados $C^2: |0\rangle, |1\rangle$](#toc0_)

1. Crear los vectores estados $C^2: |0\rangle, |1\rangle$.
2. Hallar los estados $|+\rangle, |-\rangle, |i+\rangle, |i-\rangle$ y los estados de Bell.

### <a id='toc1_3_5_'></a>[Vectores Estado $C^4$](#toc0_)

1. Encontrar la base computacional de $C^4$, por ejemplo, $|10\rangle$.

### <a id='toc1_3_6_'></a>[Vectores Específicos](#toc0_)

1. Hallar los vectores $\frac{1}{\sqrt{2}}|000\rangle + \frac{1}{\sqrt{2}}|111\rangle$, $\frac{i}{\sqrt{2}}|000\rangle - \frac{1}{\sqrt{2}}|111\rangle$, y $\frac{1}{\sqrt{2}}|000\rangle + \frac{i}{\sqrt{2}}|111\rangle$.

