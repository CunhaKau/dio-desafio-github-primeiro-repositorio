[Link de Download do Git](https://git-scm.com/downloads)

O GitBash é uma extensão do terminal para otimizar o uso do Git.

## Comandos Básicos do Git/GitHub

- git clone (é um comando para baixar o código-fonte existente de um repositório remoto, salvando uma cópia do projeto no computador) exemplo: git clone <https://link-com-o-nome-do-repositório>
- git branch (Branches são ramificações para devs trabalharem em paralelo) exemplo: git branch <nome-da-branch>
- git checkout serve para trocar de uma branch para outra exemplo: git checkout <nome-da-branch>
- git status mostra todas as informações necessárias sobre a branch atual
- git add para inclusão de alterações de um ou vários arquivos em nosso próximo commit, exemplo: git add <arquivo> já para adicionar tudo ao mesmo tempo: git add -A
- git commit serve para salvar as alterações até o momento, precisamos escrever uma mensagem sobre o que fizemos, exemplo: git commit -m "mensagem do commit"
- git push envia as alterações após o commit para o servidor remoto, exemplo: git push <repositório-remoto> <nome-da-branch> se sua branch foi recém criada use: git push --set-upstream <repositório-remoto> <nome-da-branch> ou git push -u origin <nome-da-branch>
- git pull é usado para obter as atualizações de um repositório remoto, exemplo: git pull <repositório-remoto>
- git revert desfaz as alterações que fizemos, para isso precisamos ver o histório primeiro exemplo: git log --oneline, em seguida é necessário especificar o código hash ao lado do commit que desejamos desfazer, exemplo: git revert 3321844 e depois shit+q para sair
- git merge para unir a atualização da Branch no Projeto, primeiro git checkout dev, depois git fetch para atualiza a local e por fim: git merge <nome-da-branch-com-o-recurso>