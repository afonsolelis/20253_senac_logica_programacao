# Aula — 2025-10-27 — Revisão

## 🧮 Parte 1: Tipos e Valores — *Quando os Números Contam uma História*

### 1. 🛒 **O Carrinho da Dona Marta**
Dona Marta faz compras no supermercado todo sábado. Hoje, ela comprou:  
- Leite: R$ 19,90  
- Pão: R$ 5,50  
- Café: R$ 3,25  

Ela quer saber o **total exato com duas casas decimais** para conferir no cupom.  
**Sua missão**: Some os preços e exiba o total formatado.  
```python
# Exemplo de entrada
precos = [19.90, 5.50, 3.25]
# Saída esperada: "28.65"
```

---

### 2. 🌡️ **O Termômetro do João**
João viaja para os EUA e vê no noticiário: *"Hoje fará 72.5°F!"*. Ele só entende graus Celsius!  
Sabendo que **F = C × 9/5 + 32**, ajude João a converter **22.5°C** para Fahrenheit.  
**Dica**: O resultado deve ser exibido como número real, sem formatação extra.

---

### 3. 📦 **Estoque do Seu Zé**
Seu Zé, dono de uma mercearia, digitou os dados no sistema antigo:  
- Quantidade: `"12"` (string!)  
- Preço unitário: `"3.5"` (também string!)  

Ele precisa do **valor total do item** (quantidade × preço).  
**Sua missão**: Converta os tipos corretamente e calcule o total.  
Saída esperada: `42.0`

---

### 4. 🔧 **O Cano do Engenheiro Lima**
O engenheiro Lima precisa calcular a **área interna de um cano circular** para um projeto hidráulico.  
Fórmula: **Área = π × raio²**, com **π = 3.14159**.  
Dado raio = **2.75 m**, exiba a área com **2 casas decimais**.  
Saída esperada: `23.76`

---

### 5. ⛽ **Relatório do Motorista Carlos**
Carlos dirige um caminhão e registra:  
- Quilômetros rodados: **350 km**  
- Combustível gasto: **23 litros**  

Ele quer saber o **consumo médio (km/l)** com 2 casas decimais.  
Saída esperada: `15.22`

---

### 6. 🚗 **Viagem da Família Silva**
A família Silva vai visitar os avós: **120 km** de distância, a **80 km/h**.  
Quanto tempo levará? Exiba no formato **XhYm** (horas e minutos inteiros).  
**Exemplo**: `1h30m`  
*(Dica: use divisão inteira e resto!)*

---

### 7. 💳 **Compra do Pedro**
Pedro quer comprar um jogo por **R$ 85,00**.  
Ele tem **R$ 100,00** e o cartão está **disponível**.  
A compra é **aprovada** apenas se:  
- O cartão estiver disponível **E**  
- O saldo for **≥ preço**  

Exiba `True` ou `False`.

---

### 8. ⚖️ **Etiqueta da Balança**
Na feira, a balança mostra o peso como número inteiro: **42**.  
Mas a etiqueta precisa dizer: **"42 kg"**.  
Transforme o número em string e adicione a unidade.

---

### 9. ⚙️ **Oficina do Mecânico Téo**
Téo mede:  
- Trabalho realizado: **1250 joules**  
- Tempo gasto: **4 segundos**  

A potência é **P = trabalho / tempo**.  
Exiba com **1 casa decimal** e a unidade **"W"**.  
Saída: `"312.5 W"`

---

### 10. 💰 **Desconto da Loja Online**
Uma loja oferece **15% de desconto** em um produto de **R$ 199,90**.  
Calcule o novo preço com **2 casas decimais**.  
Fórmula: `novo = preco * (1 - desconto/100)`  
Saída: `169.92`

---

## 🧠 Parte 2: Variáveis e Atribuição — *Mudando o Mundo, Uma Variável por Vez*

### 1. 🍔 **Pedido do Lanche Rápido**
Você pede **3 hambúrgueres** a **R$ 18,00** cada.  
A taxa de entrega é fixa: **R$ 7,50**.  
Qual o total? Saída: `61.50`

