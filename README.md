# Sorting Algorithms Comparison

![image](https://github.com/AkarisDimitry/SortingMethodsBenchmark/assets/34775621/ace04ddb-6114-452f-a930-7cedc5d6d540)

Este repositorio contiene una implementación y análisis de varios algoritmos de ordenamiento en Python, incluyendo Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort, Heap Sort, Counting Sort, Radix Sort, Bucket Sort y Tim Sort. El código incluye funciones para visualizar el tiempo de ejecución de cada algoritmo en diferentes tamaños de lista, así como una función para visualizar el progreso de un algoritmo de ordenamiento en tiempo real. El objetivo es proporcionar una herramienta de referencia y análisis para la comparación del rendimiento de diferentes algoritmos de ordenamiento.

## Algoritmos de Ordenamiento

A continuación se describen brevemente los algoritmos de ordenamiento implementados en este repositorio.

1. **Bubble Sort**: Compares and swaps adjacent elements until the list is sorted.
2. **Selection Sort**: Divides the list into a sorted and an unsorted region, and repeatedly selects the smallest element from the unsorted region and moves it to the sorted region.
3. **Insertion Sort**: Builds the sorted list one element at a time by inserting each element into its correct position in the already sorted list.
4. **Merge Sort**: Recursively divides the list into two halves, sorts them, and then merges the sorted halves.
5. **Quick Sort**: Selects a 'pivot' element and partitions the other elements into two sub-arrays based on the pivot, and then sorts the sub-arrays recursively.
6. **Heap Sort**: Builds a heap from the input list and utilizes the properties of the heap to sort the list.
7. **Counting Sort**: Sorts integers by counting the occurrences of each integer in the input list.
8. **Radix Sort**: Sorts integers digit by digit, using Counting Sort as a subroutine.
9. **Bucket Sort**: Divides the interval of sorted values into buckets, sorts each bucket, and gathers the sorted values.
10. **Tim Sort**: A hybrid sorting algorithm derived from Merge Sort and Insertion Sort.

## Comparación del Orden de Complejidad

- **Bubble Sort, Selection Sort, Insertion Sort**: \(O(n^2)\)
- **Merge Sort, Heap Sort, Tim Sort**: \(O(n \log n)\)
- **Quick Sort**: \(O(n^2)\) worst-case, \(O(n \log n)\) average-case
- **Counting Sort**: \(O(n + k)\)
- **Radix Sort**: \(O(nk)\)
- **Bucket Sort**: \(O(n + n^2/k + k)\)

## Dependencias

Este código depende de las siguientes bibliotecas de Python:

- `random`
- `numpy`
- `matplotlib`

## Cómo Ejecutar

1. Clona este repositorio: `git clone https://github.com/yourusername/SortingAlgorithmsComparison.git`
2. Cambia al directorio del repositorio: `cd SortingAlgorithmsComparison`
3. Instala las dependencias: `pip install numpy matplotlib`
4. Ejecuta el código: `python sorting_algorithms.py`

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre una solicitud de extracción (pull request) con tus cambios.

## Licencia

Este código se encuentra bajo la licencia MIT.

## Contacto

Si tienes preguntas o comentarios, por favor abre un problema en este repositorio.

