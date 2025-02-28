# Calculadora_de_IMC
# O Usuário vai inserir o peso corporal e a altura
# O programa vai calcular o IMC
# O programa vai mostrar o resultado do cálculo do IMC
# O programa vai mostrar a classificação do IMC

# Entrada de dados
kg = float(input("Digite o seu peso (kg): "))
m = float(input("Digite a sua altura (m): "))

# Função para calcular o IMC
def calculo_imc(kg, m):
    imc = kg / (m ** 2)
    return imc

# Processamento de dados
imc = calculo_imc(kg, m)

# Classificação do IMC
if imc < 18.5:
    print("Abaixo do peso")
elif imc < 24.9:
    print("Peso normal")
elif imc < 29.9:
    print("Sobrepeso")
elif imc < 34.9:
    print("Obesidade grau 1")
elif imc < 39.9:
    print("Obesidade grau 2")
else:
    print("Obesidade grau 3")

# Saída de dados
print("Seu IMC é: {:.2f}".format(imc))