---

### 2. 🎟️ **Ingressos do Show**
Havia **120 ingressos**. Foram vendidos **37**.  
Quantos sobraram? Use variáveis para atualizar o estoque.  
Saída: `83`

---

### 3. 💵 **Troca de Caixas**
Na loja, o caixa A tem **R$ 1500,00** e o B tem **R$ 2300,00**.  
Durante o fechamento, os valores são **trocados**.  
Exiba os novos valores: `2300.00` e `1500.00`

---

### 4. 🏭 **Controle de Qualidade**
Um lote começa com **0 defeitos**.  
Na inspeção, são encontrados **3 defeitos** (um por vez).  
Atualize a variável **três vezes**. Saída: `3`

---

### 5. 🏋️ **IMC do Aluno da Academia**
Peso: **82 kg**, Altura: **1,75 m**  
IMC = peso / (altura ** 2) → com 2 casas.  
Saída: `26.78`

---

### 6. 📊 **Arredondamento Financeiro**
Dado o valor **123.456**, gere:  
- Versão com **2 casas**: `123.46`  
- Versão **inteira**: `123`  
Exiba ambos.

---

### 7. 💼 **Reajuste do Funcionário**
Salário atual: **R$ 3500,00**  
Reajuste: **+8%**  
Novo salário: `3780.00`

---

### 8. 📦 **Frete Grátis?**
Se o total da compra for **≥ R$ 200,00**, o frete é grátis.  
Total = **199,99** → frete_gratis = `False`

---

### 9. 🔧 **Peças da Oficina**
Preços: **45,90**, **12,50**, **30,00**  
Soma + **10% de imposto** → total com 2 casas.  
Saída: `98.74`

---

### 10. 🎁 **Cupom do E-commerce**
Carrinho: **R$ 120,00**  
Aplicar:  
- Primeiro: **-R$ 5,00**  
- Depois: **-R$ 3,00**  
Total final: `112.00`

---

## 🚦 Parte 3: Condicionais — *Decisões que Mudam Tudo*

### 1. 🎫 **Meia-Entrada no Cinema**
Regras:  
- Estudante **OU**  
- Idade **≥ 60**  

Entrada: `estudante=False`, `idade=62` → Saída: `"meia"`

---

### 2. 🩺 **Diagnóstico por IMC**
Faixas:  
- `< 18.5`: magreza  
- `< 25`: normal  
- `< 30`: sobrepeso  
- `≥ 30`: obesidade  

IMC = **26.1** → `"sobrepeso"`

---

### 3. 📦 **Frete Inteligente**
Regiões: **Sul** ou **Sudeste**  
- Até 5 kg: **R$ 20**  
- Acima: **R$ 35**  
Outras regiões: sempre **R$ 35**  

Entrada: `reg="Sudeste"`, `peso=6` → `35`

---

### 4. 🔺 **Triângulo do Arquiteto**
Lados: **3, 3, 3**  
Verifique se formam triângulo (soma de dois lados > terceiro).  
Se sim, classifique:  
- Todos iguais → **equilátero**  
- Dois iguais → **isósceles**  
- Todos diferentes → **escaleno**  

Saída: `"equilátero"`

---

### 5. 📅 **Ano Bissexto?**
Regra:  
- Divisível por **400** → sim  
- Ou: divisível por **4** **e não** por **100**  

Ano: **2000** → `True`

---

### 6. 🧪 **pH da Refri**
Aceitável: **2.3 ≤ pH ≤ 2.6**  
pH = **2.4** → `"ok"`

---

### 7. 🔐 **Senha Forte?**
Regras:  
- Pelo menos **8 caracteres**  
- Contém **pelo menos um dígito**  

Senha: `"abc123"` → `False` (tem número, mas só 6 letras)

---

### 8. 🚨 **Radar na Rodovia**
Velocidade: **83 km/h**  
Limite: **80 km/h** → `"multa"`

---

