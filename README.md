# Comandos do Git

Este repositório reúne os comandos mais utilizados do Git, essenciais para o dia a dia de qualquer desenvolvedor. Os exemplos abaixo podem ser copiados diretamente para o terminal.

---

## 📦 Inicialização & Configuração

```bash
# Inicializar um novo repositório Git
git init

# Configurar nome e e-mail do usuário
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```

## 🗂️ Controle de Versão

```bash
# Verificar o status dos arquivos
git status

# Adicionar todos os arquivos ao staging
git add *

# Criar um commit
git commit -m "mensagem sobre alterações"
```

## 🔄 Envio e Sincronização com o Remoto

```bash
# Enviar alterações para o remoto
git push -u origin master        # Ou git push
git push --set-upstream origin main  # Configura o branch main para rastrear o remoto
```

## ⬇️ Puxar dados do repositório remoto

```bash
# Clonar repositório
git clone https://github.com/usuario/repositorio.git
git clone <url_do_repositorio> --mirror   # Clonar com todas as branches

# Buscar atualizações
git pull
git pull upstream main
git pull origin main
```

## 🔍 Ver configuração do repositório local

```bash
git config --global --list   # Listar nome e email do usuário configurado
git config user.name         # Mostrar nome configurado
git remote -v                # Mostrar nome do repositório remoto
git log                      # Ver histórico de commits
```

## 🌲 Gerenciamento de Branches

```bash
git checkout -b nomeNovaBranch    # Criar nova branch
git checkout nomeDaBranch         # Alterar entre branches
```

## 🔀 Merge (Unir branch com main/master)

```bash
git checkout main                 # Ir até a main
git merge nomedabranch            # Une a branch com a main/master
git add .
git commit -m "mensagem"
git push origin master
```

## 📚 Referências e Ajuda

```bash
git help
git comando --help
```

- [Documentação Oficial do Git](https://git-scm.com/doc)
- [Guia rápido de comandos Git](https://rogerdudler.github.io/git-guide/index.pt_BR.html)

---

Sinta-se à vontade para contribuir ou sugerir novos comandos! 🚀
