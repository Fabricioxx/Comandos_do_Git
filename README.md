# Comandos-do-Git
### Comandos mais utilizados do git.

---------------------------------------------------------------


_criar um repositorio local ,  add(alterar) nome e email_
>git init
>
>git config --global user.name "nome"  
>git config --global user.email "nome"@gmail.com.  

_sequência para fazer um commit_
>git status
>
>git add *
>
>git commit -m "mensagem sobre auteraçoes"
>
>git push -u origin master  ou  git push
>
>git push --set-upstream origin main ( se der problema ao enviar para o repositorio remoto )git 


_puxar dados do repositorio remoto_
>git clone htps://github.com/123456/123456.git
>
>git pull

_ver configuração do repositorio local_

> git config --global --list  ( listar nome e email do usuario configurado )
>
>git config user.name (mostrar nome configurado )
>
>git remote -v (mostrar nome do repositorio )
>
>git log ( ver historico de commits )

_checkout de branch_

> git checkout -b NOME-DA-NOVA-BRANCH ( nova  branch )
>
> git checkout -f nomeDaBranch - ( alterar entre branchs )











