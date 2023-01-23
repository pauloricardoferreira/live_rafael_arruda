QUem sou eu?

Nome: Paulo Ricardo Ferreira
Idade: 34 Anos

Trabalho na empresa Agroterenas a 7 anos, passando por diversas áreas na empresa.

Breve História
No inicio, trabalhei basicamente Excel para a criação de relatórios, e conforme sugiam problemas afui atráz de conheicmento para solucionar.

Em 2018, com a mudança de setor na empresa, inicio minha caminha com os Dados.
De forma bem simples, extraia os dados atravéz de SQL diretamente do Sistema que posteriormente foi automatizada.
E no deccorrer foi permitido o acesso a base de dados do sistema para fazer automações.
Não contente com a forma que era feito, busquei por outras soluções e me deparei com o Pentaho.
Como era algo novo, me causou estranhei na utilização, os menus pareciam complicados, termos em inglês, parametros para configurar. Levou um tempo até sair o primeira Transform.
Busquei por muito tempo conteúdo avuldo na internet para solucionar problemas específicos, e o projeto foi ganhando maturidade. Comecei a criar Jobs que chamavam as Transforms, incluí diversas automações com variáveis como Caminho de Arquivos, usuários e senhas de acesso, etc

Executava tudo na minha máquina local, com um postgres instalado.
Más isso mudou quando foi disponibilizado um usuário com diretos de gerneciar tabelas no banco de dados.
Onde pude migrar bases em excel, para esse banco, e também saindo do pentaho local para uma VM no servidor da empresa.

Acreditem, usei por um bom tempo o agendados do Linux para iniciar os Jobs do Pentaho até conhecer o Apache Airflow em um treinamento que fiz.
De imediato consegui elimitar o agendados do Linux para o Airflow, com uma receita de bolo que deixei automatizada no Pentaho.

Usei Pentaho de 2019 até out/2022 quando migrei para o Hop



Fiz o curso da Pentaho para aprimorar os conhecimentos





Iniciei com coleta de dados via sistemas em 2018, e conforme a necessidade procurei formas de melhorar a extração de dados do Sistema, e na procura por ferramente encontrei o Pentaho.
Comecei de forma simples, e fui evoluindo aos poucos.
Usei Pentaho de 2019 até out/2022 quando migrei para o Hop.


Conheci o apache hop atravez através do Ricardo Gouvea da Openin, onde postou sobre uma nova plataforma de ETL. o Hop


Apache Hop - Orquestrador de Pipeline
Hop nasceu como um fork do Pentaho 8.3 do próprio criador Matt Casters.
Sendo incubado dentro da Apache Foundation
Hoje é um projeto top level Apache, maduro e em pleno desenvolvimento.
Sendo distribuiído para ser instalado localmente atrávez de um arquivo zip, ou por imagem Docker


Airflow ->  projeto do Apache Airflow se iniciou como um piloto dentro do Airbnb, em 2015, e desde então vem sendo adotado pelas maiores empresas do mundo todo, se tornando hoje a principal referência em ferramentas de orquestração no universo de dados. No final de 2020, a versão 2.0 foi oficialmente lançada, mostrando a maturidade do projeto e contínua evolução com apoio da comunidade, incluindo diversas melhorias tanto na experiência do usuário (melhorias na UI, Task Flow API, etc.), quanto em segurança e infraestrutura.


Técnologias para Estudo
Linux -> ao usar linux, a pessoa está no mesmo ambiente no qual as técniclogias são desenvolvidas e distribuiídas atualmente
Docker -> Docker é uma técnologia que permite criar aplicações e colocar em uma espécia de Caixa, isalada do sistema princpal, pense que esse isolamnte é como um container que é transportado por um navio cargueiro. O navio é a nossa máxima com o Docker Instalado que carreda desenas de container, o conatinaer é a aplicação em si, onde dentro do container contem tudo que nossa aplicação precisa para ser executada.
com o Docker, é possivel subir um banco de dados em minutos, sem a necessidade de instaçar e configurar nada na máquina local



Participantes da Live já tem conhecimento do Pentaho.


Canais Hop
Openin
https://www.youtube.com/@ApacheHop -> Canal Oficial
https://www.youtube.com/watch?v=BCcF9eAsrWQ -> instalação
https://www.youtube.com/watch?v=NGD6PGr8Id4 -> primeiros passos
https://www.youtube.com/watch?v=Cp8hxnh_Eog -> Migração do Pentaho para o Hop

https://www.youtube.com/watch?v=4DGRqMoyrPk -> O que é o Airflow
https://www.youtube.com/@MarcLamberti -> Grande divuldador do Airflow

https://www.youtube.com/watch?v=Wm99C_f7Kxw&list=PLf-O3X2-mxDn1VpyU2q3fuI6YYeIWp5rR -> Linuxtips Docker
