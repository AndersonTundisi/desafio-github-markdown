# 🚀 Produtos e Funcionalidades do GitHub

O GitHub vai além de hospedar repositórios: oferece um ecossistema completo para **colaboração**, **automatização** e **gestão de projetos**.

---

## 📦 GitHub Pages

- Permite hospedar sites estáticos direto do repositório.
- Ideal para portfólios, documentações e projetos pessoais.

📘 Exemplo:  
https://seu-usuario.github.io/nome-do-repo/

---

## ⚙️ GitHub Actions

- Ferramenta de **CI/CD** integrada.
- Automatiza testes, deploys, builds e integrações.
- Workflows definidos em `.github/workflows/*.yml`

Exemplo:

name: Deploy
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - run: npm install && npm run build
      
🗂️ GitHub Projects
Gestão de tarefas com visual estilo Kanban.

Pode ser usado para sprints, bugs, backlog etc.

💬 GitHub Discussions
Canal de comunicação para dúvidas, feedbacks e debates.

Promove interação entre a comunidade e mantenedores.

🤖 GitHub Copilot
Assistente de código com IA (treinado em bilhões de linhas de código).

Sugestões inteligentes em tempo real.

Integrado ao VS Code e JetBrains.

🔐 GitHub Security
Dependabot: Atualiza automaticamente dependências vulneráveis.

Code scanning: Detecta falhas e práticas inseguras no código.
