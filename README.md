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

- [(API Star Wars -  Retorna dados)](https://potterdb.com/)

<br>


## ⚠️MÉTODOS
<div> 
<p>
ㅤPara acessar os dados das APIs é necessário fazer um GET solicitando os seguintes endpoints.
Vamos chamar este GET através de uma linha de comando, como por exemplo:
</p>

<b>Solicitação exemplo :</b>

``` (https://api.potterdb.com/v1/characters/star-wars) ```

<b>Exemplo da resposta :</b>

```
{
"filmes": "https://api.potterdb.com/v1/films/star-wars",
"personagens": "https://api.potterdb.com/v1/characters/star-wars"
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

ㅤㅤ```/v1/characters```-- Este método irá obter recursos hospedados no servidor e retornará a lista de todos os personagens.

ㅤㅤ```/v1/characters/:slug```-- Este método irá obter recursos hospedados no servidor e retornará a lista de personagens específicos.


<br>
<b> Atributos :</b>

- ```slug string``` -- O slug identifica o pergonagem.

- ```name string``` -- Nome do personagem.

- ```born string``` -- Data de nascimento do personagem.

- ```gender string``` -- O sexo desta pessoa. "Masculino", "Feminino" ou "desconhecido",
"n/a" se a pessoa não tiver gênero.

- ```wiki string``` -- Um link para a página Wiki 


<br>


## 🎬FILMES
<p>
ㅤUm recurso de filme é um único filme individual dentro do
universo Star Wars.
</p>

ㅤㅤ```/v1/movies/```-- Este método irá obter recursos hospedados no servidor e retornará a lista de todos os filmes.

ㅤㅤ```/v1/movies/:slug```-- Este método irá obter recursos hospedados no servidor e retornará a lista de filmes específicos.


<br>
<b> Atributos :</b>

- ```slug string``` -- O slug identifica o filme.

- ```title string``` -- Titulo do filme.

- ```summary string``` -- Data de nascimento do personagem.

- ```wiki string``` -- Um link para a página Wiki 


## 📉DIAGRAMAS 
<div> 
<b>
ㅤDiagrama de Classe: 
</b>

- [Diagrama de Classe - API (API Star Wars)](https://drive.google.com/file/d/1NH7aOl1VVXhuM86ZP43Q-jg5WE17mRK-/view?usp=drivesdk)

<br>

<b>
ㅤDiagrama de Banco de Dados: 
</b>

- [Diagrama de Banco de Dados - API (API Star Wars)](https://drive.google.com/file/d/1njkJ6Tg6g_QHogsTK1Ns24xeWfBt_mYR/view?usp=drivesdk)


<br>

<br>




# CRIAÇÃO DA NOVA API

<div> 
<p>
ㅤA API de Geração de Nomes, é uma plataforma de serviços que oferece uma maneira
intuitiva e eficiente de criar nomes únicos e personalizados para diversas finalidades, como
empresas, produtos, personagens e muito mais. Ao permitir uma gama de opções de
configuração, está API visa atender às preferências individuais e às necessidades específicas dos
usuários.
  
ㅤCom uma variedade de opções e configurações, você pode gerar nomes que se alinham
ao seu propósito e estilo.
</p>
</div>

<b>Endpoint :</b>

``` GET /generate ```


<b>Parâmetros :</b>

``` type (string): ``` O tipo de nome que você deseja gerar (empresa, produto, personagem, etc.).

``` theme (string): ``` O tema ou categoria do nome (tecnologia, moda, fantasia, etc.).

``` keywords (string): ``` Palavras-chave que devem estar presentes no nome gerado.

``` length (int): ``` O número de palavras ou caracteres no nome gerado.

``` creativity (int): ``` Nível de criatividade, variando de 1 (convencional) a 5 (muito criativo).


<b>Exemplo de solicitação :</b>

``` GET /generate?type=company&theme=fantasia&length=10&creativity=4 ```


<b>Resposta da solicitação: :</b>

```
{
 "generated_names": [
 "JadeBb8",
 "Starbaby",
 "YodaWars",
 "WarsJadeStar",
 "NaveWars"
 ]
}
```





