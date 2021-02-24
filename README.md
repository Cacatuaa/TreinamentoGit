# TreinamentoGit
Treinamento Git - Utilização e comandos básicos:

Para clonar um repositório de uma base Git
- git clone <url>
git clone https://github.com/Cacatuaa/TreinamentoGit.git
*Obs: depois de clonar, abra o git bash dentro da basta clonada
 
Para criar uma branch sua
- git branch <nome>
git branch cacatua

Para alterar de branch que você está utilizando
- git checkout <nome da branch>
git checkout cacatua

Para verificar o status atual da branch (seja alteração, exclusão ou incremento)
- git status

Para colocar os arquivos no modo staged
- git add <nome do arquivo ou . para adicionar todos>
git add Cacatua/teste.txt
git add .
  
Para retirar algum arquivo do modo staged
- git reset HEAD <nome do arquivo> ou -git reset
git reset HEAD Cacatua/teste.txt

Para commitar os arquivos que estavam no staged
- git commit -m 'nome do projeto - descrição do que rolou'
git commit -m 'Cacatua - Inclusão de arquivos'
*Obs: é bacana colocar um padrão como primeiro parametro, como nome do projeto, versão ou o autor

Para enviar as mudanças que você realizou para a base do Git
- git push origin <nome da branch>
git push origin cacatua

Paraa atualizar tudo:
- git checkout main
- git pull
