# CLI - GitHub

<aside>
💡 **Utilize a ferramenta que tiver mais familiaridade.**

Os comandos abaixo devem ser utilizados  em qualquer terminal da sua máquina, após fazer a instalação do **git bash.**

**Referência:** [https://rogerdudler.github.io/git-guide/index.pt_BR.html](https://rogerdudler.github.io/git-guide/index.pt_BR.html)

</aside>

## Comandos

---

- **Configurações iniciais** *(inserir o seu nome e e-mail)*

```bash
git config --global user.name "John Doe" 
git config --global user.email "johndoe@example.com"
```

- **Criar um repositório local**

```bash
git init
```

- **Verificar status do repositório**

```bash
git status
```

- **Adicionar todos os arquivos para um novo commit**

```bash
git add .
```

- **Adicionar um novo commit**

```bash
git commit -m "Descrição do commit"
```

- **Configurar repositório remoto** *(endereço do seu repositório)*

```bash
git remote add origin https://github.com/dideconto/teste.git
```

- **Enviar commits para o repositório remoto**

```bash
git push
```

- **Clonar repositório remoto**

```bash
git clone https://github.com/dideconto/teste.git
```

- **Requisitar novas atualizações do repositório**

```bash
git pull
```

---

## Atalhos

---

- Executar os dois comandos abaixo para abrir o arquivo de configurações do git no visual studio code

```bash
git config --global core.editor code --wait
git config --global --edit
```

- Alterar o arquivo aberto para configurar os atalhos ao CLI do git

```bash
[core]
	editor = code --wait
[user]
	email = dideconto@gmail.com
	name = Diogo Deconto
[alias]
  s = !clear & git status -s
	c = !clear & git add . & git commit -m
	l = !clear & git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(yellow)%cr'
	amend = !clear & git add . && git commit --amend --no-edit
```

---