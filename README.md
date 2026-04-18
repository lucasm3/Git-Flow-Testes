# Git-Flow-Testes


Configuração inicial:
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"

Clonar repositório:
git clone <url-do-repositorio>
cd nome-do-repositorio

Verificar status:
git status

Adicionar arquivos:
git add arquivo.txt
git add .

Criar commit:
git commit -m "mensagem do commit"

Enviar para o repositório:
git push origin main

Atualizar repositório:
git pull origin main

Criar branch:
git checkout -b nome-da-branch

Trocar de branch:
git checkout nome-da-branch

Listar branches:
git branch

Deletar branch:
git branch -d nome-da-branch

Ver histórico:
git log
git log --oneline

Corrigir commit:
git commit --amend

Desfazer commit mantendo alterações:
git reset --soft HEAD~1

Desfazer commit apagando tudo:
git reset --hard HEAD~1

Ignorar arquivos (.gitignore):
node_modules/
.env

GitFlow (conceito):
main -> produção
develop -> desenvolvimento
feature -> novas funcionalidades
release -> preparação de versão
hotfix -> correções urgentes

Exemplo GitFlow:
git checkout develop
git checkout -b feature/login
git checkout develop
git merge feature/login
git branch -d feature/login

