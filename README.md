# Teste iCasei: Front-End

Desenvolver uma aplicação HTML5.

## Instruções

- Siga as especificações abaixo.
- Crie um README com as instruções para compilar, testar e rodar o projeto.
- O link do repositório deverá ser enviado para o e-mail frontend@icasei.com.br com o título **Teste FrontEnd 2026**.

## Especificações funcionais da aplicação

Criar duas aplicações de microfrontend (no wireframe, MF_DRAWER e MF_VIDEOS).
A aplicação MF_DRAWER deve ter dois links, VÍDEOS e FAVORITOS, e a aplicação MF_VIDEOS deve conter a busca e as listagens.

  - AUTENTICAÇÃO:
    - A aplicação deve conter uma tela de login para que o usuário possa se autenticar e iniciar uma sessão.
  - VÍDEOS:
    - Ao acessar, o usuário deve poder buscar vídeos por meio de um campo de busca, no qual deverá informar os termos que serão utilizados para pesquisar vídeos na API do YouTube e listá-los conforme o wireframe.
    - O usuário pode reproduzir o vídeo e marcá-lo como favorito.
    - Ao clicar no botão de estrela, deve adicionar ou remover o vídeo da lista de favoritos e atualizar o contador total de vídeos favoritos.
  - FAVORITOS:
    - Ao clicar em FAVORITOS, deve exibir a lista de vídeos marcados como favoritos.
    - Os favoritos devem permanecer disponíveis após a atualização da página. A estratégia de persistência fica a critério do candidato.
  - ROTAS:
    - As páginas de vídeos e favoritos devem permitir acesso direto por suas respectivas rotas.

### Wireframes de referência

[Wireframe vídeos](/wireframe/wireframe_videos.png)

[Wireframe favoritos](/wireframe/wireframe_favs.png)

## Especificações técnicas

- Utilizar uma das opções para controle de sessão e BFF:
  - [Node.js](https://nodejs.org/en/)
  - [Go](https://go.dev/)
  - [Ruby](https://www.ruby-lang.org/pt/)
  - Qualquer outra linguagem de backend também será aceita.

- Utilizar a [API de busca do YouTube](https://developers.google.com/youtube/v3/docs/search/list).
- Design **responsivo**.
- A **navegação por rotas** é um requisito obrigatório.
- A utilização de frameworks JavaScript é opcional. O candidato pode utilizar React, Vue, Angular ou outra tecnologia de sua preferência.
- Cores, layout e imagens são livres.
- CSS nativo, LESS, Sass e afins são permitidos.
- O código deve ser **tipado**.
- Utilizar **microfrontend** para cada aplicação com BFF.
- Utilizar **Docker** para os microfrontends e o BFF.
- **Testes unitários** são obrigatórios.

## Decisões arquiteturais

A estratégia de composição, comunicação e implantação dos microfrontends fica a critério do candidato. Esperamos que as decisões adotadas, as alternativas consideradas e eventuais sugestões de mudança sejam documentadas no README da solução.

A quantidade e a distribuição dos BFFs fazem parte da decisão arquitetural. O candidato pode propor uma organização diferente da sugerida, desde que justifique a escolha.

## Observações

- Observar padrões e boas práticas de arquitetura.
- Para consumir os dados desta [API](https://developers.google.com/youtube/v3/docs/search/list), você deve gerar a chave de API da aplicação neste [link](https://developers.google.com/youtube/v3/getting-started?hl=pt-br).

## O que será avaliado?

- Organização do projeto.
- Lógica do código.
- Uso do Git.
- Componentização.
- Usabilidade e acessibilidade.
