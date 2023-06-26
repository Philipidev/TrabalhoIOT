# Descrição do Projeto em Metodologia Ágil Scrum

O Scrum é uma estrutura que permite ao time trabalhar juntos em projetos complexos, promovendo a divisão do projeto em pequenos pedaços chamados de "Sprints". Seguimos esta abordagem para o desenvolvimento do nosso projeto IoT com ESP32, Python e Flutter. Aqui está a descrição do nosso projeto, seguindo a estrutura do Scrum:

## Product Backlog
O product backlog inicial consistiu em um controle universal que pudesse manipular múltiplos dispositivos IoT através de um único aplicativo móvel. Especificamente, queríamos ser capazes de ligar/desligar switches, manipular LED RGB e definir a potência de um aparelho.

## Sprints
Nosso projeto foi dividido em várias sprints, que se concentraram nas seguintes áreas:

1. **Sprint 1 - Configuração do ambiente de desenvolvimento:** Esta sprint envolveu a configuração das ferramentas necessárias para o projeto, incluindo Arduino IDE, Visual Studio Code, Android Studio e MySQL Workbench.

2. **Sprint 2 - Desenvolvimento do aplicativo Flutter:** O aplicativo foi desenvolvido para permitir aos usuários interagir com os dispositivos IoT. Os usuários podem publicar tópicos de controle com base em suas entradas.

3. **Sprint 3 - Desenvolvimento do código Python:** Este sprint focou no desenvolvimento do código Python que lê os tópicos publicados pelo aplicativo e os armazena em um banco de dados MySQL.

4. **Sprint 4 - Configuração do ESP32:** Na última sprint, o ESP32 foi programado para ler os tópicos publicados pelo aplicativo. Com base nessas informações, o ESP32 executa ações como ligar/desligar switches, manipular o LED RGB e ajustar a potência de um dispositivo.

## Revisões e Retrospectivas
Após cada sprint, o time se reuniu para uma revisão e retrospectiva. Na revisão, demonstramos o trabalho concluído na sprint para receber feedback e fazer ajustes conforme necessário. Na retrospectiva, discutimos o que funcionou bem e o que poderia ser melhorado para as próximas sprints.

## Incremento de Produto
Ao final de cada sprint, tínhamos um incremento de produto funcional. Ao final do projeto, conseguimos desenvolver um aplicativo móvel que permite aos usuários controlar vários dispositivos IoT, utilizando um código Python que armazena as entradas do usuário em um banco de dados MySQL, e um ESP32 que executa ações com base nessas entradas.

## Product Owner e Scrum Master
No nosso projeto, o Product Owner foi Gabriel Volpini Nagem, que era responsável por definir as histórias de usuário e priorizar o backlog do produto. O Scrum Master foi Philipi Gariglio Carvalho Faustino Altoé, que ajudou a facilitar o processo do Scrum, removendo obstáculos e ajudando o time a se manter focado nos objetivos da sprint. 

Ao seguir a metodologia ágil Scrum, conseguimos desenvolver o projeto de forma eficiente, mantendo um alto nível de qualidade e atendendo às necessidades dos usuários.