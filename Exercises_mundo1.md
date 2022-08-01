## 1. Ex01 - Escrevendo Hello World

### >> Crie um programa que escreva "Olá Mundo!"

````python

print("Hello Mundo!")

````

## 2. Ex02 - Respondendo usuário

### >> Fazer um programa que leia o nome de uma pessoa e mostre uma mensagem de boas-vindas.

````python

nome = input('Digite seu nome: ')
print('É um prazer te conhecer {}!'.format(nome))

````

## 3. Ex03 - Somando 2 números

### >> Crie um programa que leia dois números e mostre a soma entre eles.

````python

n1 = int(input('Digite um valor:')
n2 = int(input('Digite um segundo valor:')
s = n1 + n2 
print(A soma entre {} e {} é igual a {}'.format(n1, n2, s))

````

## 4. Ex04 -  Dissecando uma variável

### >> Faça um programa que leia algo pelo teclado e mostre na tela o seu tipo primitivo e todas as informações possíveis sobre ele.

````python

entrada = input("Digite algo: \n")
print("Tipo primitivo: {}.".format(type(entrada)))

print("É numérico? {}".format(entrada.isnumeric()))
print("É alfanumérico? {}.".format(entrada.isalpha()))
print("É um decimal? {}.".format(entrada.isdecimal()))
print("Está em caixa baixa? {}.".format(entrada.islower()))
print("É apenas espaço em branco? {}.".format(entrada.isspace()))
print("Está em caixa alta? {}.".format(entrada.isupper()))

````

## 5. Ex05 -  Antecessor e sucessor

### >> Faça um programa que leia um número inteiro e mostre na tela o seu sucessor e seu antecessor:

````python

n = int(input("Digite um número: \n"))
print("O antecessor do número {} é: {}.".format(n, n - 1))
print("O sucessor do número {} é: {}.".format(n, n + 1))

````

