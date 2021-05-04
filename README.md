# **🦠 Coronavírus APP**

### 1. História

Baseado na pandemia, o governo brasileiro decidiu disponibilizar um aplicativo que possibilitaria  a população acompanhar a evolução do coronavírus no país e em países vizinhos.

Para facilitar o uso, a equipe do ministério da ciência e tecnologia solicitou para que o projeto pudesse resolver os seguintes objetivos:

### 2. Objetivos

**Objetivo 1) Tela inicial**

- Na tela inicial/apresentação do app, apresentar a quantidade de novos casos confirmados, novas mortes, casos ativos e novos casos recuperados do dia anterior no Brasil;
- Baseado na comparação do período mensal anterior, a cor de UI do app deve mudar de acordo com a gravidade da situação. Por exemplo, se o dia atual houveram mais mortes que o anterior a UI deve apresentar uma cor diferente para que o cidadão possa analisar a gravidade da situação baseado na UX do app;

**Objetivo 2) Evolução em outros países**

Para a tela de acompanhamento da evolução do coronavírus em outros países:

- Realizar busca por um país na listagem inicial onde os países são apresentados;
- Realizar a listagem de todos os países, em ordem alfabética para que ao usuário selecionar, apresentar uma tela com:
    - Seção da tela onde destaca a quantidade de novos casos confirmados, novas mortes. e novos casos recuperados do dia anterior;
    - Baseado na comparação do período anterior, a cor de UI do app deve mudar de acordo com a gravidade da situação. Por exemplo, se o dia atual houveram mais mortes que o anterior a UI deve apresentar uma cor diferente para que o cidadão possa analisar a gravidade da situação baseado na UX do app;
    - Seção da tela com a listagem de novos casos conformados e mortes. Cada item da listagem deve ter uma comparação "percentual" da diferença em relação ao dia anterior. Para o componente com o "percentual" apresentar diferenciação de cor quanto o aumento ou diminuição de novos casos;

**Objetivo 3) Definir outro país como padrão**

Para permitir que cidadão naturalizados possam acompanhar facilmente a evolução do Coronavírus do país de origem:

- Permitir com que o usuário possa definir outro país como padrão do app: Ao realizar esta escolha, a tela inicial do app apresentará as informações do país escolhido;
- Para países diferentes do Brasil, o idioma do app deverá ser alterado para en-US (inglês)

**2.1) Objetivos que serão considerados como "Plus"**

Para incrementar a qualidade do projeto, alguns dos itens abaixo podem ser implementados caso você considere interessante/necessário.

- Sugestão 1: Gráfico para acompanhar a evolução de casos para cada tela vinculada a um país;
- Sugestão 2: Compartilhar com redes sociais um screenshot da seção que apresenta os dados gerais diários do país;
- Sugestão 3: Integração de um feed de notícias (a sua escolha) relacionadas ao coronavírus;
- Outra implementação que acredita que possa trazer valor a população que irá utilizar o projeto;

### 3. O que será analisado

Após a submissão do app, analisaremos:

1. Qualidade, organização e reuso do código;
2. Estrutura arquitetural do projeto;
3. Uso do Git e organização de commits enviados;
4. Criatividade e resolução de problemas de UI/UX;
5. Recursos para melhorar a perfomance da aplicação: paginação em listagens, lazy loading, controle de estado reativo e outros recursos que melhorem a usabilidade e perfomance;

### 4. Prazo de entrega de entrega proposto

1 semana após a aprovação da realização do teste.

### 5. Recurso a ser utilizado

- Covide19api ([https://covid19api.com/](https://covid19api.com/)) - [Documentação](https://documenter.getpostman.com/view/10808728/SzS8rjbc)
- O App deverá utilizar Flutter/Dart

### 6. Sugestão de ferramentas para organização do projeto

- GitFlow: https://github.com/nvie/gitflow
- Convetional Commit: https://www.conventionalcommits.org/en/v1.0.0/

### 7. Sobre entrega do projeto
- Realizar a hospedagem do repositório no Github e enviar acesso, dentro do prazo, aberto ao email: jorge@trakto.io
- Realizar fork deste repositório e utiliza-lo ao seu projeto;
