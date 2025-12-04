Projeto: Cálculo da Média de um Estudante

Descrição:

Projeto simples usando Python para calcular a média das notas de um estudante ao longo de três trimestres.
O objetivo é aplicar:
uso de dicionários,
iteração com for,
cálculo de soma,
média,
arredondamento com round()

notas = {'1º Trimestre': 8.5, '2º Trimestre': 7.5, '3º Trimestre': 9}

soma = 0
for nota in notas.values():

    soma += nota

media = soma / len(notas)
media = round(media, 1)

print("Média final:", media)


Resultado:
Média final: 8.3
