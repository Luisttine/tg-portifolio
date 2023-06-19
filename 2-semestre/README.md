## Em 2021-2

Neste segundo projeto, foi o primeiro com uma empresa parceira, a JetSoft, uma empresa de software que oferece serviços e produtos a outros clientes.

O objetivo do projeto foi de criar um CRUD (Create, Read, Update e Delete) para essa empresa de software com intuito de emitir relatórios mensais de controle de presença de colaboradores com alocação específica de diferentes postos de trabalhos acordados em um contrato com o seu respectivo cliente.

Assim como está sendo mostrado no GIF abaixo, a partir do problema, foi criado um aplicativo web para solucioná-lo. E nele foi implementado as seguintes funcionalidades:

* **Marcação de presença:** Com o colaborador autenticado pelo sistema, na tela inicial, é possível marcar a presença no dia letivo de trabalho;
* **Autenticação e nivelamento de acesso:** Ao entrar no site, será necessário o login e senha do usuário para acessar as funcionalidades do sistema. Além disso, dependendo do nível de acesso, será permitido apenas acessar algumas páginas da aplicação. Desse modo, os níveis de acesso e suas permissões são:
    - **Nível Operacional:** Nesse nível mais baixo, só é permitido entrar na páginas Home (para marcar a própria presença) e na página com mais informações dos desenvolvedores;
    - **Nível Tático:** Esse é o nível mais alto do sistema. Com esse perfil é possível acessar todas as páginas e realizar todas as funcionalidades do site.
* **Controle de Perfis:** Nesta página, é possível ver os 6 cadastros implementados para solução do problema, sendo eles: Colaboradores, Contratos, Clientes, Postos de Trabalho, Alocações e Usuários. E, ao serem clicados, o usuário é redirecionado para um formulário para inserir os campos necessários e cadastrá-los no sistema;
* **Quadro de Presença:** A página principal com o quadro de presenças. Nele contém as presenças dos postos de trabalho e também as presenças de cada colaborador do seu respectivo posto que são possíveis de serem editados e excluídos. Nesta tela, também é permitido realizar pesquisas com o nome do colabodor ou posto e existe a funcionalidade de gerar relatório do quadro de presença (com uma cópia do quadro e com dados de frequência de presença) e relatório gerencial (com gráficos, dados e porcentagens relacionados a frequência de colaboradores e postos), que podem ser exportados como pdf ou salvos dentro de um histórico na aplicação;
* **Edições:** Tela com tabelas de Colaboradores, Contratos, Clientes, Postos de Trabalho, Alocações e Usuários e seus respectivos dados. Nesta página é possível a visualização, edição e exclusão destes dados;
* **Página dos Desenvolvedores:** Informações sobre os desenvolvedores do sistema;
* **Guias:** Além das páginas do sistema, foram implementados os seguintes PDF's:
    - **Guia de Instalação:** Com instruções de como executar a aplicação em localhost;
    - **Guia de Usuário:**: Para auxiliar os usuários a utilizar o sistema;
    - **Contenção de Problemas:** Soluções de erros que podem ocorrer na aplicação.

<img src="https://github.com/Inodevs/Inodevs/blob/main/Execu%C3%A7%C3%A3o%20Final.gif" width="90%">

Caso queira saber mais, segue o link do repositório oficial: [GitHub](https://github.com/Inodevs/Inodevs)

## Tecnologias Utilizadas

### Back-End:
* MySQL -> Essa linguagem foi utilizada para manipulação dos dados cadastrais do site 
* PHP -> Essa linguagem foi utilizada para conversar diretamente com o banco de dados com os métodos POST e GET

### Front-End:
* HTML -> Essa linguagem de marcação foi utilizada na criação das páginas do site
* CSS -> Essa linguagem de estilização foi utilizada no tratamento de UX/UI do site
* JS -> Essa linguagem foi utilizada para proporcionar uma maior dinamicidade no site, popups de confirmação de ações do usuário por exemplo

### Ferramentas para desenvolvimento:
* PHPMyAdmin -> Essa ferramenta foi utilizada para servir o banco de dados do site
* Visual Studio Code -> Essa ferramenta foi utilizada para desenvolimento dos códigos em geral
* Discord -> Essa ferramenta foi utilizada para meio de comunicação entre a equipe
* GIT -> Essa ferramenta foi utilizada para controle de versão do projeto
* Figma -> Essa ferramenta foi utilizada para desenvolvimento do Wireframe (Protótipo) do projeto


## Contribuições Pessoais

Nesse projeto atuei como Desenvolvedor Front-End, criando, estilizando e revisando todas páginas, mas dentre as páginas eu foquei mais nas de cadastro, tabelas para visualização e página home. Por último ainda contribui na construção dos scripts na qual geram relatórios de faltas e presenças por mês.  

Algumas das vezes também ajudei a organizar e separar tasks para a sprint juntamente com a Master, utilizando sempre o Discord para comunicação e troca de arquivos Power Point


## Hard Skills

Com todas os desafios e dificuldades que tivemos durante o desenvolvimento web tive várias novos conhecimentos que ainda utilizo no cotidiano.

Consigo atuar/utilizar com autonomia:
* HTML 
* CSS 
* MySQL 
* Metodologia Scrum
* Visual Studio Code
* Figma
* GIT

Mesmo com muitos aprendizados ainda possuo certas dificuldades por falta de conhecimento nas seguintes tecnologias:
* PHP
* JS

## Soft Skills

Algo que aprendi neste projeto foi o trabalho em equipe. No meu primeiro projeto como não sabia direito qual caminho seguir acabei muitas das vezes atuando sozinho, porém no segundo projeto que participei vi como trabalhar em equipe e o quanto isso ajuda no desenvolvimento, tanto pessoal, quanto profissional, se assim posso dizer.
