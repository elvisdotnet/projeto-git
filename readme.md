Aprendendo e treinando comandos git.
Instrutora: Rafaella Ballerini.

----

git --version --> Versão do Git instalada.

----

git init
--> Inicia um repositório git vazio.

----

git add
--> Adiciona a "staging area" ("área de preparação/espera para o commit"), os arquivos modificados e novos.

git add arquivo.extensao (git add readme.md)

-----

git status
--> Mostra as mudanças a serem commitadas e se há arquivos modificados para adicionar.

----

git commit -m
--> Registra as alterações no controle de versão, é como uma "fotografia" do código no momento.

git commit -m "texto do commit"

----

//Após criar o repositório no github:

----

git remote add origin https://github.com/elvistrindade/nome-do-repositorio.git
--> Vincula o respositório local ao repositório remoto (GitHub) .

----

git push -u origin main
--> "Empurra os arquivos para o repositório.

----

git branch -M "nomedabranch" --> Modifica o nome da branch principal, caso seja necessário.

----

