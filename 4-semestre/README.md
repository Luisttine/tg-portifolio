## Em 2022-2

O cliente do projeto no quarto semestre foi a 2RP, uma empresa que traz soluções e serviços personalizados para demandas na área de TI, atuando em qualquer segmento de mercado.

O objetivo do projeto deste semestre foi de desenvolver uma plataforma web para controlar a jornada de trabalho dos colaboradores da empresa em horas extras e sobreavisos.

A partir disso, como está sendo apresentado no GIF abaixo, a solução que foi implementada para o problema foi criar um um site com as seguintes funcionalidades:

* **Autenticação:** Inicialmente, temos a tela de autenticação de usuário que necessita do e-mail e senha para acessar o sistema;
* **Home:** Após se autenticar, o usuário estará na página Home com detalhes de seus últimos apontamentos e as horas trabalhadas, além de botões que redirecionam para páginas de apontar horas e visualizar esses apontamentos;
* **Cadastrar Horas:** Página com a funcionalidade principal do sistema. É um cadastro com 3 etapas para realizar o cadastro das horas extras e de sobreavisos trabalhadas por um colaborador;
* **Tabela de Apontamentos:** Nesta tela é possível visualizar os apontamentos de todos os colaboradores e, ao clicar no botão visualizar, é possível ter mais detalhes dos apontamentos e editá-los;
* **Usuários, Projetos, Clientes e Centros de Resultados:** Nestas páginas, temos a listagem, cadastro e edição de usuários, projetos, centros de resultados e clientes;
* **Manipulação de Verbas:** Similar com as páginas anteriores, nesta tela é possível visualizar, cadastrar e editar as verbas que serão utilizadas para o cálculo do valor de cada hora dos apontamentos;
* **Dashboards Individuais e Dashboards Gerais:** Nessas páginas, podemos visualizar dados anuais e mensais sobre os apontamentos de horas extras e de sobreavisos realizados durante este período. Nos Dashboards Individuais é apresentado dados do usuário autenticado e nos Dashboards Gerais é dado as informações gerais dos apontamentos de toda a empresa. Além disso é possível gerar um pdf com um resumo desses dados;
* **Histórico de Apontamentos:** Nesta tela, pode ser visualizado histórico de apontamentos do usuário que está utilizando o sistema;
* **Integração do Login:** Para maior facilidade de acessar a aplicação, foi implementada uma integração com o login da Google como opção de autenticação;
* **Nivelamento de Acesso:** Por fim, também implementamos três níveis de acesso de acordo com a pessoa autenticada, esses níveis são:
    * **Administrador:** Possui acesso completo da aplicação; 
    * **Gestor:** Possui o acesso completo da aplicação, com exceção da páginas de Usuários e Manipulação de Verbas;
    * **Colaborador:** Só tem permissão de acessar a página Home, Cadastrar de Horas, Dashboards Individuais e Histórico de Apontamentos (ele pode editar o Apontamento, porém a aprovação ou reporvação só será feita pelo gestor ou administrador).

<img src="https://github.com/GustavoAndo/portifolio-TG/blob/main/img/4-semestre.gif" width="90%">

Caso queira saber mais, segue o link do repositório oficial: [GitHub](https://github.com/Inodevs-4/2RP)

## Tecnologias Utilizadas

### Front-end:
  * HTML -> linguagem de marcação para a criação do site;
  * CSS -> linguagem para a estilização do site;
  * TypeScript -> linguagem de programação para a criação do site;
  * React -> biblioteca para desenvolvimento de interfaces gráficas em páginas web.
    
### Back-end: 
  * TypeScript -> linguagem de programação para contrução do Back-End;
  * NodeJS -> para execução de JavaScript fora de um navegador web;
  * TypeORM -> ORM em TypeScript para criação da persistência de dados;
  * PostgreSQL -> linguagem de programação para banco de dados para pesistência de dados.
    
### Ferramentas para desenvolvimento:
* Visual Studio Code -> Essa ferramenta foi utilizada para desenvolimento dos códigos em geral
* Discord -> Essa ferramenta foi utilizada para meio de comunicação entre a equipe
* GIT -> Essa ferramenta foi utilizada para controle de versão do projeto
* Figma -> Essa ferramenta foi utilizada para desenvolvimento do Wireframe (Protótipo) do projeto

## Contribuições Pessoais

No quarto projeto, como foi um requisito do cliente, ajudei nas pesquisas e no desenvolvimento do login e criação de tokens para tal. Assim como em outros projetos, nesse também participei mais ativamente do Front-End no desenvolvimento das páginas de formulário, porém atuando também no Back-End ajudando na criação do CRUD para os cadastros.


## Hard Skills

Com todas os desafios e dificuldades que tivemos durante o meu primeiro contato com desenvolvimento web tive várias novos conhecimentos que ainda utilizo no cotidiano.

Consigo atuar/utilizar com autonomia:
* HTML 
* CSS
* React
* NodeJS 
* Typeorm
* MySQL
* TypeScript

Mesmo com muitos aprendizados ainda possuo certas dificuldades por falta de conhecimento nas seguintes tecnologias:
* Java (Consigo utilizar com auxilio de pesquisas)
* Java Script (Consigo utilizar com auxilio de pesquisas)
* Spring (Consigo utilizar com auxiilio de pesquisas)


## Soft Skills

Atuando como Master da equipe, pude aprender a lidar melhor com as pessoas e também como gerenciá-las melhor, seja em uma conversa sobre alguma task e suas dificuldades, ou até mesmo fazendo algum tipo de cobrança ou aviso sobre a data de entrega de certas tasks.
