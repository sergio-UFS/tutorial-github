## 6. Fixando o conteúdo

Com todo o conhecimento apresentado anteriormente, já podemos aplicar esse conhecimento em um projeto pessoal. Lembrando que esse exercício usará as ferramentas do github para auxílio de algumas operações, ou seja, alguns comandos serão ocultados, mas explicados como fazer sem o github posteriormente. Além disso, haverá a resposta de cada parte do exercício.

Recomenda-se tentar fazer todos os passos antes de checar a aba de resposta, assim, é mais fácil de fixar e é possível conferir depois.

### 1. Criar e clonar o repositório

Antes de mais nada, é obrigatório possuir um repositório para ser trabalhado, seja criando um novo, ou reutilizando algum que já possua.

Após criar, clone esse repositório localmente em sua máquina.

<details>
  <summary>Resposta Q1</summary>
  
  Para esse passo, após criar o repositório diretamente no github além disso, é necessário clonar o repositório localmente. Para isso, podemos utilizar o gitCLI, com o comando ```git clone <link_do_repositório>```. Além disso, caso esteja utilizando o github Desktop, basta acessar a aba superior ```File -> Clone Repository``` e escolher a pasta de alocação.
  
</details>


### 2. Adicionar novos arquivos no repositório remoto

Nessa etapa, basta criar um novo arquivo README.md (caso não tenha sido criado na criação do repositório) com alguma descrição do repositório ou um texto de escolha. Depois isso, adicione esse arquivo no github remotamente e atualize a main com as alterações.

<details>
  <summary>Resposta Q2</summary>
  
  Nesse passo, é necessário apenas criar um arquivo, seja localmente ou no github, realizar algumas alterações e subir no github por meio do "combo" de comandos 
  ```
  git add .
  git commit -m "First Commit"
  git push origin main
  ```
  
</details>

### 3. Realize alterações em um branch diferente da main

Nessa etapa, basta criar uma nova Branch e realizar alterações (criar novos arquivos, editar o arquivo inicial). Depois isso, suba suas alterações na branch de trabalho.

<details>
  <summary>Resposta Q3</summary>
  
  Para criar uma nova branch, utilizamos os dois comandos:
  ```
  git branch nova_branch
  git checkout nova_branch
  ```
  Depois disso, basta alterar alguns detalhes no arquivo e, novamente, subir o código.
  
</details>

### 4. Junte as alterações feitas em outro branch, na main. 

Com essas alterações feitas, ao voltar para a main, por meio do ```git checkout main```. é notado que as alterações ficaram em outra branch, traga as alterações da outra branch, para a main

<details>
  <summary>Resposta Q4</summary>
  
  Para juntar alterações de uma branch diretamente na linha de comando, precisamos nos deslocar para a branch de destino, a que queremos que as alterações sejam inseridas, nesse caso, a main. Então, basta aplicar ``` git merge nova_branch```
  
</details>

### 5. Crie uma nova issue e adicione um arquivo de código simples e cria um branch para trabalhar nesta.

No github, crie uma issue de seu agrado, que justifique uma nova alteração. Depois disso, crie uma branch de desenvolvimento para aquela issue por meio de sua página no github e faça o checkout para ela.

<details>
  <summary>Resposta Q5</summary>
  
  Para esse passo, basta abrir a aba de issues do repositório e criar uma nova issue, depois disso, basta ir na aba development, na página da issue e criar uma branch. Depois isso, basta acessar a nova branch via checkout. Talvez, necessite do comando ```git fetch origin``` para atualizar o estado do repositório
  
  
</details>

### 6. Crie um Pull Request do branch trabalhado para a main, checando os conflitos.

Com as alterações feitas, é hora de trazer todo o código para a branch principal. Para garantir que nada será perdido, crie um pull Request e analise a possibilidade de merge.

<details>
  <summary>Resposta Q6</summary>
  Na aba de Pull Request, basta escolher a main como destino e a branch de desenvolvimento como origem e comparar as alterações. Criando assim, o pull request.
  
  
</details>

### 7. Faça o merge do seu novo código com a main através do Pull Request.

Depois de checkar, basta realizar o merge e fechar o Pull Request.

<details>
  <summary>Resposta Q7</summary>
  Depois disso, basta avaliar se há algum conflito e realizar o merge das branches, depois disso, é possivel fechar o Pull Request.
  
  
</details>

