import matplotlib.pyplot as plt
import numpy as np

# Exemplo plotar pontos x e y em um gráfico
x = np.array([1, 2, 3, 4, 5])
y = np.array([2, 8, 15, 6, 11])

# Criando o gráfico de dispersão
plt.scatter(x, y, color='blue', marker='o')
plt.title('Mapa do caminho')
plt.xlabel('Eixo X')
plt.ylabel('Eixo Y')
plt.grid(True)
plt.show()
