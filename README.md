# Site Previsao Tempo Python

🌤️ Criando um Aplicativo de Previsão do Tempo com Streamlit e OpenWeather API 🌤️

Nos últimos dias, desenvolvi uma aplicação de previsão do tempo utilizando o Streamlit e a API da OpenWeather. O app permite que os usuários insiram o nome de uma cidade e obtenham a previsão detalhada para os próximos cinco dias, incluindo temperaturas e ícones das condições climáticas.

💡 Principais Funcionalidades:

Previsão para 5 dias: O app utiliza geolocalização para obter a latitude e longitude da cidade e, com essas informações, acessar a previsão do tempo.

Conversão de temperatura: A API retorna a temperatura em Kelvin, mas o app converte automaticamente para Celsius.

Interface intuitiva com Streamlit: Usei CSS customizado para deixar a interface mais amigável e visualmente atraente.

Atualização em tempo real: A data e hora da consulta são atualizadas automaticamente a cada nova busca.

🛠️ Tecnologias Utilizadas:

Streamlit: Para criar a interface interativa.

Requests: Para fazer as chamadas à API do OpenWeather.

OpenWeather API: Para obter os dados meteorológicos com base na cidade digitada.

Python: Lógica principal do app, incluindo tratamento de erros e manipulação de dados.

🔥 Desafios:

Manipular os dados da API para gerar previsões organizadas em intervalos de tempo foi um desafio interessante, além de apresentar tudo de forma clara com ícones e textos explicativos.

Além disso, hospedei o site no GitHub para que ele fique acessível a todos que queiram testar e explorar a aplicação. Para rodar o app localmente, basta substituir "sua chave" pela chave que você obtém ao se cadastrar no site da OpenWeather, para poder utilizá-lo adequadamente.

👉 O projeto é um exemplo de como APIs públicas e ferramentas como Streamlit podem ser usadas para criar aplicativos interativos e úteis com Python.

Se quiser testar o app ou saber mais sobre o desenvolvimento, fique à vontade para comentar! 👇

#Python #APIs #Streamlit #OpenWeatherAPI #Desenvolvimento
