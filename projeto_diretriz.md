# Projeto Semestral

## 🎯 **Título do Projeto**:

### **"Sistema de Gestão de Tarefas Acadêmicas com Interface Interativa"**

Um sistema simples, mas completo, que permite a um estudante (ou grupo) gerenciar suas tarefas, prazos, prioridades e acompanhar o progresso — tudo com lógica de programação clara, estruturas de controle, funções, vetores/listas, documentação e simulação de algoritmos.

---

## 🧩 **Objetivo Geral**

Desenvolver um programa em Python que:

- Permita **cadastrar, visualizar, atualizar e excluir tarefas**.
- Classifique tarefas por **prioridade** e **data de entrega**.
- Mostre **relatórios** (ex: tarefas vencidas, próximas entregas).
- Use **lógica condicional, iteração, seleção múltipla, variáveis, tipos de dados**, etc.
- Seja **modularizado** com funções bem definidas.
- Inclua **documentação** e **simulação passo a passo** de partes críticas.

---

## 👥 **Divisão de Tarefas para 5 Pessoas**

| Integrante | Responsabilidade | Conceitos da Ementa Cobertos |
| --- | --- | --- |
| **1** | **Estrutura de dados e CRUD básico**<br>- Criar lista de tarefas (dicionários em uma lista)<br>- Funções `adicionar_tarefa()`, `listar_tarefas()` | Variáveis, atribuição, tipos de dados (str, int, bool, list, dict), listas/vetores |
| **2** | **Lógica condicional e iteração**<br>- Função `tarefas_vencidas()`<br>- Função `proximas_entregas(n)`<br>- Validação de datas e prioridades | Condicionais (`if/else`), iteração (`for`/`while`), lógica booleana, tabelas verdade (implícita) |
| **3** | **Estruturas de seleção múltipla e menu interativo**<br>- Criar menu com `while` e `match-case` (ou `if-elif`)<br>- Opções: 1) Adicionar, 2) Listar, 3) Filtrar por prioridade, 4) Relatórios, 5) Sair | `switch/case` (ou equivalente), iteração, seleção, controle de fluxo |
| **4** | **Modularização e funções avançadas**<br>- Funções reutilizáveis com parâmetros e retorno<br>- Validação de entrada do usuário<br>- Tratamento de erros básicos (ex: data inválida) | Funções, modularização, escopo, parâmetros, retorno |
| **5** | **Documentação, simulação e integração**<br>- Adicionar docstrings e comentários<br>- Criar célula de "simulação" (ex: passo a passo de como o programa processa uma tarefa)<br>- Garantir que tudo funcione junto no Colab | Documentação, simulação de algoritmos, resolução de problemas, integração de conceitos |

---

## 📁 **Estrutura do Notebook no Google Colab**

```python
# Célula 1: Título e equipe
# Célula 2: Introdução ao projeto (objetivo, escopo)
# Célula 3: Estrutura de dados (lista de tarefas) + funções básicas (Integrante 1)
# Célula 4: Lógica de filtragem e relatórios (Integrante 2)
# Célula 5: Menu interativo com seleção múltipla (Integrante 3)
# Célula 6: Funções avançadas e validação (Integrante 4)
# Célula 7: Documentação, simulação e exemplo de execução (Integrante 5)
# Célula 8: Testes integrados (ex: fluxo completo do usuário)
```

---

## ✅ **Exemplo de Funcionalidades Esperadas**

```python
# Exemplo de tarefa:
tarefa = {
    "id": 1,
    "descricao": "Entregar projeto de lógica",
    "data_entrega": "2025-12-08",
    "prioridade": "alta",  # baixa, média, alta
    "concluida": False
}
```

**Menu interativo:**

```
=== Sistema de Gestão de Tarefas ===
1. Adicionar tarefa
2. Listar todas as tarefas
3. Marcar tarefa como concluída
4. Ver tarefas vencidas
5. Ver próximas 3 entregas
6. Filtrar por prioridade
7. Sair
Escolha uma opção: _
```

---

## 📚 **Como o Projeto Cobre a Ementa**

| Tópico da Ementa | Como é abordado no projeto |
| --- | --- |
| Valores e tipos de dados | Strings, inteiros, booleanos, listas, dicionários |
| Variáveis e atribuição | Uso constante em todas as funções |
| Comandos de atribuição | Atribuição de valores, atualização de status |
| Condicionais (`if/else`) | Validação, filtragem, lógica de relatórios |
| Iteração (`for`, `while`) | Percorrer listas, menu contínuo |
| Seleção múltipla (`match`/`elif`) | Menu de opções |
| Resolução de problemas | Modelagem do problema real (gestão de tarefas) |
| Representação de algoritmos | Código estruturado + comentários |
| Simulação | Célula dedicada mostrando passo a passo |
| Documentação | Docstrings, comentários explicativos |
| Funções e modularização | Cada funcionalidade em função separada |
| Estruturas de dados simples | Lista de dicionários (vetor de registros) |
| Integração de conceitos | Projeto final unifica tudo |

---

## 📅 **Dicas para Entrega (17 de novembro)**

1. **Use um único notebook no Google Colab** com todos os integrantes como editores.
2. **Nomeie o arquivo** como: `ProjetoLogicaProg_EquipeX.ipynb`
3. **Inclua no início**:
    - Nome dos 5 integrantes
    - RA (se aplicável)
    - Data de entrega
4. **Teste tudo** antes de entregar — o menu deve funcionar do início ao fim.
5. **Grave um pequeno vídeo (opcional, mas recomendado)** mostrando o sistema em ação para a prova oral.

---

## 🔗 **Links Úteis para o Colab**

- [Como compartilhar um notebook no Colab](https://colab.research.google.com/)
- Use `from datetime import datetime` para manipular datas
- Para simular passo a passo, use `print()` com mensagens explicativas
Se quiser, posso gerar um **modelo inicial do notebook** com a estrutura básica para vocês começarem! É só pedir.

Boa sorte com o projeto! 🚀
