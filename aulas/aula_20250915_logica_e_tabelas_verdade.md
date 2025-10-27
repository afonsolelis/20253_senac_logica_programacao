# Aula — 2025-09-15 — Lógica e Tabelas Verdade

- Resolução do EC da aula passada

  Pequena lista de correções dos exercícios de revisão.

---

## Objetivos

- Entender operadores lógicos (and, or, not, xor) e tabelas verdade.
- Relacionar com portas lógicas e simular em Python.

---

## Tabelas Verdade em Python

```python
def porta_or(a, b):
    return 1 if (a == 1 or b == 1) else 0

def porta_and(a, b):
    return 1 if (a == 1 and b == 1) else 0

def porta_not(a):
    return 1 if a == 0 else 0

def porta_xor(a, b):
    return 1 if (a != b) else 0

for a in (0, 1):
    for b in (0, 1):
        print(a, b, porta_or(a, b), porta_and(a, b), porta_xor(a, b))
```

---

## Estudo de Caso rápido

Portões de acesso: abrir se cartão válido ou botão supervisor, e não estiver bloqueado.

---

## Referência

- Material: Lógica e Tabelas Verdade — ver espaço do curso.


