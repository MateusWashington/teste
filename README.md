# teste
# produto = input('Digite qual o produto: ')
gramatura = int(input('Digite a gramatura do produto: '))
porcao_dia = int(input('Quantas porções por dia você vai consumir ?'))
peso_porcao = int(input('Qual o peso da porção (em gramatura) ?'))

consumo_diario = porcao_dia * peso_porcao

duracao_dias = gramatura // consumo_diario

print (f'O produto {produto} durará aproximadamente {duracao_dias} dias')
