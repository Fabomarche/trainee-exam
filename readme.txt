Dada la siguiente problemática: ¿puede un número X formarse
usando la suma de 2 elementos de un array?
Ejemplo 1
Input: nums = [1,4,3,9], requiredSum = 8
Output: False
Ejemplo 2
Input: nums = [1,2,4,4], requiredSum = 8
Output: True
Desarrolle (en pseudo código o su lenguaje de preferencia):
1. Un algoritmo que resuelva el problema asumiendo que la máquina en donde va a correrse el
programa tiene recursos infinitos, que el tiempo de ejecución no importa y que lo más
importante es realizar el desarrollo en el menor tiempo posible.
2. Un algoritmo que resuelva el problema asumiendo que los recursos son un bien preciado,
que el tiempo de ejecución si importa y que el tiempo de desarrollo no es importante.

-----------------------------------------------------------------------------------------

resuelto con JavaScript ejecutado en Node v20.7.0

isRequiredSum = programa tiene recursos infinitos = O(n^2)
isSumOptimized = el tiempo de ejecución si importa = O(n)

isRequiredSumMap = es una versión en la que se emplea .map() en lugar de un bucle for, demostrando ser la opción más óptima para arrays de longitud reducida. No obstante, su eficiencia disminuye al enfrentarse a arrays más extensos. 

Según mi investigación, he llegado a las siguientes conclusiones:
O(n) significa que el tiempo de ejecución crece linealmente con el tamaño de la entrada, mientras que O(n^2) significa que crece cuadráticamente. En términos prácticos, al tratar con grandes cantidades de datos, O(n) es mucho más eficiente que O(n^2).

Se incorporó console.time para analizar los tiempos de ejecución y extraer conclusiones.
