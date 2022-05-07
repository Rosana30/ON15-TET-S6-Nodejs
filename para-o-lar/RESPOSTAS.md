# Respostas
1º qual nível de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
API Maturidade 2
Na criação de uma tela de cadastro, é de extrema importância que as operações simples como, criar recurso, atualizar recurso, buscar recurso e deletar recurso sejam implementadas. Nesse nível de maturidade a mesma ideia deve ser utilizada com os verbos HTTP, eles devem ser suficientes para um CRUD (Crate, Read, Update, Delete). Para cada ação de um recurso da API são aplicados verbos diferentes. Dentre as opções disponíveis, baseado na arquitetura REST.





2º qual a relação entre os métodos HTTP e o CRUD?
É um protocolo de transferência que possibilita que as pessoas que inserem a URL do seu site na Web possam ver os conteúdos e dados que nele existem. A sigla vem do inglês Hypertext Transfer Protocol.
CRUD é a composição da primeira letra de 4 funções básicas de um sistema que trabalha com banco de dados:
C: Create (criar) - criar um novo registro.
 R: Read (ler) - ler (exibir) as informações de um registro.
 U: Update (atualizar) - atualizar os dados do registro.
 D: Delete (apagar) - apagar um registro.







3º o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
São uma restrição que faz parte da arquitetura de aplicações REST, cujo objetivo é ajudar os clientes a consumirem o serviço sem a necessidade de conhecimento prévio profundo da API.
O acrônimo HATEOAS vem de Hypermedia As the Engine Of Application State e o termo “hypermedia” no seu nome já dá uma ideia de como este componente funciona em uma aplicação RESTful. Ao ser implementado, a API passa a fornecer links que indicarão aos clientes como navegar através dos seus recursos. Não é obrigado embora mais caso queira usar uma api o padrão RESTful, o HATEOAS deve ser implementado nela.


4º    O que quer dizer quando dizemos que uma API é idempotente?
Um método é considerado idempotente se o resultado de uma requisição realizada com sucesso é independente do número de vezes que é executada. Idempotente é um método P que pode ser chamado muitas vezes sem resultados diferentes. Não importa se o método é chamado apenas uma vez ou dez vezes. 



       5º) PUT: Geralmente, ao usar-se o PUT, fica legível que a alteração do dado será com referência a         entidade completa. É quando se faz uma requisição a um recurso para modificá-lo. Nesse método   irá mudar     todo os dados do recurso, se caso esse recurso não exista, é possível criá-lo através dessa única requisição.
PATCH:  usa-se quando vai alterar alguns dados de um recurso. Ele não pode criar um novo recurso como é feito no put.

