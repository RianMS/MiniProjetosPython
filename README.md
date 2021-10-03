while True:
    operação = input("Qual Operação pretende fazer (+,-,*,/), ou se desejar sair, digite (sair)")
    if operação == 'Sair':
        print ("você saiu")
        break
    n1 = int(input("Escolha um numero: "))
    n2 = int(input("Escolha Outro numero: "))
    if operação == '+':
        total = n1 + n2
        print(total)
    elif operação == '-':
        total = n1 - n2
        print(total)
    elif operação == '*':
        total = n1 * n2
        print(total)
    elif operação == '*':
        total = n1 / n2
        print(total)
    else: print("Operação invalida")
