# 🧱 Conceitos de Git

Este documento resume os principais conceitos e comandos do **Git**, sistema de controle de versão distribuído utilizado por desenvolvedores para gerenciar o histórico de alterações em projetos.

---

## 📌 O que é Git?

- Git é um sistema de versionamento criado por Linus Torvalds.
- Permite registrar o histórico de modificações em arquivos e projetos.
- É distribuído: cada desenvolvedor tem uma cópia completa do repositório.

---

## 🔁 Ciclo de vida dos arquivos no Git

1. **Modified** – Arquivo foi alterado.
2. **Staged** – Alterações preparadas para commit.
3. **Committed** – Alterações salvas no histórico do repositório.

---

## 🔧 Comandos básicos

git init                # Inicia um novo repositório Git

git status              # Verifica o estado dos arquivos

git add arquivo.txt     # Adiciona um arquivo ao staging

git commit -m "mensagem" # Cria um commit

git log                 # Exibe o histórico de commits

git diff                # Mostra diferenças entre arquivos

🌐 Trabalhando com repositórios remotos

git remote add origin <url>   # Adiciona um repositório remoto

git push -u origin main       # Envia as alterações

git pull origin main          # Atualiza com alterações remotas

git clone <url>               # Clona um repositório remoto

🔀 Branches
Utilizadas para desenvolver funcionalidades isoladamente.

Exemplo:
git checkout -b nova-feature

git switch main

git merge nova-feature

🧠 Dica
"Commite cedo, commite com frequência. Documente bem cada mudança."

