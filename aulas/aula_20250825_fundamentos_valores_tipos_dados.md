# Aula — 2025-08-25 — Fundamentos de Valores e Tipos de Dados

- Resolução do EC da aula passada

  Sem EC — atividade de fixação breve: soma de dois números (revisão).

---

## Objetivos

- Entender valores, literais e tipos (int, float, str, bool).
- Realizar conversões (casting) e operações básicas.

---

## Tipos e Conversões

```python
x = 10          # int
y = 3.14        # float
nome = "Ana"    # str
ativo = True    # bool

print(type(x), type(y), type(nome), type(ativo))

# conversões
nota = float("9.5")
quant = int("42")
flag = bool(1)
```

---

## Operadores

- Aritméticos: +, -, *, /, //, %, **
- Comparação: ==, !=, >, >=, <, <=
- Lógicos: and, or, not

```python
a = 7
b = 3
print(a / b, a // b, a % b, a ** b)
```

---

## Exercícios Propostos

1. Leia três notas (float) e imprima média com 2 casas.
2. Receba um inteiro e informe se é par.
3. Converta temperatura Celsius->Fahrenheit.

---

## Referência

- Material: Fundamentos de Valores e Tipos de Dados — ver espaço do curso.


