# projeto-03
parte 03 do projeto 

Como utilizar a API
Para utilizar a API, é necessário realizar as seguintes etapas:

baixar o repositório do projeto para sua máquina local.

Certificar-se de que o Flask está instalado na máquina. Caso não esteja, utilize o seguinte comando no terminal para instalar: 

" pip install flask "

Executar o arquivo app.py no terminal com o seguinte comando: python app.py

Utilizar um software para realizar requisições HTTP, como o Postman ou o Insomnia.


-particularmente eu utilizei o POSTMAN

![image](https://user-images.githubusercontent.com/126974287/230821537-bafa918a-a587-43d3-a903-2e06a835b876.png)


ao instalar o postman, basta adicionar a rota do URL do projeto  para que possa ser feito alterações como:
1.adicionar personagem
2.remover personagem
3.ver os personagens criados

-ultilize a seguinte rota para a API:

- http://127.0.0.1:5000/personagens
![image](https://user-images.githubusercontent.com/126974287/230821389-fe0d50c8-0016-4993-a521-4d43386a3381.png)


Realizar as requisições para as rotas disponíveis, seguindo os métodos HTTP e os formatos de dados aceitos pela API.

Rotas disponíveis
A API possui as seguintes rotas disponíveis:

Consultar todos os personagens: GET /personagens
Consultar um personagem por ID: GET /personagens/{id}
Editar um personagem por ID: PUT /personagens/{id}
Criar um novo personagem: POST /personagens
Excluir um personagem por ID: DELETE /personagens/{id}
Consultar todos os personagens
A rota GET /personagens retorna todos os personagens cadastrados na API em formato JSON.

Consultar um personagem por ID
A rota GET /personagens/{id} retorna um personagem específico cadastrado na API, com base no seu ID, em formato JSON.

Editar um personagem por ID
A rota PUT /personagens/{id} permite editar um personagem cadastrado na API, com base no seu ID. É necessário enviar um JSON com os dados atualizados do personagem.

Criar um novo personagem
A rota POST /personagens permite criar um novo personagem na API. É necessário enviar um JSON com os dados do personagem a ser criado.

Excluir um personagem por ID
A rota DELETE /personagens/{id} permite excluir um personagem cadastrado na API, com base no seu ID.
