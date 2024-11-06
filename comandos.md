## criar nova branch e ir pra nova branch
git checkout -b nome-nova-branch

## criar nova branch e permanecer na mesma branch
git branch nome-nova-branch

## mostrar as branchs criadas e a ativa
git branch

## analisar o status do repositório/branch
git status

## preparando arquivo pro commit
git add nome-do-arquivo

ou 

git add . <!--commita todos os arquivos-->

## fazendo o envio
git commit -m "mensagem"

## subindo para o servidor
git push

ou 

git push -u origin nome-da-branch

## descartar o commit
git reset nome-do-arquivo <!--descarta o arquivo do commit-->

ou 

git reset . <!--descarta todo o commit-->