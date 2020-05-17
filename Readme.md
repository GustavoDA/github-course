# Git Course

Este e um repositorio teste para mostrar como o git funciona

Comandos aprendidos: 

git --version : comando para verificar a versao do git.

git config --global user.name "username": Comando para definir o usuário do git globalmente.

git config --global user.email "email" : 

git init : inicia um repositorio local.

git status : comando para verificar o status.

git log : verifica o histórico de commits.

git add : adiciona arquivos a staging.

git add [nome-arquivo.extensao] : adiciona o arquivo a staging.

git add - A : Adiciona todos os arquivos novos e alterados a staging.

git commit -m  : cria um commit contendo as mudanças para o repositorio com uma mensagem.

git shortlog : retorna um histórico simplificado dos commits.

git show [ID_Commit]: comando que mostra as alteraçoes feitas no commit.

git diff : comando que mostra todos os conflitos entre arquivos.

git diff [nome-arquivo.extensao] : comando que exibe as diferenças entre o arquivo original e o alterado.

git restore [nome-arquivo.extensao] : restaura o conteudo do arquivo para o correspondente da origem, caso seja um novo arquivo o mesmo é excluido. 

git reset (--soft | --hard | --mixed) [ID_Commit]: retorna o repositorio para a versao do commit passado, podendo manter ou nao os arquivos alterados dependento do comando utilizado.
