git add .

(caso queira ver o status)
git status

git commit -m "nome-projeto"

(só para fazer a ponte na primeira vez)
git remote add origin https://github.com/meu-user/nome-projeto.git

git push -u origin main || git push origin main

--------------------------------------------------------------

git checkout -b "nome-branch" || git checkout "local"  (main, etc...)

(juntar alteracoes branch com a main/outra) (deve estar na pasta que vc quer que receba as alteracoes)
git merge local onde esta com as alteracoes