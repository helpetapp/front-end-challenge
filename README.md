# front-end-challenge
Desafio para os futuros front-ends do [@Helpet](https://github.com/helpetapp)

## Desafio

Crie uma aplicação React (web ou mobile, fica à seu critério) com UI agradável, onde seja possível pesquisar filmes por nome e o resultado desta busca deve ser uma lista de filmes, sendo cada filme apresentado em um card. 

O usuário deve ter a opção de visualizar mais informações sobre um filme ao entrar no card do Filme. O mesmo deve exibir informações sobre o filme (Título, Imagem, Descrição...). Também deve ser possível ao usuário salvar (favoritar) um filme. Ao sair da aplicação e abri-la novamente no mesmo device, o usuário pode ver os filmes que salvou.

Utilize o mecanismo de infinite scroll para apresentar novos filmes ao usuário (tanto na busca quanto em "filmes salvos"), porém não carregue mais de 10 filmes por vez, para não prejudicar a performance do app e consequentemente a experiência do usuário.


**Para obter esse resultado, use esta API GraphQL:**

/POST https://tmdb.apps.quintero.io

Fazendo um GET para este mesmo endereço, ou seja, abrindo essa url no browser, você vai encontrar uma forma descobrir e testar as queries que precisa, pois abrirá um painel de testes com um link para a documentação da API no canto superior direito.

Observação: Esta API é um wrapper da API REST pública do The Movie Database, mantida de maneira open source neste repo: https://github.com/nerdsupremacist/tmdb. Caso tenha algum problema em utilizá-la, não exite em avisar.
