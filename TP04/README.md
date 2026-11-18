## Convenciones

- Redondeo a 2 decimales, salvo que se indique otra cosa.
- **Decimales intermedios**: arrastro 4 decimales en las cuentas y redondeo a 2 solo al escribir cada resultado.
- Si no se indica otra medida, la distancia es la euclídea.
- K-Means: si un punto empata entre dos centroides, va al cluster de menor número.
- **Iteraciones de K-Means**: una iteración es asignar y después recalcular. El algoritmo para cuando una asignación no cambia respecto de la anterior.
- **Porcentaje del codo**: la bajada de K a K+1, dividida por la SSE de K.
- **Silueta promedio**: promedio los s(i) sin redondear y redondeo el promedio.

Todos los números de esta resolución están verificados con scripts de Python (numpy, scipy, scikit-learn).
