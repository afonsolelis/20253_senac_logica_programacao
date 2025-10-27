# Aula — 2025-10-13 — Estruturas de Seleção (switch/case ou equivalente)

- Resolução do EC da aula passada

  Correção pós-prova: esclarecimentos rápidos e retomada.

---

## Objetivos

- Simular switch/case em Python (match/case — Python 3.10+) ou if-elif.
- Organização de decisões múltiplas com dicionários de função.

---

## Exemplos (match/case)

```python
op = input("Operação: ")
match op:
    case "+":
        print("somar")
    case "-":
        print("subtrair")
    case "*":
        print("multiplicar")
    case "/":
        print("dividir")
    case _:
        print("inválido")
```

---

## Exercícios Propostos

1. Menu de conversões (temperatura, moeda, medidas) com match/case.
2. Calculadora de tarifas por código.

---

## Referência

- Material: Estruturas de Seleção — ver espaço do curso.


