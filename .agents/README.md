# .agents

Agente para gerar mensagens de commit no padrão Conventional Commits.

## Uso rápido

1. Gere o diff das mudanças (staged ou working tree):

```bash
git diff --staged > /tmp/diff.txt
```

2. Alimente o conteúdo do diff para o agente `conventional_commit_agent.yml` na sua ferramenta de IA (Cursor/CLI/Outro) usando a variável `{{diff}}`.

3. Copie a mensagem produzida e faça o commit:

```bash
git commit -m "$(cat /tmp/mensagem.txt)"
```

## Padrão

- Site: https://www.conventionalcommits.org/pt-br/v1.0.0/
- Estrutura: `tipo(escopo opcional): assunto`
- Tipos comuns: feat, fix, docs, style, refactor, perf, test, build, ci, chore, revert

Exemplo:

```
feat(aulas): adicionar exercícios contextualizados na revisão

inclui 50 problemas reais por tema com gabarito
melhora engajamento e clareza dos objetivos

Refs: #12
```
