# Formula-de-peso-ideal
Fórmula para calcular o peso ideal para Homens e Mulheres

genero=input("M para Masculino e F para feminino?").upper()

altura=float(input("Digite a sua altura "))

pesoIdealM= ((72.7 * altura) - 58)

pesoIdealF= ((62.1 * altura) - 44.7)

if genero == "M":

    print("Seu peso ideal é:" , (round(pesoIdealM, 2)))

else:

    print("Seu peso ideal é: " , (round(pesoIdealF, 2)))
