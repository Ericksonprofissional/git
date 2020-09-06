# git
Controle de versionamento de código


Aula1
Nesta aula, aprendemos:

O que são (e para que servem) sistemas de controle de versões e como eles podem ajudar o nosso fluxo de desenvolvimento
Nos ajudam a manter um histórico de alterações;
Nos ajudam a ter controle sobre cada alteração no código;
Nos ajudam para que uma alteração de determinada pessoa não influencie na alteração realizada por outra;
Etc.
O que é o Git e como instalá-lo
Que, com o comando git init, nós conseguimos criar um repositório Git;
Como analisar o estado do nosso repositório através do comando git status.

Aula2
Nesta aula, aprendemos:

Que um commit é a forma de salvar um estado ou versão do nosso código;
Como adicionar arquivos para serem commitados com git add;
Como commitar arquivos, utilizando o comando git commit;
Como verificar o histórico de commits, através do git log e algumas de suas opções:
git log --oneline
git log -p
git log --pretty="parametros de formatação"
Como fazer o Git não monitorar arquivos, através do .gitignore
Que não devemos realizar commit, ou seja, salvar um estado, da nossa aplicação que não esteja funcionando.

Aula3
Nesta aula, aprendemos:

O que são repositórios remotos;
Como criar um repositório Git sem uma cópia dos arquivos (com --bare) para ser utilizado como servidor;
Como adicionar links para os repositórios remotos, com o comando git remote add;
Como baixar um repositório pela primeira vez, clonando-o com o comando git clone;
Como enviar as nossas alterações para um repositório remoto, com git push;
Como atualizar o nosso repositório com os dados no repositório remoto, utilizando git pull;
O que é e para que serve o GitHub;
Como criar um repositório no GitHub;
Como adicionar um repositório do GitHub como repositório remoto.

aula5
Nesta aula, aprendemos:

Que o Git pode nos ajudar a desfazer alterações que não vamos utilizar;
Que, para desfazer uma alteração antes de adicioná-la para commit (com git add), podemos utilizar o comando git checkout -- <arquivos>;
Que, para desfazer uma alteração após adicioná-la para commit, antes precisamos executar o git reset HEAD <arquivos> e depois podemos desfazê-las com git checkout -- <arquivos>;
Que, para revertermos as alterações realizadas em um commit, o comando git revert pode ser a solução;
Que o comando git revert gera um novo commit informando que alterações foram desfeitas;
Que, para guardar um trabalho para retomá-lo posteriormente, podemos utilizar o git stash;
Que, para visualizar quais alterações estão na stash, podemos utilizar o comando git stash list;
Que, com o comando git stash apply <numero>, podemos aplicar uma alteração específica da stash;
Que o comando git stash drop <numero> remove determinado item da stash;
Que o comando git stash pop aplica e remove a última alteração que foi adicionada na stash;
Que o git checkout serve para deixar a cópia do código da nossa aplicação no estado que desejarmos:
git checkout <branch> deixa o código no estado de uma branch com o nome <branch>;
git checkout <hash> deixa o código no estado do commit com o hash <hash>.