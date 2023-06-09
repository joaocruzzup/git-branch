# Anotação de estudos do uso das branchs e do git clone

Esse repositório tem como intuito a criação de um tutorial para o uso do git clone e as branchs. Você pode visualizar o tutorial tanto por esse readme.md como pelo arquivo `tutorial.md`.

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
Abaixo há uma imagem explicando como é a visualização de uma branch. 
Na imagem as bolinhas são os commits e as cores distinguem a branch, ao criar uma nova branch é possível realizar commits normalmente, 
e quando estiver finalizado é possível realizar o `merge` de forma que todas as informações ficarão unidas na branch principal main.

![Imagem branch](https://github.com/joaocruzzup/git-branch/blob/main/branch-explicacao.jpg)
fonte: imagem modificada do [site](https://www.nobledesktop.com/learn/git/git-branches)

Utilizando o git branch:

- Passo 1: Abra o git bash no diretório escolhido;
- Passo 2: Verifique quais branchs você tem atualmente com o comando `git branch`, a branch atual estará com um asterisco na frente;
- Passo 3: Caso queira uma nova branch digite `git checkout -b nome_da_branch`;
- Passo 4: Caso deseje mudar de branch digite `git checkout nome_da_branch`;
- Passo 5: Para dar um git push com determinada branch utilize `git push origin nome_da_branch`;

Pronto! Com isso já é possível gerenciar e utilizar as suas branchs!

### Seção de Créditos das Imagens
A imagem [branch-explicacao](https://github.com/joaocruzzup/git-branch/blob/main/branch-explicacao.jpg) foi utilizada e modificada do [site](https://www.nobledesktop.com/learn/git/git-branches)
