## 5. Ferramentas do Github para facilitar o versionamento de código e colaboração 

### 5.1 Github Desktop

O Github Desktop é um Software do próprio Github para facilitar as operações de git, sem a necessidade de utilizar as linhas de comando. Nele é possível monitorar os arquivos alterados, realizar os commits e os pushs diretamente e até resolver conflitos. Além disso, permite criar branchs e clonar os repositórios diretamente.

![alt text](/assets/image-4.png)

>Eu, particularmente, uso essa ferramenta em 90% do tempo, principalmente pela praticidade.

### 5.2 Issues

O uso de issues do github é uma maneira muito interessante de separar as tarefas por problema a ser resolvido, seja ele de qual for o tamanho. Por meio da issue, é possível criar uma pagina de interação envolvendo o problema a ser resolvido, sendo possível, além disso, associar a projetos em andamento, milestones, definir quem está resolvendo aquela issues, além de permitir comentários sobre a issue, permitindo que revisores, usuário e outros desenvolvedores possam colaborar na resolução da issue. 

Além disso, é possível associar uma branch diretamente à cada issue, criando uma ramificação por problema a ser resolvido, o que facilita a organização e ajuda no controle das versões.

![alt text](/assets/image-5.png)

![alt text](/assets/image-6.png)


### 5.3 GitHub Projects

O GitHub Projects é uma ferramenta de organização de tarefas, podendo assumir vários formatos e organizações, como por data, listas de tarefas, e até quadro interativo, que é o formato mais comum de utilização. Essa ferramenta funciona diretamente com o conceito das issues. Permitindo que sejam classificadas por seu tamanho, prioridade, dificuldade, ou qualquer outro critério tomado. Com esse, é mais simples trabalhar com as issues, já que todas as issues estão, além de listadas, organizadas. 

![alt text](/assets/image-7.png)


### 5.4 Pull Requests

Pull Request consiste, resumidamente em uma proposta de junção de branch. O PR, comumente chamado, é um pedido de que uma branch faça merge em outra. Geralmente uma branch mais externa com uma branch mais importante. Por exemplo: 

![alt text](/assets/image-9.png)


Se eu crio um Pull Request da branch: ```1-adicionar-topico-6``` para a ```main ```. Minha intenção é que as alterações realizadas na minha branch de issue sejam incorporadas na branch principal. Além disso, os Pull Requests permitem que vejamos se esse merge pode ser feito automaticamente e traz uma interface para que essas alterações sejam visualizadas graficamente. 

![alt text](/assets/image-8.png)

Outro detalhe interessante é que podem ser cadastrados revisores para cada Pull Request, solicitando que alguém revise manualmente o código antes de ser puxado pra a main.

![alt text](/assets/image-10.png)