# front-end-challenge
Desafio para os futuros front-ends do [@Helpet](https://github.com/helpetapp).

## Desafio

Crie uma aplicação React (web ou mobile, fica à seu critério) com UI agradável, onde seja possível pesquisar filmes por nome e o resultado desta busca deve ser uma lista de filmes, sendo cada filme apresentado em um card. 

O usuário deve ter a opção de visualizar mais informações sobre um filme ao entrar no card do Filme. O mesmo deve exibir informações sobre o filme (Título, Imagem, Descrição...). Também deve ser possível ao usuário salvar (favoritar) um filme. Ao sair da aplicação e abri-la novamente no mesmo device, o usuário pode ver os filmes que salvou.

Utilize o mecanismo de infinite scroll para apresentar novos filmes ao usuário (tanto na busca quanto em "filmes salvos"), porém não carregue mais de 10 filmes por vez, para não prejudicar a performance do app e consequentemente a experiência do usuário.


**Para obter esse resultado, use esta API GraphQL:**

/POST https://tmdb.apps.quintero.io

Fazendo um GET para este mesmo endereço, ou seja, abrindo essa url no browser, você vai encontrar uma forma descobrir e testar as queries que precisa, pois abrirá um painel de testes com um link para a documentação da API no canto superior direito.

Observação: Esta API é um wrapper da API REST pública do The Movie Database, mantida de maneira open source neste repo: https://github.com/nerdsupremacist/tmdb. Caso tenha algum problema em utilizá-la, não exite em avisar.

****************************************************

**Dicas importantes:**

Esta aplicação é relativamente simples. Nós não estamos preocupados somente se você vai conseguir entregá-la, mas como vai, ou seja, vamos analisar a arquitetura do projeto, fluxo de desenvolvimento, organização do código, etc.

Considere usar suas melhores skills neste projeto. Boas práticas e padrões de projeto serão observados. 

Certifique-se também de escrever um README claro, como se este fosse um projeto de código aberto. Pense que um novo desenvolvedor pode se juntar ao projeto e ele deve conseguir obter as informações necessárias para rodar o projeto e entendê-lo através do README.

Quer nos agradar? Escreva testes unirários para seus componentes e métodos. :)

## Como entregar

Publique o código-fonte no Github, BitBucket ou Gitlab. Recomendamos que coloque a aplicação para rodar em algum lugar, se possível. Caso opte fazer uma aplicação mobile, o Expo é opção para publicação. Caso opte fazer web, tem o Heroku, Netlify e outros.

Envie os respectivos links (código e aplicação rodando) para [it@helpetapp.com](mailto:it@helpetapp.com).


Obrigado e boa sorte!
