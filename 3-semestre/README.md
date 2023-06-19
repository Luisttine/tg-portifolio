## Em 2022-1

No terceiro semestre, o cliente foi a TecSus, uma empresa de automação empresarial.

A proposta fornecida pela empresa foi de criar um sistema para coletar e processar contas de água, energia e gás com direcionamento a diversas empresas de setores de atacado e varejo, para assim ser possível realizar a digitação de todos os campos das contas de forma fácil, eficiente e agradável que serão salvos em um banco de dados para eventuais consultas e análises técnicas ou financeira, possibilitando trazer ao cliente oportunidades de redução de custos e alteração de contratos.

Desse modo, de acordo com o que foi solicitado, foi criado um website para solucionar este problema. Como pode ser visto no GIF abaixo, as funcionalidades implementadas na aplicação foram:

* **Autenticação:** Ao entrar no sistema, a primeira tela será para a autenticação do usuário com login e senha;
* **Dashboards:** A primeira página, após o usuário ser autenticado, é a de dashboards. Primeiramente, nela contém uma lista de unidades que podem ser clicadas para exibir gráficos e outros dados relevantes relacionados aos gastos das contas do contrato com a concessionária, disparando uma mensagem de aviso para caso o consumo seja maior que a do mês anterior. Além disso, é possível gerar um relatório em pdf com estes dados;
* **Tabelas:** Nesta página é possível visualizar e excluir os dados dos cadastros de contas, concessionárias, unidades e contratos. Além disso, ao clicar em um cadastro específico, é possível ver todos os campos para editá-los;
* **Cadastros:** Na barra de navegação, a opção de cadastros abre uma janela com as seguintes opções de formulários: 
    * **Conta:** para cadastrar as contas (com um campo incluso para upload do arquivo da conta);
    * **Concessionária:** para cadastrar as concessionárias (com opções se ela é de água, energia ou gás);
    * **Unidade:** para cadastrar unidades (com um auxílio de uma API para a automatização de preenchimento de dados apenas com o CEP);
    * **Contrato:** para cadastrar os contratos (com dois selects com apenas concessionárias e unidades cadastradas no sistema).
* **Perfils:** página com um CRUD de usuários, sendo possível visualizar, cadastrar, editar e excluir. Além disso, também possui uma opção para redefinição de senha;
* **Histórico:** A última página é a de histórico. Nela contém informações de quem, o que e quando algum dado de cadastro foi adicionado, alterado ou excluído;
* **Perfil, ajuda, notificações, e pesquisa:** No canto superior direito da tela, temos alguns ícones que trazem infromações de perfil (dados do usuário logado e botão de sair), ajuda (instruções sobre a página em questão), notificações (com avisos de pendência e reprovação de cadastros) e pesquisa (em algumas páginas com tabela com vários dados é possível realizar uma pesquisa para encontrá-los mais facilmente);
* **Níveis de Acesso:** Por fim, neste sistema existe um nivelamento de acesso de acordo com a pessoa autenticada, e cada tipo de usuário possui as seguintes funcionalidades:
    * **Digitador:** Consegue cadastrar, visualizar e editar contas, concessionárias, unidades e contratos. Ele recebe notificações para caso seus cadastros sejam reprovados pelo gestor;
    * **Gestor:** Pode realizar todas as funções do sistema. Ele possui um papel de analisar o que foi cadastrado pelo digitador, recebendo sempre notificações de novos cadastros;
    * **Administrador:** Assim como o gestor, possui todo acesso da aplicação. Porém, ele tem uma função mais geral da manipulação do sistema, cuidando, principalmente, do controle de usuários e seus históricos de ações.

<img src="https://github.com/GustavoAndo/portifolio-TG/blob/main/img/3-semestre.gif" width="90%">

Caso queira saber mais, segue o link do repositório oficial: [GitHub](https://github.com/NewInoDevs/NewInoDevs)

## Tecnologias Utilizadas

### Back-End:
* MySQL -> Essa linguagem foi utilizada para manipulação dos dados cadastrais do site 
* Java -> Essa linguagem foi utilizada para todas as ações do beckend, sendo cadastros, listagens e até mesmo persistência dos dados
* Spring -> Framework em java utilizado para controle de dependência

### Front-End:
* HTML -> Essa lingugagem de marcação foi utilizada na criação das páginas do site
* CSS -> Essa linguagem de estilização foi utilizada no tratamento de UX/UI do site
* JS -> Essa linguagem foi utilizada para proporcionar uma maior dinamicidade no site, popups confirmando ações do usuário por exemplo
* Bootstrap -> Framework utilizado para desenvolvimento web de interfaces gráficas 

### Ferramentas para desenvolvimento:
* Visual Studio Code -> Essa ferramenta foi utilizada para desenvolimento dos códigos em geral
* Discord -> Essa ferramenta foi utilizada para meio de comunicação entre a equipe
* GIT -> Essa ferramenta foi utilizada para controle de versão do projeto
* Figma -> Essa ferramenta foi utilizada para desenvolvimento do Wireframe (Protótipo) do projeto


## Contribuições Pessoais

Nesse projeto atuei novamente como Desenvolvedor Front-End, assim como citado no 2º semestre, com a diferença de ter "brincado" um pouco mais com o Back-End, ajudando na geração dos PDF's como relatório final das contas cadastradas, na conexão com o banco de dados, juntamente com os formulários já cadastrando suas respectivas informações.

Como meus planos para o próximo semestre eram ser master, acompanhei mais de perto os passos da nossa master Julia Maria para ter uma idéia do caminho que eu deveria seguir, ajudando ela com excel para organização das tasks, desenvolvimento das User Stories e também na estimativa das tasks.


## Hard Skills

Com todas os desafios e dificuldades que tivemos durante o meu primeiro contato com desenvolvimento web tive várias novos conhecimentos que ainda utilizo no cotidiano.

Consigo atuar/utilizar com autonomia:
* HTML 
* CSS
* Bootstrap
* MySQL 
* Metodologia Scrum
* Visual Studio Code
* Figma
* GIT

Mesmo com muitos aprendizados ainda possuo certas dificuldades por falta de conhecimento nas seguintes tecnologias:
* Java (Consigo utilizar com auxilio de pesquisas)
* Java Script (Consigo utilizar com auxilio de pesquisas)
* Spring (Consigo utilizar com auxiilio de pesquisas)

## Soft Skills

Com este terceiro projeto aprendi mais sobre gestão de pessoas e como um bom humor pode influenciar grandemente no desenvolvimento, tanto mental quanto técnico de uma pessoa no grupo, sendo assim pude ver na prática o desempenho de cada integrante com um bom ou mal humor por exemplo.
