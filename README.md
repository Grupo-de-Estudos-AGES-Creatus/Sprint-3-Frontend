# Sprint 2 - APIs | Clima Tempo & Conversor de Moedas 🌅🌃🤑

## Visão Geral

Bem-vindo ao repositório da Sprint 2 do nosso grupo de estudos! Nesta sprint, vamos praticar os conceitos fundamentais de **JavaScript**, manipulação do **DOM** e **consumo de APIs públicas**.

O objetivo é desenvolver uma aplicação utilizando somente **HTML, CSS e JavaScript puro**, sem frameworks ou bibliotecas como React.

A proposta principal é criar uma aplicação de **previsão do tempo**, na qual o usuário poderá pesquisar uma cidade e visualizar informações climáticas obtidas através de APIs públicas.

Como alternativa, o grupo também poderá desenvolver um **conversor de moedas**, utilizando uma API para obter as taxas de câmbio e outra API para exibir informações ou bandeiras dos países relacionados às moedas.

---

## 🚀 Descrição do Projeto

### Opção 1 - Clima Tempo 🌤️

Desenvolver uma aplicação que permita ao usuário pesquisar uma cidade e consultar sua previsão do tempo.

A aplicação deverá utilizar uma API para **geocodificar a cidade**, transformando o nome informado pelo usuário em coordenadas de latitude e longitude.

Com essas coordenadas, uma segunda API deverá ser utilizada para buscar as informações climáticas da localização.

### Objetivo

A aplicação deve permitir ao usuário:

- Digitar o nome de uma cidade em um campo de busca. 🔍
- Buscar a latitude e longitude da cidade através de uma API.
- Visualizar as condições climáticas atuais. ☀️🌧️
- Visualizar a previsão do tempo para os próximos dias. 📅
- Consultar informações como:
  - Temperatura;
  - Sensação térmica;
  - Umidade;
  - Velocidade do vento;
  - Condição climática.

### Funcionalidades Principais

- Busca por cidade.
- Consumo de pelo menos **duas APIs públicas**.
- Manipulação dinâmica do HTML através do JavaScript.
- Exibição dos dados retornados pelas APIs.
- Layout responsivo. (opcional)
- Feedback visual enquanto os dados estiverem sendo carregados. ⏳
- Tratamento de erros, como cidade não encontrada ou falha na API. ❌

---

# 💱 Opção 2 - Conversor de Moedas

Como alternativa ao projeto de clima, o grupo poderá desenvolver um **conversor de moedas utilizando APIs públicas**.

A aplicação deve permitir que o usuário escolha duas moedas e informe um valor para realizar a conversão utilizando a cotação atual.

Além da API responsável pelas taxas de câmbio, deverá ser utilizada uma segunda API para obter informações relacionadas aos países que utilizam cada moeda, como suas respectivas bandeiras.

### Objetivo

A aplicação deve permitir ao usuário:

- Informar um valor para conversão. 💰
- Selecionar a moeda de origem.
- Selecionar a moeda de destino.
- Consultar a cotação atual através de uma API.
- Exibir o valor convertido.
- Exibir as bandeiras dos países relacionados às moedas selecionadas. 🌎
- Atualizar os dados dinamicamente sem recarregar a página.

### Exemplo

```text
Valor: 100

De:
🇧🇷 BRL - Real Brasileiro

Para:
🇺🇸 USD - Dólar Americano

Resultado:
100 BRL = 18,50 USD
```

### Funcionalidades Principais

- Seleção de moedas.
- Conversão utilizando valores reais de câmbio.
- Consumo de pelo menos **duas APIs públicas**.
- Exibição dinâmica das bandeiras.
- Botão para inverter as moedas selecionadas. 🔁
- Tratamento de erros.
- Layout responsivo e amigável.

---

## 🛠️ Tecnologias Utilizadas

O projeto deverá ser desenvolvido utilizando:

- **HTML5**: estrutura da aplicação.
- **CSS3**: estilização e responsividade.
- **JavaScript**: lógica da aplicação, manipulação do DOM e comunicação com APIs.
- **Fetch API**: realização de requisições HTTP para APIs públicas.

Não utilizar frameworks front-end como:

- React;
- Vue;
- Angular.

A ideia desta sprint é praticar os fundamentos antes de utilizar abstrações fornecidas por frameworks.

---

# 📚 Materiais e Tutoriais de Apoio

Aqui você encontrará alguns materiais para auxiliar durante o desenvolvimento.

## Consumo de APIs

- **Fetch API**
  https://developer.mozilla.org/pt-BR/docs/Web/API/Fetch_API

- **Async/Await**
  https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/async_function

---

# 🌤️ APIs Sugeridas - Clima

Algumas opções de APIs que podem ser utilizadas:

### OpenWeatherMap

**Geocoding API**

Converte o nome de uma cidade em latitude e longitude.

https://openweathermap.org/api/geocoding-api

**Weather API**

Permite consultar informações climáticas utilizando coordenadas.

https://openweathermap.org/api

### Open-Meteo

Outra alternativa para consulta de informações meteorológicas.

https://open-meteo.com/

---

# 💱 APIs Sugeridas - Conversor de Moedas

### ExchangeRate API

API para consulta de taxas de câmbio.

https://www.exchangerate-api.com/

### Frankfurter

API gratuita para consulta de taxas de câmbio.

https://www.frankfurter.app/

### REST Countries

Pode ser utilizada para obter informações sobre países, moedas e bandeiras.

https://restcountries.com/

---

# 🎉 Próximos Desafios (Extras)

Caso o grupo termine as funcionalidades principais, algumas funcionalidades extras podem ser implementadas.

### Clima Tempo

- Utilizar a geolocalização do navegador para detectar automaticamente a localização do usuário. 📍
- Salvar as últimas cidades pesquisadas utilizando `localStorage`.
- Alterar o visual da página dependendo da condição climática.
- Adicionar ícones representando chuva, sol, nuvens etc.
- Permitir alternar entre °C e °F. 🔁

### Conversor de Moedas

- Salvar as últimas conversões utilizando `localStorage`.
- Criar uma lista de moedas favoritas. ⭐
- Adicionar um botão para inverter rapidamente as moedas.
- Exibir a cotação atual entre as duas moedas.
- Mostrar a variação da cotação.
- Permitir pesquisar moedas pelo nome ou código.

---

Divirta-se codando e bons estudos! 🚀✨
