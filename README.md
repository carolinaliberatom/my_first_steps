1 - https://github.com/carolinaliberatom/my_first_steps

2 - echo "# my_first_steps" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/carolinaliberatom/my_first_steps
git push -u origin main

3 - echo "# Primeiro_repositório" >> ola_mundo.txt
git status
git add .
git commit ola_mundo.txt -m "questao3"
git push

4 - echo "# sono" >> serei_ignorado.txt
touch .gitignore
git status
echo serei_ignorado.txt >> .gitignore
git add
git commit .gitignore -m "questao4"
git push
