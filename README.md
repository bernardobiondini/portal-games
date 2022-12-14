# UGame
Portal de Games desenvolvido durante a disciplina de Desenvolvimento de Interfaces WEB. Para a realização do projeto foi utilizado a API RAWG, de forma em que o site pudesse exibir as informações de forma dinâmica.

<a href="https://bernardobiondini.github.io/portal-games/">Link do Portal de Games</a>

## Sobre a Disciplina
A disciplina busca introduzir o aluno ao desenvolvimento WEB, utilizando puramente HTML, CSS e Javascript. 

## Desenvolvimento do Projeto
Primeiramente, foi proposto o desenvolvimento de um site estático, com interface adaptada pelo aluno, com diversas informações sobre Jogos, suas plataformas, criadores, entre outros. Ao decorrer da disciplina, foi possível obter maiores conhecimento sobre as tecnologias, de forma em que a apresentação dinâmica das informações fosse possível.


### Requisitos do Projeto
(adaptado pelo aluno)

O site que você fará deve atender aos seguintes requisitos: 

- O site deve ser publicado em um ambiente da Internet (Repl.it, GitHub Pages, Netlify ou outro a sua escolha); 
- O site deve trazer dados do aluno tais como seu nome completo, curso e número de matrícula, OBRIGATORIAMENTE visíveis na Home-Page;
o site deverá ser responsivo permitindo a visualização em um celular de forma adequada;
- O site deve ter uma Home-Page (index.html) com duas (2) seções com dados dinâmicos obtidos via RAWG API. Uma seção deve, OBRIGATORIAMENTE, trazer uma lista de jogos digitais utilizando o endpoint GAMES.
- Na primeira seção da Home-Page, você deve mostrar uma lista de jogos obedecendo os seguintes requisitos:
  - para cada game deve ser exibidos um mínimo de três (3) dados textuais obtidos por meio da API que descrevam sucintamente o referido item (Ex: nome, data de liberação, rating, etc);
para cada game, deve ser exibida uma imagem ilustrativa (background);
  - para cada game, deve haver um link que leve o usuário para uma Página de Detalhes (detalhes.html) que exibirá mais informações sobre o game. O id do game, obtido via API deve ser passado como parâmetro na URL  da página de detalhes conforme mostrado nas aulas síncronas realizadas na Semana 11. 
- Na segunda seção (adicional) da Home-Page, você deve mostrar uma lista associada a outra informação fornecida pela API como: creators, plataformas, publishers, lojas, gêneros, etc.
- O site deve apresentar uma Página de pesquisa (pesquisa.html) de games ou a funcionalidade integrada no cabeçalho da home-page, que permita ao usuário informar um texto e obter, como resultado da pesquisa, a lista de games associados a partir da RAWG API. 
- Na página de resultados da pesquisa, devem ser obedecidos os seguintes requisitos:
  - O resultado da pesquisa poderá ser paginado ou não
  - O resultado deve mostrar uma lista de games tal qual a home-page com imagem e textos que descrevam os games retornado;
  - Na apresentação de cada game do resultado da pesquisa deve ter um link que, ao ser acionado, leve o usuário para a Página de Detalhes (detalhes.html) onde são exibidas mas informações sobre o game.
