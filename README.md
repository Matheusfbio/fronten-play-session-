# Projeto Front-End

### Objetivo

Este projeto consiste na criação de um aplicativo React utilizando Vite, com o objetivo de desenvolver uma interface que permita a criação e visualização de sessões de jogo. O aplicativo interage com um back-end para persistir e recuperar os dados das sessões.

### Funcionalidades

- **Formulário para criar nova sessão de jogo**: 
  - O formulário coleta os seguintes detalhes da sessão de jogo: `hostname`, `players`, `map` e `mode`.
  - Ao enviar, os dados são enviados para a API de back-end por meio de uma solicitação POST para criar uma nova sessão de jogo.

- **Visualização de lista das sessões de jogo**: 
  - O aplicativo busca e exibe uma lista de sessões de jogo a partir da API de back-end.
  - Os detalhes exibidos incluem: `hostname`, `players`, `map` e `mode`.

### Requisitos e Implementação

1. **Formulário**:
   - [x] Coleta dos detalhes da sessão de jogo: `hostname`, `players`, `map` e `mode`.
   - [x] Envio de solicitação POST para a API de back-end para criar uma sessão de jogo. 

2. **Visualização de lista**:
   - [x] Busca e exibição da lista de sessões de jogo a partir da API de back-end.
   - [x] Exibição dos detalhes: `hostname`, `players`, `map` e `mode`.

3. **Experiência do usuário (UX/UI)**:
   - [x] Implementação de um design responsivo e fácil de usar. 
   - [x] Utilização de uma estrutura CSS, neste caso, Tailwind CSS. 

4. **Qualidade do código**:
   - [x] Garantia de alta legibilidade e facilidade de manutenção do código.
   - [x] Utilização de práticas modernas de desenvolvimento React, como hooks e componentes funcionais.

### Tecnologias Utilizadas

- **React** com **Vite** para o desenvolvimento da interface do usuário.
- **Tailwind CSS** para estilização e design responsivo.
- **Axios** para comunicação com o back-end.

### Como Executar

1. Clone este repositório:
```
git clone https://github.com/Matheusfbio/full-stack-web-challenge.git
```
2. Navegue para a pasta do projeto
```
cd full-stack-web-challenge
```
3. Instale as dependencias
```
npm i
```
4. defina o .env para fazer integração com o back-end localmente para afins de teste
```
VITE_API_ENDPOINT="http://localhost:3000/sessions"
```
5. execute o projeto
```
npm run dev
