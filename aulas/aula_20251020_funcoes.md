# Aula — 2025-10-20 — Como funcionam as funções?

- Resolução do EC da aula passada

  Exercícios de seleção múltipla: revisão rápida.

---

## Objetivos

- Definir e chamar funções; parâmetros e retorno.
- Escopo de variáveis e docstrings.

---

## Exemplos

```python
def media(a: float, b: float, c: float) -> float:
    return (a + b + c) / 3

def saudacao(nome: str, formal: bool = False) -> None:
    if formal:
        print(f"Olá, {nome}.")
    else:
        print(f"Oi, {nome}!")

print(media(7, 8.5, 10))
saudacao("Ana")
```

---

## Exercícios Propostos

1. Função para IMC e classificação.
2. Função calculadora com operação como string.
3. Função verificador de primo.

---

## Referência

- Material: Funções — ver espaço do curso.


