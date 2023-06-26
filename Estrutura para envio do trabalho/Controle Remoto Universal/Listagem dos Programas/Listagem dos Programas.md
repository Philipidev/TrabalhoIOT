# Projeto IoT com ESP32, Python e Flutter

Este projeto apresenta uma solução integrada para a interação com dispositivos IoT através de um aplicativo móvel. Ele utiliza uma variedade de ferramentas e linguagens de programação para proporcionar uma experiência de controle de dispositivos inteligentes.

## Ferramentas e Tecnologias Utilizadas:

**1. Arduino IDE:** 
Utilizamos o Arduino IDE para criar o código que é executado no ESP32. A IDE Arduino fornece um ambiente de desenvolvimento integrado que facilita a escrita, compilação e upload de códigos para placas compatíveis com Arduino, incluindo o ESP32. O código desenvolvido para o ESP32 é responsável por ler os tópicos MQTT publicados pelo aplicativo e executar ações correspondentes aos comandos do usuário.

**2. Visual Studio Code (VS Code):**
O Visual Studio Code foi a ferramenta escolhida para desenvolver o script Python deste projeto. O VS Code é um editor de código-fonte leve, mas poderoso, que suporta várias linguagens de programação. O script Python gerencia a leitura de tópicos MQTT publicados pelo aplicativo Flutter e armazena essas informações em um banco de dados MySQL para registro e análise futura.

**3. Android Studio:**
O Android Studio foi utilizado para desenvolver o aplicativo móvel em Flutter. Este aplicativo atua como um controle remoto universal, permitindo ao usuário enviar comandos a uma variedade de dispositivos IoT por meio de uma interface de usuário intuitiva. O Flutter é um framework de UI criado pelo Google, que permite a criação de belas aplicações compiladas nativamente a partir de uma única base de código.

**4. MySQL e MySQL Workbench:**
Usamos MySQL como sistema de gerenciamento de banco de dados para armazenar informações sobre os comandos emitidos pelo usuário através do aplicativo Flutter. O MySQL é um sistema de banco de dados relacional de código aberto, amplamente utilizado para aplicativos baseados na web. Para facilitar o gerenciamento, a visualização e a manipulação do banco de dados MySQL, também utilizamos o MySQL Workbench, uma ferramenta visual unificada para arquitetos de banco de dados, desenvolvedores e DBAs.

**5. MQTT (Message Queuing Telemetry Transport):**
MQTT é um protocolo de mensagens leve que foi usado para enviar comandos do aplicativo Flutter para o ESP32 via broker. Ele é útil para conexões remotas onde uma pequena pegada de código é necessária e/ou a largura de banda da rede é limitada.