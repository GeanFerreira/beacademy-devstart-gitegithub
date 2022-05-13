# Conhecendo o Git e Github
 O GIT é um repositório de controle de versão de arquivos, utilizado para controlar versões de códigos-fontes e desenvolvimento colaborativo.
 
## Como instalar GIT em Linux Debian/Ubuntu
  - abra o terminal
  - apt-get install git
  - git -- version (para verificar se o GIT está instalado)
 
## Como configurar o GIT
  - abra o terminal
  - git config --global user.name "Seu nome"
  - git config --global user.email "seuemail@domain.com"
 
  
## Comandos básico utilizado no GIT
 + git status - Verificar estado dos arquivos/diretórios
 + git init - Criar novo repositório
 + git add <nome_do_arquivo.txt> - Adicionar arquivo específico
 + git add . - Adiciona todos os arquivos/diretórios
 + git rm --cached - desfaz o git add <arquivo>
 + git log - Exibir histórico
  
 + git branch - Mostrar em qual branch eu estou
 + git branch <nome_da_branch> - Criar uma nova branch
 + git checkout <nome_da_branch> - Mudar de branch
 + git checkout -b <nome_da_branch> - Criar e mudar de branch
 + git checkout -d <nome_da_branch> - Remover branch
 + git commit -m "Adicionar sua mensagem sobre o que foi feito" - 'Comitar' informando uma mensagem
 + git push - Enviar o repositório local para um repositório remoto
  
  
 ####Autor
  - Gean Marcel Ferreira (https://github.com/GeanFerreira)
  
 #####Agradecimentos:
  Aos instrutores Regis e Luan da beacademy, que me ajudodaram a entender como funciona o controle de versão utilizando Git e Github.
