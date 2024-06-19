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