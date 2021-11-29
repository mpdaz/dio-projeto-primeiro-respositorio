# Comandos no Git Bash

#### Comandos de ajuda
* git --help
* git help
	Mostra lista de comandos do Git. O comando funciona com "--" ou sem.
* git help _comando_
	Mostra descri��o de um comando espec�fico.

#### Configura��o do Git
* git config --global user.email "_email_"
	Informa o email do usu�rio (igual ao GitHub).
* git config --global user.name "_nome_"
	Informa o nome do usu�rio (igual ao GitHub).

#### Criar/clonar resposit�rio
* git clone _link do diret�rio no GitHub_
	Clona um diret�rio do GitHub para a m�quina.
* git init _nome do reposit�rio_
	Cria um reposit�rio vazio.

#### Comitar modifica��es
* git status
	Verifica se h� modifica��es que n�o foram adicionaos � lista de arquivos que devem ser comitados
* git add .
	Adiciona os arquivos modificados � lista de arquivos que devem ser comitados.
* git commit -m "_descri��o do commit_"
	Registra as altera��es no reposit�rio
* git push origin main
	Envia os commits para o GitHub.