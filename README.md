# Git-Flow-Testes

##  Comandos principais do Git

###  Clonar repositório
git clone <url>

###  Inicializar repositório
git init

###  Ver status
git status

###  Adicionar arquivos
git add .
git add nome-do-arquivo

###  Criar commit
git commit -m "mensagem do commit"

###  Enviar para o GitHub
git push origin main

###  Atualizar repositório
git pull origin main

---

##  Branches

### Criar branch
git branch nome-branch

### Trocar de branch
git checkout nome-branch

### Criar e trocar ao mesmo tempo
git checkout -b nome-branch

### Deletar branch
git branch -d nome-branch

---

##  Merge

git merge nome-da-branch

---

##  Correções de commits

### Alterar último commit
git commit --amend -m "nova mensagem"

### Remover arquivo do commit
git reset HEAD nome-do-arquivo

### Voltar commit
git reset --soft HEAD~1
git reset --hard HEAD~1

---

##  Envio de branch

git push origin nome-branch

---

##  Git Flow (conceito básico)

- main → produção
- develop → desenvolvimento
- feature → novas funcionalidades
- hotfix → correções urgentes

---

##  Fluxo básico GitFlow

1. Criar branch develop
2. Criar feature a partir de develop
3. Desenvolver
4. Merge na develop
5. Enviar para main quando pronto