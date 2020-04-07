# Desafio 3 - Conceitos de ReactJS
O objetivo do desafio é criar um aplicação para treinar os conhecimentos aprendidos sobre ReactJS.

## Sobre
Deve-se criar uma aplicação para comunicar com a api do desafio anterior, que permita criar, listar e remover repositórios.

### Funcionalidades da aplicação

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista com o campo **title** de todos os repositórios que estão cadastrados na sua API.

- **`Adicionar um repositório a sua API`**: Deve ser capaz de adicionar um novo item na sua API através de um botão com o texto **Adicionar** e, após a criação, deve ser capaz de exibir o nome dele após o cadastro.

- **`Remover um repositório da sua API`**: Para cada item da sua lista, deve possuir um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do seu frontend e da sua API.

### Específicação dos testes

Para esse desafio temos os seguintes testes:

- **`should be able to add new repository`**: Para que esse teste passe, sua aplicação deve permitir que um repositório seja adicionado ao seu backend e listado no seu frontend dentro de uma `LI`.

- **`should be able to remove repository`**: Para que esse teste passe, sua aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `LI` do repositório adicionado

## Tecnologia
Este projeto foi desenvolvido utilizando as seguintes tecnologias:

- [ReactJS](https://pt-br.reactjs.org/)
- [Jest](https://jestjs.io/)

## Instalação e Execução
1. Faça a instalações dos pacotes executando o comando: 
```bash 
yarn
```

2. Execute a aplicação com o comando: 
```bash 
yarn dev
```

3. Execute os testes com o Jest utilizando o comando: 
```bash
yarn test
```

## Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/AleixoGJunior/desafio-conceitos-reactjs/blob/master/LICENSE) para mais detalhes.

