# Atividade-Python-M1

#1° Faça um programa que peça dois números e verifique (usando if e else) e imprima o maior deles.
n1 = int(input('qual o primeiro numero:'))
n2 = int(input('qual o segundo numero:'))
if n1 > n2:
    print ('Maior numero é', n1)
else : 
    print ('Maior numero é', n2):

#2° Faça um programa que verifique (usando if e else) se uma letra digitada é vogal ou consoante.
letra = input ("Digite uma letra:")
if letra =='a' or letra =='e' or letra =='i' or letra =='o' or letra =='u' :
    print("Letra é uma vogal")
else:
    print(" Letra é uma consoante")    

#3° Faça um programa que pergunte em que turno você estuda. Peça para digitar M-matutino ou V-vespertino ou N-noturno. Imprima a mensagem “Bom dia!” ou “Boa Noite” ou “Valor inválido”, conforme o caso.
turno = input ("Qual o seria seu horario\n"
            "M-matutino\n"
            "V-vespertino\n" 
            "N-noturno\n")

if turno == 'M':
print("Bom dia!")
elif turno =='V':
        print("Boa tarde")
elif turno == 'N':
        print ("Boa noite!")
else:
    print("Valor inválido")


#4° Faça um Programa que peça um número inteiro e determine se ele e par ou ímpar. Dica: utilize o operador módulo (resto da divisão).

numero3  = int(input("Digite um numero:"))
if numero3 % 2 == 0:
    print("O numero é par")
else:
    print("O numero é impar")


 #  5° Faça um programa que receba um número e usando laços de repetição calcule e mostre a tabuada desse número.
numero = int(input("digite um numero;"))
for i in range(1 ,11 ,1):
    print(f"{numero} * {i} = {numero * i}")

 #6° Faça um programa que verifique e mostre os números entre 1.000 e 2.000 (inclusive) que, quando divididos por 11 produzam resto igual a 2.

for i in range (1000, 2001, 1):
    if i % 11 == 2:
        print(i)

  #7° Escreva um programa que lê o tamanho do lado de um quadrado e imprime um quadrado daquele tamanho com asteriscos. Seu programa deve usar laços de repetição e funcionar para quadrados com lados de todos os tamanhos entre 1 e 20.
lado = int(input("ditigar os lados do quadrado:"))
i = 0
j = 0
while i <lado:
    while j < lado:
        print("*", end='')
        j += 1
    print('')
    i += 1
    j =0 

#8° Faça um programa que recebe a altura de um triangulo em um número inteiro e imprima-o utilizando asteriscos.
lado = int(input("Digitar o lado do triangulo:"))
i = 0
j = 0
k = 1

while i <lado :
    while j < k:
        if k <= lado:
            print("*" , end='')
            j += 1
        print('')
        k += 1
        j = 0
        i += 1

