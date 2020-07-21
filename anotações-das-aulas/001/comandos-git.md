`git init` - Inicia o rastreamento do git na pasta local.

`git status` - Verifica o que está acontecendo na pasta.

`git add <nomedosarquivos>` - Selecionar os nomes dos arquivos para ir ao commit.

`git add .` - Selecionar todos os arquivos de uma só vez para ir ao commit.

`git commit -m`(Pasta old que você criava para o ponto de restaura do código) - Ponto de checkpoint. Enviando os nossos arquivos para o repositório local. 

`git commit -am` - Ponto de checkpoint. Enviando os nossos arquivos para o repositório local, porém esse comando funciona apenas para os arquivos modificados e não novos.

`git log` - Podemos ver todos os commit´s que fizemos. Seja eles seus ou de seu time.

`O que é hash?` - É o nome do commit. Quando damos um git commit e depois damos um git log, aparece alguns caracteres estranhos. Isso é a hash. Podemos pegar essa hash para modificar ela em dúvidas futuras. É o nome do checkpoint por exemplo.

`git remote` - Para fazer a ligação do repositório local com o remoto

`git push` - Para empurrar nossos arquivos ao repositório remoto

`git reset --soft` - Para excluir o último commmit. Pegando a hash do penultimo commit iremos excluir o último.

`git commit -m "Mensagem correta" --amend` - Para corrigir a mensagem que foi enviada errada para o commit.