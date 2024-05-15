## 3. Conexão com o GitHub

Aprendido como criar um repositório local, é importante saber como trazer um repositório do github para o repositório local e vice-versa.

Primeiramente, caso ainda não tenha um repositório que queira clonar do git, basta acessar o [Github](https://github.com) e criar um novo repositório.

![alt text](/assets/image.png)

É nessa tela que algumas configurações são definidas, como a visibilidade, o nome e a licença

![alt text](/assets/image-1.png)

Com o Repositório criado e o git instalado, basta que criemos uma pasta de interesse de onde esse repositório ficará e abrir o git bash. Feito isso, basta utilizar o comando ``` git clone <link do repositório>.git ```

> O  link do repositório é o link dele no github com .git no final, também é encontrado ao clicar em code e https ![alt text](/assets/image-2.png)


Caso queira começar a colaboração e adicionar mais pessoas para terem acesso e colaborarem em seu projeto, basta acessar a aba de settigns do seu projeto e ir na aba de colaboradores. Ainda que seu projeto seja público, ele é apenas livre para fork e visualização, mas não para edição, a não ser que seja criado um request ou seja solicitado acesso a este. 

![alt text](/assets/colaboration.png)

Com o repositório devidamente clonado em sua máquina, é possível realizar as operações-chave para a colaboração, como:

```
git add .
git commit -m "mensagem"
git push origin branch_atual
```

Ademais, além dessas operações serem realizadas na linha de comando, o github possui o [Github Desktop](https://desktop.github.com/). Que é uma plataforma desktop que ajuda no monitoramento de alterações no código e permite realizar commits, pushs e até clonar o repositório diretamente por ele, sem necessitar os comandos do git CLI.

![alt text](/assets/gh-desktop.png)


Além disso, de maneira complementar e muito útil, existem algumas extensões no VSCode que ajudam no monitoramento de alterações e também pode poupar o uso de alguns comandos. 

![alt text](/assets/vscode-img.png)

