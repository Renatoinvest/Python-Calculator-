print("\n********** Python Calculator ***********")

def soma(x, y):
    return x + y
def subtração(x, y):
    return x - y
def multiplicação(x, y):
    return x * y
def divisão(x, y):
    if y != 0:
        return x / y
    else:
        return "Erro: Divisão por zero não é permitida."
    def calculadora():
    print("Bem-vindo à Calculadora Simples!")
    print ("Escolha uma operação")
    print ("1 - Soma")
    print ("2 - Subtração")
    print ("3 - Multiplicação")
    print ("4 - Divisão")

    operação = int(input("Digite o número da operação desejada (1/2/3/4): "))

    if operação not in [1, 2, 3, 4]:
    print("Operação inválida. Tente novamente.")
    return

    num1 = int(input("Digite o primeiro número: "))

    num2 = int(input("Digite o segundo número: "))

    if operação == 1:
    resultado = soma(num1, num2)
    print(f"O resultado da soma é: {resultado}")

    elif operação == 2:
    resultado = subtração(num1, num2)
    print(f"O resultado da subtração é: {resultado}")

    elif operação == 3:
    resultado = multiplicação(num1, num2)
    print(f"O resultado da multiplicação é: {resultado}")

    elif operação == 4:
    resultado = divisão(num1, num2)
    print(f"O resultado da divisão é: {resultado}")
