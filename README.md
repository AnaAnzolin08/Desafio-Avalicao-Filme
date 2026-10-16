# Projeto - Avaliação de Filmes

## Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio de estudos em programação e testes de software.

O objetivo é analisar avaliações de filmes, calcular a quantidade de votos e a média arredondada para o inteiro mais próximo, e classificar cada filme de acordo com a média.

As classificações são:

- **Filme recomendado:** média igual ou superior a 4.
- **Filme razoável:** média igual ou superior a 3 e menor que 4.
- **Filme ruim:** média menor que 3.

## Tecnologias utilizadas

- [Node.js](https://nodejs.org/): ambiente de execução JavaScript.
- [Mocha](https://mochajs.org/): framework utilizado para executar os testes automatizados.


## Como executar o projeto

1. Instale as dependências:

	```bash
	npm install
	```

2. Execute os testes automatizados:

	```bash
	npm test
	```

## Testes automatizados

Os testes verificam a classificação de filmes nas três categorias, médias arredondadas e o processamento de uma lista de filmes mantendo a ordem recebida.
