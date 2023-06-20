## Em 2023-1

A empresa parceira deste projeto foi a IACIT, uma empresa que atua no desenvolvimento de produtos e sistemas aplicados às áreas de auxílio do controle e do tráfego aéreo e marítimo, defesa e segurança pública, fábrica de software, meteorologia, telemetria e agronegócio e pesquisa, desenvolvimento e inovação.

O cliente propôs para o quinto semestre o desenvolvimento de uma aplicação híbrida que funcione como Serviço de Atendimento ao Cliente (SAC), onde o usuário poderá cadastrar registros de ocorrências (RO's) e o suporte conseguirá verificar as solicitações criadas e solucionar os problemas do usuário, podendo também entrar em contato via chat.

Sendo assim, a solução que implementamos foi o desenvolvimento de uma aplicação mobile e web, que pode ser visto sua execução no primeiro e segundo GIF abaixo respectivamente. Portanto, as funções implementadas foram:

* **Autenticação:** Para acessar a aplicação, primeiramente, é necessário se autenticar no sistema com e-mail e senha;
* **Nivelamento de Acesso:** Existem dois níveis de acesso:
    * **Cliente:** Usuários que criam os RO's e aguardam serem resolvidas. Ele tem as seguintes permissões: acessar a página Home; criar, fechar e acompanhar os RO's; e entrar em contato com o suporte via chat;
    * **Administrador:** Encaminhado para resolver os RO's. Possui acesso completo da aplicação;
* **Home:** Após se autenticar, o usuário possui várias opções de botões para acessar as funcionalidades do sistema (apenas na versão mobile, na versão web o usuário é redirecionado para página Registro de Ocorrência, já que temos um menu de navegação maior);
* **Registro de Ocorrência:** Nesta página, contém a listagem de registros de ocorrências, que podem ser buscados por ID ou título e, caso o usuário seja um administrador, pode ser filtrado por Minhas Tasks, onde é mostrado apenas ROs indicados para o usuário resolver. Além disso, ao clicar em um RO específico, o administrador consegue atualizá-lo com uma solução para o problema. Após esta resposta, o cliente poderá analisar e concluir ou recusar o RO. Caso seja a primeira opção, o RO é fechado, caso contrário, ele deverá ser analisado novamente pelo administrador; 
* **Membros do Suporte:** Tela com a listagem dos usuários cadastrados no sistema. Ao clicar em um usuário específico, será mostrado mais detalhes dele e seus dados poderão ser atualizados;
* **Novo Registro de Ocorrência:** Nesta tela é possível cadastrar um novo Registro de Ocorrência;
* **Cadastrar Novo Usuário:** Página para a criação de um novo usuário para entrar na aplicação;
* **Redefnição de Senha:** Quando um usuário é criado pelo administrador, o usuário receberá um e-mail com um link de redefinição de senha, que será redirecionado a uma página da aplicação para que ele possa definir sua senha. Além disso, também é possível clicar em "Esqueci a senha" para receber um e-mail para a redefinição;
* **Meus Chats:** Página que é possível conversar diretamente com o responsável da resolução dos RO's; 
* **Opções Extras:** Tela com opções extras de segurança. É possível, caso o usuário seja um administrador, criar um backup e restaurar o último backup, além de disponibilizar, independetemente de ser administrador, os termos de compromisso na utilização da aplicação;
* **Relatório:** Nesta página temos um gráfico com os dados dos RO's que foram abertos, além de especificar quantos estão sem tratamento, em tratamento e concluídos. É possível filtrar os dados do dashboard pro mês e usuário;
* **Notificações:** Nesta tela, é possível visualizar as notificações que aparecem para caso um RO seja criado, atualizado, recusado ou concluído. Além disso, caso o usuário queira, ele pode receber e-mails dessas notificações;
* **Perfil:** Página com as informações do usuário.
  
## Desenvolvimento Mobile (APP):
<img src="https://github.com/GustavoAndo/portifolio-TG/blob/main/img/5-semestre-app.gif">

## Desenvolvimento Web (Site):
<img src="https://github.com/GustavoAndo/portifolio-TG/blob/main/img/5-semestre-web.gif">

Caso queira saber mais, segue o link do repositório oficial: [GitHub](https://github.com/inodevs-5/Reportify_Doc)

## Tecnologias Utilizadas

### Front-end:
* TypeScript -> linguagem de programação para criação tanto da aplicação mobile quanto da web;
* React Native -> biblioteca para desenvolvimento de sistemas Android e iOS de forma nativa;
* HTML -> linguagem de marcação para a criação do site;
* CSS -> linguagem para a estilização do site;
* React -> biblioteca para desenvolvimento de interfaces gráficas em páginas web.
    
### Back-end:
* JavaScript -> linguagem de programação para contrução do Back-End;
* NodeJS -> para execução de JavaScript fora de um navegador web;
* MongoDB -> banco de dados NoSQL para pesistência de dados;
* Mongoose -> ORM em JavaScript para o MongoDB.
    
### Ferramentas para desenvolvimento:
* Visual Studio Code -> Essa ferramenta foi utilizada para desenvolimento dos códigos em geral
* Discord -> Essa ferramenta foi utilizada para meio de comunicação entre a equipe
* GIT -> Essa ferramenta foi utilizada para controle de versão do projeto
* Figma -> Essa ferramenta foi utilizada para desenvolvimento do Wireframe (Protótipo) do projeto


## Contribuições Pessoais

Neste projeto voltei a ser desenvolvedor, e dessa vez tentei ajudar mais no Back-End, criando conexões com o banco de dados, etc. Como requisito da matéria de Segurança da Informação, tivemos que escolher algumas regras do LGPD, sendo elas o Termo de Compromisso, Backup e Restauração do Banco de Dados e Exclusão de Usuários.
Tive a proatividade e curiosidade de pegar a task de Backup e também ajudei na Exclusão de Usuários. Com essas tasks atuei pesquisando e colocando em prática a conexão de dois banco de dados no mesmo projeto, encriptação de dados e também utilizei as ferramentas do nosso próprio Banco de Dados, o MongoDB Tools, na questão do Backup e Restore.

## Hard Skills

Com todas os desafios e dificuldades que tivemos durante o meu primeiro contato com desenvolvimento web tive várias novos conhecimentos que ainda utilizo no cotidiano.

Consigo atuar/utilizar com autonomia:
* TypeScript 
* React Native 
* React 
* JavaScript 
* NodeJS 
* MongoDB

## Soft Skills
Procurei evoluir mais minha Comunicação começando com as mensagens de commit melhor formulado para atualizações ou correções de código, e também problemas ou dificuldades que tive durante o projeto foram todos esclarecidos para o grupo, deixando assim mais visível para a Master, PO e os devs como estão minhas tasks.  
Outro ponto que eu precisava melhorar na minha perspectiva era a Proatividade, mesmo ja tendo mais que a maioria dos integrantes, ainda sobravam tasks em que ninguém se propunha a ser responsável, e seguindo meu objetivo, eu tomava frente e me encarregava de tal.
