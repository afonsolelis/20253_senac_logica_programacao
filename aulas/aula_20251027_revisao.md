# Aula — 2025-10-27 — Revisão

- Resolução do EC da aula passada

  Correção dos exercícios de funções.

---

## Objetivos

- Consolidar os conteúdos: tipos, variáveis, condicionais, laços e funções.
- Resolver exercícios integradores.

---

## Lista Integrada

Cada exercício traz um contexto real, a tarefa e um exemplo de entrada. Resolva em Python lendo os dados via input ou usando os exemplos diretamente no código de teste.

### Tipos e Valores (10 exercícios)

1) Supermercado — soma e arredondamento
- Contexto: Somar itens do carrinho e exibir total com 2 casas.
- Tarefa: Some os preços e formate com 2 casas decimais.
- Entrada (exemplo): 19.90, 5.50, 3.25 → Saída esperada: 28.65

2) Clima — conversor Celsius para Fahrenheit
- Contexto: Painel deve exibir também em °F.
- Tarefa: Converta C para F usando F = C*9/5 + 32.
- Entrada (exemplo): 22.5 → Saída esperada: 72.5

3) Estoque — total por item
- Contexto: Sistema recebe quantidade como string e preço como string.
- Tarefa: Converta tipos corretamente e calcule total = qtd*preco.
- Entrada (exemplo): "12", "3.5" → Saída esperada: 42.0

4) Engenharia — área de círculo
- Contexto: Calcular a área de um tubo circular.
- Tarefa: Use π=3.14159 e arredonde em 2 casas.
- Entrada (exemplo): raio=2.75 → Saída esperada: 23.76

5) Frota — consumo de combustível
- Contexto: Relatório de km/l do veículo.
- Tarefa: consumo = km / litros, 2 casas.
- Entrada (exemplo): km=350, litros=23 → Saída esperada: 15.22

6) Viagem — estimativa de tempo
- Contexto: Exibir duração em horas e minutos.
- Tarefa: tempo = distancia/velocidade, converter p/ h e min inteiros.
- Entrada (exemplo): 120 km, 80 km/h → Saída esperada: 1h30m

7) Compra — verificação de orçamento
- Contexto: Aprovar compra se disponível e saldo ≥ preço.
- Tarefa: Exibir True/False.
- Entrada (exemplo): preco=85.0, saldo=100.0, disponivel=True → True

8) Formatação — peso com unidade
- Contexto: Gerar etiqueta com peso e unidade.
- Tarefa: Transforme inteiro em string e concatene " kg".
- Entrada (exemplo): 42 → Saída esperada: "42 kg"

9) Oficina — potência mecânica (simplificado)
- Contexto: Potência P = trabalho/tempo.
- Tarefa: Calcular P a partir de trabalho (J) e tempo (s), 1 casa.
- Entrada (exemplo): 1250 J, 4 s → Saída esperada: 312.5 W

10) Finanças — preço com desconto percentual
- Contexto: Aplicar desconto e exibir novo preço.
- Tarefa: novo = preco*(1 - desc/100), 2 casas.
- Entrada (exemplo): 199.90, 15% → Saída esperada: 169.92

### Variáveis e Atribuição (10 exercícios)

1) Lanchonete — total do pedido
- Contexto: Preço unitário e quantidade variam.
- Tarefa: Calcule total, aplique taxa fixa de entrega 7.50.
- Entrada (exemplo): 18.00, 3 → Saída esperada: 61.50

2) Evento — controle de ingressos
- Contexto: Venda reduz ingressos disponíveis.
- Tarefa: Subtraia vendidos do estoque.
- Entrada (exemplo): estoque=120, vendidos=37 → Saída esperada: 83

3) Loja — troca de valores
- Contexto: Trocar caixas registradoras.
- Tarefa: Troque valores de caixaA e caixaB.
- Entrada (exemplo): 1500.00 e 2300.00 → Saída esperada: 2300.00 e 1500.00

4) Produção — ajuste de lote
- Contexto: A cada inspeção, lote recebe +1 defeito.
- Tarefa: Atualize contador três vezes.
- Entrada (exemplo): inicio=0 → Saída esperada: 3

5) Academia — IMC
- Contexto: Registrar IMC do aluno.
- Tarefa: Calcule IMC = peso/(altura^2), 2 casas.
- Entrada (exemplo): 82 kg, 1.75 m → Saída esperada: 26.78