### 9. 📝 **Conceito Escolar**
- A: ≥90  
- B: ≥80  
- C: ≥70  
- D: ≥60  
- F: <60  

Nota: **85** → `"B"`

---

### 10. 🔒 **Bloqueio de Login**
Tentativas: **2**  
Máximo permitido: **3**  
Status: `"permitido"`  
(Se ≥3 → `"bloqueado"`)

---

## 🔁 Parte 4: Laços — *Automatizando o Cotidiano*

### 1. 📉 **Total de Despesas**
Despesas do mês: `[120.50, 89.90, 30.00]`  
Some todas → `240.40`

---

### 2. ✅ **Itens Aprovados**
Medidas: `[9, 10, 11, 8, 12]`  
Conte quantas ≥ **10** → `3`

---

### 3. 📚 **Tabuada do 7**
Imprima:
```
7 x 1 = 7
7 x 2 = 14
...
7 x 10 = 70
```

---

### 4. 📦 **Reposição de Estoque**
Lotes recebidos: `[30, 20, 25, 10, 15]`  
Some até atingir **≥100**.  
Pare assim que atingir. Total final: `100`

---

### 5. 👟 **Média de Passos**
Passos em 7 dias: `[8000,9000,7500,10000,5000,6000,7000]`  
Média **inteira**: `7500`

---

### 6. 🖥️ **Erros no Log**
Linhas: `["OK","ERROR","WARN","ERROR"]`  
Conte `"ERROR"` → `2`

---

### 7. 🔢 **Fatorial de 5**
5! = 5×4×3×2×1 = `120`

---

### 8. 🔢 **Soma dos Pares**
N = **10** → pares: 2+4+6+8+10 = `30`

---

### 9. 📊 **Pesquisa de Opinião**
Respostas: `["Sim","nao","SIM","talvez"]`  
Conte `"sim"` (case-insensitive) → `2`

---

### 10. 🐇 **Fibonacci para Crianças**
N = **6** → sequência: `0 1 1 2 3 5`

---

## 🧩 Parte 5: Funções — *Reutilizando Soluções Inteligentes*

> Agora, encapsule cada lógica em uma **função reutilizável**!

### 1. `imc(peso, altura)` → `26.78`  
### 2. `juros_compostos(1000, 1, 6)` → `1061.52`  
*(Fórmula: valor × (1 + taxa/100)^meses)*  
### 3. `celsius_para_f(30)` → `86.0`  
### 4. `dentro_faixa(2.4, 2.3, 2.6)` → `True`  
### 5. `contar_vogais("Programar")` → `3`  
### 6. `area_triangulo(5, 8)` → `20`  
### 7. `frete_por_peso(4.2)` → `20`  
### 8. `mediana([1,3,2,4])` → `2.5`  
### 9. `eh_primo(29)` → `True`  
### 10. `snake_para_camel("primeiro_nome")` → `"primeiroNome"`

---

# 💻 Soluções em Python — Todos os Exercícios

> Todas as soluções usam os **exemplos de entrada fornecidos** e imprimem a **saída esperada exata**.  
> Funções estão definidas conforme solicitado.

---

## 🔢 Parte 1: Tipos e Valores

```python
# 1) Supermercado — soma e arredondamento
precos = [19.90, 5.50, 3.25]
total = sum(precos)
print(f"{total:.2f}")

# 2) Clima — conversor Celsius para Fahrenheit
c = 22.5
f = c * 9/5 + 32
print(f)

# 3) Estoque — total por item
qtd_str = "12"
preco_str = "3.5"
total = int(qtd_str) * float(preco_str)
print(total)

# 4) Engenharia — área de círculo
raio = 2.75
pi = 3.14159
area = pi * raio ** 2
print(f"{area:.2f}")

# 5) Frota — consumo de combustível
km = 350
litros = 23
consumo = km / litros
print(f"{consumo:.2f}")

# 6) Viagem — estimativa de tempo
distancia = 120
velocidade = 80
tempo_horas = distancia / velocidade
horas = int(tempo_horas)
minutos = int((tempo_horas - horas) * 60)
print(f"{horas}h{minutos}m")

# 7) Compra — verificação de orçamento
preco = 85.0
saldo = 100.0
disponivel = True
print(disponivel and saldo >= preco)

# 8) Formatação — peso com unidade
peso = 42
print(f"{peso} kg")

# 9) Oficina — potência mecânica
trabalho = 1250
tempo = 4
potencia = trabalho / tempo
print(f"{potencia:.1f} W")

# 10) Finanças — preço com desconto percentual
preco = 199.90
desconto = 15
novo = preco * (1 - desconto/100)
print(f"{novo:.2f}")
```

