capital = float(input("Digite o valor do capital"))
print(f"Seu capital é igual a {capital}")

juros = float(input("Digite o valor de juros mensal"))
print(f"Seu juros mensal terá o valor de {juros}")

periodo = int(input("Digite a quantidade de mês que fará seu dinheiro render"))
print(f"Seu periodo de rendimento será de {periodo} meses")

for i in range (0+periodo):
    capital = capital + (capital * (juros/100))
    print(capital)
