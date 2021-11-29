# Comandos no Git Bash

#### Comandos de ajuda
* git --help
* git help
	Mostra lista de comandos do Git. O comando funciona com "--" ou sem.
* git help _comando_
	Mostra descrição de um comando específico.

#### Configuração do Git
* git config --global user.email "_email_"
	Informa o email do usuário (igual ao GitHub).
* git config --global user.name "_nome_"
	Informa o nome do usuário (igual ao GitHub).

#### Criar/clonar respositório
* git clone _link do diretório no GitHub_
	Clona um diretório do GitHub para a máquina.
* git init _nome do repositório_
	Cria um repositório vazio.

#### Comitar modificações
* git status
	Verifica se há modificações que não foram adicionaos à lista de arquivos que devem ser comitados
* git add .
	Adiciona os arquivos modificados à lista de arquivos que devem ser comitados.
* git commit -m "_descrição do commit_"
	Registra as alterações no repositório
* git push origin main
	Envia os commits para o GitHub.