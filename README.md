# TreinamentoGit
Treinamento Git - Utilização e comandos básicos para utilizar o Git:

## Clonar um repositório de uma base Git
- git clone \<url>
Ex: git clone https://github.com/Cacatuaa/TreinamentoGit.git

>_Obs: depois de clonar, abra o git bash dentro da basta clonada!_
 
## Criar uma branch
- git branch \<nome>
Ex: git branch cacatua

## Alterar a branch
- git checkout \<nome da branch>
Ex: git checkout cacatua

## Verificar o status atual da branch (seja alteração, exclusão ou incremento)
- git status

## Colocar os arquivos no modo _staged_
- git add <nome do arquivo ou . para adicionar todos>
Ex: git add Cacatua/teste.txt
Ex: git add .
  
## Retirar algum arquivo do modo _staged_
- git reset HEAD <nome do arquivo> ou -git reset
Ex: git reset HEAD Cacatua/teste.txt

## _Commitar_ os arquivos que estavam no staged
- git commit -m 'nome do projeto - descrição do que rolou'
Ex: git commit -m 'Cacatua - Inclusão de arquivos'

>_Obs: é bacana colocar um padrão como primeiro parâmetro, como nome do projeto, versão ou o autor_

Para enviar as mudanças que você realizou para a base do Git
- git push origin <nome da branch>
git push origin cacatua

Para atualizar tudo:
- git checkout main
- git pull
