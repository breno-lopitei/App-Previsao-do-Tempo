# APP - Previsão do Tempo

Uma aplicação simples de previsão do tempo desenvolvida com HTML, CSS e JavaScript.

## Descrição

Este projeto consulta a API do WeatherAPI para exibir a previsão atual de uma cidade pesquisada pelo usuário. A interface apresenta:

- nome da cidade
- temperatura em °C
- descrição da condição climática
- ícone da condição do tempo
- umidade
- velocidade do vento

## Como usar

1. Abra o arquivo `index.html` no navegador.
2. Digite o nome de uma cidade no campo de busca.
3. Clique no botão de busca (lupa).
4. Veja as informações do clima atual atualizarem na tela.

## Estrutura do projeto

- `index.html` - página principal da aplicação.
- `src/css/reset.css` - estilo de reset básico.
- `src/css/estilos.css` - estilos da interface.
- `src/js/index.js` - lógica de busca e exibição de dados do WeatherAPI.
- `src/imagens/` - assets de imagem usados no layout.

## Tecnologia

- HTML
- CSS
- JavaScript

## API utilizada

- WeatherAPI: `https://api.weatherapi.com/v1/current.json`

## Observações

- O projeto atualmente utiliza uma chave de API diretamente em `src/js/index.js`.
- Para produção, é recomendado não expor a chave no frontend e usar um backend ou variáveis de ambiente.
- Se desejar rodar em um servidor local, basta usar um servidor estático como `Live Server` ou qualquer servidor web.

## Melhorias possíveis

- adicionar tratamento de erro para cidades inválidas ou falha na requisição
- carregar dados automaticamente ao pressionar Enter
- exibir previsão para os próximos dias
- melhorar a acessibilidade e responsividade
