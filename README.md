Meu primeiro repositório git!!
git init - Para que a pasta se torne um repositório git.
git branch - Para verificar em qual branch estou.
git branch -m main - Para renomear a branch atual (no inicio, no caso, a branch denominada master) para main.
git config --global init.defaultBranch main - Para configurar o nome main ( como padrão).
git status - Para verificar a situação atual do repositório e informa quais arquivos foram modificados, quais estão sendo monitorados etc. git status pode ser utilizado sempre que você quiser verificar o que foi alterado.
git config --global user.name "Nome Sobrenome" - Para configurar o nome e sobrenome para o git.
git config --global user.email "SEU_EMAIL" - Para configurar o e-mail para o git, pois será usado para conectar ao github.
git config user.name - Para conferir se a configuração do nome e sobrenome funcionou.
git config user.email - Para conferir se a configuração do e-mail funcionou.
code . - Para abrir o repositório no VS Code.
git add - Adicionar a alteração realizadas em stage(ou staging) na branch. git add . ou git add nome-do-arquivo nome-do-outro-arquivo adicionam as modificações em staging e informam ao Git que as modificações realizadas vão estar no próximo commit;
git add . - Adiciona todas as alterações realizadas em stage(ou staging) na branch.
git add nome do arquivo - Adiciona apenas as alterações feitas nesse arquivo realizadas em stage(ou staging) na branch.

* Uma boa prática é utilizar o comando git status antes de git add para checar quais arquivos foram modificados. Dessa forma, você consegue visualizar quais arquivos sofreram alteração e garantir que vai executar o comando git add . sem enviar arquivos indesejados.

Você também pode usar o git status após o git add. Essa ação vai mostrar quais arquivos estão na zona de stage ou staging, isto é, a área de arquivos que estão preparados para serem enviados no próximo commit. * 

git commit -m "Mensagem sobre as alterações realizadas" - informa quais alterações foram realizadas e cria uma versão do projeto que pode ser acessada a qualquer momento;

* O hábito de realizar commits com frequência é considerado uma boa prática, pois facilita o acompanhamento das alterações e a correção de possíveis erros em seu código. Evite commits muito extensos e/ou com muitas alterações. * 

git checkout -b nome-da-branch - Para criar uma nova branch e acessá-la e escolher o nome que quiser para a sua branch.

* Você pode criar quantas branches (ramificações) forem necessárias, bem como criar novas branches a partir de branches já existentes. Para verificar em qual branch você está, utilize o comando git branch ou, se preferir, verifique o lado inferior esquerdo do seu VS Code, local em que há a informação da branch em que você está atualmente. * 

git checkout main - Acessar a branch main.
git merge nome-da-branch - Estando na branch em que deseja realizar o merge, em que nesse caso o "nome-da-branch" é o nome da branch que foi criada para realizar as alterações.

