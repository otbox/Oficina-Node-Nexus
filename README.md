# Oficina de API  
Repositório da oficina de API ofericida pela Nexus Girls por Ana Luiza Sampaio

## Client 
Camada que realiza requisiçẽos para servidores e outras coisas, sendo o meio que o usuário utilizara a iternet, informando tudo que acontecerá entre o servidor e usuarios, o mais importante é fazer solicitações e receber responses.

O DNS, é uma forma de lista telefonica, então enquanto escrevemos o dominio, o client mandará uma requisição e um servidor DNS irá devolver o IP da aplicação

**URI:** para entendermos uma URI temos a URL e a URN, URL: tf.unicamp.br, já a URN: /contato, /cronograma
a URI é a junção do protocolo, da URL e da URN. protocolo, endereço, recurso

## Requests
o HTTP é baseado em requests e responses.
- *GET*: ler 
- *Post*: criar
- *Put*: substituir
- *Patch*: modificar
- *Delete*: deletar

**Códigos de Resposes**

|Codigo | Tipo de resposta |
----|----
|100-199|Informação|
|200-299|Sucesso|
|200-299|Redirecionamento|
|300-399|erro de cliente|
|400-499|erro de servidor|

## API
- Interface de programação de Aplicativos: Criando formas e ferramentas de se usar uma funcionalidade ou uma informação sem realmente ter que "reinventar a tal função"

Ela pode ser uma lib ou um framework, uma função já pronta em uma linguagem especifica.

**Web APIs:** Conjunto de instruções e padrões de programação para ter acessoa a um aplicativo de software. Uma empresa de software lança sua API para o público de modo que outros criadores de software possam desenvolver produtos acionados por esse serviço.

- Brincar com API do banco central e do SUS.

**APIs REST e RESTfull:** (Representational State Tansfer), sendo um conjutno de restrições e boas praticas utilizadas para que as requisições HTTP atendam as diretrizes definidas na arquitetura.
*API REST* refere-se à uma abordadgem arquitetural em si, descrevendo os princípios gerais que  guiam a criação de serviços web.
*API RESTful* é uma implementação espedcífica de uma API que adere aos príncipios do REST, seguindo as diretrizes e boas práticas.

Suporte a HATEOAS, permitindo a descoberta dinâmica de recursos relacionados por meio links.

curl: forma de requisição direta pelo terminal, podemos consumir API por isso


















,