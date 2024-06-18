# Fotton Labs

Bem vindo ao Fotton Labs. O seu repositório de soluções de infraestrutura de TI.

Aqui você vai encontrar informações a respeito do desenho e construção de recursos de infraestrutura de TI baseado no que há de mais usual pelas maiores e mais destacadas empresas de diversos segmentos. 

Terá conhecimento das práticas e metodologias usadas e toda abordagem e conhecimento necessário para utilizar os mesmos templates e sugestões, alinhado às boas práticas de mercado e às normas vigentes sobre o uso de cada segmento e tecnologia.

## 1. Cases
   ### 1. f_saldo

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
       ### 1. Fundação
          ### 1. AWS
             ### 1. Contas
             ### 2. Redes
             ### 3. Conectividade
          2. OnPrem
             1. Servidores
             2. Conectividade
        2. Recursos da aplicação
        3. Recursos de observabilidade
        4. Recursos de segurança
           1. ZTNA
           2. DSPM
              1. Confidencialidade
              2. Integridade
              3. Disponibilidade
              4. Autenticidade
              5. Responsabilidade
              6. Não Repúdio
        5. Deploy Aplicação
   
    7. Testes