6) Financeiro — arredondamentos
- Contexto: Registrar com 2 casas e também inteiro.
- Tarefa: Dado 123.456, gere 123.46 e 123.
- Entrada (exemplo): 123.456 → Saída esperada: 123.46 e 123

7) RH — reajuste salarial
- Contexto: Reajuste de 8%.
- Tarefa: novo = salario * 1.08.
- Entrada (exemplo): 3500.00 → Saída esperada: 3780.00

8) E-commerce — frete grátis
- Contexto: Flag se total ≥ 200 ativa frete_gratis.
- Tarefa: Use variável booleana.
- Entrada (exemplo): total=199.99 → Saída esperada: False

9) Oficina — custo de peças
- Contexto: Some três itens e aplique 10% imposto.
- Tarefa: total = (a+b+c)*1.10, 2 casas.
- Entrada (exemplo): 45.9, 12.5, 30.0 → Saída esperada: 98.74

10) Marketing — cupom progressivo
- Contexto: Aplicar -5 e depois -3 no carrinho.
- Tarefa: Atualize total duas vezes.
- Entrada (exemplo): total=120.00 → Saída esperada: 112.00

### Condicionais (10 exercícios)

1) Bilheteria — meia-entrada
- Contexto: Paga meia se estudante ou idoso (≥60).
- Tarefa: Dado estudante(bool) e idade, informe "meia" ou "inteira".
- Entrada (exemplo): estudante=False, idade=62 → Saída: meia

2) Saúde — classificação de IMC
- Contexto: Use faixas OMS simplificadas.
- Tarefa: <18.5 magreza, <25 normal, <30 sobrepeso, senão obesidade.
- Entrada (exemplo): IMC=26.1 → Saída: sobrepeso

3) Frete — região e peso
- Contexto: Sul/Sudeste até 5kg = 20; demais = 35; >5kg soma 15.
- Tarefa: Calcule valor do frete.
- Entrada (exemplo): reg="Sudeste", peso=6 → Saída: 35

4) Triângulo — classificação
- Contexto: Dados lados a,b,c.
- Tarefa: Verifique se formam triângulo e classifique.
- Entrada (exemplo): 3,3,3 → Saída: equilátero

5) Calendário — ano bissexto
- Contexto: Regras de ano bissexto.
- Tarefa: Divisível por 400 ou (divisível por 4 e não por 100).
- Entrada (exemplo): 2000 → Saída: True

6) Qualidade — pH da bebida
- Contexto: Aceitar 2.3 ≤ pH ≤ 2.6.
- Tarefa: Imprima "ok" ou "fora".
- Entrada (exemplo): 2.4 → Saída: ok

7) Segurança — senha forte
- Contexto: Senha válida se len≥8 e contém número.
- Tarefa: Validar string.
- Entrada (exemplo): "abc123" → Saída: False

8) Trânsito — limite de velocidade
- Contexto: Multa se velocidade > limite.
- Tarefa: Informe "multa" ou "ok".
- Entrada (exemplo): v=83, limite=80 → Saída: multa

9) Notas — conceito
- Contexto: A(≥90), B(≥80), C(≥70), D(≥60), F(else).
- Tarefa: Dado score, imprima conceito.
- Entrada (exemplo): 85 → Saída: B

10) Acesso — login com bloqueio
- Contexto: Bloquear após 3 tentativas.
- Tarefa: Se tentativas≥3 → "bloqueado" senão "permitido".
- Entrada (exemplo): tentativas=2 → Saída: permitido

### Laços (while, for) (10 exercícios)

1) Finanças — soma de despesas do mês
- Contexto: Some N valores lidos.
- Tarefa: Exibir total com 2 casas.
- Entrada (exemplo): [120.50, 89.90, 30.00] → Saída: 240.40

2) Produção — contagem de itens aprovados
- Contexto: Conte valores ≥ especificação.
- Tarefa: Dada lista de medidas, conte quantas ≥ 10.
- Entrada (exemplo): [9,10,11,8,12] → Saída: 3

3) Tabuada — impressão formatada
- Contexto: Exibir 7×1..10.
- Tarefa: Use for e formatação.
- Entrada (exemplo): 7 → Saída: linhas 7×1..7×10

4) Estoque — reposição até atingir meta
- Contexto: Somar lotes até atingir 100.
- Tarefa: Leia valores e pare quando soma≥100.
- Entrada (exemplo): [30,20,25,10,15] → Saída: 100 (parou ao atingir/ultrapassar)

5) Saúde — média de passos
- Contexto: Média de passos em 7 dias.
- Tarefa: Calcular média inteira.
- Entrada (exemplo): [8000,9000,7500,10000,5000,6000,7000] → Saída: 7500

