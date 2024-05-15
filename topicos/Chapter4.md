## 4. Versionamento do repositório

Até aqui, vimos a parte de instalação do git e github e a criação de repositórios, contudo, em um ambiente colaborativo/corporativo, é normal que mais de uma pessoa precise trabalhar no mesmo código ao mesmo tempo, que pode gerar um dos problemas mais comuns (e chatos) de tratar, que são os conflitos.

Para isso, é utilizada a lógica de branchs, que consiste em basicamente criar uma cópia separada de um estado do código, onde é possível editar sem alterar de fato o código original. Com a possibilidade de ser incorporado no código original por meio de um "merge".

No git, para criarmos uma branch, basta usar o comando ```git branch <nome da branch>```. E então, para nos deslocarmos para esta, usamos ```git checkout <nome da branch>```

![alt text](/assets/image-3.png)

Notem que no bash, a branch saiu de (main) para (teste), o que significa que todas as alterações feitas nessa nova branch, pertencerão a essa nova branch ao invés de alterar diretamente a main.

> Os comandos para adicionar, commit continuam os mesmos, contudo, no caso do push, precisamos alterar o nome da branch, agora, no caso, seria: ```git push origin teste```


### Merge de Branches

Dada a necessidade de juntar o código de uma ou mais branches em um branch destino padrão, temos o comando ``` git merge branch_alteraçoes ```. Onde branch_alterações corresponde à branch onde as alterações estão. Esse comando deve ser realizado na branch de destino, a que receberá as alterações das branchs mais externas.

![alt text](/assets/flow-teste.png)



> Boa prática na organização das branches: Criar uma ramificação intermediária para desenvolvimento, servindo para receber as alterações de várias branches antes de ir para a main, com o objetivo de proteger o estado do código principal
![alt text](/assets/flow-dev.png)

