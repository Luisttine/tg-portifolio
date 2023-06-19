                                                                                                               README.md                                                                                                                       Modified
luções e serviços personalizados para demandas na área de TI, atuando em qualquer segmento de mercado.

O objetivo do projeto deste semestre foi de desenvolver uma plataforma web para controlar a jornada de trabalho dos colaboradores da empresa em horas extras e sobreavisos.

A partir disso, como está sendo apresentado no GIF abaixo, a solução que foi implementada para o problema foi criar um um site com as seguintes funcionalidades:

* **Autenticação:** Inicialmente, temos a tela de autenticação de usuário que necessita do e-mail e senha para acessar o sistema;
* **Home:** Após se autenticar, o usuário estará na página Home com detalhes de seus últimos apontamentos e as horas trabalhadas, além de botões que redirecionam para páginas de apontar horas e visualizar esses apontamentos;
* **Cadastrar Horas:** Página com a funcionalidade principal do sistema. É um cadastro com 3 etapas para realizar o cadastro das horas extras e de sobreavisos trabalhadas por um colaborador;
* **Tabela de Apontamentos:** Nesta tela é possível visualizar os apontamentos de todos os colaboradores e, ao clicar no botão visualizar, é possível ter mais detalhes dos apontamentos e editá-los;
* **Usuários, Projetos, Clientes e Centros de Resultados:** Nestas páginas, temos a listagem, cadastro e edição de usuários, projetos, centros de resultados e clientes;
* **Manipulação de Verbas:** Similar com as páginas anteriores, nesta tela é possível visualizar, cadastrar e editar as verbas que serão utilizadas para o cálculo do valor de cada hora dos apontamentos;
* **Dashboards Individuais e Dashboards Gerais:** Nessas páginas, podemos visualizar dados anuais e mensais sobre os apontamentos de horas extras e de sobreavisos realizados durante este período. Nos Dashboards Individuais é apresentado dados do usuário autenticado e no>
* **Histórico de Apontamentos:** Nesta tela, pode ser visualizado histórico de apontamentos do usuário que está utilizando o sistema;
* **Integração do Login:** Para maior facilidade de acessar a aplicação, foi implementada uma integração com o login da Google como opção de autenticação;
* **Nivelamento de Acesso:** Por fim, também implementamos três níveis de acesso de acordo com a pessoa autenticada, esses níveis são:
    * **Administrador:** Possui acesso completo da aplicação;
    * **Gestor:** Possui o acesso completo da aplicação, com exceção da páginas de Usuários e Manipulação de Verbas;
    * **Colaborador:** Só tem permissão de acessar a página Home, Cadastrar de Horas, Dashboards Individuais e Histórico de Apontamentos (ele pode editar o Apontamento, porém a aprovação ou reporvação só será feita pelo gestor ou administrador).

![Gif da execução do projeto](../img/4-semestre.gif)

> [Acesse o repositório no GitHub clicando aqui](https://github.com/Inodevs-4/2RP)

## Tecnologias Utilizadas

* **Front-end:**
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **TypeScript:** linguagem de programação para a criação do site;
    - **React:** biblioteca para desenvolvimento de interfaces gráficas em páginas web.
* **Back-end:**
    - **TypeScript:** linguagem de programação para contrução do Back-End;
    - **NodeJS:** para execução de JavaScript fora de um navegador web;
    - **TypeORM:** ORM em TypeScript para criação da persistência de dados;
    - **PostgreSQL:** linguagem de programação para banco de dados para pesistência de dados.
* **Outros:**
    - **Figma:** ferramenta para criação do protótipo do projeto.

## Contribuições Pessoais

No quarto projeto, sendo desenvolvedor, colaborei com minha equipe principalmente na parte do Back-End, utilizando NodeJS com TypeScript. Primeiramente, realizei a modelagem das entidades com TypeORM. Fiz a parte da persistência de dados e as operações de CRUD para os a>

## Hard Skills

* **HTML5** - sei fazer com autonomia;
* **CSS3** - sei fazer com auxílio de consultas;
* **TypeScript** - sei fazer com auxílio de consultas;
* **React** - sei fazer com auxílio de consultas;
* **NodeJS** - sei fazer com autonomia;
* **Typeorm** - sei fazer com autonomia;
* **MySQL:** - sei fazer com autonomia.

## Soft Skills

* **Comunicação:** com uma equipe com 8 integrantes, uma boa comunicação para todos se interarem com o andamento do projeto foi essencial para a entrega das sprints;
* **Proatividade:** para trabalhar com tecnologias novas (TypeScript, NodeJs e React), tanto no front-end e back-end, foi necessário proatividade para aprender as linguagens e realizar as tarefas com sucesso;
* **Organização:** com maior número de pessoas no time, a organização das atividades foi imporante para entregar tudo o que foi proposto para as sprints.






