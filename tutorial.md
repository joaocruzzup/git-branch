# Tutorial git clone

Para clonar um repositório utilizando o `git clone` é necessário seguir os seguintes passos:

- Passo 1: Ir ao diretório local onde você deseja clonar o diretório do github;
- Passo 2: Abrir o git bash no diretório escolhido;
- Passo 3: Ir ao github (sem fechar o git bash) no repositório que você deseja clonar
- Passo 4: Busque o botão "<> Code";
- Passo 5: Clique no botão e copie o link HTTPS do repositório;
- Passo 6: digite o seguinte comando: `git clone "cole_aqui_o_link_https"`

Após seguir esses passos, o repositório remoto já estará clonado no seu diretório local escolhido, parabéns!

# Tutorial git branch 

Em resumo, uma branch é uma ramificação do código. É possível ter várias branchs dentro de um código.

Utilizando o git branch:

- Passo 1: Abra o git bash no diretório escolhido;
- Passo 2: Verifique quais branchs você tem atualmente com o comando `git branch`, a branch atual estará com um asterisco na frente;
- Passo 3: Caso queira uma nova branch digite `git checkout -b nome_da_branch`;
- Passo 4: Caso deseje mudar de branch digite `git checkout nome_da_branch`;
- Passo 5: Para dar um git push com determinada branch utilize `git push origin nome_da_branch`;

Pronto! Com isso já é possível gerenciar e utilizar as suas branchs!