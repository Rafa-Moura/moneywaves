# Money waves bank

Money Waves é um projeto de estudo desenvolvido por Rafael Moura e Karol Susan.
O intuito do projeto é focar no desenvolvimento de habilidades de desenvolvimento, 
metodologia ágil, devOps, versionamento e gestão de projetos.

## Conceito do projeto

O Money waves irá simular um banco digital em que seu CORE será a disponibilização
de crédito via cartão. O público alvo do money waves serão pessoas que necessitem
ou estejam em busca de uma oportunidade de obtenção de crédito de maneira mais
ágil e com um processo menos burocrático.

## Organização e gestão do projeto

A gestão do projeto será feita com o auxílio das ferramentas Notion e Trello.
O notion irá provar um espaço para descrição e history case da aplicação. O trello
será utilizada como BOARD do projeto, sendo escolhido como ferramenta para aplicação
da metodologia ágil SCRUM.

## Stack utilizada

### Backend

No backend, foi adotada a solução de microsserviço, desenvolvendo uma API RESTFul
que irá prover endpoints para controles de usuários, serviços do banco e análises.
A api será desenvolvido utilizando o JAVA em sua versão 17, SpringBoot em sua versão 3.1.5,
MySql, H2DB para ambiente de testes e GitHub como repositório de versionamento.

#### Serviços de usuários

Será fornecido um controller com todas as funcionalidades para realização de gestão de usuários.
Desde sua criação até o end-user que seria exclusão de contas e admin.

#### Serviços bancários

Será fornecido um controller com funcionalidades de serviços bancários como: 
Solicitação de cartão, abertura de conta digital, visualização de extrato e solicitação de aumento de limite.

#### Serviços de admin

Será fornecido um controller com funcionalidades de serviços onde será possível
realizar a parte administrativa do banco. Inclusão de funcionários, alteração de taxas,
novos produtos e outros.

### Frontend

No frontend, será adotado a utilização do React para criação de serviços reativos.
O intuito é utilizar de uma biblioteca que irá fornecer estabilidade e segurança
para trocas de estados da aplicação, agilidade de comunicação e escalabilidade.
