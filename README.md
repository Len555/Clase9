1. Análisis de Fuerzas
Se utiliza una matriz 3x3 para representar fuerzas en nodos de una estructura.
 Se calculan las reacciones mediante sumatorias.
2. Simulación de fluido
Se modela un fluido en una matriz 3D (3x3x3).
La propagación de presión se simula mediante el promedio de vecinos.
3. Imégenes médicas 3D
Se aplica un filtro de suavizado (promedio) para reducir el ruido en un volumen tridimensional.

4.Sensores
Se analizan datos de sensores (5x5), calculando promedios y desviaciones estándar. 
Se incluye visualización.

5.Transformación de coordenadas
Se aplican transformaciones lineales (rotación) a puntos en un plano cartesiano usando matrices.

Enfoque:
- Uso de `NumPy` permite operaciones vectorizadas eficientes.
- Reducción de bucles explícitos mejora el rendimiento.
- Las estructuras multidimensionales permiten representar sistemas complejos de forma compacta.
- En simulaciones, el uso de vecinos directos reduce complejidad computacional.
