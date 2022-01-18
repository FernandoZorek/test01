#Projeto test01

##Projeto para explorar 

API Restfull (GET, POST, PUT, DELETE)com interação com o Banco de dados utilizando Sequelize 
    • Tabela de produtos com os campos: 
    • Id – UUID (PK) NN 
    • Nome – String NN 
    • Estoque – Número NN 
    • Valor unitário – Número NN 
    • Foto – Arquivo 
    • Marca – Chave estrangeira NN 
    • Tabela de Marcas 
    • Id – UUID (PK) NN 
    • Nome – String NN 
    • A API GET precisa retornar o produto + a marca vinculada no mesmo JSON 
    • O projeto precisa ter um Docker-compose para subir a aplicação + MySQL 
    • Aplicação na porta 3306 
    • BD na porta 3308 
    • (+) Dentro do próprio backend terá um front para fazer as operações, com VueJS e UI Quasar 