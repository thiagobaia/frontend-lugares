# Desafio de Frontend

## Descrição

Este desafio tem como objetivo avaliar as habilidades técnicas de desenvolvedor frontend React.
consiste em um aplicativo para programar viagens e locais que deseja conhecer.

#### O Desafio

Consiste em desenvolver um sistema que permita o CRUD de lugares para se conhecer ao redor do mundo. Como na imagem a seguir:

O Sistema deverá conter um formulário com 3 campos:

- País: um select contendo a lista de todos os países existentes;
- Local: um input para que o usuário digite o local que ele deseja conhecer no país selecionado;
- Meta: um input para que o usuário digite a o mês e o ano que ele pretende visitar o local em questão.

Quando o usuário clicar em "Adicionar", o formulário deverá ser resetado e o local deverá aparecer na listagem dos cards, como mostrado na imagem abaixo.

#### Layout do projeto
- O Layout apresentado na imagem abaixo pode ser encontrado no [Figma](https://www.figma.com/file/IC0xt3K3X21rLEfLRQ3mpl/Lugares-que-quero-conhecer?node-id=0%3A1);


<img src="src/img/icons/challenge.png" alt="Desafio" >

## Começando

Para rodar esse projeto na sua maquina, é necessário ter duas ferramentas instaladas em sua máquina, o [Git](https://git-scm.com/) e o [Node.js](https://nodejs.org/).

- Clone o projeto com os comando abaixo:
```
$ https://github.com/thiagobaia/clubpetro-frontend.git

$ cd clubpetro-frontend
```

- Logo após, instale todas as dependencias com:
```
$ yarn install
```

### Para iniciar um servidor de desenvolvimento
```
$ yarn dev
```

### Para iniciar api mock 
```
$ yarn server
```
### API e endpoints usado no projeto:
```
- Api paises

    * https://restcountries.eu
    
- Endpoint mock jsonserver

    * http://localhost:3004/cards
```

### Tecnologias e bibliotecas usadas no projeto: 
```
- React & TypeScript
- Styled Coponents
- Input Mask
- Axios 
- Json Server
```


