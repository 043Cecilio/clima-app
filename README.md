# Explorador de Clima - Projeto 1 (ReactJS)

Este projeto é uma Single Page Application (SPA) desenvolvida para a disciplina de Programação Web Fullstack. A aplicação permite consultar o clima em tempo real de qualquer cidade do mundo.

## Tecnologias e Requisitos Atendidos

Para cumprir os requisitos do Projeto 1, foram utilizadas as seguintes ferramentas:

* **API Externa (JSON):** [OpenWeatherMap](https://openweathermap.org/). Utilizada para consumir os dados meteorológicos reais via AJAX (utilizando a função nativa `fetch` do JavaScript).
* **React Hook Exigido:** `useRef`. Foi aplicado no campo de texto (`TextField`) para capturar o nome da cidade digitada pelo utilizador. A escolha do `useRef` em vez do `useState` evita que o componente seja re-renderizado a cada letra digitada, otimizando o desempenho da aplicação.
* **Biblioteca Externa:** [Material-UI (MUI)](https://mui.com/material-ui/). Utilizada para a construção da interface de utilizador (UI), garantindo um design responsivo e moderno com componentes prontos como `Card`, `TextField`, `Button` e `Typography`.

## Uso de Inteligência Artificial

Conforme as diretrizes do projeto, o desenvolvimento contou com o apoio de ferramentas de IA (Google Gemini) para os seguintes fins:
1. Estruturação inicial do ficheiro `App.jsx` com os componentes do Material-UI.
2. Esclarecimento de dúvidas sobre a integração correta do hook `useRef` em conjunto com eventos de clique e teclado (Enter).
3. Auxílio na resolução de códigos de erro HTTP (como o erro 401 de ativação da chave da API) e formatação deste ficheiro README.

## Como executar o projeto localmente

1. Clone este repositório.
2. Abra o terminal na pasta do projeto e instale as dependências:
   ```bash
   npm install