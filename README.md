# Comandos Básicos **Git Bash**  
  

  * ### Versão do Git

    > **git --version**

Configuração do Git informação sobre usuario que esta utilizando o git
git config --global user.name "Nome_do_usuário"

Configuração do Git informação sobre e-mail que esta utilizando o git
git config --global user.email "seu@email.com"

Criar Agente no GitBash para vincular ao github
eval $(ssh-agent)

Vincular Key SSH do github ao Git
ssh-add Key_SSH

Confirmar se esta logado
ssh -T git@github.com


==========================
Clonar (copiar) um repositorio do github para a maquina (local).
git clone "HTTPS_DO_REPOSITORIO_GITHUB"

Vincular um repositorio do github com o diretorio local.
git remote set-url origin "SSH_DO_REPOSITORIO_GITHUB"
==========================

Criação de novo repositorio (Adicionar o diretorio "pasta" ao Git)
git init

Alterar a nomenclatura da branch principal para Main
git branch -m main

Status dos arquivos se estão no repositorio
git status

Adicionar o arquivos do diretorio (repositorio) para rastreio do git
git add "nome_do_arquivo"

Adicionar todos arquivos do diretorio (repositorio) para rastreio do Git
git add .

Enviar as alterações realizadas no diretorio (repositorio) para registro
git commit -m "mensagem_informações_sobre_o_commit"

Mostra o historico de commit realizados
git log

Ver alterações realizadas nos arquivos
git diff

Adicionar o repositorio remoto ao diretorio da maquina
git remote add origin "HTTPS_DO_REPOSITORIO_GITHUB"

Comando para envio dos arquivos do repositorio local (maquina) "commitados" para o github (repositorio remoto).
git push -u origin main

Verificar em qual repositorio do githut o seu diretorio da maquina esta vinculado
git remote -v



# Comandos Básicos **CMD**  
* ### Listar Aquivos e pastas

    > **Dir**  

    > **Ls**

    > **Ls -a**

* ### Acessar pasta Raiz  

    > **Cd**

* ### Acessar pasta desejada  

    > **Cd "nome_da_pasta"**  

* ### Acessar nivel anterior da pasta  

    > **Cd ..**  

* ### Criar Pasta  

    > **mkdir > "nome_da_pasta"**  

* ### Deletar Pasta  

    > **rmdir > "nome_da_pasta"**

* ### Criar Arquivo

    > **echo > "nome_do_arquivo.txt"**

* ### Deletar Arquivo

    > **rm > "nome_do_arquivo.txt"**

* ### Limpar tela  

    > **Clear**  

* ### Abrir Arquivo  

    > **code "nome_do_arquivo"**  

* ### Fechar Git Bash  

    > **Exit**  