---

## 🧠 Parte 2: Variáveis e Atribuição

```python
# 1) Lanchonete — total do pedido
preco_unit = 18.00
qtd = 3
total = preco_unit * qtd + 7.50
print(f"{total:.2f}")

# 2) Evento — controle de ingressos
estoque = 120
vendidos = 37
estoque -= vendidos
print(estoque)

# 3) Loja — troca de valores
caixaA = 1500.00
caixaB = 2300.00
caixaA, caixaB = caixaB, caixaA
print(caixaA, caixaB)

# 4) Produção — ajuste de lote
defeitos = 0
defeitos += 1
defeitos += 1
defeitos += 1
print(defeitos)

# 5) Academia — IMC
peso = 82
altura = 1.75
imc = peso / (altura ** 2)
print(f"{imc:.2f}")

# 6) Financeiro — arredondamentos
valor = 123.456
com_duas = round(valor, 2)
inteiro = int(valor)
print(com_duas, inteiro)

# 7) RH — reajuste salarial
salario = 3500.00
novo = salario * 1.08
print(f"{novo:.2f}")

# 8) E-commerce — frete grátis
total = 199.99
frete_gratis = total >= 200
print(frete_gratis)

# 9) Oficina — custo de peças
a, b, c = 45.9, 12.5, 30.0
total = (a + b + c) * 1.10
print(f"{total:.2f}")

# 10) Marketing — cupom progressivo
total = 120.00
total -= 5
total -= 3
print(f"{total:.2f}")
```

---

## 🚦 Parte 3: Condicionais

```python
# 1) Bilheteria — meia-entrada
estudante = False
idade = 62
if estudante or idade >= 60:
    print("meia")
else:
    print("inteira")

# 2) Saúde — classificação de IMC
imc = 26.1
if imc < 18.5:
    print("magreza")
elif imc < 25:
    print("normal")
elif imc < 30:
    print("sobrepeso")
else:
    print("obesidade")

# 3) Frete — região e peso
reg = "Sudeste"
peso = 6
if reg in ["Sul", "Sudeste"]:
    if peso <= 5:
        frete = 20
    else:
        frete = 35
else:
    frete = 35
print(frete)

# 4) Triângulo — classificação
a, b, c = 3, 3, 3
if a + b > c and a + c > b and b + c > a:
    if a == b == c:
        print("equilátero")
    elif a == b or b == c or a == c:
        print("isósceles")
    else:
        print("escaleno")
else:
    print("não é triângulo")

# 5) Calendário — ano bissexto
ano = 2000
bissexto = (ano % 400 == 0) or (ano % 4 == 0 and ano % 100 != 0)
print(bissexto)

# 6) Qualidade — pH da bebida
ph = 2.4
if 2.3 <= ph <= 2.6:
    print("ok")
else:
    print("fora")

# 7) Segurança — senha forte
senha = "abc123"
tem_numero = any(char.isdigit() for char in senha)
valida = len(senha) >= 8 and tem_numero
print(valida)

# 8) Trânsito — limite de velocidade
v = 83
limite = 80
print("multa" if v > limite else "ok")

# 9) Notas — conceito
score = 85
if score >= 90:
    print("A")
elif score >= 80:
    print("B")
elif score >= 70:
    print("C")
elif score >= 60:
    print("D")
else:
    print("F")

# 10) Acesso — login com bloqueio
tentativas = 2
print("bloqueado" if tentativas >= 3 else "permitido")
```

