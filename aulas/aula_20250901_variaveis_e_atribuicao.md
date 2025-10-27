# Aula — 2025-09-01 — Variáveis e Atribuição

- Resolução do EC da aula passada

  Exercício guiado: calcular IMC (peso/(altura^2)).

---

## Objetivos

- Declarar e usar variáveis em Python.
- Entender atribuição simples e múltipla, atualização e boas práticas de nomes.

---

## Exemplos

```python
nome = input("Nome: ")
idade = int(input("Idade: "))
peso = float(input("Peso (kg): "))
altura = float(input("Altura (m): "))

imc = peso / (altura ** 2)
print(f"{nome} tem IMC = {imc:.2f}")

# atribuição múltipla
a, b = 10, 20
a, b = b, a  # troca
```

---

## Exercícios Propostos

1. Troque valores de duas variáveis sem variável auxiliar.
2. Leia três inteiros e some-os.
3. Calcule o custo total de um pedido (qtd * preço + frete).

---

## Referência

- Material: Variáveis e Atribuição — ver espaço do curso.


