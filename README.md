# Entradas
try:
    t_max = float(input("Temperatura MÁXIMA: "))
    t_min = float(input("Temperatura MÍNIMA: "))
    
    media = (t_max + t_min) / 2
    variacao = abs(t_max - t_min)
    
    print(f"Média: {media:.2f}")
    print(f"Variação: {variacao:.2f}")
except ValueError:
    print("Valor de temperatura inválido!")

# Soma dos dígitos
num = input("Informe um número inteiro: ")
if num.lstrip("-").isdigit():
    soma = sum(int(d) for d in num if d.isdigit())
    print(f"Soma dos dígitos: {soma}")
else:
    print("Número inválido! Informe um inteiro.")
