# contador-de-acessos

Software utilizado:
* Arduino Cloud
  
Para executar este projeto é necessário criar uma conta no site: https://login.arduino.cc
Após realizar o cadastro é necessário criar um "Things", onde você criará duas variaveis:
 * bool builtInLED
 * int ocupacao
O sistema irá gerar um "Sketch" (código) automaticamente com as variáveis declaradas.
Será preciso configurar a lógica para enviar ao arduino que será adicionado ao arduino cloud via cabo usb.
Para adicionar o arduino é solicitado que você baixe em seu computador o Agent arduino.
Após baixar o agente, basta configurar o Wifi na aba "things" na parte do setup, na parte sketch, selecionar o arduino e clicar em "->" (verify and upload).
Isso fará com que suas configurações sejam enviadas para o arduino.
Para monitorar o funcionamento é necessário criar um "dashboards".
No projeto foi utilizado os seguintes widgets:
 * Switch, com o link da variavel BuiltInLED.
 * Slider, com o link da variavel ocupacao.

Na parte de hardware será necessario adquirir:
 * Arduino nano 33 IoT
   O Arduino Nano 33 IoT é a menor placa do Arduino para começar a usar a Internet das Coisas (IoT). Usando o popular processador Arm® Cortex®-M0 SAMD21 de 32 bits, ele também possui o poderoso módulo Wi-Fi u-blox NINA-W102 e o chip criptográfico ECC608A para segurança.
O microcontrolador no Arduino Nano 33 IoT funciona a 3,3 V, o que significa que você nunca deve aplicar mais de 3,3 V aos seus pinos digitais e analógicos.

 * Conversor de nivel lógico Bidireccional  5V - 3,3V
   O conversor fará com que o Arduino Nano 33 Iot que funciona 3,3 V se comunique pelo protoboard com os sensores de proximidade funcionando em 5V.
Este módulo pode ser usado para realizar a interligação entre o canal I2C, SPI, Serial RS232 e outros entre o microcontrolador e outros módulos como bluetooth, módulo ethernet e etc, quando um dos dispositivos for 3,3V e o outro 5V.

 * Duas placas Protoboards
   Permitirá uma maior área de trabalho, organização, e possibilitará a gamificação e inserção de diversos sensores e conexões no projeto.
   
 * Sensor de proximidade infravermelho
   Este sensor de proximidade infravermelho é um módulo de reflexão fotoelétrica que integra um emissor IR e um receptor IR, no mesmo corpo.
   O Sensor captara o movimento de entrada e saída e como o sensor funciona a 5V será necessário um conversor, pois o Arduino utilizado no projeto utiliza 3,3V. 
   
 * Jumpers
   Conjunto de fios condutores utilizados para conectar extremidades distintas do circuito do projeto.
   


