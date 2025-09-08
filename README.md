# Sprint 3 - React | Clima Tempo 🌅🌃

## Visão Geral

Bem-vindo ao repositório da Sprint 3 do nosso grupo de estudo! Nesta sprint, vamos aprender os conceitos básicos do React e consumo de APIs. O objetivo é desenvolver uma aplicação para mostrar ao usuário a previsão do tempo de uma cidade de sua escolha, utilizando APIs públicas e o conceito de componentização para facilitar o desenvolvimento.

A aplicação deve utilizar uma API para geocodificar (encontrar a latitude e longitude) a cidade que o usuário digitar em um campo de input e, em seguida, usar essas coordenadas para buscar e exibir a previsão do tempo para os próximos 7 dias. O projeto será criado com a ferramenta **Vite**.

---

## 🚀 Descrição do Projeto

### Objetivo

Desenvolver uma Single Page Application (SPA) em React que permita ao usuário:

- Digitar o nome de uma cidade em um campo de busca. 🔍
- Visualizar a previsão do tempo atual para essa cidade. ☀️🌧️
- Visualizar a previsão do tempo para os próximos 7 dias. 📅
- Ver informações como: temperatura, sensação térmica, umidade, velocidade do vento e condições climáticas (céu limpo, nublado, etc.).

### Funcionalidades Principais

- Busca por cidade.
- Exibição dos dados meteorológicos em componentes reutilizáveis.
- Layout responsivo e amigável.
- Feedback visual durante o carregamento dos dados (loading). ⏳
- Tratamento de erros (ex.: cidade não encontrada). ❌

---

## 🛠️ Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construir interfaces de usuário.
- **Vite**: Ferramenta de build e desenvolvimento front-end, rápida e moderna.
- **CSS Modules / Styled Components / Tailwind CSS / Chakra UI**: Para estilização componentizada (escolha à preferência do grupo).
- **APIs Públicas**:
  - **Geocoding API** (ex.: OpenWeather Geocoding API, GeoDB Cities API) - Para converter o nome da cidade em coordenadas.
  - **Weather API** (ex.: OpenWeather One Call API, Visual Crossing Weather API) - Para obter a previsão atual e dos próximos dias usando as coordenadas.

---

## 📚 Materiais e Tutoriais de Apoio

Aqui você encontrará links e referências para facilitar o aprendizado:

### React & Vite

- **Documentação do React**: [https://react.dev/](https://react.dev/) 📖
- **Documentação do Vite**: [https://vitejs.dev/](https://vitejs.dev/) 📖
- **Tutorial: Começando com React e Vite**: (Pedir ajuda pro Léo)🎥

### Consumo de API

- **Fetch API ou Axios**: Como fazer requisições HTTP.
  - [MDN Web Docs - Fetch API](https://developer.mozilla.org/pt-BR/docs/Web/API/Fetch_API) 📖
  - [Documentação do Axios](https://axios-http.com/) 📖
- **Como usar useEffect para operações assíncronas**: [Um guia para useEffect](https://beta.reactjs.org/learn/synchronizing-with-effects) 📖

### APIs Sugeridas

- **OpenWeatherMap**:
  - [Geocoding API](https://openweathermap.org/api/geocoding-api)
  - [One Call API](https://openweathermap.org/api/one-call-api) (Obs.: Requer cadastro para obter chave API)
- **Visual Crossing Weather**:
  - [Weather API](https://www.visualcrossing.com/weather-api) (Tem um plano gratuito generoso)

---

## 🎯 Conceitos React para Praticar

- **Componentes Funcionais**: Criar a aplicação usando componentes funcionais.
- **Hooks**: `useState` para gerenciar o estado da aplicação (dados do clima, termo de busca, loading, erro). `useEffect` para disparar as buscas na API.
- **Props**: Passar dados entre componentes (ex.: do componente pai `App` para os componentes `CurrentWeather` e `Forecast`).
- **Event Handling**: Capturar o evento de submit do formulário de busca.
- **Conditional Rendering**: Mostrar componentes condicionalmente (ex.: mostrar Loader apenas quando `isLoading` for true).

---

## 🎉 Próximos Desafios (Extras)

- Adicionar um toggle para alternar entre unidades métricas (°C, m/s) e imperiais (°F, mph). 🔁
- Salvar as últimas cidades buscadas no `localStorage`.
- Usar a API de geolocalização do navegador para mostrar a previsão do tempo da localização atual do usuário ao carregar a página. 📍
- Melhorar a UI/UX com ícones representando as condições climáticas.

---

Divirta-se codando e bons estudos! 🚀✨
