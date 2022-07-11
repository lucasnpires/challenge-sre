
# DevOps/SRE

O teste de SRE é composto pela construção de uma **arquitetura** e o IAC dessa arquitetura. 
Segue abaixo as informações relevantes sobre esta aplicação:

- É construída em Java;
- A forma de conexão dela é HTTP;
- É uma aplicação que não pode ter downtime (nem de poucos segundos);
- Essa aplicação tem dependências externas (bando de dados, rabbitmq, etc)

## Arquitetura

- Leia o cenário a seguir antes de prosseguir:

Visto que a aplicação precisa ser entregue de forma que não haja downtime nenhum e precisamos entregar uma nova versão gradativamente. Crie uma arquitetura que contemple esse cenário explicando a estratégia que acha que faz sentido utilizar e como as requisições HTTP devem chegar nas duas versões da aplicação.

> \* Assumir que é uma solução gerenciada. Ex: AKS

#### O resultado deve conter um documento de texto (pdf, markdown, git, etc) contendo a arquitetura proposta, documentação relevante (se houver) e o IAC de forma reprodutível.


## Avaliação

Discutiremos como esse sistema evoluiria ao longo do tempo, e quais trade-offs você fez hoje e/ou teria que fazer em futuros hipotéticos.