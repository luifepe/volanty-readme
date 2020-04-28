## Prerequisitos / Instalação

* **`npm install`**


# Match-making

A Match-making é um aplicativo feito no ambiente React-hooks, no qual o usuário pode fazer comparações de vários bancos de dados carregados no servidor

Primeiramente na tela de login, teremos a opção de usar nosso correio já cadastrado na máquina

![FazendoLogin](https://user-images.githubusercontent.com/52355873/80542017-a417d300-8982-11ea-9c0e-01daf6f254aa.gif)

Logo enseguida, aparecera na tela as cards de comparação com os bancos de datos, à esquerda, teremos o banco de dados base para obter os dados, por definição, a base é da Webmotors, porém teremos uma opção de fazer Upload de um banco diferente, no card central e na direita, teremos os cards onde poderemos visualizar os matchs, por definição, as tabelas de matchs contém as bases de dados da Localiza e da Movida respetivamente.

![ComparandoTabelas](https://user-images.githubusercontent.com/52355873/80542014-a2e6a600-8982-11ea-8933-797013f25dbd.gif)

Depois de encontrar matchs nas diferentes bases de datos, poderemos enviar a uma tabela donde poderemos editar se for preciso, pudendo, adicionar dados, ou remover.

![EditandoTabelaDeMatchs-](https://user-images.githubusercontent.com/52355873/80542010-a11ce280-8982-11ea-895f-a92b9ef9b66f.gif)


Se deseja fazer um novo processo de Match pode clicar no botão **`Novo Match`**,  voltara na tela principal.

![ProcurandoMatchNovo](https://user-images.githubusercontent.com/52355873/80542036-ada13b00-8982-11ea-97fd-a1253613f4cd.gif)



* **`URL Base para consulta`** [Match] (https://match-api-rest.herokuapp.com)


## Rotas

* **`/match`** - Posta um novo Match no banco de dados
* **`/match/all`** - Retorna todos os matches já feitos 
* **`/match/:id`** - Retorna um match específico de acordo com o Id 
* **`/match/delete/:id`** - Deleta um match específicado por Id 
* **`/match/update/:id`** - Atualiza um match específicado por Id







