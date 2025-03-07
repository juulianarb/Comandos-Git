# Comandos-Git

git-init - Cria um repositório Git vazio ou reinicializa um existente.

git add . - Adicionar todos os arquivos existentes ao índice.

git commit - Registra o estado original como o primeiro commit no histórico.

git commit -m "mensagem do commit".

git push <repositório-remoto> <nome-da-branch> - Salva suas alterações ao servidor remoto.

git push -u origin <nome-da-branch> - Se a sua branch foi recém-criada, também é preciso fazer o upload da branch com o seguinte comando.

git push -u <local-remoto> <nome-da-branch> - Cria uma branch no local de trabalho para fazer o push (algo como enviar) da nova branch para o repositório remoto.

git pull <repositório-remoto> - git pull é usado para obter as atualizações de um repositório remoto. 

git clone - Permite clonar um repositório Git existente.

git status - Verifica o status dos arquivos no diretório de trabalho.

git branch <nome-da-branch> - Lista, cria ou exclui branches.

git branch ou git branch --list - Ver todas as branchs.

git branch -d <nome-da-branch> - Excluir uma branch.

{git checkout  <nome-da-branch> - Muda para a branch especificada.

*As alterações em sua branch atual devem estar em um commit ou em um stash antes de você fazer a troca.

*A branch na qual você quer fazer o checkout deve existir no seu espaço de trabalho local.

Comando de atalho para criar e trocar a branch ao mesmo tempo - 

git checkout -b <nome-da-branch>}

git tag - Cria, lista, exclui ou verifica tags.

git show - Permite ver as alterações que foram feitas no branch em que se está.

git log - Visualiza o histórico de commits.

git revert <Código hash ex:3321844> - Desfaz commits sem tocar no histórico de commits. (antes faça um git log -- oneline: para ver o histórico de commits)  shift + q para sair

git rm - Remove arquivos do git e para de monitorá-los
