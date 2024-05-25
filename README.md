# Comandos-do-Git
### Comandos mais utilizados do Git

---------------------------------------------------------------

#### Criar um repositório local e adicionar/alterar nome e email

>git init
>
>git config --global user.name "nome"
>
>git config --global user.email "nome@gmail.com"


Sequência para fazer um commit
>git status
>
>git add *
>
>git commit -m "mensagem sobre alterações"
>
>git push -u origin master  # ou git push
>
>git push --set-upstream origin main //Para enviar este novo branch main para o repositório remoto e configurá-lo para rastrear automaticamente o branch remoto



Puxar dados do repositório remoto
>git clone htps://github.com/123456/123456.git ou git clone <url_do_repositorio> --mirror ( clonar com todas as branchs )
>
>git pull
>
>git pull upstream main

Ver configuração do repositório local

> git config --global --list  ( listar nome e email do usuario configurado )
>
>git config user.name (mostrar nome configurado )
>
>git remote -v (mostrar nome do repositorio )
>
>git log ( ver historico de commits )

Checkout de branch

> git checkout -b nomeNovaBranch (criar nova  branch )
>
> git checkout -f nomeDaBranch - ( alterar entre branchs )

Merge (unir a branch com main)

> git checkout main - ( ir ate a main )
>
> git merge nomedabranch - ( une a brench com a master )
>
> git add .
>
> git commit -m"xxx"
> 
> git push origin master






