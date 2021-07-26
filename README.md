# README

Challenge CAIENA
=
## Description

Faça uma aplicação integrada com o OpenWeatherMap e o Twitter para que seja possível enviar um tweet com a temperatura atual e a previsão dos próximos 5 dias (média diária).
A aplicação não precisa disponibilizar uma interface gráfica. Basta que disponibilize um endpoint HTTP, que receba dados por parâmetro e, aí, construa o texto e publique o tweet.
```
Não é necessário implementar controle de autenticação.
```
Um exemplo de tweet seria:
```
34°C e nublado em <cidade> em 12/12. Média para os próximos dias: 32°C em 13/12, 25°C em 14/12, 29°C em 15/12, 33°C em 16/12 e 28°C em 16/12.
```
## Entregáveis
### Os seguintes entregáveis são solicitados:
### Uma gem de um SDK para utilização do OpenWeatherMap;
- Uma API que utiliza o SDK criado acima para realizar as requisições na API do
OpenWeatherMap;
- A API precisa expor um endpoint que deverá receber (POST) um ID para utilizar no SDK; A API deverá se comunicar com o Twitter utilizando um sdk, como este por exemplo. É necessário habilitar a conta de desenvolvedor do twitter. Portanto, é importante realizar esse passo para que o tempo de aprovação - idealmente de minutos - não impacte no desenvolvimento final.

Os itens devem ser hospedados em alguma plataforma de gerenciamento/versionamento de código como GitHub, GitLab, etc.

```
Os repositórios devem contar com um arquivo README contendo instruções de configuração e inicialização do projeto em questão
```

## Diferenciais:
```
docker
baixo número de dependências
```

Ciclo
=
- OpenWeatherMap
```
API externa a ser consumida
```

- API Ruby
```
1 - chamará a API externa;
2 - processará o JSON recebido;
3 - enviará pro twitter;
```

- Twitter Develop
```
Diretrizes pra formular e enviar
via API
um twitte
com previsão do tempo
```


Instruções
=

Requisitos:
- ruby 2.6.3

```
git clone https://github.com/allysonhalley/weather_forecast_tweet.git
```

