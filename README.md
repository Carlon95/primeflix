# PrimeFlix

![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)
![React](https://img.shields.io/badge/React-18.2.0-blue)
![Node.js](https://img.shields.io/badge/Node.js-16.x-green)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Downloads](https://img.shields.io/badge/downloads-1k-brightgreen)

## Descrição

PrimeFlix é uma aplicação web que oferece uma interface para explorar, buscar e assistir trailers de filmes e séries. O projeto consome dados da API do [The Movie Database (TMDb)](https://www.themoviedb.org/) para exibir conteúdos atualizados, categorizados e organizados de forma simples e intuitiva.

Este projeto é ideal para quem deseja aprender sobre integração com APIs externas, React.js, consumo de dados e criação de interfaces modernas para catálogos de mídia.

## Demonstração Online

Acesse a aplicação no link abaixo para testar sem necessidade de instalação:

[PrimeFlix Online](https://primeflix-2ic7e3g78-carlon95s-projects.vercel.app/)

## Funcionalidades

- Busca de filmes e séries por título
- Exibição de detalhes como sinopse, avaliação, data de lançamento
- Categorias com listas de filmes populares, em alta, lançamentos etc.
- Interface responsiva e amigável
- Player de trailers integrado

## Screenshots

  
_Tela inicial mostrando filmes populares_

 
_Tela de busca por título_


_Detalhes do filme com sinopse e player de trailer_

> **Obs:** Para adicionar as imagens, crie a pasta `/screenshots` na raiz do projeto e adicione os arquivos de imagem lá.

## Tecnologias Utilizadas

- [React.js](https://reactjs.org/) 18.2.0
- [Axios](https://axios-http.com/) para requisições HTTP
- CSS Modules / Styled Components para estilização
- API TMDb para dados de filmes e séries

## Requisitos

- Node.js 16.x ou superior
- npm 8.x ou superior (ou yarn)

## Como Rodar Localmente

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/primeflix.git
Entre na pasta do projeto:

bash
Copiar
Editar
cd primeflix
Instale as dependências:

bash
Copiar
Editar
npm install
# ou
yarn install
Crie um arquivo .env na raiz do projeto e adicione sua chave da API TMDb:

ini
Copiar
Editar
REACT_APP_TMDB_API_KEY=sua_api_key_aqui
Inicie o servidor de desenvolvimento:

bash
Copiar
Editar
npm start
# ou
yarn start
Acesse no navegador: http://localhost:3000

Estrutura do Projeto
bash
Copiar
Editar
/src
  /components   # Componentes React reutilizáveis
  /pages        # Páginas da aplicação
  /services     # Configuração da API e requisições
  /styles       # Arquivos CSS e estilizações
  App.js        # Componente principal
  index.js      # Ponto de entrada
Roadmap
 Integração com API TMDb para exibir filmes e séries

 Sistema de busca por título

 Visualização de detalhes do filme com trailer

 Implementar sistema de login de usuário

 Permitir salvar filmes favoritos

 Adicionar avaliações e comentários dos usuários

 Melhorar o layout para dispositivos móveis

 Suporte a múltiplos idiomas (i18n)

 Deploy automatizado via CI/CD

Como Contribuir
Contribuições são bem-vindas! Para contribuir:

Faça um fork do projeto

Crie uma branch para sua feature (git checkout -b feature/nova-feature)

Faça commit das suas alterações (git commit -m 'Adiciona nova feature')

Faça push para a branch (git push origin feature/nova-feature)

Abra um Pull Request aqui no GitHub

Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Desenvolvido por: Carlos Pimenta
Contato: carlon95s@gmail.com
LinkedIn | GitHub
