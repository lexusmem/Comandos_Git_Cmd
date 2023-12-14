# Comandos Básicos **Git Bash**  
* ### Versão do Git

    > **git --version**

* ### Configuração do Git informação sobre usuário que esta utilizando o git

    > **git config --global user.name "Nome_do_usuário"**

* ### Configuração do Git informação sobre e-mail que esta utilizando o git

    > **git config --global user.email "seu@email.com"**

> [Youtube Ignorância Zero - Git e Github - Setup](https://youtu.be/alxRKszfTck)

* ### Criar Agente no GitBash para vincular ao github

    > **eval $(ssh-agent)**

* ### Vincular Key SSH do github ao Git

    > **ssh-add Key_SSH**

* ### Confirmar se esta logado

    > **ssh -T git@github.com**

* ### Clonar (copiar) um repositório do github para a maquina (local).

    > **git clone "HTTPS_DO_REPOSITORIO_GITHUB"**

* ### Vincular um repositório do github com o diretório local.

    > **git remote set-url origin "SSH_DO_REPOSITORIO_GITHUB"**

* ### Criação de novo repositório (Adicionar o diretório "pasta" ao Git)

    > **git init**

* ### Alterar a nomenclatura da branch principal para Main

    > **git branch -m main**

* ### Status dos arquivos se estão no repositório

    > **git status**

* ### Verificar se o repositorio local esta atualizado com relação ao Github online (site)

    > **git fetch**

* ### Atualizar repositorio local conforme consta online no Github

    > **git pull**

* ### Adicionar o arquivos do diretório (repositório) para rastreio do git

    > **git add "nome_do_arquivo"**

* ### Adicionar todos arquivos do diretório (repositório) para rastreio do Git

    > **git add .**

* ### Enviar as alterações realizadas no diretório (repositório) para registro

    > **git commit -m "mensagem_informações_sobre_o_commit"**

* ### Mostra o histórico de commit realizados

    > **git log**

* ### Ver alterações realizadas nos arquivos

    > **git diff**

* ### Adicionar o repositório remoto ao diretório da maquina

    > **git remote add origin "HTTPS_DO_REPOSITORIO_GITHUB"**

* ### Comando para envio dos arquivos do repositório local (maquina) "repositório" para o github (repositório remoto).

    > **git push -u origin main**

* ### Verificar em qual repositório do GitHut o seu diretório da maquina esta vinculado

    > **git remote -v**

* ### Remover repositório local do git (parar de rastrear determinada pasta)

    > **rm -rf "nome_do_arquivo"**  

* ### Excluir arquivo commitado do git

    > **git rm "nome_do_arquivo"**  

* ### Restaurar arquivo excluído no git

    > **git log --diff-filter=D --summary**  
    > **git checkout "id_do_commit"~1 "nome_do_arquivo"**  

# Comandos Básicos **CMD**  
* ### Listar Aquivos e pastas

    > **Dir**  

    > **Ls**

    > **Ls -a**

    > **Dir -a**  

* ### Acessar pasta Raiz  

    > **Cd**

* ### Acessar pasta desejada  

    > **Cd "nome_da_pasta"**  

* ### Acessar nível anterior da pasta  

    > **Cd ..**  

* ### Acessar outra unidade  

    > **X:**

* ### Criar Pasta  

    > **mkdir > "nome_da_pasta"**  

* ### Deletar Pasta  

    > **rmdir > "nome_da_pasta"**

* ### Criar Arquivo

    > **echo > "nome_do_arquivo.txt"**

* ### Criar arquivo com lista nome dos arquivos que consta na pasta

    > **dir> "nome_do_arquivo.txt"**

* ### Deletar Arquivo

    > **rm "nome_do_arquivo.txt"**

* ### Limpar tela  

    > **Clear**  

* ### Abrir Arquivo  

    > **code "nome_do_arquivo"**  
    > **start code "nome_do_arquivo"** 

* ### Ler arquivo no terminal  

    > **cat "nome_do_arquivo"**  

* ### Fechar Git Bash  

    > **Exit**  
