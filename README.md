# github-desafio-primeiro-repositorio
Desafio sobre Git/GitHub

# Cria uma matriz vazia de 5x5
matriz = [[0 for _ in range(5)] for _ in range(5)]

# Pede ao usuário para preencher a matriz
for i in range(5):
    for j in range(5):
        matriz[i][j] = int(input(f"Insira o valor para a linha {i+1}, coluna {j+1}: "))

# Imprime a matriz
for linha in matriz:
    print(linha)
