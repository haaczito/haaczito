▼ LISTA 1 - EXERCÍCIOS 1, 2 E 3 ▼

h = float(input("Digite sua altura: "))
g = float(input("Agora, seu genero (1 para Masculino/2 para Feminino): "))

if g == 1:
	p = (72.7*h) - 58 
elif g == 2:
	p = (62.1*h) - 44.7 
else:
	print("E eu sou o Michael Jackson")

print("O peso ideal é de: ",p)

p = float(input("Qual o peso do peixe?: "))

if p <= 50 :
excesso = 0
else:
excesso = p-50
multa = 4*excesso

if multa != 0:
print("Sua multa é de R$%d,00." % multa)
else:
print("Mó peixe pequeno, nem vou multar kkkkkkk")

gph = float(input("Quanto você ganha por hora?: ")) 
hpm = float(input("Quantas horas você trabalha por mês?: "))

bruto = gph*hpm
ir = bruto*0.11
inss = bruto*0.08
sind = bruto*0.05
desc = ir + inss+ sind
liq = bruto – desc

print("O salário bruto é de R$%d,00." % bruto)
print("O Imposto de Renda é de R$%d,00." % ir)
print("O INSS é de R$%d,00." % inss)
print("O Sindicato é de R$%d,00." % sind)
print("O salário líquido é de R$%d,00." % liq)

▲LISTA I - EXERCÍCIOS 1, 2 E 3 ▲


▼ LISTA II - EXERCÍCIOS 1, 2, 3 ▼

x = float(input("Digite um número inteiro: "))
 
if (x%2 == 0):
    print("O número é par")
else:
    print("O número é ímpar")

x = float(input("Digite um número inteiro: "))
 
if (x%1 == 0):
    print("O número é inteiro")
else:
    print("O número é decimal")


valor = float(input("Digite o valor que deseja sacar: "))
 
if (10 < valor < 600):
    nota100 = int(valor/100)
    print("Quantidade de notas de 100: ",nota100)
    
    valor2 = valor - 100*nota100
    nota50 = int(valor2/50)
    print("Quantidade de notas de 50: ",nota50)
    
    valor3 = valor2 - 50*nota50
    nota10 = int(valor3/10)
    print("Quantidade de notas de 10: ",nota10)
    
    valor4 = valor3 - 10*nota10
    nota1 = int(valor4)
    print("Quantidade de notas de 1: ",nota1)
    
else:
    print("Valor inválido.")
