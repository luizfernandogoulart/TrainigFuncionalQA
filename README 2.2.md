# Projeto de Conclusão de Curso - Desafio QA - Code Chalenge 



## Projeto Acelera ASAPLOG



Para entendimento inicial, o curso tem como objetivo capacitar colaboradores da **Via**, para atuação no departamento de **TI**.

​	Este white paper tem como objetivo informar a maior quantidade possível de informações segmentadas que foram utilizadas neste projeto.

* Foram utilizadas as boas práticas aprendidas e com padrões simplórios de aprendizado; 
* A Estrutura de pastas foi respeitada e o código foi versionado;  
* Em virtude da baixa expertise, o código foi desenvolvido de forma simples e sem complexidade técnica).



## 1 - Requisitos utilizados no Desenvolvimento do Projeto


 - #### **1.1 - Equipamento**

    - Notebook Dell - Core i5 2021 - com **16**GB RAM e **250**GB de Armazenamento


 - #### **1.2 - Software**

    - VSCode - https://code.visualstudio.com/ - versão 1.68.1

    - Node.js - https://nodejs.org/en/ - versão 16.13.2

    - Cypress - https://cypress.io/ - versão 10.3.0

    - Postman - https://www.postman.com/ - versão 9.21.0

    - Typora - https://typora.io/ - versão 1.3


 - #### **1.3 - Sites de Apoio e Teste**

     - Openweathermap - https://openweathermap.org/current/
     - GitHub - https://github.com/
     - Git - https://git-scm.com/


 - #### **1.4 - Linguagem de Programação**

     - JavaScript - https://www.javascript.com/


 - #### **1.5 - Conexão**

     - Via rede **Wifi** - prédio de TI - Hub São Caetano do Sul - Jul/22
     - Via rede **Wifi** - caseira - Jul/22   


 - #### **1.6 - Trilha Sonora**

     - Via Spotify - [Jazz & Soul instrumental](https://open.spotify.com/playlist/1AmDyRcMV7ebvwzmVjFoaL?si=37e9fbe34ce04cd2)   

- #### **1.7 - Combustível**

     - Café e Chá Mate



## 2 - Endereço do Repositório com Dados do teste



 - #### **2.1 - Links úteis**

    - Github Pessoal - https://github.com/luizfernandogoulart/Treinamento-Final-ASAP.git/
    - Github Desafio ASAP - https://github.com/qa-via-code-challenge/desafio-asaplog/



## 3 - Instrução para Instalação dos Softwares utilizados

​	Para este projeto, caso precise reproduzi-lo será necessário instalar **4** softwares adicionais: 



- #### **3.1 - Softwares úteis**

  - **NodeJS**, necessário para executar código JavaScript;

  - **Visual Studio Code** ou VSC (Editor que usamos para escrever código);

  - **Cypress** no qual processaremos o teste **e2e** (end to end);

  - **Postman** para teste de API.   

    

- #### **3.2 - NodeJS**

​		O **NodeJS** é software baseado no interpretador [V8](https://pt.wikipedia.org/wiki/Node.js) que permite a execução de códigos JavaScript.

​		**Via browser** - https://nodejs.org/en/

​		O site do NodeJS oferece duas opções para download, a LTS e a "current" (atual).

​		Neste projeto utilizamos a versão LTS (**Long Term Support**).

​		Caso precise de mais **instruções técnicas** veja mais detalhes na página do [NodeJS](https://nodejs.org/pt-br/download/package-manager/).    

   

- #### **3.3 - Visual Studio Code**

​		O **Visual Studio Code** é o editor utilizado neste projeto para edição do código dos testes.	

​		**Via browser** - https://code.visualstudio.com/

​		A instrução de instalação é bem simples, basta clicar no executável e seguir as instruções.     

 

- #### **3.4 - Cypress**

​		O **Cypress** é um framework para automação de testes end-to-end, que utiliza o **JavaScript** como linguagem de programação. 

​		**Via browser** - https://download.cypress.io/desktop/

​			A instrução de instalação é simples, clique no executável e siga as instruções.

​		**Via VSCode** - npm install cypress    



- #### **3.5 - Postman**

​		O **Postman** é uma plataforma de testes de API para projetar, **testar** e iterar APIs e suas nuances.

​		**Via browser** - https://dl.pstmn.io/download/latest/win64/

​			A instrução é simples, clique no executável e siga as instruções.	  





## 4 - Execução dos Testes

Para este projeto, os testes foram aplicados no principal site de vendas da Via. O site das [Casas Bahia](https://www.casasbahia.com.br/) foi utilizado no case de estudo para aplicação dos testes. Na segunda parte do projeto fora utilizado a **API** do site [Openweathermap](https://openweathermap.org/current) para teste de chamada de **dados de tempo**.

Em observação após o término dos testes, pode se notar uma maior expertise nos testes via **Cypress** devido ao **tempo aplicado** e a complexidade que os testes exigiram. O site proposto, se mostrou muito mais complexo de se testar do que outros varejistas testados a princípio. 

Conforme a expertise no **framework** de teste foi ganhando corpo, os **testes** em outros varejistas se mostraram mais fáceis de se concluir em menor tempo e complexidade. 

Foi observado na última semana de testes, que o site das **Casas Bahia** passou por algumas **reformulações** que forçaram o **teste completo** no "**carrinho de compras**" se refeito por 3 vezes devido a mudanças constantes no algoritmo do carrinho e na última parte do processo de vendas.

 Fato este que proporcionou **muito mais horas** de estudo e busca de soluções para a construção e término do teste.   



## 5 - Autor

**Luiz Fernando Goulart** em estudo e desenvolvimento há 10 meses a partir do curso de aprendizado na trilha de conhecimento conhecida como **QA**. 
O estudo deu-se inicialmente a partir da plataforma [Alura](https://www.alura.com.br/) e complementado com pesquisas suplementares em parte no **Youtube** e em livros físicos. 

Este autor é formado em Ciências Contábeis, entrou na Via em 2013 como **Supervisão de Operações Logísticas** , vindo do **RJ** e lotado hoje no departamento de **Planejamento Financeiro de Fretes** a nível Brasil, sendo responsável pelo **monitoramento** e controle de toda a despesa de **Frete de Entrega das Vendas Online**. Controle e monitoramento este que deriva **insight diários** que produzem economia real na operação logística.  

A expertise acumulada de certo tempo na via proporcionou algum conhecimento na construção de indicadores, utilizando-se as plataformas **SAS** e **PowerBi** como alavancas de produção de estudo estatísticos seja na **Operação Logística** e também na **Economia Real** dos nossos Negócios.

A busca pela equação que equilibre o operacional e a economia é a meca de todo analista, desta forma  acredito que eu possa fazer um grande trabalho migrando para novas as novas paragens dentro do **algoritmo** dessa grande escola chamada **Via**.  



## 6 - Colaborando

Contribuíram para este projeto com sua magnânima ajuda: 

* **Celso Tavares** - com paciência e instrução técnica;

* **Sílvio José** - instruções técnicas e tutoria

* **Renato Daniel** - instruções técnicas

* **Jaderson Pessoa** - instruções técnicas

* **Sabrina Ellis** - mentoria 

* **Vanessa de Souza** (*wife*) - mentoria, paciência e ternura

  

## 7 - Agradecimentos

Agradeço, a todos que puderam participar com qualquer ajuda. 

Seja na confecção, estudo e melhoria deste projeto.



## 

Esperamos poder seguir a diante >>
