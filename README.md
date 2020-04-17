# inGaia - Back-end Developer

Um estudo organizado por um grupo de pesquisadores desocupados demonstrou que as pessoas tendem a preferir diferentes gêneros musicais de acordo com a temperatura ambiente. Baseado nesta incrível descoberta, contratamos você para desenvolver um serviço revolucionário que irá sugerir músicas ao usuário de acordo com a temperatura atual da cidade dele! Não é sensacional?

## Requisitos Funcionais

- Seu serviço deve ser acessível através de uma API REST

- Seu serviço deve aceitar o nome de uma cidade como parâmetro, e a partir disso retornar uma playlist (somente o nome das músicas já é o suficiente) de acordo com a temperatura atual na cidade fornecida

- Se a temperatura:
    - for maior que 25°C, o serviço deve sugerir músicas pop
    - estiver entre 10°C e 25°C, o serviço deve sugerir músicas de rock
    - estiver abaixo de 10°C, o serviço deve sugerir músicas clássicas

- Seu serviço deve possuir um endpoint que indique as estatísticas de cidades consultadas desde a criação do serviço.

## Requisitos não funcionais
- Seu serviço deve executar em um container **Docker**.

- Seu serviço deve ser construído com atenção aos seguintes aspectos:
    - Latência
    - Resiliência
    - Tolerância à falhas
    - Segurança
    - Escalabilidade

- Seu serviço deverá ser stateless, porém poderá fazer uso de ferramentas de **cache** para garantir a performance nas respostas.

- Você deve apresentar uma **documentação** que represente a arquitetura de seu serviço e, se necessário, uma explicação para suas decisões de arquitetura.


## Detalhes

Você pode utilizar qualquer linguagem, ferramenta, framework ou biblioteca com as quais se sentir confortável ou julgar necessário.

Caso tenha quaisquer dúvidas sobre este teste, a qualquer momento, sinta-se à vontade para entrar em contato através do e-mail engineering-tests@ingaia.com.br

Suba seu código em um repositório do GitHub e, ao final, certifique-se de torna-lo público ou compartilhá-lo com os seguintes usuários:

- stefanobaldo
- batosti
- jesse1983

Além disso disponibilize uma **versão online** dele.

## Dicas importantes:

- Por uma questão de aderência a posição, a utilização da linguagem para qual está descrita esta vaga será um diferencial.

- A temperatura da cidade deve ser, de fato, a temperatura real naquele momento. Para ter acesso a este dado, você pode utilizar qualquer API aberta de serviços meteorológicos que preferir. Nossa sugestão é a do [API do OpenWeatherMaps](https://openweathermap.org/api).

- Você também pode, a seu critério, utilizar um serviço terceiro para gerar as sugestões de músicas para as playlists que você irá retornar. Uma boa dica nesse caso é a [API do Spotify](https://developer.spotify.com/documentation/web-api/). O Spotify tem inclusive  uma lista de bibliotecas, em diversas linguagens, para acesso à API.

- Para deixar seu serviço disponível online, uma boa dica é o [Heroku](https://www.heroku.com/). Ele permite que você publique algumas aplicações gratuitamente.
