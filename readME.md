git --version

git config --global user.name "Some name here!"

git config user.name

Some name here!

git config --global user.email "Some email here!"

git config user.email

Some email here!

Obs: Se vc estiver com varios valores no user.name (ou user.email), e todos eles forem o "="
utilize esse comando: git config --global --replace-all user.name "Some name here"

Após inicializar o usuario, vc deve entrar na pasta do seu projeto e utilizar o seguinte comando: git init

git add .

git commit -m "Initial Commit"

git push -u origin master

git clone https://github.com/jaymeco/Trainee_Aula_2021.git

git pull origin master