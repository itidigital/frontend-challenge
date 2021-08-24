# frontend-challenge

Desafio de frontend do iti Itaú.

**Este desafio é enviado por email para pessoas avaliadas no processo seletivo para frontend no Iti Itaú.**

## Introdução

Será avaliado a qualidade do seu código, a documentação e outras características importantes de engenharia de software como: escalabilidade, manutenibilidade e observabilidade.

Damos muito valor para: 

- Web semântica
- CSS escalável
- JavaScript Testável
- Acessibilidade
- Boas práticas de componentização (CSS e JavaScript)
- Performance Web
- Plataforma Web (Web APIs)

Lembrando que o desafio é o mesmo para qualquer nível de conhecimento e você receberá uma avaliação das pessoas desenvolvedoras do nosso time de acordo com o seu nível de conhecimento. A pessoa junior não será "cobrada" da mesma maneira que uma pessoa senior.

Abaixo temos uma sessão de entregáveis que tenta te ajudar a entender os níveis de dificuldade da implementação

## Desafio

1. Criar uma página de busca de usuários do GitHub onde possamos digitar um username e retorne as seguintes informações através da busca:
    
    - Name
    - Username
    - Description
    - Followers
    - Following
    - Stars
    - Location
    - Profile Image

2. Além das informações acima, construa um meio de ordenar e filtrar a lista recebida via API por quantidade de estrelas e/ou por nome do repositório (crescente e decrescente).

Você pode se basear em qualquer layout disponível na internet.

Não precisa ser algo muito complexo, bastando: uma **página de busca**, **página de resultados da busca**, **página de detalhes do repositório** e os campos de ordenação.

## Requisitos

- React* (não necessário TypeScript)
- Preferencialmente Sass*
- README detalhado*
- Aplicação acessível através de alguma URL*
- Testes de unidade (se possível com React Testing Library)
- Testes E2E com Cypress
- Aplicação disponibilizada na AWS e desenho da arquitetura

OBS: itens marcados com __*__ são obrigatórios, os demais são opcionais.

## Recursos

- [GitHub REST API](https://docs.github.com/en/rest)
- [Exemplos de Motores de Busca](https://dribbble.com/tags/search_engine)
- [Exemplo de Página de Resultados de Busca](https://dribbble.com/search/search%20result%20page)
- [Ilustrações gratuitas](https://undraw.co/)
- [+Ilustrações gratuitas](https://www.pixeltrue.com/free-illustrations)
- [Hospedagem React gratuita](https://www.netlify.com/)

## Prazo

O prazo é acordado com a pessoa que te enviou este desafio.

## Entega do desafio

- Subir o desafio em um repositório no GitHub/GitLab/Bitbucket e responder o email da pessoa avaliadora com o link
- Não ter nenhuma mensão do Itaú/Iti no repositório/projeto

## Entregáveis

Cada nível abaixo é uma dificuldade maior para a entrega do desafio. 

**Você pode implementar de acordo com o seu nível de conhecimento.** 

Dê o melhor com o que você já sabe, não precisa tentar impressionar e fazer algo sem qualidade. 

Pense como [MVP](https://fia.com.br/blog/mvp/) e entregue o que conseguir em seu tempo com qualidade e funcional. 

Não é necessário bater todos os requisitos abaixo.

1. Eu, como usuário, preciso de um campo onde inserir um usuário do GitHub e, clicando em um botão ou pressionando enter, a aplicação faça uma busca e me envie para uma página com o resultado dessa pesquisa listando os repositórios do usuário localizado. Se o usuário não existir, preciso receber um alerta da aplicação
2. Eu, como usuário, gostaria de receber um feedback de carregamento enquanto a aplicação busca os dados do usuário que eu digitei
3. Eu, como usuário, gostaria de receber o feedback da aplicação quando o usuário inserido no campo de busca não for válido de acordo com as regras de validação do GitHub
4. Eu, como usuário, gostaria de receber uma notificação caso perca a conexão com a internet durante a busca dos dados pela aplicação
5. Eu, como usuário, gostaria de poder acessar os dados de usuários que já pesquisei de modo offline
