# Fotton Labs

Bem vindo ao Fotton Labs. O seu repositório de soluções de infraestrutura de TI.

Aqui você vai encontrar informações a respeito do desenho e construção de recursos de infraestrutura de TI baseado no que há de mais usual pelas maiores e mais destacadas empresas de diversos segmentos. 

Terá conhecimento das práticas e metodologias usadas e toda abordagem e conhecimento necessário para utilizar os mesmos templates e sugestões, alinhado às boas práticas de mercado e às normas vigentes sobre o uso de cada segmento e tecnologia.

## 1. Cases
   ### 1. AppSaldo

        Esse cenário foi projetado para suportar em nível de missão crítica uma aplicação que coleta o saldo online da conta de um usuário a partir de um sistema web.
        Essa aplicação deve utilizar recursos de nuvem pública a fim de ser capaz de escalar e sustentar uma demanda esperada por volta de 100 requests por hora. 
        A aplicação deverá utilizar paradigmas modernos de desenvolvimento, infraestrutura e segurança.
        A aplicação consumirá informações que serão consolidadas a partir de servidores remotos OnPremise, cujo entregarão as informações de saldo consolidadas através um arquivo de aproximadamente 50GB.

   ### 2. Desenho
         <img src="fottonlabs.png" alt="AppSaldo - Infra Layout" />
   ### 3. Detalhamento do Desenho
   
   ### 4. Pré Requisitos da Aplicação
    
   ### 5. ADR
   
   ### 6. Procedimento de Construção
   
   #### 6.1. Fundação
   
   ##### 6.1.1. AWS
   
   ###### 6.1.1.1. Contas
   
   ###### 6.1.2. Redes
   
   ###### 6.1.3. Conectividade
   
   #### 6.2. OnPrem
   
   ##### 6.2.1. Servidores
   
   ##### 6.2.2. Conectividade
   
   #### 6.3. Recursos de observabilidade
   
   #### 6.4. Recursos de segurança
   
   ##### 6.4.1. ZTNA
   
   ##### 6.4.2. DSPM
   
   ###### 6.4.2.1. Confidencialidade
   
   ###### 6.4.2.2. Integridade
   
   ###### 6.4.2.3. Disponibilidade
   
   ###### 6.4.2.4. Autenticidade
   
   ###### 6.4.2.5. Responsabilidade
   
   ###### 6.4.2.6. Não Repúdio

   #### 6.5. Deploy Aplicação
   
   ### 7. Testes