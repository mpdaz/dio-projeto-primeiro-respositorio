# Comandos no Git Bash

#### Comandos de ajuda
* git --help
* git help<br>
Mostra lista de comandos do Git. O comando funciona com "--" ou sem.
* git help _comando_<br>
Mostra descrição de um comando específico.

#### Configuração do Git
* git config --global user.email _email_<br>
Informa o email do usuário (igual ao GitHub).
* git config --global user.name "_nome_"<br>
Informa o nome do usuário (igual ao GitHub).
* git config --list<br>
Para ver as configurações feitas no Git.

#### Criar/clonar respositório
* git clone _link do diretório no GitHub_<br>
Clona um diretório do GitHub para a máquina.
* git init _nome do repositório_<br>
Cria um repositório vazio.

#### Comitar modificações
* git status<br>
Verifica se há modificações que não foram adicionaos à lista de arquivos que devem ser comitados
* git add .<br>
Adiciona os arquivos modificados à lista de arquivos que devem ser comitados.
* git commit -m "_descrição do commit_"<br>
Registra as alterações no repositório
* git push origin main<br>
Envia os commits para o GitHub.