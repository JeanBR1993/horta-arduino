# horta-arduino PT-BR

Esse algoritmo foi feito para controlar o sistema de irrigação de uma horta pequena urbana.

Ele faz a leitura de dois sensores de umidade capacitivos conectados às portas analógicas 0 e 1 do Arduíno e colocados em diferentes locais da horta em terra.

Após somar as leituras dos sensores o algoritmo faz a média, se a média for maior que "600" é porque o solo está relativamente seco e é dado o comando de abertura de uma válvula senoidal que esteja ligada a uma torneira sempre aberta e ao sistema de irrigação desenhado.

A variável 'aberto' é o tempo em milissegundos o qual a válvula fica aberta e irrigando.

A variável 'proxleitura' é o tempo em milissegundo o qual o algoritmo pausa para novas leituras dos sensores de umidade.


Nos parâmetros fixados no código o Arduíno fará a leitura duas vezes por dia e caso a terra esteja seca a irrigação ocorrerá por dois minutos.
Faça mudança nas variáveis a depender do tipo clima e tamanho da horta.

# arduino-garden US-EN

This algorithm has been made to control an irrigation system of an urban small garden. It reads two humidity capacitive sensors connected to analog Arduino ports and placed on different spots in the soil. 

After summing the sensors readings the algorithm calculates the average and if it's above '600' it's because the soil is somewhat dry, then open the valve which is attached to a tap and to the irrigation system. 

The variable 'aberto' is the time in miliseconds in which the valve stays open and irrigating. The variable 'proxleitura' is the time in milisecons which the algorithm pauses for humidity sensors new readings.


On the fixed parameters coded the arduino will make readings twice a day and irrigate for two minutes if the soil is dry enough.
It's best to make changes on the variables depending on type of weather and garden size.
