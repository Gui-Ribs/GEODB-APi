# Documentação da API GEO_DB Cidade

<center>

![GeoDBlogo](http://geodb-cities-api.wirefreethought.com/assets/images/logo.png)

</center>

Licença da API: [Creative Commons Attribution 3.0](https://creativecommons.org/licenses/by/3.0/) <br>
Link da API: https://rapidapi.com/wirefreethought/api/geodb-cities <br>
Link da Documentação Oficial: https://wirefreethought.github.io/geodb-cities-api-docs/

**Descrição:** API consiste em retornar dados geográficos de lugares como regiões, cidades, países, atributos e entre outros. **GET** é único método de requisição usado.


> Para utiliza-la é necessário possuir uma api Key, sendo o seu nome no cabeçalho: `X-RapidAPI-Key`. Para consegui-la, acesse o site de [hospedagem](https://rapidapi.com/wirefreethought/api/geodb-cities) da mesma e crie sua conta, automáticamente será gerado.
` Key: X-RapidAPI-Key value: xxxxxx `


Os endpoints que serão utilizados:

- Encontre Cidades [`/geo/cities`](https://wft-geo-db.p.rapidapi.com/v1/geo/cities)
- Encotre Países [`/geo/countries`](https://wft-geo-db.p.rapidapi.com/v1/geo/countries)
- Encontre novas localizações [`/geo/places`](https://wft-geo-db.p.rapidapi.com/v1/geo/places)

Todos os endpoints da API (Excluindo especificações):

- Find admin divisions
- Find cities
- Find Countries
- Find Places

Retornos de códigos:

<center> 

![200](https://imgur.com/Tdo9Y6o.png)

200 (Success)- sucesso, retorna o JSON com as informações;

![400](https://imgur.com/Zt613zL.png)

400 (Erro) - erro, retornando uma mensagem;

![403](https://imgur.com/X9XI1ch.png)

403 (forbidden) - erro, falha ao carregar

</center>
