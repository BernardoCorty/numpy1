# numpy1
Python Open Data Science Stack - Numpy1
# instalando o numpy
import numpy as np
# checking version of Nunpy
np.__version__
# array criado a partir de uma lista
vetor1 = np.array([0, 1, 2, 3, 4, 5, 6, 7, 8])
print(vetor1)
type(vetor1)
# método para calcular a soma acumulada
vetor1.cumsum()
# criando uma lista. Com a tecla Tab é possível ver a diferença no nº de funções.
lst = [0,1,2,3,4,5,6,7,8]
# imprimindo na tela um valor específico do array
vetor1[0]
# changing an element of array
vetor1[0] = 100
