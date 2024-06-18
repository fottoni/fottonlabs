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

## 1. Cases

   ### 1. Case 1 - AppSaldo

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