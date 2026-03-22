import numpy as np

# Matriz de fuerzas (3x3)
fuerzas = np.array([
    [10, 5, -2],
    [3, -6, 4],
    [7, 8, -5]
])

# SUMA DE FUERZA POR FILAS
reacciones_filas = np.sum(fuerzas, axis=1)
# SUMA DE FUERZAS POR COLUMNAS
reacciones_columnas = np.sum(fuerzas, axis=0)

print("Matriz de fuerzas:\n", fuerzas)
print("Reacciones por filas:", reacciones_filas)
print("Reacciones por columnas:", reacciones_columnas)

