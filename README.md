# Desafio Android - Star Wars

Olá pessoa desenvolvedora Android!

Este desafio consiste em desenvolver um aplicativo que consuma uma API para exibir os filmes de Star Wars lançados até então.

## Detalhes
- A API ```https://api.npoint.io/dc12046175d1c54574fb``` retornará uma lista de filmes com o seguinte formato:

    ```
    [
      {
        "cover": "https://www.coverwhiz.com/uploads/movies/star-wars-episode-iv-a-new-hope.jpg",
        "title": "A New Hope",
        "director": "George Lucas",
        "episode_id": "IV",
        "release_date": "1977-05-25"
      }
  ]
  ```
  
  
  **cover** <br>URL da imagem de capa do filme, que deve ser carregada na lista<br><br>
  **title** <br>Nome do filme<br><br>
  **director** <br>Nome do diretor do filme<br><br>
  **episode_id** <br>Número romano equivalente ao episódio do filme<br><br>
  **release_date** <br>Data de lançamento no formato YYYY-MM-DD<br><br>
  
  Todos os dados devem ser exibidos na lista.
  

## Requisitos

- A tela deve possuir uma toolbar (podendo ser colapsada ou não) e um RecyclerView para exibir a lista de dados
- Para este desafio, é esperado que a tela seja desenvolvida utilizando layout XML e não Compose
- O aplicativo deve ser desenvolvido inteiramente em Kotlin, utilizando as arquiteturas Clean e MVVM/MVI
- O aplicativo poderá ter grandes mudanças no futuro e para isso possuir testes unitários é essencial
- Uso de coroutines código executado de forma assincrona
- Mudanças de configuração, como rotacionar o celular, podem causar em perda do estado da tela. É ideal que o estado permaneça nessas situações.

## Desejável

- Desenvolvimento de testes instrumentados utilizando Espresso

## Exemplo
![starwars](https://user-images.githubusercontent.com/11378932/192324338-17f6385b-cd0e-487c-94d1-253e2d1ad2d6.gif)

