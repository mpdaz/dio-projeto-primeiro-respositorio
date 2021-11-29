# Comandos no Git Bash

#### Comandos de ajuda
* git --help
* git help<br>
Mostra lista de comandos do Git. O comando funciona com "--" ou sem.
* git help _comando_<br>
Mostra descri��o de um comando espec�fico.

#### Configura��o do Git
* git config --global user.email _email_<br>
Informa o email do usu�rio (igual ao GitHub).
* git config --global user.name "_nome_"<br>
Informa o nome do usu�rio (igual ao GitHub).
* git config --list<br>
Para ver as configura��es feitas no Git.

#### Criar/clonar resposit�rio
* git clone _link do diret�rio no GitHub_<br>
Clona um diret�rio do GitHub para a m�quina.
* git init _nome do reposit�rio_<br>
Cria um reposit�rio vazio.

#### Comitar modifica��es
* git status<br>
Verifica se h� modifica��es que n�o foram adicionaos � lista de arquivos que devem ser comitados
* git add .<br>
Adiciona os arquivos modificados � lista de arquivos que devem ser comitados.
* git commit -m "_descri��o do commit_"<br>
Registra as altera��es no reposit�rio
* git push origin main<br>
Envia os commits para o GitHub.