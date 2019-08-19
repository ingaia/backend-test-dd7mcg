# inGaia - Back-end Developer

Um estudo organizado por um grupo de pesquisadores desocupados demonstrou que as pessoas tendem a preferir diferentes gêneros musicais de acordo com a temperatura ambiente. Baseado nesta incrível descoberta, contratamos você para desenvolver um serviço revolucionário que irá sugerir músicas ao usuário de acordo com a temperatura atual da cidade dele! Não é sensacional?

## Requisitos Funcionais

- Seu serviço deve ser acessível através de uma API REST
- Seu serviço deve aceitar o nome de uma cidade como parâmetro, e a partir disso retornar uma playlist (somente o nome das músicas já é o suficiente) de acordo com a temperatura atual na cidade fornecida
- Se a temperatura:
    - for maior que 25°C, o serviço deve sugerir músicas pop
    - estiver entre 10°C e 25°C, o serviço deve sugerir músicas de rock
    - estiver abaixo de 10°C, o serviço deve sugerir músicas clássicas

## Detalhes

Uma vez que este serviço será utilizado por milhares de pessoas, estratégias para torná-lo escalável e resiliente são muito bem-vindas.

Você pode utilizar qualquer linguagem, ferramenta, framework ou biblioteca com as quais se sentir confortável ou julgar necessário, apenas certifique-se de descrever brevemente sua solução, explicando suas decisões de arquitetura.

Caso tenha quaisquer dúvidas sobre este teste, a qualquer momento, sinta-se à vontade para entrar em contato através do e-mail engineering-tests@ingaia.com.br

Suba seu código em um repositório **privado** do GitHub e, ao final, certifique-se de compartilhá-lo com os seguintes usuários:

- stefanobaldo
- tcarmona
- jesse1983

Além disso, indique como rodar o seu serviço localmente ou disponibilize uma versão online dele.

## Dicas importantes:

- Por uma questão de aderência a esta posição específica, a utilização de [Node.js](https://nodejs.org) como linguagem principal será um diferencial.

- A temperatura da cidade deve ser, de fato, a temperatura real naquele momento. Para ter acesso a este dado, você pode utilizar qualquer API aberta de serviços meteorológicos que preferir. Nossa sugestão é a do [API do OpenWeatherMaps](https://openweathermap.org/api).

- Você também pode, a seu critério, utilizar um serviço terceiro para gerar as sugestões de músicas para as playlists que você irá retornar. Uma boa dica nesse caso é a [API do Spotify](https://developer.spotify.com/documentation/web-api/). O Spotify tem inclusive  uma lista de bibliotecas, em diversas linguagens, para acesso à API.

- Caso queira deixar seu serviço disponível online, uma boa dica é o [Heroku](https://www.heroku.com/). Ele permite que você publique algumas aplicações gratuitamente.
