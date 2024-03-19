# IoT_Project
Desenvolvimento de um projeto para a disciplina IoT

# Objetivos
Desenvolver um sistema para uma casa inteligente automatizada e conectada visando proporcionar conforto e segurança aos moradores desta residência.

# Funcionalidades
Automatizar a abertura e o fechamento de um portão de garagem que, através de sensores, emitirá para uma plataforma móvel o estado em que se encontra o portão para que seja tomada a decisão pelo usuário de abrir, fechar ou deixar o portão no estado em que se encontra. Ainda sendo possível detectar quem o acionou.

# Lista de Dispositivos IoT
Sensor de abertura de porta;
Atuador de contato seco;
Sensor de movimento;
Esp32;

# Arquitetura do Sistema
Camada de Dispositivos: Sensores e atuadores coletam e controlam o ambiente físico.
Camada de Rede: Dispositivos IoT se conectam à rede Wi-Fi.
Camada de Intergração: Hub central processa dados e envia comandos aos dispositivos.
Camada de Aplicação: Aplicativo de controle permite ao usuário interagir com o sistema.

