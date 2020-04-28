## Prerequisitos / Instalação

* **`npm install`**


# Match-making

App de comparações entre diferentes bancos de dados de venta de veiculos.

# Funcionamento

Tela de login com opção de usar correio já cadastrado da Volanty na máquina

![FazendoLogin](https://user-images.githubusercontent.com/52355873/80542017-a417d300-8982-11ea-9c0e-01daf6f254aa.gif)

Tela de comparação de dados entre diferentes bancos de veiculos 

![ComparandoTabelas](https://user-images.githubusercontent.com/52355873/80542014-a2e6a600-8982-11ea-8933-797013f25dbd.gif)

Tela onde poderemos editar se for preciso, pudendo, adicionar dados, ou remover.

![EditandoTabelaDeMatchs-](https://user-images.githubusercontent.com/52355873/80542010-a11ce280-8982-11ea-895f-a92b9ef9b66f.gif)

Para um novo processo de Match pode clicar no botão **`Novo Match`**.

![ProcurandoMatchNovo](https://user-images.githubusercontent.com/52355873/80542036-ada13b00-8982-11ea-97fd-a1253613f4cd.gif)



* **`URL Base para consulta`** [Match] (https://match-api-rest.herokuapp.com)


## Rotas

* **`/match`** - Posta um novo Match no banco de dados
* **`/match/all`** - Retorna todos os matches já feitos 
* **`/match/:id`** - Retorna um match específico de acordo com o Id 
* **`/match/delete/:id`** - Deleta um match específicado por Id 
* **`/match/update/:id`** - Atualiza um match específicado por Id







