<div> 
  <h1> API - STAR WARS 🛸</h1>
</div>



<div align="center">
  <img src = "https://rollingstone.uol.com.br/media/_versions/poster_classico_de_star_wars__uma_nova_esperanca_-_reproducao__lucasfilm_widelg.jpg" width="500px">
</div>

## 📰Funcionalidades Da Aplicação 
<div> 
<p>
ㅤO tema do nosso projeto foi sobre a saga “Star Wars”, onde trabalhamos com o
intuito de desenvolver uma aplicação diretamente focada em atrair os grandes espectadores
e fãs dessa saga, procurando levar informações e trazer diversas funcionalidades e
exclusividades ao usuário.
  
ㅤA API Star Wars é uma API com dados do universo da saga Star Wars, tendo-se,
personagens e filmes, onde sua principal funcionalidade é retornar dados referentes ao
tema, como: personagens e filmes.
</p>

<b>Dupla:</b> Emilynn Zabala e Polianna Abulquerque | 3 DS | Desenvolvimento de Sistemas 

</div>
<br>

## 🔗URL BASE
<div> 
<p>
ㅤA URL base é a URL raiz para a API utilizada.
</p>

- [SWAPI - API (API Star Wars)](https://swapi.dev/documentation#planets)

<br>


## ⚠️RECURSOS RAIZ
<div> 
<p>
ㅤO recurso raíz fornece informações sobre todos os recursos disponíveis na API.
</p>

<b>Solicitação exemplo :</b>

``` http https://swapi.dev/api/ ```

<b>Exemplo da resposta :</b>

```
{
"films": "https://swapi.dev/api/films/",
"people": "https://swapi.dev/api/people/"
}
```

<b> Atributos :</b>

```Filmes - String``` A raiz do URL para recursos dos filmes

```Personagens - String``` A raiz do URL para recursos dos personagens

<br>


## 🧝‍♀️PERSONAGENS 
<p>
ㅤUm recurso Personagem é uma pessoa ou personagem individual dentro do
universo Star Wars.
</p>

ㅤㅤ```/people/```-- obter todos os recursos de pessoas

ㅤㅤ```/people/:id/```-- obter um recurso de pessoas específico

ㅤㅤ```/people/schema/```-- visualize o esquema JSON para este recurso

<br>
<b> Atributos :</b>

- ```name string``` -- O nome desta pessoa.

- ```birth_year string``` -- O ano de nascimento da pessoa, usando o padrão do universo de
BBY ou ABY

- ```gender string``` -- O sexo desta pessoa. "Masculino", "Feminino" ou "desconhecido",
"n/a" se a pessoa não tiver gênero.

<br>


## 🎬FILMES
<p>
ㅤUm recurso de filme é um único filme individual dentro do
universo Star Wars.
</p>

ㅤㅤ```/films/```-- obter todos os recursos dos filmes

ㅤㅤ```/films/:id/```-- obter um recurso do filme específico

ㅤㅤ```/films/schema/```-- visualize o esquema JSON para este recurso

<br>
<b> Atributos :</b>

- ```title string``` -- O título deste filme

- ```episode_id integer``` -- O número do episódio deste filme.

- ```director string``` -- O nome do diretor deste filme.


