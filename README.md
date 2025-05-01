Ejercicio 1 – Operaciones Vectoriales
Se emplean funciones de NumPy como np.dot, np.cross y np.linalg.norm para calcular productos escalares, productos cruzados y normas. También se usa Matrix de SymPy para realizar una descomposición ortogonal de vectores.

Ejercicio 2 – Criptografía con Matrices
Se utilizan np.linalg.inv y np.matmul para invertir la matriz de codificación y decodificar el mensaje. Posteriormente, se redondea con np.round y se aplica módulo 27 para mapear los números a letras del alfabeto.

Ejercicio 3 – Determinante Simbólico
Se emplea Matrix.det() de SymPy junto con simplify para obtener el determinante simbólico. Luego se usa solve con Eq para resolver ecuaciones en función de un parámetro 
𝑘
k.

Ejercicio 4 – Área de un Triángulo
Se usa Matrix.det() para aplicar la fórmula del área mediante determinantes. En el inciso b, se plantea una ecuación cuadrática con solve para encontrar valores de 
𝑘
k que satisfagan un área específica.

Ejercicio 5 – Coordenadas en Base
Se construye una matriz con Matrix.hstack y se determina su rango con Matrix.rank(). Para resolver el sistema lineal y encontrar coordenadas del vector en la base, se aplica LUsolve.

Ejercicio 6 – Estructura Algebraica
Se realizan operaciones personalizadas usando NumPy, simulando definiciones alternativas de suma y producto escalar. Se verifica la estructura con operaciones básicas para concluir que no se cumple la definición de espacio vectorial.
