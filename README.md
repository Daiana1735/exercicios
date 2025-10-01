# exercicios
exercicio01 - Crie um programa que peça ao usuário o seu nome e exiba a mensagem: 'Olá,
<nome>!'.
R= nome = input("Digite seu nome: ")
print(f"Olá, {nome}!")

exercicio02 - Crie um programa que peça ao usuário um número inteiro e exiba esse número na
tela.
R= numero = int(input("Digite um número inteiro: "))
print(f"O número digitado foi: {numero}")

exercicio03 - Crie um programa que peça dois números inteiros e mostre a soma entre eles.
R= numero1 = int(input("Digite o primeiro número inteiro: "))
numero2 = int(input("Digite o segundo número inteiro: "))
soma = numero1 + numero2
print(f"A soma entre {numero1} e {numero2} é {soma}.")

exercicio04 - Crie um programa que peça a idade do usuário e mostre: 'Você tem X anos'.
R= idade = int(input("Digite sua idade: "))
print(f"Você tem {idade} anos.")

exercicio05 - Crie um programa que leia o preço de um produto e mostre o valor com 10% de
desconto.
R= preco = float(input("Digite o preço do produto: "))
preco_desconto = preco * 0.9
print(f"O preço com 10% de desconto é: R$ {preco_desconto:.2f}")

exercicio06 - Crie um programa que leia a altura e o peso de uma pessoa e mostre o IMC (peso /
altura2).
R=altura = float(input("Digite sua altura (em metros): "))
peso = float(input("Digite seu peso (em kg): "))
imc = peso / (altura ** 2)
print(f"Seu IMC é: {imc:.2f}")

exercicio07 - Crie um programa que leia a temperatura em graus Celsius e converta para Fahrenheit
(F = C * 9/5 + 32).
R=celsius = float(input("Digite a temperatura em graus Celsius: "))
fahrenheit = celsius * 9 / 5 + 32
print(f"A temperatura em Fahrenheit é: {fahrenheit:.2f}°F")

exercicio08 - Crie um programa que leia dois números e mostre a média aritmética deles.
R=numero1 = float(input("Digite o primeiro número: "))
numero2 = float(input("Digite o segundo número: "))
media = (numero1 + numero2) / 2
print(f"A média aritmética entre {numero1} e {numero2} é {media:.2f}")
print(f"A média é {media:.2f}")

exercicio09 - Crie um programa que leia a quantidade de dias, horas, minutos e segundos e converta
tudo para o total em segundos.
R=dias = int(input("Digite a quantidade de dias: "))
horas = int(input("Digite a quantidade de horas: "))
minutos = int(input("Digite a quantidade de minutos: "))
segundos = int(input("Digite a quantidade de segundos: "))
total_segundos = dias * 86400 + horas * 3600 + minutos * 60 + segundos
print(f"O total em segundos é: {total_segundos}")

Exercicio10 - Crie um programa faça a tabuada de Multiplicar, Dividir, adição e Subtração com
sequência de dados (sem nenhuma estrutura de condição ou estrutura de repetição)
R=numero = int(input("Digite um número inteiro para a tabuada: "))
print(f"{numero} x 1 = {numero * 1}")
print(f"{numero} x 2 = {numero * 2}")
print(f"{numero} x 3 = {numero * 3}")
print(f"{numero} x 4 = {numero * 4}")
print(f"{numero} x 5 = {numero * 5}")
print(f"{numero} x 6 = {numero * 6}")
print(f"{numero} x 7 = {numero * 7}")
print(f"{numero} x 8 = {numero * 8}")
print(f"{numero} x 9 = {numero * 9}")
print(f"{numero} x 10 = {numero * 10}")

# Divisão
print(f"{numero} / 1 = {numero / 1}")
print(f"{numero} / 2 = {numero / 2}")
print(f"{numero} / 3 = {numero / 3}")
print(f"{numero} / 4 = {numero / 4}")
print(f"{numero} / 5 = {numero / 5}")
print(f"{numero} / 6 = {numero / 6}")
print(f"{numero} / 7 = {numero / 7}")
print(f"{numero} / 8 = {numero / 8}")
print(f"{numero} / 9 = {numero / 9}")
print(f"{numero} / 10 = {numero / 10}")
# Adição
print(f"{numero} + 1 = {numero + 1}")
print(f"{numero} + 2 = {numero + 2}")
print(f"{numero} + 3 = {numero + 3}")
print(f"{numero} + 4 = {numero + 4}")
print(f"{numero} + 5 = {numero + 5}")
print(f"{numero} + 6 = {numero + 6}")
print(f"{numero} + 7 = {numero + 7}")
print(f"{numero} + 8 = {numero + 8}")
print(f"{numero} + 9 = {numero + 9}")
print(f"{numero} + 10 = {numero + 10}")
# Subtração
print(f"{numero} - 1 = {numero - 1}")
print(f"{numero} - 2 = {numero - 2}")
print(f"{numero} - 3 = {numero - 3}")
print(f"{numero} - 4 = {numero - 4}")
print(f"{numero} - 5 = {numero - 5}")
print(f"{numero} - 6 = {numero - 6}")
print(f"{numero} - 7 = {numero - 7}")
print(f"{numero} - 8 = {numero - 8}")
print(f"{numero} - 9 = {numero - 9}")
print(f"{numero} - 10 = {numero - 10}")

