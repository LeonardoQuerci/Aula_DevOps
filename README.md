# ♾️ DevOps: Versionamento de Código com Git

Este repositório foi criado para documentar e armazenar os aprendizados práticos da disciplina de **DevOps**, com foco inicial em **Versionamento de Código** utilizando o Git.

O objetivo principal é dominar as ferramentas que permitem o rastreamento de alterações, colaboração em equipe e a manutenção da integridade do código em projetos de software, preparando a base para fluxos de CI/CD.

---

## 🎯 Objetivos de Aprendizado

Nesta etapa da disciplina, o foco está em entender o ciclo de vida do desenvolvimento de software através de:
* **Controle de Histórico:** Entender o que foi alterado, por quem e por quê.
* **Trabalho em Equipe:** Gerenciar conflitos e integrar códigos de diferentes desenvolvedores.
* **Ciclo de Vida do Arquivo:** Dominar os estados `Untracked`, `Modified`, `Staged` e `Committed`.

## 🛠️ Comandos Praticados

Aqui estão os comandos fundamentais que compõem o fluxo de trabalho neste repositório:

```bash
# 1. Configuração e Início
git init                         # Inicializa um novo repositório local
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"

# 2. Fluxo de Trabalho (Snapshot Local)
git status                       # Verifica o estado dos arquivos
git add .                        # Adiciona todos os arquivos à Stage Area
git commit -m "sua mensagem"     # Grava a alteração no histórico local

# 3. Sincronização Remota
git remote add origin <url>      # Conecta ao repositório remoto (ex: GitHub)
git push origin main             # Envia as alterações locais para o servidor
git pull origin main             # Traz as atualizações do servidor para o local
