#API-Restaurant-NodeJs.
 
 Projeto de uma API para um restaurante utilizando NodeJs com framework Express.

- Alcançado: Uma API de pedidos do restaurante. Abertura de mesa para pedidos do cliente, controle de abertura e fechamento de mesas, criação de pedidos, encerramento de mesa depois de pagamamento, e por fim, a mesa
volta a ficar disponível para novos clientes e pedidos.

- Foi desenvolvido com SQL Query Builder Knex.js.

____________________________________________________________________________________________________________________________________________________________________________________________________________________
____________________________________________________________________________________________________________________________________________________________________________________________________________________
- Migrations:
  
- um recurso importante para definir a estrutura das tabelas em um banco de dados porque permitem criar, modificar e gerenciar mudanças no banco de dados ao longo do tempo, possibilitando o versionamento do banco de dados
- Criação da Mesa.
- Criação dos Produtos.
- Criação da sessão da mesa para saber sua disponibilidade.
- Criação dos pedidos.

____________________________________________________________________________________________________________________________________________________________________________________________________________________
____________________________________________________________________________________________________________________________________________________________________________________________________________________
- Manipulações:
  
- Método Insert para inserir dados na tabela.
- Método RAW para escrever SQL no Query Builder, permitindo flexibilidade. inserir dados em uma tabela usando SQL, com a opção de concatenar valores.
- Método Select para listar os dados na tabela com ou sem parâmetros.
- Método Update para atualizar os dados recuperando o ID a ser atualizado e o nome a ser modificado no corpo da requisição filtrando com WHERE.
- Método Delete para remover os registros.
- Utilizado o recurso de SEED com o Knex para popular tabelas com vários registros de uma vez.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
____________________________________________________________________________________________________________________________________________________________________________________________________________________
- Relacionamentos:
  
- Criado o relacionamento dos Pedidos com a mesa utilizando o ID como parâmetro.
- Parâmetro: Primary Key com Foreign Key para obter os resultados de ambas em uma só.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
____________________________________________________________________________________________________________________________________________________________________________________________________________________
-------> Ferramentas:

- visualizar um banco de dados SQLite utilizando o Beekeeper:
![telabeekeeper](https://github.com/user-attachments/assets/068cae40-96a2-4509-8882-d4b7b3aa48c5)


- o uso do Insomnia para testar as requisições:
![telainsomnia](https://github.com/user-attachments/assets/a8c332a8-1558-47bb-8304-60280670bbea)

____________________________________________________________________________________________________________________________________________________________________________________________________________________
____________________________________________________________________________________________________________________________________________________________________________________________________________________

Tecnologias: TYPESCRIPT. NODEJS.
