## Removendo arquivos e pastas do Repositótio do GitHub

#### Remover o arquivo/diretório dos arquivos monitorados. Perceba que o arquivo não foi excluído, somente removido dos arquivos trackeados.
- git rm -rf --cached folder1/
- Se for um arquivo, vc não adicionará o -rf nem a barra no final.

#### Adicionar o arquivo/diretório no .gitignore 
 - echo "folder1/" > .gitignore

#### Realizar um novo commit.
- git add .gitignore 
- git commit -m 'adicionado gitignore e removido folder1/'
- git push origin main

Depois do commitvc envia novamente para o Github, desta vez, o arquivo/diretório removido não será enviado. Ao final, o arquivo removido do track continua no projeto, mas não será mais commitado.