# GIT

- git status
    //Retorna qual é o estado de como estão os status das diferentes "áreas" do git;
    ex.: Fiz alterações, quero commit-á-las MAS não dei "git add .";

- git init
    //Inicializa um repositório .git na sua pasta local;

- git clone
    //Inicializa um repositório .git, porém, clonando um repositório já existente para a sua pasta local;
    ex.: git clone "https://github.coom/algum-repositorio.git

- git remote add origin [link para o repositório remoto]
    Pede para o git atribuir um repositório remoto à uma variável específica.
    Por convenção, nós damos a essa variável o nome "origin".
    ex.: git remote add origin "https://github.coom/algum-repositorio.git

- git add .
    //Rastrear todas as alterações, adições e remoções feitas nos arquivos da pasta que contém o .git

- git commit -m "Alguma coisa"
    //Criar alguma referencia para as alterações feitas no git add .
    Você pode ver todos os commits do projeto através do comando git log --all

- git checkout
    //Acessar um commit ou branch especifico. Permite navegar entre branchs.
 ex: git checkout "EF023298328943FE20" //commit
 ex: git checkout estilizacoes //branch

- git checkout -b [nome da branch]
    //Cria uma nova branch (assim como o git branch) com o nome especificado e faz checkout para aquela branch criada.

- git branch [nome da branch]
    //Adiciona uma nova branch

- git branch -a
    // Lista todas as branchs criadas no projeto

- git branch -d
    //Deleta uma branch com o nome passado no terminal git
    Tem que estar em outra branch para excluir a branch atual. Para sair da branch, usar git checkout

- git merge [nome da branch que você deseja trazer as alterações]
    //Utilizado para mesclar alterações feitas em duas branchs

- git push [nome da variavel do repositorio local] [nome da branch]
    //Utilizado para enviar as modificações de uma branch local a uma branch do repositorio remoto
    ex: git push origin master

- git push --set-upstream [nome da variavel do repositorio local] [nome da branch]
    //Utilizado para explicitar que queremos fazer push para uma branch especifica.

- git pull [nome da variavel do repositorio local] [nome da branch]
    //Utilizado para enviar as modificações de uma branch do repositorio remoto a uma branch local
    ex: git push origin master






- git merge