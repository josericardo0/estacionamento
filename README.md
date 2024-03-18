# API de Gerenciamento de Estacionamento

Desafio/projeto prático para o desenvolvimento de uma API Restful para gerenciar um estacionamento de carros com Java e Spring, seguindo a ideia proposta pelo dev brabissimo e também meu parceirão, Gilberto Neto. De acordo com o repositório : 
https://github.com/GilbertoNeto/desafio-estacionamento

## Funcionalidades principais da API:

- **Consulta de Vagas Disponíveis:** Visualizar a quantidade de vagas disponíveis no estacionamento.
- **Posição das Vagas Disponíveis:** Obtenher uma lista das posições das vagas disponíveis.
- **Estacionamento de Carros:** Estacionar um carro no estacionamento, respeitando a quantiadade de vagas.
- **Consulta do Valor do Ticket:** Calcular o valor a ser pago pelo tempo de permanência do carro no estacionamento.
- **Pagamento do Ticket:** Registrar o pagamento e liberar a vaga do carro.
- **Relatório Gerencial:** Gerar um relatório com a quantidade de veículos estacionados e o total recebido.


## Serviços a serem desenvolvidos:

- [ ] Consultar valor do ticket a ser pago
- [ ] Pagamento do ticket
- [ ] Estacionar o veículo em vaga disponível 
- [ ] Consultar quantidade de vagas disponíveis 
- [ ] Listar as vagas disponíveis
- [ ] Relatório gerencial com quantidade de veículos estacionados e somatório dos pagamentos realizados (JSON)




## Especificações técnicas:

- **Versão do Java:** Para esse projeto, optei por usar o Java 21.
- **Versão do Spring Boot:** Usando a versão 3.2.0
- **Gerenciador de dependências:** Maven
- **Banco de dados:** PostgreSQL rodando em container Docker.
