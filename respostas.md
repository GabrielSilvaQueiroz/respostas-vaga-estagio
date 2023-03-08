<h1> Questões da Avaliação Job Rotation - Ribeirão Preto </h1>

# 1 Questão: 
O valor da variável SOMA será 91. 

# 2 Questão:
PYTHON 

num = int(input("Digite um número: "))

fib_ant = 0
fib_atual = 1
pertence_fibonacci = False

while fib_atual <= num:
    if fib_atual == num:
        pertence_fibonacci = True
        break

fib_ant, fib_atual = fib_atual, fib_ant + fib_atual

if pertence_fibonacci:
    print(f"O número {num} pertence à sequência de Fibonacci.")

else:
    print(f"O número {num} não pertence à sequência de Fibonacci.")

# 3 Questão: 
a) A lógica é adicionar 2 ao número anterior. O próximo elemento é 9.

b) A lógica é multiplicar o número anterior por 2. O próximo elemento é 128.

c) A lógica é elevar o número anterior ao quadrado. O próximo elemento é 49.

d) A lógica é adicionar 12 ao número anterior. O próximo elemento é 100.

e) A lógica é somar os dois números anteriores para obter o próximo. O próximo elemento é 13.

f) A lógica é somar 8 ao número anterior se for par, caso contrário, somar 2. O próximo elemento é 20.

# 4 Questão: 

O carro e o caminhão estão à mesma distância de Ribeirão Preto ao eles se cruzarem, eles se encontram a 60,9 km de Ribeirão Preto.

# 5 Questão:
PYTHON

string = input("Digite uma string: ")

lista_caracteres = list(string)

tamanho_lista = len(lista_caracteres)

for i in range(tamanho_lista // 2):

    lista_caracteres[i], lista_caracteres[tamanho_lista - i - 1] = lista_caracteres[tamanho_lista - i - 1], lista_caracteres[i]

    string_invertida = "".join(lista_caracteres)

    print("String invertida: ", string_invertida)


