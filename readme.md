# Git/Github
## Olá, este projeto busca ser uma pequena ajuda para aqueles que não compreendem muito o Git/Github, estou fazendo também para não esquecer sobre os comandos e revisar alguns assuntos.

## **git --version**
### É uma forma de verificar a versão do Git

## **git init**
### Começa o repositório em determinada pasta, recomendável usar em arquivos de projetos para enviar ao repositório git

## **git add "exemplo.exe"**
### Adiciona determinado arquivo ao stage, arquivos que estão no stage estão preparados para serem commitados e as mudanças serem definidas no repositório

## **git status**
### Mostra a situação de arquivos, se precisam ser commitados ou se estão em staging, também mostram mais informações sobre arquivos que foram excluídos ou adicionados

## **git commit -m "mensagem do commit"**
### Faz o commit das alterações do projeto para mandar para o repositório, arquivos que estão em stage são salvos de forma definitiva no repositório local

## **git remote add origin <a href="https://github.com">linkrepositório.git</a>**
### Faz a ligação do repositório local com o remoto, o link deverá ser de um repositório criado remotamente

## **git push -u origin main**
### Envia os arquivos adicionados/alterados para o repositório remoto.

## **git branch -M main**
### Muda o nome da branch _master_ para a branch _main_

## **git checkout -b "nome-nova-branch"**
### Cria uma nova branch no repositório local e navega até a mesma

## **git branch**
### Lista as branches que há no repositório LOCAL

## **git branch -a**
### Lista as branches que há no repositório REMOTO

## **git checkout _branch_**
### Acessa a branch desejada no repositório pelo seu nome
Ex: _git checkout main_

## **git merge nova-branch**
### Usamos este comando para fazer o _merge_ de uma branch para a outra, o comando será usado na branch que está sendo acessada.
Ex: Se queremos fazer _merge_ de uma branch nova com a main devemos estar na main primeiramente e posteriormente usamos:
_git merge branch-nova_

## **git clone _link_**
### Clona um repositório remoto para o local

## **git pull _link_**
### Atualiza o repositório local a partir da versão remota