6) TI — contagem de erros em logs
- Contexto: Contar ocorrências de "ERROR".
- Tarefa: Percorra lista de linhas e conte.
- Entrada (exemplo): ["OK","ERROR","WARN","ERROR"] → Saída: 2

7) Matemática — fatorial
- Contexto: Calcule n! com laço.
- Tarefa: 5!.
- Entrada (exemplo): n=5 → Saída: 120

8) Números — soma de pares em 1..N
- Contexto: Somar apenas pares.
- Tarefa: Para N=10, some pares.
- Entrada (exemplo): 10 → Saída: 30

9) Pesquisa — contagem de respostas "sim"
- Contexto: Calcular apoio a proposta.
- Tarefa: Conte "sim" ignorando maiúsculas/minúsculas.
- Entrada (exemplo): ["Sim","nao","SIM","talvez"] → Saída: 2

10) Série — Fibonacci até N termos
- Contexto: Gerar primeiros N termos.
- Tarefa: Para N=6, gere a sequência.
- Entrada (exemplo): 6 → Saída: 0 1 1 2 3 5

### Funções (10 exercícios)

1) Saúde — função imc(peso, altura)
- Contexto: Reutilizar cálculo.
- Tarefa: Retornar IMC com 2 casas.
- Entrada (exemplo): 82, 1.75 → Saída: 26.78

2) Financeiro — juros_compostos(valor, taxa, meses)
- Contexto: Simulação mensal.
- Tarefa: Retorne montante com 2 casas.
- Entrada (exemplo): 1000, 1%, 6 → Saída: 1061.52

3) Conversão — celsius_para_f(c)
- Contexto: API interna.
- Tarefa: Retorne float.
- Entrada (exemplo): 30 → Saída: 86.0

4) Qualidade — dentro_faixa(x, lo, hi)
- Contexto: Reaproveitar em inspeções.
- Tarefa: Retorne True se lo ≤ x ≤ hi.
- Entrada (exemplo): 2.4, 2.3, 2.6 → Saída: True

5) Texto — contar_vogais(s)
- Contexto: Relatórios.
- Tarefa: Retorne número de vogais aeiou (case-insensitive).
- Entrada (exemplo): "Programar" → Saída: 3

6) Geometria — area_triangulo(b,h)
- Contexto: Orçamento de materiais.
- Tarefa: Retorne (b*h)/2.
- Entrada (exemplo): 5, 8 → Saída: 20

7) E-commerce — frete_por_peso(peso)
- Contexto: Até 2kg=12; até 5kg=20; acima=28.
- Tarefa: Retorne o valor do frete.
- Entrada (exemplo): 4.2 → Saída: 20

8) Dados — mediana(lista)
- Contexto: Estatística simples.
- Tarefa: Retorne mediana correta para N par/ímpar.
- Entrada (exemplo): [1,3,2,4] → Saída: 2.5

9) Números — eh_primo(n)
- Contexto: Filtros de dados.
- Tarefa: Retorne True/False (n≥2).
- Entrada (exemplo): 29 → Saída: True

10) Texto — snake_para_camel(s)
- Contexto: Converter nomes de campos.
- Tarefa: "primeiro_nome" → "primeiroNome".
- Entrada (exemplo): "primeiro_nome" → Saída: "primeiroNome"

---

## Referência

- Materiais anteriores e exercícios integradores.


## Feedback (Gabarito)

### Tipos e Valores
1) 28.65
2) 72.5
3) 42.0
4) 23.76
5) 15.22
6) 1h30m
7) True
8) "42 kg"
9) 312.5 W
10) 169.92

### Variáveis e Atribuição
1) 61.50
2) 83
3) 2300.00 e 1500.00
4) 3
5) 26.78
6) 123.46 e 123
7) 3780.00
8) False
9) 98.74
10) 112.00

### Condicionais
1) meia
2) sobrepeso
3) 35
4) equilátero
5) True
6) ok
7) False
8) multa
9) B
10) permitido

### Laços (while, for)
1) 240.40
2) 3
3) 7×1..7×10 (linhas)
4) 100 (parada ao atingir/ultrapassar)
5) 7500
6) 2
7) 120
8) 30
9) 2
10) 0 1 1 2 3 5

### Funções
1) 26.78
2) 1061.52
3) 86.0
4) True
5) 3
6) 20
7) 20
8) 2.5
9) True
10) "primeiroNome"