---

## 🔁 Parte 4: Laços (while, for)

```python
# 1) Finanças — soma de despesas do mês
despesas = [120.50, 89.90, 30.00]
total = sum(despesas)
print(f"{total:.2f}")

# 2) Produção — contagem de itens aprovados
medidas = [9, 10, 11, 8, 12]
aprovados = sum(1 for m in medidas if m >= 10)
print(aprovados)

# 3) Tabuada — impressão formatada
n = 7
for i in range(1, 11):
    print(f"{n} x {i} = {n*i}")

# 4) Estoque — reposição até atingir meta
lotes = [30, 20, 25, 10, 15]
soma = 0
for lote in lotes:
    soma += lote
    if soma >= 100:
        break
print(soma)

# 5) Saúde — média de passos
passos = [8000,9000,7500,10000,5000,6000,7000]
media = sum(passos) // len(passos)
print(media)

# 6) TI — contagem de erros em logs
logs = ["OK","ERROR","WARN","ERROR"]
erros = logs.count("ERROR")
print(erros)

# 7) Matemática — fatorial
n = 5
fatorial = 1
for i in range(1, n+1):
    fatorial *= i
print(fatorial)

# 8) Números — soma de pares em 1..N
N = 10
soma_pares = sum(i for i in range(2, N+1, 2))
print(soma_pares)

# 9) Pesquisa — contagem de respostas "sim"
respostas = ["Sim","nao","SIM","talvez"]
sim_count = sum(1 for r in respostas if r.lower() == "sim")
print(sim_count)

# 10) Série — Fibonacci até N termos
N = 6
fib = []
a, b = 0, 1
for _ in range(N):
    fib.append(a)
    a, b = b, a + b
print(" ".join(map(str, fib)))
```

---

## 🧩 Parte 5: Funções

```python
# 1) Saúde — função imc(peso, altura)
def imc(peso, altura):
    return round(peso / (altura ** 2), 2)

print(imc(82, 1.75))

# 2) Financeiro — juros_compostos(valor, taxa, meses)
def juros_compostos(valor, taxa, meses):
    montante = valor * (1 + taxa/100) ** meses
    return round(montante, 2)

print(juros_compostos(1000, 1, 6))

# 3) Conversão — celsius_para_f(c)
def celsius_para_f(c):
    return c * 9/5 + 32

print(celsius_para_f(30))

# 4) Qualidade — dentro_faixa(x, lo, hi)
def dentro_faixa(x, lo, hi):
    return lo <= x <= hi

print(dentro_faixa(2.4, 2.3, 2.6))

# 5) Texto — contar_vogais(s)
def contar_vogais(s):
    vogais = "aeiouAEIOU"
    return sum(1 for char in s if char in vogais)

print(contar_vogais("Programar"))

# 6) Geometria — area_triangulo(b,h)
def area_triangulo(b, h):
    return (b * h) / 2

print(area_triangulo(5, 8))

# 7) E-commerce — frete_por_peso(peso)
def frete_por_peso(peso):
    if peso <= 2:
        return 12
    elif peso <= 5:
        return 20
    else:
        return 28

print(frete_por_peso(4.2))

# 8) Dados — mediana(lista)
def mediana(lista):
    lista_ordenada = sorted(lista)
    n = len(lista_ordenada)
    meio = n // 2
    if n % 2 == 1:
        return lista_ordenada[meio]
    else:
        return (lista_ordenada[meio - 1] + lista_ordenada[meio]) / 2

print(mediana([1,3,2,4]))

# 9) Números — eh_primo(n)
def eh_primo(n):
    if n < 2:
        return False
    for i in range(2, int(n**0.5)+1):
        if n % i == 0:
            return False
    return True

print(eh_primo(29))

# 10) Texto — snake_para_camel(s)
def snake_para_camel(s):
    partes = s.split('_')
    return partes[0] + ''.join(p.capitalize() for p in partes[1:])

print(snake_para_camel("primeiro_nome"))
```