## 2. Instalando o git

Após baixar o git, basta apenas abrir e seguir os passos de instalação. Com isso, já podemos utilizar o "bash" do git. Então, para testar, basta:
- Criar uma pasta
- Adicionar um arquivo .txt e preencher 
- Abrir o git bash
- Digitar ```git init``` (Esse comando serve para iniciar um repositório git localmente)


Para registrar as alterações feitas, utilizamos um conjunto quase indispensável de comandos. (Depois de um tempo, já fica no automático 😂)

1. O git status, que serve para mapear arquivos que foram alterados e ainda necessitam ser adicionados no commit
```
git status  

``` 

2. o git add serve para adicionar um ou mais arquivos para serem commitados
```bash
git add .  #adiciona todos os arquivos do repositório 
git add <arquivo> #adiciona um arquivo específico para o commit
``` 

3. já o git commit, que é um dos comandos-chave da colaboração, com ele é possível usar o código alterado e devidamente adicionado para o commit em um "pacote" de alterações que será enviado ao repositório.
```bash
git commit -m "Primeiro commit" 

``` 

4. Ademais, temos o comando git push, que pega os commits pendentes na sua máquina e joga diretamente no repositório. O deixando disponíveis para consumo de outros colaboradores.

```bash
git push origin <branch>
```