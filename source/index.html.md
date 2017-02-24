# Pipz | Manual do Usuário

Olá! Seja muito bem vindo ao Pipz Automation! 

Estamos muito felizes que você escolheu a nossa plataforma de automação de marketing. Excitado para dar um upgrade na sua empresa? Nós, com certeza estamos ![Eddie feliz](https://pipz.com/static/images/blog/eddie.png)
Para começar, preparamos um manual que vai te ajudar a tirar o máximo proveito do nosso software. A partir de agora, você poderá gerenciar o seu negócio de forma automatizada, cada vez mais eficaz.  
Caso tenha alguma dúvida você sempre pode falar com a nossa equipe de Customer Success. Estamos à disposição!
*Boa leitura!*

## Começando
Antes de começar a utilização do Pipz, temos certeza que você quer dividir o acesso à ferramenta com outras pessoas que também farão parte do seu Dream Team no Pipz. Para isso vamos começar falando sobre como gerenciar o seu perfil e o de seus usuários. 


### Usuários e Times
* Gerenciando o seu perfil
Você terá acesso ao seu perfil de usuário através do seu avatar na canto superior esquerdo. Uma nova aba será aberta, onde você pode fazer logout de sua conta e acessar o perfil clicando em My profile. Nesta página você tem acesso a quatro sub-menus:
-Personal: aqui você encontra as informações de API Key e API Secret; seu email pessoal do sistema(mensagens enviadas para este endereço são recebidas pelo Conversations); pode alterar o seu nome e fazer upload de uma foto para seu avatar;
-Change password: adicione aqui a nova senha que deseja utilizar e clique em’ Change Password’;
-Change Email: aqui você visualiza o email atualmente utilizado para acesso ao sistema e pode alterá-lo, adicionando o novo endereço de email e clicando em ‘Change Email’.
-Preferences: aqui você seleciona o timezone a ser considerado pelo sistema.
* Como gerenciar o meu menu lateral
Pode ser que você e seu time não utilizem todos os recursos presentes no menu, mas somente aqueles mais relevantes para a sua equipe. Para manter a visibilidade mais, você pode gerenciar os módulos que aparecerão na sua conta. Para tal, vá ao menu Settings, clique em System e depois clique em Manage Modules. Os recursos Dashboard e Contacts são fixos no menu, mas todos os outros podem ser desativados e não aparecerão mais pra você, podendo ser novamente ativados a qualquer momento. 
* Como adicionar novos usuários
Para adicionar um novo usuário, acesse o menu Settings, depois clique em Team, e depois clique em Users. No campo superior direito, clique no botão ![botão de adicionar](https://pipz.com/static/images/blog/add.png) e você será redirecionado para a página de preenchimento de informações , sendo elas: Name, Job Title e Email.
Na página inicial aparecem todos os seus usuários criados, um overview de suas informações e você poderá acessar o submenu de cada perfil, formado por um Dashboard, Profile, Password e Email.
* Como criar times
Para criar um novo time, acesse o menu Settings, depois clique em Team, e depois clique em Teams. No campo superior direito, clique no botão ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) e você será redirecionado para a página de preenchimento do nome do novo time a ser criado.
Na página inicial de cada time você terá uma lista de todos os usuários criados na ferramenta, cada um precedido por uma checkbox. Desta forma, você pode facilmente gerir quais os contatos farão parte desta lista.
* Como atribuir permissões
**Ainda não está Disponível. Como será? Já adicionar agora? (Perguntar Dev)**
### Dashboard
* O que é e qual a sua função
O dashboard é um painel que fornece uma visão geral com as métricas chave para o seu negócio. Após a configuração inicial do Pipz, você aprenderá a criar o seu próprio dashboard personalizado com o B.I. (Business Intelligence).
![Dashboard](https://pipz.com/static/images/blog/dashboard.png)
### Instalando o Tracker
Antes de começar, é importante saber que as ações iniciais dentro do Pipz tem caráter mais técnico, pois serão feitas dentro do código HTML do seu site/app. Portanto será necessário contar com o auxílio de um integrante da sua equipe de DEV ou do desenvolvedor do seu Website/App. Se você não tiver acesso a alguém com este perfil, entre em contato conosco para encontrarmos uma solução.
* O que é o Tracker e qual sua função
O Tracker é um snippet de Javascript gerado dentro de sua conta Pipz e que deverá ser instalado no código HTML de seu Website/App. Ele irá fazer a conexão entre o seu Website/App e o Pipz, monitorando os eventos gerados pelos seus contatos dentro do seu domínio e os enviando para nossa plataforma. Além disso, o tracker possibilita o envio de in-app messages e a habilitação do chat online para todos os contatos já identificados com nome e email.
 ![Tracker 1](https://pipz.com/static/images/blog/Tracker1.png)
Como criar o tracker no Pipz
Para criar o tracker no Pipz, clique em Settings, em seguida clique em Apps e, por último, clique em Tracker (você pode selecionar tanto a opção no sub-menu lateral, quanto no painel central). Clique no botão ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) (você pode selecionar tanto o ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) no canto superior direito, quanto no painel central), escolha um nome para o Tracker e clique em .
> Resumo: Settings > Apps > Tracker > ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) > digite um novo nome > clique em **CREATE**
![Tracker 2](https://pipz.com/static/images/blog/Tracker2.png)
![Tracker 3](https://pipz.com/static/images/blog/createtracker.png)
* Como configurar um tracker
Após criar o Tracker, você terá acesso a três novas abas no painel central:
![Tracker Options](https://pipz.com/static/images/blog/tracker-options.png)
Auth: as informações de API Key e API Secret[^footnote].
  [^footnote]:  API Key e API Secret: são as informações de autenticação para acesso via API. A API Key funciona como o nome de usuário e a API Secret como a senha de acesso.
![Tracker auth](https://pipz.com/static/images/blog/auth.png)
Integration code: aqui está o código que deverá ser instalado no HTML do seu App/Website;
![Tracker integration code](https://pipz.com/static/images/blog/integrationcode.png)
Options: aqui você define o tipo de contato (lead ou customer) cujas ações o tracker irá mapear. 
- Na opção “Lead” você pode habilitar o chat e conversar com os visitantes que já se cadastraram no seu website/app informando, pelo menos, nome e email: 
![Tracker type lead](https://pipz.com/static/images/blog/tracker-lead.png)
-Na opção “Customer” você pode não só habilitar o chat, como também o mapeamento de engajamento (que irá mostrar quantas interações, eventos, foram gerados pelo contato) e de tempo de duração de sessão(onde você pode definir qual o tempo mínimo e máximo para se considerar uma sessão. Você pode querer desconsiderar um acesso se o usuário apenas ficou online por 1min, por exemplo). Este tipo de tracker permite a visualização dos usuários online.
* Como instalar o Tracker no seu website/app
![Tracker 4](https://pipz.com/static/images/blog/Tracker4.png)
Está é uma das partes em que pode ser necessário o auxílio de um integrante da sua equipe de DEV ou do desenvolvedor do seu Website/App. Copie o código do Tracker e insira-o  no Integration Code antes da tag </head> do código HTML de cada página do seu Website/App que você deseja monitorar. Assista uma animação demonstrando o processo.
### Adicionando contas de envio
* O que são e pra que servem
As contas de envio serão utilizadas como endereço de email remetente de suas campanhas de email marketing, dos emails enviados através de automações- tantos os que serão enviados a seus contatos quanto aos seus usuários internos- e dos emails de confirmação/sucesso oriundos dos formulários de cadastro.
### O que são Eventos e como funciona o CEI
 * O que são eventos?
Logo abaixo, no mesmo submenu onde está localizado o tracker, é possível acessar a lista de eventos pré-estabelecida do Pipz. Esses eventos são todas as ações geradas pelos seus contatos, tanto anônimos quanto identificados, dentro de seu Website/App. Os eventos de contatos identificados podem ser utilizados na criação de fluxos de automação, na definição de segmentos inteligentes e na geração de relatórios, funis e dashboards analíticos. 
Os eventos de usuários identificados estão sempre atrelados a um endereço de e-mail, sendo este o identificador único de cada contato. Antes de começar a criar eventos e alimentar a plataforma, tire um tempo para mapear o seu negócio e defina todos os eventos importantes da jornada dos seus usuários.

 **Assista uma representação animada de como funciona o registro de eventos na plataforma.**

Todos os eventos enviados ao Pipz ficam armazenados em Settings > Apps > Events
![Events armazenados no Pipz](https://pipz.com/static/images/blog/events2.png) 
Há três métodos padrões para o envio de informações ao Pipz. Todos devem ser incluídos ao código  HTML de seu Website/App com o auxílio de um desenvolvedor.
*Ps: Os métodos a seguir devem ser adicionados ao código HTML após o tracker, para que este seja carregado antes e possa enviar as informações para o Pipz.*
* Como identificar contatos (pipz.identify)
Para identificar os contatos ativos no seu Website/App, você deve executar o método identify com as informações mínimas necessárias para que um usuário anônimo passe a ser um lead: Nome e Email. Esta identificação é o que permite a conexão com o web socket, responsável por permitir o envio de in app messages e a utilização do chat. Além destes atributos básicos do contato, você também pode enviar diversos outros, como cidade, estado, país, cargo, data de aniversário e afins. Assista uma representação animada do registro de novos contatos pelo Pipz.
 
    <script>
    pipz.identify("contact.email", {
        "name": "contact.name",
        "email": "contact.email",
        "city": "contact.city"
        });
    </script>

* Como criar eventos personalizados (pipz.track)
Para enviar eventos para o Pipz, você deve executar o método track. Inúmeras propriedades podem ser enviadas nesse método. É importante salientar que para ser possível utilizar tais propriedades como condições nas automações e na definição de segmentos, elas devem ser enviadas na raiz, ou seja, não envie objetos dentro de outros objetos.

    <script>
    pipz.track('Ebook Download', {
          	title: 'Growth Hacking 101',
          	language: 'English'
     	    });
    </script>
 
* Como rastrear visualizações de página (pipz.page)
Este método, para registrar o evento Page view - quando um visitante anônimo ou identificado acessa o seu Website/App - conta com uma diferença importante: ele atribui, automaticamente, informações relacionadas à origem do contato, como título da página acessada, URL, path, referrer e search, logo,você não precisa enviar estes atributos junto ao evento. Segue modelo: 

    <script> 
    pipz.page();
    </script>

 * Como criar e enviar eventos para o sistema
A criação e envio dos eventos devem ser feitos conforme os modelos apresentados acima. Caso o seu usuário ainda seja anônimo, e você queira identificá-lo ao mesmo tempo em que envia o evento,o faça da seguinte forma (este método deve ser inserido dentro de uma função no seu arquivo javascript):
   
 <script>
    pipz.identify('johndoe123', {
        name: 'John Doe',
        job_title: 'CEO',
        e-mail: 'joe@doe.com',
        company: {
            name: 'JDoe LLC',
            website: 'www.iamjohn.com'
        }
    });
    </script>

 * Como atribuir CEI e Lead Score à eventos
Ao criar e enviar eventos para o Pipz, eles ficam armazenados na sua conta, e você pode acessá-los clicando no menu Settings, depois em Apps e por fim em Events. Nesta página você visualiza todos os eventos criados na sua conta com os seus respectivos Presentation Name(o nome como aparece nas listagens de eventos dentro do Pipz), Event (o nome do evento conforme criado na base de dados), a data de criação e os valores de Lead Score e CEI. 
Para editar os seus eventos, clique no Presentation Name e você será redirecionado para uma nova página, onde poderá editar o Presentation Name e o friendly Text (o texto que aparecerá na linha do tempo toda vez que algum de seus contatos gerar o evento) e atribuir os valores de CEI e Lead score. Se o evento for gerado por um contato do tipo lead, será considerado o valor do Lead score. E se o evento for gerado por um contato do tipo customer, será considerado o valor do CEI.
O CEI (sigla para *Índice de Engajamento* em inglês) consiste em um sistema de atribuição de valores aos eventos de forma a medir a interação dos usuários do seu app de forma flexível e assertiva. Através do CEI, é possível entender como seu Website/App é utilizado e quais recursos possuem maior demanda. O CEI será essencial na configuração das regras de engajamento de usuários(Settings > Engagement > Rules), que será explicado mais adiante. Com uma pontuação clara definindo o que é um usuário engajado, será possível identificar rapidamente os que estão mais distantes do ideal, possibilitando a elaboração de uma estratégia para reduzir o churn. 
Uma diferença primordial entre o Lead score e o CEI, além do óbvio (um se trata de leads/prospects e outro de clientes ), é que o Lead Score vai se somando sempre que um evento com este valor for gerado por um lead, uma vez que o CEI é considerado dentro de horas de utilização ou dentro de uma sessão, ou seja, ele não é cumulativo indefinidamente. O CEI também pode ser utilizado no BI, como uma métrica na geração de relatórios referentes à engajamento.
 ### Contacts & Custom Fields
* Diferença entre contatos anônimos e identificados
-Contatos anônimos: são os contatos ainda não identificados com e-mail e nome, mas que já têm as suas ações monitoradas pelo Pipz. Destes contatos já é possível observar dados referentes à origem, mas não é possível se comunicar com eles através de chats nem de In app messages, uma vez que os dados de e-mail e nome são necessários para se iniciar a conexão com o websocket.
-Contatos identificados: são os contatos previamente identificados, que possuem um cookie armazenado pelo Pipz, e que já estão tendo todas as suas ações rastreadas através dos eventos enviados pelo pipz.track. Todas os eventos deste tipo de contato já são atrelados ao seu perfil. 
* Diferença entre Contacts e Companies
No Pipz é possível manter o registro de eventos tanto de Contacts(contatos) quanto de Companies(empresas). Os contatos são identificados através de um e-mail único e têm todas as suas ações atreladas a ele. Já as empresas(companies) são identificadas pelo seu nome e podem ter vários contatos(contacts) simultaneamente. Enquanto cada contato tem um registro próprio e individual de eventos, a empresa possui um registro composto da totalidade de ações geradas por todos os contatos atrelados a ela.
* Como adicionar contatos
No pipz, é possível adicionar contatos no sistema via importação de listas, identificação no Website/App ou por meio de cadastro em um formulário . Entenda como funciona cada uma delas:
-Importação: Clique no menu Settings, selecione a opção Contacts no sub-menu e, então, escolha o board Lists. 
![Como importar listas de contatos1](https://pipz.com/static/images/blog/contacts-list.png) 
Em seguida clique no ícone ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) na tela central ou no canto superior direito para adicionar uma nova lista. 
![Como importar listas de contatos2](https://pipz.com/static/images/blog/contactslistsplus.png) 
Dê um nome a sua lista e clique no botão CREATE
![Como importar listas de contatos3](https://pipz.com/static/images/blog/contacts-lists.png)
 Selecione a aba ***Import contacts*** para adicionar contatos à sua lista.
![Como importar listas de contatos4](https://pipz.com/static/images/blog/importcontact.png) 
Adicione uma lista de contatos em formato .CSV. A lista deve estar formatada conforme às exigências da plataforma. Nesta etapa também já é possível adicionar tags específicas aos novos contatos e selecionar a qual(is) lista(s) eles serão adicionados. Baixe um template de exemplo e evite problemas de configuração.
![Como importar listas de contatos5](https://pipz.com/static/images/blog/csv.png) 
-Identificação: à medida que seus contatos (tanto leads quanto customers) forem se identificando e interagindo no seu App/Website, os trackers instalados no mesmo irão enviar os dados cadastrados para o Pipz. É sempre bom lembrar que, quanto mais atributos forem atrelados aos contatos, maiores serão as possibilidades de segmentação e interação personalizada com eles.

-Formulários: com a utilização de nossos Web forms (formulários online), todas as informações preenchidas por seus contatos serão automaticamente enviadas para o Pipz, gerando a criação de um perfil de contato. Se o formulário já requisitar informações sobre a empresa, um perfil de Company também será criado e este contato será automaticamente atrelado à ele. Para saber mais sobre como fazer o seu próprio formulário, *clique aqui*.
* Lifecycle Stage
Uma informação muito importante a ser enviada ao Pipz é em qual estapa o seu contato se encontra no ciclo de vida do cliente. Você pode enviar esta informação por importação(criando uma coluna no arquivo CSV), através de um campo de um formulário de cadastro ou adicionando manualmente diretamente no perfil do seu contato(na aba profile da página de cada contato). Para criar etapas customizadas ao seu negócio, acesse o menu Settings, clique em Contacts e depois em Lifecycle stage. No canto superior direito você deverá clicar no botão ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) e dar um nome ao stage.
Estes valores criados podem ser utilizados para dar início à uma automação quando forem modificados, por exemplo; podem ser modificados através do passo "Update Lifecycle" de uma automação; e podem ser utilizados como propriedade de um filtro, a fim de ajudar a sua empresa a ter uma comunicação e ações mais personalizadas para os contatos de cada etapa.
* Como criar e gerenciar listas
No menu Settings > Contacts > Lists você deve clicar no ícone ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) no canto superior direito e dar um nome à lista a ser criada. Dentro do perfil de cada lista você encontra:
-**Dashboard**: com informações quantitativas da lista;
-**Contacts**: listagem de todos os contatos da lista;
-**Add to flow**: aqui você pode, de forma manual, adicionar todos os contatos desta lista à uma automação pré-existente e online;
-**Import Contacts**: aqui você pode importar contatos por meio de um arquivo CSV(você encontra um template modelo nesta página) ou por “copy and paste”:
![Gerir as suas listas](https://pipz.com/static/images/blog/manage-list.png) 
* Como criar campos customizados (custom fields)
Com os campos customizados (custom fields) você pode criar campos específicos para armazenar quaisquer informações personalizadas que sejam pertinentes e relevantes para o seu negócio. Para criá-los acesse o menu Settings > Custom Fields e escolha se os campos serão referentes a um contato (contact) ou a uma empresa (company). Depois clique no ícone ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) > defina um *Field Name*[^2] e um *Presentation Name*[^3]. 
[^2]:(Database)Field name: este é o nome interno do campo e que será usado nas importações, exportações e ao salvar os dados na base de dados.
[^3]:Presentation name: este é o nome do campo que será visível nos forms, listas e dashboards.
Após criado, você poderá editar o *Presentation Name* e o *Field Name* previamente definidos além de escolher o Field Type (123: campo numérico, abc:alfabético ou date) e Presentation Type (Text; Number; Datetime; Checkbox; Dropdown: adicionando opções com Nome e Valor; e Textarea).
![Como criar campos personalizados no form](https://pipz.com/static/images/blog/customfield.png) 
### Perfil de Contatos (contacts) vs Perfil de Empresas (companies)
O perfil de contatos (contacts) contém os seguintes campos:
-Dashboard: Você encontra uma visão geral do contato, com informações referentes à últimos eventos gerados, localização, interação com e-mails recebidos, score e ticket médio;
-Profile: aqui estão os principais dados do contato, tais como nome, e-mail, tipo(customer/lead), Lifecycle Stage(New, Subscriber, Evangelist, Opportunity,etc.) endereço, redes sociais, cargo, empresa, entre outros;
-Fields: aqui estão os campos customizados que você cria para armazenar informação personalizada sobre os seus contatos. Ex.: Ramo da empresa, tamanho do sapato, etc;
-Events: apresenta toda a linha do tempo de ações deste usuário;
-Lists: mostra todas as listas das quais o usuário faz parte. Aqui você pode também adicioná-lo/retirá-lo de listas.
-Automations: mostra as automações das quais o contato faz parte no momento. Clicando no ícone ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) você pode escolher uma automação pré-existente(que esteja online) e adicionar este contato a ela;
-Origin: aqui você encontra as informações de origem do contato;
-Note:  adicione notas que poderão ser visualizados por todos os outros usuários do sistema.
O perfil de uma empresa (company) contém seguintes os campos:
-Profile: aqui estão os principais dados da company, tais como nome, e-mail, endereço, redes sociais, ramo de atuação, quantidade de funcionários, entre outros;
-**Fields**: aqui estão os campos customizados que você cria para armazenar informação personalizada sobre a empresa. Ex.:gasto mensal, tipo de plano, etc;
-Contacts: a lista de todos os contatos atrelados à esta company;
-Events: apresenta a linha do tempo com as ações de todos os usuários atrelados à -esta company;
-Notes: adicione notas que poderão ser visualizados por todos os outros usuários do sistema.
### Tipos de filtros
Todos os contatos e empresas armazenados na sua conta Pipz aparecem pra você na página inicial do menu Contacts e do menu Companies. No canto superior direito você encontra o ícone (imagem do ícone de contagem de contatos) que te mostra a contagem de contatos. Logo ao lado você vê a opção *Online*, a qual você pode selecionar para visualizar apenas os contatos online no momento. No campo de busca de contatos, você pode buscar tanto por nome quanto por e-mail. 
Para filtrá-los, e poder  para visualizá-los de forma mais segmentada, você tem quatro opções- quick filter, segments, lists, e tags. O valor mostrado na contagem de contatos se atualiza sempre que você filtrar a sua lista por qualquer um destes filtros.
![Filtros](https://pipz.com/static/images/blog/segments.png)
* Quick Filter
Os quick filters são filtros rápidos e práticos de serem criados, quando o seu objetivo for filtrar os seus contatos e empresas por apenas um atributo. Clique em "+ New quick filter", selecione o campo que quer utilizar como filtro, decida se este filtro será público (visível para outros usuários da sua conta) e clique em salvar. Pronto! O seu quick filter ficará salvo na barra lateral esquerda. Para utilizá-lo, basta selecionar as opções desejadas no campo criado.
* Smart Segments
Os smart segments (segmentações inteligentes) são filtros que você pode criar para segmentar os seus contacts/companies baseados em uma série de regras. Tais regras podem ser agrupadas e comparadas a outros grupos de regras para atingir uma segmentação ainda mais personalizada. Atributos dos contatos/companies, eventos e propriedades de eventos podem ser utilizados para criar estes segments. Este tipo de segmentação permite ter uma comunicação muito mais direcionada com os seus contatos.
* Como configurar um segment
Os segmentos são criados na barra lateral esquerda dentro do Menu Contacts, clicando em “+ New Segment”, dando um nome a ele e depois clicando em *Save*. Todos os segmentos criados ficam disponíveis para seleção nesta barra lateral. Depois de criado, você irá selecionar a propriedade que quer filtrar e seus atributos. Você tem opção de selecionar propriedades relacionadas ao contato, empresa, tags, eventos do contato, notas, engajamento, Milestones, Custom Fields, relatórios e muito mais. 
>Ex.: **Property**: *Name*  **Operator**: *Is*  **Attribute**: *Mariana* |
Este segmento irá filtrar todos os contatos que tiverem o nome Mariana. 
As propriedades podem ser agrupadas e comparadas a outros grupos de propriedades. Você pode definir se os resultados filtrados terão de responder aos parâmetros de todos os grupos comparados (AND) ou de pelo menos um deles (OR). 
* Tags e Lists
Você pode utilizar uma lista ou uma tag para filtrar os seus contatos ou empresas. Para isso, selecione uma das listas ou tags exibidas no menu lateral esquerdo. 
* Como utilizar os filtros
Para filtrar os contatos e empresas, basta selecionar dentre os filtros previamente criados aquele que contenha os parâmetros que você deseja utilizar. Ao selecioná-lo, aparecerá a informação ”Filtered by segment/quick filter/tag/list ‘nome do filtro’ ”, especificando em que aquele resultado se baseia.  Para sair dos resultados do filtro, clique no ‘x’ logo após esta  informação.
* Como criar ações personalizadas com filtros
Ao selecionar o filtro desejado, seja quick filter, segment, lists ou tags, o resultado aparecerá à direita. Nesse momento você pode minimizar a área dos filtros clicando no ícone ![Minimizar área dos filtros](https://pipz.com/static/images/blog/flechax.png) para ter mais espaço de tela para a visualização dos contatos. Ao selecionar os contatos com os quais você deseja interagir, você verá opções de ações aparecerem no topo direito na página. Estas ações são:
-Enviar um email: será aberta uma área para edição de texto para a criação do email;
-Add to Automation: você poderá adicionar todos os contatos selecionados à uma automação já existente na sua base;
-Add to List: esta ação adiciona todos os contatos à lista que você selecionar;
-Add a Tag: você pode definir uma ou mais tags a serem adicionadas ao usuários selecionados;
-Remove: Você irá deletar todos os contatos selecionados.
A nossa página de contatos, assim como a de events, é uma página infinita. Desta forma é importante salientar que se um filtro retornar 1000 contatos, por exemplo, e você marcar a Checkbox ao lado de ‘Name’ para selecionar todos, somente os contatos já carregados na página serão selecionados. É necessário que você role a página até o fim, para que todos os contatos já estejam carregados, e somente então selecione a checkbox.*
### Forms
* O que são e pra que servem
Os web forms são utilizados para converter visitantes de uma página em leads de qualidade. Eles devem ser criados com pelo menos 2 campos: E-mail e Nome.
* Como configurar um form
Vá em Settings > Form > Web form > clique no ícone ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) no canto superior direito e dê um nome ao novo Form. Após criado, você deve definir alguns pontos importantes: 
-a lista à qual este novo contato será adicionado;
-uma automação a ser iniciada após o preenchimento e envio dos dados para o Pipz;
-mensagem de sucesso após o preenchimento;
-template a ser utilizado no email de confirmação da inscrição do contato;
-template a ser utilizado no email de sucesso da inscrição do contato.
* Como criar um form personalizado
Para editar o seu form, clique na aba “Form” e depois em EDIT FORM:
![Como criar um formulário](https://pipz.com/static/images/blog/webform.png)
Você será direcionado à edição do formulário onde pode facilmente escolher se o campo será relacionado à company ou contact (a informação será enviada para o respectivo perfil).  Você pode selecionar campos default do sistema Pipz, custom fields criados por você anteriormente ou ainda criar novos custom fields de contact ou company. Para adicionar um novo campo, clique em um dos campos da aba esquerda e o arraste até o formulário na posição desejada:
![Editando o formulário de contato](https://pipz.com/static/images/blog/forms2.png)
* Como editar um Formulário
Para editar o form você tem as seguintes opções no menu lateral direito:
-Global layout: aqui você determina as questões estéticas do seu form. As cores, margens, dimensão e tipo de fonte; 
-Input Layout: aqui você determina aspectos gerais da apresentação dos campos: a presença de uma etiqueta de nome do campo, o tamanho da fonte da etiqueta e dos campos de preenchimento, cor e dimensão das bordas dos campos;
-Title: habilite ou desabilite um título para o form. Se decidir utilizar um, defina o seu texto, sua cor e dimensões.
-Subtitle: habilite ou desabilite um subtítulo para o form. Se decidir utilizar um, defina o seu texto, sua cor e dimensões.
-Footer: habilite ou desabilite um footer para o form. Se decidir utilizar um, defina o seu texto, sua cor e dimensões.
-Button: aqui você define as propriedades do botão do seu form. O texto, cores, dimensões e posicionamento.
-Fields:  aqui você define se os fields serão de preenchimento obrigatório(Required), o nome da etiqueta (Label name), Placeholder (o nome explicativo do campo que será exibido até o preenchimento do mesmo ser iniciado), Validation (se os dados preenchidos estão em um formato correto para o campo, para url e e-mails) e o quantidade máxima de caracteres a ser preenchida em cada campo.
Após editar o form, clique em salvar .
* Como implementar um formulário
Para implementar o form você deve voltar ao início da aba “Form” e copiar o snippet de Javascript disponível do lado direto. Este código já contém todas as edições feitas por você no form. Este código de JS deve ser adicionado ao código da página onde você quer que ele apareça.
![Como implementar um formulário](https://pipz.com/static/images/blog/formscript.png)
 ### Automação de Marketing 
![Imagem do fluxo de automação](https://pipz.com/static/images/blog/drag-and-drop-marketing-automation.png) 
* O que é e pra que serve uma automação
As automações de marketing são fluxos inteligentes que são iniciados por eventos gerados pelos seus contatos. Uma automação irá permitir que o sistema responda a cada contato de forma personalizada de acordo com as ações tomadas por ele no seu Website/App. 
* Como criar e configurar uma automação
Para criar uma automação vá ao menu Automations > clique no ícone ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) > Defina o nome da automação e o Tracker que estará conectado a ela (O tracker que monitora os eventos chave para esta automação). Você também pode selecionar “None” para que os eventos de todos os trackers sejam considerados.
Após criada, você irá acessar a aba Settings para definir as seguintes configurações:
- the automation should run: aqui você determina se a automação irá acontecer todas as vezes que o contato realizar a ação definida como Trigger, ou somente em uma dada ocorrência (Ex.: somente no 3 Login, na 1a visita a certa página, etc.).
- Contact run simultaneously:se você selecionar esta opção, o contato poderá figurar em mais de uma automação simultaneamente.
-Start/End date: defina o timing para esta automação acontecer. Você pode definir apenas uma data de início, por exemplo, e deixar a data final em aberto. Ou se for uma automação sazonal, você poderá configurar tanto as datas e os horários quanto os dias da semana em que a automação deverá acontecer. 
- Tracker: se você for utilizar um evento como gatilho para dar início à automação, selecione aqui o tracker que monitora este evento(outras opções de gatilho você encontra abaixo);
- Status: também nesta página você gerencia o status da sua automação, podendo ser online, offline ou paused. Em online, todos os contatos que realizarem o evento definido como trigger irão entrar neste fluxo. Em offline, os contatos não entrarão no fluxo, nem se você você alterar o status para online posteriormente. E em paused, o fluxo não será imediatamente iniciado quando os contatos realizarem o evento do trigger, mas estes contatos serão adicionados a uma fila e todos entrarão no fluxo após este ser definido como online novamente.
* Como escolher o "gatilho"(trigger)  da automação
Após configurar a sua automação, defina qual será o gatilho responsável por iniciá-la. Para isso existem 3 opções:
-evento: Selecione o evento que dará início ao flow. Não se esqueça de selecionar um evento que esteja sendo monitorado pelo tracker definido por você em Settings.
- Form: ao definir um form como gatilho, todos os contatos que o preencherem serão adicionados ao fluxo da automação;
- Update Field: você pode selecionar um campo que ao ser atualizado dará início a automação. Este campo pode ser name, email, phone, contact type, stage, job title, etc;
- Other: este tipo de gatilho permite que a automação seja salva, fique online e se inicie a partir da movimentação de cards nos boards.
* Como adicionar passos à automação
Na aba Steps, você terá acesso ao coração do Pipz. O primeiro passo é definir o seu “Flow start”, que será o evento que dará início a automação(trigger) sempre que for gerado por um contato. Se o evento escolhido tiver atributos atrelados a ele, você pode escolher se irá, ou não, defini-los nesse passo. Se decidir por não defini-los, somente o core event será levado em consideração na iniciação da automação.
O fluxo também pode ser iniciado pelo preenchimento de um formulário, e neste caso basta definir quais dos seus forms já existentes será o responsável por adicionar os contatos à automação.
Após definir o trigger, você irá criar um fluxo de automação com todos os passos que achar necessários. Não há limites para a sua imaginação. Para adicionar um novo step, posicione o cursor em cima do ícone laranja do Flow Start, clique no  e o arraste. Ao soltar, uma lista de opções irá aparecer na sua tela para que você escolha qual será o próximo passo.
 Os possíveis steps de uma automação são:
-Add a Tag: defina tags que poderão ser utilizadas posteriormente na segmentação de seus contatos, possibilitando ações personalizadas;
Add to list: adicione o contato em uma lista específica tendo por base as suas ações;
-API Call: você pode fazer uma requisição via API de outros sistemas que você utiliza. Quais ações você conseguirá executar com esta integração dependerão do acesso que você tem a API da ferramenta desejada. Num sistema próprio, por exemplo, onde o acesso ä API é total, as possibilidades desta integração aumentam exponencialmente.
-Condition: A definição de uma condição no fluxo faz com que apenas os contatos que estiverem dentro dos parâmetros desta condição sejam direcionados para o passo seguinte;
-End Automation: este passo fará com que a automação chegue ao fim para todos os contatos que chegarem a ele;
-Do Nothing: este step faz com que a automação não execute nenhuma ação subsequente, mas não necessariamente finaliza a automação;
-Jump to Automation: contatos que passarem por este passo serão redirecionados para uma nova automação definida por você;
-Remove from Automation: se o contato estiver em mais de uma automação simultaneamente, você pode definir este step para retirá-lo de uma delas caso ele atinja determinado passo dentro do fluxo atual;
-**Remove from List**: caso o contato chegue a este step, você poderá definir que ele seja retirado de uma lista (e pode adicioná-lo a outra com o step Add to List, de acordo com suas ações);
-Remove Tag: nesse step pode pode remover uma tag que este contato possua;
Send e-mail: de acordo com as ações realizadas por este contato, envie e-mails a ele. Nas configurações deste passo você tem de definir qual a conta de envio será utilizada, o assunto do e-mail e se a resposta será recebida no e-mail do remetente ou no Conversation do Pipz.
Quanto ao conteúdo do e-mail, você pode utilizar um template previamente criado ou pode criar um nome e-mail no editor de texto/html presente neste step.
-Notify Someone else: este é um envio de e-mail para notificação de alguém da sua equipe. Este recurso é muito útil para situações do tipo: Se um contato não visualizou/respondeu um e-mail enviado há 3 dias, avise alguém da sua equipe para que seja feito contato telefônico, por exemplo.
Set Lead Score: se o seu contato fizer as ações definidas por você, atribua a ele um lead score. Você pode somar ou subtrair pontos do lead score, ou sobrescrever o valor já existente;
-Update Lifecycle: aqui você pode modificar o status dos seus contatos para as seguintes opções: New, Marketing Qualified lead, Evangelist, Lead ou Customer;
-Update Field: defina um novo valor para um campo de contact ou de company para todos os contatos que realizarem determinadas ações.
* Overview das integrações nativas
O Pipz tem algumas integrações nativas, sendo elas:
-Hubspot: 
-Freshdesk: ao receber uma mensagem/email do seu contato, um ticket será gerado no freshdesk. Você pode adicionar um passo de”notify someone else” para avisar à alguém da equipe que um novo ticket foi aberto;
-Maildocker: 
-Mailchimp: 
-Pipedrive: existem dois tipos, blue e black. Blue out- cada novo lead postar o novo deal no pipedrive. black in- um evento no pipedrive pode ser enviado e armazenado no piz
-Slack: 
-Pushbullet:
-RD Station: leads gerados no Pipz podem ser enviados para o RD Station;
-Pipz: esta integração serve para conectar duas contas Pipz. Se determinado evento acontecer em uma conta, ele dá início a uma automação em outra conta Pipz;
-Unbounce:
 * Onde visualizar as integrações ativas
Para acessar todas as integrações já ativadas na sua conta Pipz, clique no menu Settings, depois em Apps, e depois clique em Integrations. Além de visualizar as integrações, você pode criar uma nova clicando no botão ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) no canto superior direito e selecionando o software com o qual você deseja integrar.  Dê um nome à integração e forneça as informações de acesso solicitadas (geralmente API Key e API Secret).
* Overview de Automations(abas)
Dentro de cada automação, além do menu Settings e Steps, você tem acesso aos seguintes submenus: 
-Queue: aqui você vê a listagem de contatos esperando pra entrar em uma automação, no caso de um fluxo que esteja com o status “Paused”, ou contatos que estão entre passos que tenham algum delay entre eles. Ex.:  Preencheu form *3 days later* > Send e-mail. Os contatos que preencherem o form e entrarem nesta automação, estarão na Fila(Queue) por 3 dias, até o momento de receberem o e-mail, que é o próximo passo do fluxo.
A fila é mais um ponto onde você pode adicionar um contato manualmente a uma automação. Você pode procurar por um contato já existente na plataforma, ou adicionar um novo. 
-History: aqui você acessa por ordem cronológica todos os eventos gerados por esta automação.;
-Events: aqui você acessa todos os eventos gerados por esta automação em ordem - cronológica, mas organizados separadamente por contato;
-Priorities: se você definir que um contato não pode estar simultaneamente em mais de uma automação(na aba Settings), você deve classificar a ordem de prioridades entre elas, para que o contato esteja sempre participante do fluxo de maior prioridade determinado por você.
### Templates
* O que são e pra que servem
Os templates são uma forma prática de padronizar todos os emails enviados aos seus clientes e também à sua equipe. Os templates criados em sua conta Pipz podem ser  posteriormente utilizados nos passos de envio de email dentro de uma automação- Send Email e Notify Someone Else- e como email de confirmação e de sucesso dos cadastros efetuados através dos formulários Pipz .
* Como criar um novo template
Para criar templates você deve acessar o menu Settings , depois clicar em Emails e então clicar em Templates. Você será redirecionado para a tela inicial do recurso, onde todos os seus templates ficarão armazenados e onde você poderá buscá-los por nome ou por Tag; organizar por ordem alfabética de Nome, Subject(Assunto), Email do remetente (From name) ou Nome do remetente (From name). No canto superior direito você deverá clicar no botão ![Botão de adicionar](https://pipz.com/static/images/blog/add.png), nomear o template e escolher o assunto.
* Como criar o layout de um template
Após criado, você estará na página de Settings, uma das 3 abas do menu de um template, e poderá alterar o assunto do mesmo. No canto superior direito você tem 3 botões: o preview, o de deleção e o de envio de teste de template. Este último irá te solicitar o(s) endereço(s) de email do(s) usuário(s) Pipz que você quer que recebam este email.
Na próxima aba, HTML, você tem acesso a caixa de edição da campanha. Aqui você poderá criar um novo layout ou adicionar um template pronto em imagem ou código HTML (acesse o source code clicando no ícone “<>” no menu superior da área de edição).
Para gerar a versão plain text, muito importante para a melhoria de entregabilidade de emails, vá para a aba Text e clique em “Copy text from HTML version” e depois em salvar. Pronto! Você já tem uma versão texto da sua campanha. Para adicionar o link de descadastramento, obrigatório no email marketing, adicione a variável {{unsubscribe}} diretamente no source code.

### Funnels
 ![Funis](https://pipz.com/static/images/blog/funnels.png)
* O que são e para que servem
Os funis são uma forma visual de analisar as conversões de eventos, e que facilita a tomada de decisões relacionadas ao planejamento e estrutura da jornada de clientes.
>Ex.:
 -De 1000 e-mails enviados para contatos, quantos foram abertos? Destes, quantos clicados? E destes, quantos respondidos?
-De 500 formulários preenchidos em uma Landing Page do seu produto, quantos contatos converteram em trial? Quantos converteram em clientes pagos?
* Como criar e configurar um funil personalizado
Acesse o menu Funnels > clique no ícone ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) e dê um nome ao seu funil. Para decidir os eventos que serão analisados, selecione o Tracker que deseja, escolha os eventos que aparecem em lista do lado esquerdo e os arraste para a área de Funnel’s events à direita. Quando todos os eventos já estiverem definidos, clique no ícone  ![Botão de salvar](https://pipz.com/static/images/blog/save.png)  para salvar no topo direito e então o funil será gerado com os dados das conversões definidos por você.
### Engagement
* O que é e para que serve
Neste recurso você tem acesso à duas métricas importantes- Milestones e Rules. Ambos com o objetivo de facilitar o entendimento de como os seus contatos interagem e se engajam com o seu produto.
#### Milestones
![Milestones](https://pipz.com/static/images/blog/milestones.png)
São marcos importantes para a jornada do seu contato no seu negócio. Todo Milestone é único, logo ele deve ser iniciado por um evento que só aconteça uma única vez. Este é o caso do onboarding: para que um contato seja considerado ativado ele deve percorrer todos os eventos que fazem parte do processo de onboarding de novos clientes da sua empresa, e o evento inicial é o Sign up. Este evento acontece apenas uma vez.
* Como configurar os eventos de cada Milestone
Agora que você já sabe o que são os milestones, acesse o Menu Settings > Engagement > Milestones > clique no ícone  ![Botão de adicionar](https://pipz.com/static/images/blog/add.png) > nomeie o seu Milestone e defina qual será o evento único que dará início a este fluxo. Após criado você estará na aba Settings, onde poderá editar o nome do Milestone, adicionar uma descrição que ficará visível para outros usuários e definir quantos dias o contato terá pra completar todos os eventos necessários para atingir o Marco. Acesse a aba Events dentro do seu Milestone e escolha, dentre os eventos listados, aqueles obrigatórios para que o Milestone seja atingido. Os eventos podem acontecer em qualquer ordem, não interferindo no resultado do Milestone.
![Como configurar os eventos do Milestones (https://pipz.com/static/images/blog/milestone-onboarding.png)
* Como conectar automações à Milestones
O milestone terá sempre 2 possíveis resultados: Sucesso (Success) e Fracasso (Failure), dependendo se o contato completou, ou não, os eventos no período estipulado. Na página de Settings do Milestone,  você pode conectar uma automação a cada um destes resultados. Estas automações tem de estar previamente criadas e então você pode selecionar cada um delas nas opções de On Success e On Failure. As automações serão iniciadas após os dias estipulados, no caso de fracasso, e assim que o contato completar todos os eventos (desde que dentro do tempo estipulado) no caso de sucesso.
#### Rules 
O significado do que é ser um usuário ativo é muito peculiar em cada negócio. Com as regras de engajamento, você define o que é ser ativo diariamente, semanalmente ou diariamente no seu produto, com base em pontuação dos eventos(pontuação atribuída aos eventos no menu Settings > Apps > Events)  e/ou tempo que o usuário esteve online no seu produto.
* Como configurar  as regras
Você encontrará uma página com três informações a serem preenchidas. As três se diferem apenas no que toca à frequência: Diária, Semanal e Mensal. 
To consider user daily/weekly/monthly active: aqui você define o que é ser um usuário diariamente, mensalmente ou mensalmente ativo no seu produto. Você pode atribuir os pontos e tempo gasto a serem considerados ativos, e decidir se as duas regras tem que ser verdadeiras ao mesmo tempo (AND) ou se podem acontecer separadamente (OR).
Estas regras serão a base para um email que lhe será enviado diariamente pelo Pipz, te informando o ranking dos usuários mais ativos e menos ativos no dia, semana e mês. Este recurso será o seu melhor amigo na prevenção do churn.
### Tags
* Oque são e pra que servem
Tags(do inglês “etiqueta”) são usadas para adicionar características personalizáveis a diferentes elementos do sistema. Elas podem ser adicionadas não apenas à contatos, como também à companies, listas, templates, web forms, automações e campanhas e ficam bem abaixo do nome de cada um destes elementos. Desta forma, você consegue criar um denominador comum que não existiria de outra forma.
>Dica: utilize as tags para organizar as suas campanhas, automações e templates. Nestes casos, a tag funciona como uma pasta de organização para te ajudar a agrupar itens que tenham características em comum dentro de um mesmo recurso. 
* Como criar e atribuir Tags
Você pode criar Tags de duas formas, as adicionando diretamente abaixo do nome do elemento ao qual você a deseja adicionar - clicando no campo ´Add Tag´ e adicionando o nome que desejar-  ou acessando o menu Settings, clicando em Apps e depois em Tags. Nesta página você visualiza todas as tags já criadas na sua conta; pode selecionar múltiplas tags- o que irá habilitar o botão de exclusão “Remove” no canto superior direito da página; pode filtrar as tags por Contexto ou buscar por nome; e pode também acessar cada Tag individualmente para editá-la. Para isso, clique no nome da Tag desejada e será redirecionado à página de edição, podendo editar o nome e escolher o contexto no qual ela se enquadra - company, case, campaign, contact, event, flow, list, tag, entre outros.
Para criar uma nova Tag, clique no botão ![Botão de adicionar](https://pipz.com/static/images/blog/add.png, nomeie a Tag e selecione o Contexto no qual ela se encaixa.
* Onde utilizar as tags
As tags podem ser adicionadas manualmente ou através de uma automação e são utilizadas para diferentes fins, sendo eles:
-identificar um elemento do sistema com alguma característica personalizável;
-filtrar a lista de contatos, a fim de só visualizar/interagir com os contatos que possuem determinada tag;
-efetuar o envio de campanhas de email marketing apenas para contatos com uma determinada tag;
-organizar as campanhas, templates, relatórios, automações- e todos os outros recursos que contenham tags- de maneira a facilitar a visualização e busca de elementos.
### Campaigns
![Campanhas](https://pipz.com/static/images/blog/campaigns.png)
* O que são e para que servem
Com o recurso de Campaign você poderá criar de suas campanhas de email marketing em modo texto ou direto no source code e criar layouts personalizáveis utilizando variáveis e manter os seus contatos atualizados sobre as novidades de sua empresa. 
* Como selecionar conta de envio e linha de assunto da campanha
Dentro de cada campanha você encontra a aba Settings, onde você poderá configurar a sua campanha. É aqui que você adiciona o assunto de sua campanha (Subject), define qual a conta de envio a ser utilizada (esta já tem de estar previamente criada para figurar na lista de opções) e decide se as respostas recebidas serão geridas no recurso Conversations do Pipz. 
![Como selecionar conta de envio e linha de assunto da campanha](https://pipz.com/static/images/blog/campaign-settings.png)
* Como adicionar o corpo da mensagem e versão plain-text
Na próxima aba, HTML, você tem acesso a caixa de edição da campanha. Aqui você poderá criar um novo layout ou adicionar um template pronto em imagem ou código HTML (acesse o source code clicando no ícone “<>” no menu superior da área de edição).
Para gerar a versão plain text, muito importante para a melhoria de entregabilidade de emails, vá para a aba Text e clique em “Copy text from HTML version” e depois em salvar. Pronto! Você já tem uma versão texto da sua campanha. Para adicionar o link de descadastramento, obrigatório no email marketing, adicione a variável {{unsubscribe}} diretamente no source code.
* Como adicionar/excluir contatos para receberem a campanha
Na aba recipients você irá adicionar todos os contatos que devem receber a sua campanha. Você pode selecionar quantas listas, tags ou segments desejar. É importante ressaltar que se você selecionar uma lista, uma tag e um segment, por exemplo, só irão receber esta campanha aqueles contatos que se encaixarem em todos os parâmetros selecionados.
* Como rastrear clicks e UTMs aos links da campanha[^4] 
[^4]:Veja mais informações sobre campanhas personalizadas com UTMs: https://support.google.com/analytics/answer/1033863?visit_id=1-636199356691585403-2328798487&rd=1
Há um total de cinco parâmetros que você pode adicionar aos seus URLs: 
-utm_source: identifique o anunciante, o site, a publicação etc. que está enviando tráfego para sua propriedade (por exemplo: google, facebook, quora, reddit, twitter…)
-utm_medium: a mídia de publicidade ou marketing (por exemplo: cpc, banner, email newsletter).
-utm_campaign: o nome da campanha individual, o slogan, o código promocional etc. de um produto.
-utm_term: identifique palavras-chave de pesquisa paga. Se você estiver codificando manualmente campanhas de palavras-chave pagas, também deverá usar o parâmetro utm_term para especificar a palavra-chave.
-utm_content: usado para diferenciar conteúdo semelhante ou links dentro do mesmo anúncio. Por exemplo, se tiver dois links de call to action na mesma mensagem de e-mail, você poderá usar utm_content e definir valores diferentes para cada um. Assim, saberá qual versão é a mais eficiente.
>Ex.: defina o parâmetro utm_source como newsletter para identificar o tráfego proveniente de boletins informativos. Em seguida, combine-o com o parâmetro utm_campaign definido como june para identificar que essa foi a campanha do mês de junho.
Os parâmetros utm_source, utm_medium e utm_campaign são obrigatórios, os demais são opcionais e podem ser usados para acompanhar informações adicionais:
* Como pré-visualizar, testar e enviar uma campanha
No header dentro de cada campanha você terá acesso a alguns ícones, sendo eles:
-Preview (ícone do olho): Você poderá visualizar a sua campanha a cada passo, antes mesmo de ela estar finalizada. É importante sempre clicar no botão  ![Botão de Salvar](https://pipz.com/static/images/blog/save.png) para não correr o risco de perder edições feitas a campanha.
Duplicate: a sua campanha e todas as suas configurações serão duplicadas.
Test Campaign: você pode adicionar contatos que você queira que recebam um teste de sua campanha. Esta função ajuda muito na aprovação de campanhas de email marketing, se tal aprovação não depender só de você.
* Quais são os status de uma campanha
-Editing: você ainda está trabalhando na edição desta campanha. É o único status que permite a deleção da campanha;
-Waiting for approval: este status aparece se outra pessoa for a responsável pela aprovação da campanha antes da liberação do envio;
-Reproved: a pessoa responsável não aprovou a campanha;
-Moderation: você enviou a campanha e ela chegou no processo de moderação da nossa equipe. Em poucos minutos ela será liberada para envio;
-Released: a campanha foi liberada para o envio. Este status pode permanecer por um tempo se o envio da campanha estiver agendado;
-Creating queue to send: é chegado o momento do envio e os contatos já estão alinhados na fila de envio;
-Limit Exceeded: o seu limite de envios foi excedido. Ex: seu saldo de envios é de 5mil mas a sua lista de inclusão para o envio tem 7500 contatos. Este será o status neste caso;
-No contacts to send: a lista de contatos ou a segmentação selecionadas para o envio estão vazias;
-Sending: o envio já foi iniciado e seus contatos começam a receber a sua campanha;
-Paused: o envio da campanha foi pausado e poderá ser liberado para o envio posteriormente;
-Canceled: o envio da campanha foi cancelado manualmente por alguém com acesso à campanha. Pode ser alguém do nosso time, por apresentar alguma irregularidade,  ou alguém da sua empresa. 
-Interrupted: o seu envio foi interrompido para proteger o seu domínio e sua entregabilidade. Isso acontece por duas razões principais: Quantidade muito alta de hard bounces (contatos inválidos) e/ou denúncias de abuso/SPAM por parte de seus contatos;
-Finished: o envio de sua campanha foi finalizado.
 ### Conversations
![Conversations - Chat](https://pipz.com/static/images/blog/conversations.png)
* O que é e para que serve
Este é o recurso onde as conversas oriundas do chat, respostas de In app messages e In app mails se concentram. Aqui também podem ser geridas as respostas de emails enviados pela automação ou das campanhas de email marketing(desde que seja configurado em cada step).
No conversations todas conversas com os contatos ficam acessíveis a todos os usuários da sua equipe, facilitando o compartilhamento de dados entre vocês. Além de responder aos contatos, você pode adicionar uma nota que fica em destaque com a cor amarela, o que te ajuda a fazer observações que facilitem a sua compreensão ou a de outros team members ao acessar esta conversa posteriormente.
* Como habilitar o chat no Tracker
Dentro do painel do tracker, que está monitorando a(s) páginas(s) onde você quer que o chat apareça, você pode habilitá-lo na aba Options, marcando a checkbox da opção “Enable chat”, tanto com tracker de Lead quanto de Customer. Vale relembrar que para que o chat num tracker de Leads seja habilitado, é necessário que o lead esteja identificado com no mínimo Nome e Email.
A opção de Enable secure connections ajuda a manter as conversas entre a sua equipe e seus contatos privadas e a prevenir que um contato se passe por outro.
![Conversations tracker](https://pipz.com/static/images/blog/tracker-setup-chat.png)
![Configuração do conversation no tracker](https://pipz.com/static/images/blog/trackerchat-config.png )
* Status das mensagens
Dentro de conversations as suas conversas ficam organizadas dentro de cinco diferentes pastas:
-Open: conversas ativas ou que ainda não foram fechadas pelo usuário responsável;
-Closed: a conversa foi fechada por um usuário, mas pode voltar para a pasta open caso o contato volte a enviar uma mensagem através dela;
-Answered: este status é exclusivo para as conversas provenientes de In app emails. as conversas irão para a pasta
-Snoozing: nesta pasta ficam armazenadas as conversas aguardando resposta pelo período estipulado por você na opção de snoozing. Esta opção se encontra no ícone de relógio situado no canto superior direito da conversa. Ao clicar no ícone você terá algumas de tempo para escolher, entre 5 min e 24 horas.
-Deleted: aqui ficam as conversas deletadas. 
* Como visualizar o perfil do contato 
As informações do clientes serão exibidas ao clicar no ícone de perfil localizado no canto superior direito da conversa. As informações exibidas são: nome da empresa, email do usuário, primeira e última visualização.
![Como visualizar o perfil do contato](https://pipz.com/static/images/blog/conversations-profile.png)
