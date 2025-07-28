# 🔐 Administração e Gerenciamento de Repositórios GitHub

Este documento traz as principais práticas e configurações administrativas para manter repositórios GitHub organizados, seguros e colaborativos.

---

## 🧑‍💻 Permissões de Acesso

| Papel        | Permissões principais                      |
|--------------|--------------------------------------------|
| **Owner**    | Controle total do repositório              |
| **Admin**    | Gerencia configurações e colaboradores     |
| **Write**    | Push/pull, cria branches e PRs             |
| **Read**     | Apenas leitura do código e issues          |

---

## 🔒 Proteção de Branches

Para proteger a branch `main` contra alterações indesejadas:

1. Acesse *Settings > Branches > Add Rule*.
2. Selecione a branch `main`.
3. Ative:
   - ✅ Require pull request reviews
   - ✅ Require status checks
   - ✅ Include administrators (opcional)

---

## 🔄 Pull Requests

- Permitem integrar mudanças por meio de revisão.
- Favorecem colaboração, revisão de código e testes.

Etapas:
1. Criar nova branch
2. Fazer commit das alterações
3. Abrir um PR para `main`
4. Solicitar revisão
5. Após aprovação, fazer merge

---

## 📊 Insights do Repositório

- Métricas de contribuição, frequência de commits e participação.
- Caminho: *Insights > Contributors*

---

## 🧼 Boas práticas de administração

- Manter a `main` protegida e estável
- Nomear branches de forma padronizada (`feature/`, `fix/`, `hotfix/`)
- Usar arquivos como:
  - `README.md`: Documentação principal
  - `LICENSE`: Tipo de licença (MIT, GPL etc.)
  - `CONTRIBUTING.md`: Como contribuir com o projeto
  - `CODE_OF_CONDUCT.md`: Regras de conduta para a comunidade

---

## 📁 Templates e Arquivos Especiais

| Arquivo            | Função                                           |
|--------------------|--------------------------------------------------|
| `.gitignore`       | Define o que o Git deve ignorar                 |
| `LICENSE`          | Define os termos de uso do projeto              |
| `README.md`        | Apresenta o repositório                         |
| `CONTRIBUTING.md`  | Instruções para contribuir                      |
| `.github/ISSUE_TEMPLATE` | Modelos para abrir issues                 |
