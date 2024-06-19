# Fotton Labs

Bem vindo ao Fotton Labs. O seu repositório de soluções para infraestrutura de TI.

Aqui você vai encontrar informações a respeito do desenho e construção de recursos de infraestrutura de TI baseado no que há de mais usual pelas maiores e mais destacadas empresas de diversos segmentos. 

Terá conhecimento das práticas e metodologias usadas e toda abordagem e conhecimento necessário para utilizar os mesmos templates e sugestões, alinhado às boas práticas de mercado e às normas vigentes sobre o uso de cada segmento e tecnologia.

No meu entendimento e experiência de anos atuando em empresas do setor financeiro e em consultorias globais parceiras de  AWS, Microsoft e Google, a melhor maneira de exemplificar suas capacidades é através da demonstração de suas habilidades de entregar aquilo que você está vendendo e/ou propondo a adoção.

Em TI, demonstrar significa, principalmente nos dias de hoje, em infraestrutura, provisionar todos os recursos tecnológicos que sustentam diversos tipos de aplicações, sob as mais diversas exigências em termos de disponibilidade, elasticidade e capacidade de suportar crescimentos e reduções sem interrupção e/ou degradação dos serviços de uma aplicação.

Enfim, todos sabemos que para o provisionamento de uma aplicação não somente são necessários os conhecimentos sobre as tecnologias, como também são, tão importantes ou até mais importantes, a maneira como se relacionam as tecnologias e como as diversas possibilidades e combinções se adequam melhor a umas situações ou outras.

Isso tudo, geralmente, é definido a partir dos requisitos da aplicação e de um grande conhecimento e experimentação pelo times de Arquitetura, que através de POCs(Proof of Concept) desenham e prototipam essas hipóteses para propor melhorias e/ou novas abordagens, que acabam se tornando padrões de construção pelas empresas e são replicadas entre os profissionais de TI pelo mundo.

Assim, o intuito desse repo é identificar e detalhar no máximo possível TODO o conhecimento inerente às diversas demandas de algumas das mais conhecidas funções e papéis dentro das verticais de infraestrutura e segurança de TI mais usuais e mais comumente adotadas, de modo a servidr como proposta de referência agnóstica para o uso de cases semelhantes ou idênticos.

Vale lembrar que, como apoio para definição dos perfis, estou seguindo um roteiro de conhecimento muito interessante, que conheço há muito tempo e uso como uma espécie de bíblia para o meu aperfeiçoamento pessoal, que o site roadmap.sh. Super recomendo.

Vamos ao que interessa, os cases. 

Boa leitura. Divirta-se!

-----------------------------------------------------------------------------------

Conforme comentado acima, vamos atravessar todos os cases, imaginando que estamos participando de todos os processos, desde o nascimento das workloads até seu provisionamento e produção/sustentação tanto em nuvem quanto para as situações em que tecnologias OnPremise foram mais adequadas e/ou limitadas a esse.
Sendo assim a estrutura proposta para o ciclo de vida de nossas aplicações conterá as seguintes fases:

## 1. Processos de Design

   ### 1.1 Mapeamento dos Pré Requisitos da Aplicação
   ### 1.2 Definição das tecnologias
   ### 1.3 Desenvolvimento da ADR (Architecture Decision Register)
   ### 1.4 Desenho do layout de infra
   ### 1.5 Desenho do Fluxo da Aplicação
   ### 1.6 Detalhamento do cenário
   ### 1.7 Desenvolvimento da Matriz RACI

## 2. Processos de Provisionamento
   
   ### 2.1 Recursos de Gerência e Plataforma
   #### 2.1.1 Fundação
   #### 2.1.2 Contas
   #### 2.1.3 Redes
   #### 2.1.4 Segurança
   ##### 2.1.4.1 ZTNA
   ##### 2.1.4.2 DSPM
   ##### 2.1.4.3 Confidencialidade
   ##### 2.1.4.4 Integridade
   ##### 2.1.4.5 Disponibilidade
   ##### 2.1.4.6 Autenticidade
   ##### 2.1.4.7 Responsabilidade
   ##### 2.1.4.8 Não repúdio
   
   #### 2.1.5 Observabilidade
<!-- Os princípios básicos de observabilidade de aplicações são essenciais para monitorar e compreender o comportamento de sistemas complexos em produção. Eles ajudam a identificar e resolver problemas rapidamente, garantindo a alta disponibilidade e performance dos sistemas. Aqui estão os princípios fundamentais:
-->
   ##### 2.1.5.1 Coleta de dados
   ###### 2.1.5.1.1 Logs
<!--
Logs: Captura de eventos discretos que ocorreram no sistema, incluindo mensagens de erro, avisos e informações de depuração.
-->   
   ###### 2.1.5.1.2 Métricas
<!--
Métricas: Dados quantitativos que medem o comportamento do sistema ao longo do tempo, como o uso de CPU, memória, tempo de resposta, taxa de erros, etc.
-->   
   ###### 2.1.5.1.3 Traces
<!--
Traces: Rastreamento de pedidos de ponta a ponta através do sistema, permitindo ver o caminho de uma solicitação e identificar gargalos ou falhas.
-->
   ##### 2.1.5.2 Correlação e Contexto
   ###### 2.1.5.2.1 Contexto de solicitação
<!--
Contexto de Solicitação: Informações adicionais que acompanham uma solicitação ao longo de sua trajetória, como IDs de rastreamento e metadados.
-->
   ###### 2.1.5.2.2 Mapeamento de dependências
<!--
Mapeamento de Dependências: Entendimento das dependências entre diferentes serviços e componentes para identificar rapidamente onde os problemas podem estar se originando.
-->
   ##### 2.1.5.3 Análise em tempo real
<!--
Ferramentas e sistemas que permitem a análise de dados de observabilidade em tempo real para detectar anomalias e responder rapidamente a incidentes.
-->
   ##### 2.1.5.4 Alertas e Notificações
<!--
Definição de regras de alerta baseadas em métricas e logs para notificar a equipe responsável imediatamente quando ocorrerem problemas.
Priorização de alertas para evitar sobrecarga de notificações e focar nos problemas mais críticos.
-->
   ##### 2.1.5.5 Visualização
<!--
Dashboards e outras ferramentas de visualização para apresentar dados de forma clara e acessível, facilitando a identificação de padrões e tendências.
-->
   ##### 2.1.5.6 Automação e integração
<!--
Integração com ferramentas de CI/CD para garantir que a observabilidade esteja presente em todas as fases do ciclo de vida de desenvolvimento de software.
Automação de respostas a certos tipos de incidentes para reduzir o tempo de resolução.
-->
   ##### 2.1.5.7 Retenção e análise histórica
<!--
Armazenamento de dados históricos para permitir análises retroativas e identificação de tendências a longo prazo.
-->
   ##### 2.1.5.8 Cultura de observabilidade
<!--
Fomentar uma cultura onde a observabilidade é uma responsabilidade compartilhada entre todas as equipes, incentivando práticas como o logging estruturado e a revisão contínua de métricas e logs.
-->
   ### 2.2 Ambiente de POC
      
   ### 2. Ambiente de DEV
   
   ### 3. Ambiente de HML
   
   ### 4. Ambiente de PRD

## 3. Processos de Validação e Testes

## 4. Processos de Deploy

## 5. Processos de Sustentação


-----------------------------------------------------------------------------------

Abaixo temos os links diretos para os cases já desenvolvidos no FottonLabs:

## 1. Cases

   ### 1. Case 1 - AppSaldo

         <img src="fottonlabs.png" alt="AppSaldo - Infra Layout" />
