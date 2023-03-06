Comandos GIT 

1 - git init #inicializa o repositório do GIT
2 - git add Readme.nd #adiciona o arquivo Readme.nd à área de stadding
3 - git status #retorna os arquivos a serem commitados
4 - git commit -m "título do commit" #comenta o arquivo adicionado à área de stadding
5 - git branch -M "main" #muda o nome da branch principal para main
6 - git remote add origin https://github.com/thomaslavruhin/THOMASGIT.git # conecta o repositório local(main) com o link do repositório do github(origin)
7 - $ git push -u origin main #envia os arquivos do repositório local(main) para o repositório do github(origin)
8 - git add . #envia todos os arquivos modificados para à área de stadding
9 - git checkout projetoPrincipal #Sai da branch main e vai para a branch projetoPrincipal
10 - git merge projetoPrincipal # junta tudo que foi feito na branch projetoPrincipal com a brach main (para dar esse comando é necessário estar na brach que será modificada, no caso a "main")