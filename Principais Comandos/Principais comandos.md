# Primeiros passos com Git utilizando Windows 10 
## O que é o Git?
- Git é um sistema distribuído opensource de controle de versão

## Instalando o Git no Windows
- Acessar o link [git para Windows](https://git-scm.com/download/win)
- Realizar a instalação
- Deixa marcado as opções: Git BASH e Git GUI

## Iniciando um repositorio no Git
- Criar uma pasta de trabalho:
- C:/Users/user/my_project

- Acessar o Git BASH, navegar até a pasta: cd /Users/user/my_project
- Iniciar o repositório do git: git init
- Irá criar uma pasta .git
- Para apagar um repositório execute: rm -rf .git

## Principais comandos:

## git config
Quando você está utilizando o Git pela primeira vez ou com uma instalação nova, em um projeto colaborativo, esse comando é fundamental para configurar sua identidade de usuário, inserindo informações como nome e email que serão empregadas em cada commit.

- git config –global user.name “Seu nome”
- git config –global user.email “Seu email”

## git remote add <nomecurto> <url>
- Estabelece uma conexão entre seu repositório local e um repositório remoto.
## git clone <https://url-do-link>
- Clona um repositorio do GitHub para sua máquina
## git checkout <nome-da-ramificação>
- Muda de branch
## git status
- Verificar arquivos modificados: 
## git add <arquivo>
- Para incluír alterações para o próximo commit 
## git commit -m "mensagem explicando a mudança no código"
- Define um ponto de verificação 
## git push <remote> <nome-do-branch>
- Enviar as alterações para o servidor remoto
  
## git pull <URL>
- O comando Git pull baixa o conteúdo (não os metadados) do que foi alterado no repositório remoto para o seu repositório local e imediatamente atualiza seu contreúdo para a última versão.