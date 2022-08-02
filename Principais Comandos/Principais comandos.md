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
- git clone <https://url-do-link>
  Clona um repositorio do GitHub para sua máquina
  
- git checkout <nome-da-ramificação>
  Muda de branch

- git status
  Verificar arquivos modificados: 

- git add <arquivo>
  Para incluír alterações para o próximo commit
  
- git commit -m "mensagem explicando a mudança no código"
  Define um ponto de verificação
  
- git push <remote> <nome-do-branch>
  Enviar as alterações para o servidor remoto