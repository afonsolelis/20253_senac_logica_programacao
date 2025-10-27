# Aula — 2025-09-29 — Estruturas de Controle: Iteração (while, for)

- Resolução do EC da aula passada

  Correção de classificações e condicionais.

---

## Objetivos

- Repetir ações com while e for.
- Laços contáveis e condicionais; range; acumulação.

---

## Exemplos

```python
# soma de 1..n
n = int(input("n: "))
soma = 0
for i in range(1, n + 1):
    soma += i
print("soma:", soma)

# while com sentinela
total = 0.0
while True:
    x = input("Valor (vazio para sair): ").strip()
    if x == "":
        break
    total += float(x)
print("total:", total)
```

---

## Exercícios Propostos

1. Fatorial de n.
2. Tabuada (1..10) formatada.
3. Leitura de valores até sentinela e média.

---

## Referência

- Material: Iteração (while, for) — ver espaço do curso.


