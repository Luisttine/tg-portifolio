# Em 2023-2

## Sobre o Projeto

Para o último projeto no sexto semestre, a empresa colaborativa foi a [Pro4Tech](https://www.pro4tech.com.br/), uma empresa que trabalha com soluções inovadoras que impulsionam o crescimento, otimizam processos e potencializa o negócio de seus clientes. Eles possuem serviços na área de desenvolvimento web, aplicativos, inteligência artificial (IA), inteligência empresarial (BI), automação de processos robóticos (RPA) e inteligência das coisas (IoT), utilizando métodos ágeis.

O projeto proposto pelo cliente foi de desenvolver uma aplicação para empresa com intuito de otimizar o processo de recrutamento e seleção de candidatos através de cadastros de vagas com uma descrição que demonstre um CHA (conhecimentos, habilidades e atitudes) indicado para ela. A partir desta descrição, será realizado um Web Scrapping para que se obtenha um ranqueamento de melhores candidatos com perfil mais aderente a vaga.

Assim, a partir da proposta e requisitos solicitados pela empresa, a solução implementada trouxe as seguintes funcionalidades ao sistema:

* **Autenticação:** A primeira tela apresentada é a de autenticação. Nela a empresa, antes de obter acesso a qualquer funcionalidade, deve enviar suas credenciais feitas através pelo e-mail e senha, além de uma autenticação de dois fatores;
* **Autenticação dois fatores:** Como citado anteriormente, a empresa deve realizar uma autenticação de dois fatores para acessar a aplicação, que é feito através de um e-mail que a empresa cadastrou; 
* **Cadastro de Empresa:** Caso a empresa ainda não tenha uma conta, é possível se cadastrar ao indicar que a mesma não possui conta na tela inicial. Após isso, o usuário será redirecionado para um formulário que deverá ser preenchido para fazer seu cadastro e a empresa conseguirá acessar o sistema;
* **Listagem das Vagas:** Ao entrar na aplicação, será exibido a listagem de vagas que foram cadastradas pela empresa. Nessa página, a empresa consegue editar as informações da vaga e visualizar o último ranqueamento de candidatos feito para vaga;
* **Ranqueamento de Candidatos:** Quando clicado no ícone de visualização, o usuário consegue visualizar os 8 melhores candidatos para aquela vaga e a porcentagem de match que cada um possui, ou seja, o quão apto para aquela vaga o candidato é; 
* **Cadastro da Vaga (CHA):** Nessa tela, o usuário pode cadastar uma vaga, colocando seu nome e nível, e a partir destes dois campos, uma IA gerará a descrição de vaga com base no CHA (conhecimentos, habilidades e atitudes) que podem ser posteriormente editados e aprimorados pela IA. Após isso, é possível salvar os dados da vaga novamente ou solicitar para fazer o match dos candidatos, que será realizado o Web Scrapping e selecionados os melhores perfis para vaga;
* **Perfil:** Também é possível a empresa visualizar suas informações cadastradas nesta página, além de editá-las e fazer a redefinição de senha;
* **Redefinição de senha:** Além de fazer a redefinição através da página de perfil citada anteriormente, é possível redefinir na tela de login, caso a pessoa tenha esquecido a sua senha;
* **Notificações:** Quando a empresa gera uma descrição CHA ou realiza um match, a empresa é notificada por e-mail. Além disso, é possível acessar uma página de notificações dentro do site.

Segue abaixo o GIF com a demonstração das funcionalidades descritas anteriormente:

![Gif da execução](https://github.com/GustavoAndo/portifolio-TG/blob/main/img/6-semestre.gif)

Caso queira saber mais, segue o link do repositório oficial: [GitHub](https://github.com/Inodevs-6/Inodevs-doc)

## Tecnologias Utilizadas

### Front-end:
* TypeScript -> linguagem de programação para criação tanto da aplicação mobile quanto da web;
* Vue.js -> framework em JavaScript para desenvolvimento de interfaces gráficas;
* HTML -> linguagem de marcação para a criação do site;
* CSS -> linguagem para a estilização do site.
    
### Back-end:
* Java -> linguagem de programação para controle do Back-End;
* Spring -> framework em Java para controle de dependência para fazer a persistência de dados;
* MySQL -> sistema de gerenciamento de banco de dados.

### Inteligência Artificial:
* Python -> linguagem de programação usada para criar o modelo de IA;
* Django -> framework utilizado para criar rotas para funções Back-End independentes.

### Ferramentas para desenvolvimento:
* Visual Studio Code -> Essa ferramenta foi utilizada para desenvolimento dos códigos em geral
* Discord -> Essa ferramenta foi utilizada para meio de comunicação entre a equipe
* GIT -> Essa ferramenta foi utilizada para controle de versão do projeto
* Figma -> Essa ferramenta foi utilizada para desenvolvimento do Wireframe (Protótipo) do projeto
* Jira -> Essa ferramenta foi utilizada para gestão de projetos utilizando a metodologia Scrum


## Contribuições Pessoais

#### Neste último projeto da faculdade, foi dado o desafio de construir um sistema integrado com nossa própria inteligência artificila, e como curioso que sou, levei meus aprendizados do INPE
em consideração e apliquei certos métodos de treinamento utilizando Scikit Learn do Python. 
#### Caso o sistema do Front e Back ficarem fora de serviço, tive a idéia de criar rotas separadas para raspagem da dados dos candidatos, geração da descrição CHA e match de candidatos utilizando o framework Django.
#### Sendo assim atuei fortemente na Inteligência Artificial, pesquisei sobre algoritmos e apliquei o que mais cabia dentro de nossos objetivos, o chamado Bag of Words.
#### Ainda atuei em algumas páginas do Front e tasks do Back, como a página de notificações e o envio de emails como notificação de que a busca de candidatos foi concluida.

## Hard Skills

Com esse tema de Inteligência Artificial pude aprimorar meus conhecimentos em Python para aplicação de IA que aprendi nos meus poucos meses no INPE, conhecendo novas bibliotecas, novos algoritmos 
e entendendo melhor o termo de IA.

Consigo atuar/utilizar com autonomia:
* Python 
* Django
* Vue.js 
* MySQL 
* Node 
* Spring
* HTML
* CSS3
* Jira
* Java
* Java Script

## Soft Skills
Obtive uma melhor visão macro da solução de problemas, pensando em casos de testes variados para tentar suprir a maioria dos possiveis bugs ou erros, e tive uma melhora muito grande de proatividade para pesquisar
sobre algoritmos aplicáveis para nosso projeto, fazendo com que desde a primeira sprint, a equipe atacasse o real problema do cliente, a raspagem de candidatos e o match com a vaga gerada.
