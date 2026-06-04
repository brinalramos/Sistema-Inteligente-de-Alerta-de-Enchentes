# Sistema-Inteligente-de-Alerta-de-Enchentes
OBJETOS INTELIGENTES CONECTADOS - Análise e Desenvolvimento de Sistemas - 2026

# Vídeo-Demonstração:
[https://youtu.be/wDp0C1E_Tf4 ](https://youtu.be/ZjQtY4Zxtc0 )
* No vídeo são apresentados o funcionamento do protótipo, a lógica implementada no software, a comunicação via protocolo MQTT e os resultados obtidos durante os testes realizados.

# Codigo fonte esta no arquivo anexado: Firmware.zip

# Sistema Inteligente de Alerta de Enchentes

Este projeto foi desenvolvido para a disciplina de Objetos Inteligentes Conectados e tem como objetivo monitorar o nível da água em áreas com risco de enchentes utilizando conceitos de Internet das Coisas (IoT).

A solução utiliza um microcontrolador NodeMCU (ESP8266), um sensor ultrassônico HC-SR04 para medir a distância até a superfície da água e atuadores (LED e buzzer) para emissão de alertas locais. Além disso, os dados coletados são enviados por meio do protocolo MQTT para um broker Eclipse Mosquitto, permitindo o monitoramento remoto em tempo real.

## Funcionamento

O sensor HC-SR04 realiza medições contínuas da distância até a superfície da água. Essas informações são processadas pelo NodeMCU, que classifica a situação em três níveis:

* **Normal:** monitoramento sem alertas.
* **Atenção:** acionamento do LED para alerta visual.
* **Crítico:** acionamento do LED e do buzzer para alerta visual e sonoro.

Os dados também são publicados em tópicos MQTT para acompanhamento remoto.

## Hardware Utilizado

* NodeMCU ESP8266
* Sensor Ultrassônico HC-SR04
* LED
* Buzzer

## Tecnologias Utilizadas

* Arduino IDE
* MQTT
* Eclipse Mosquitto
* Circuito.io
* Lucidchart
* GitHub

## Estrutura do Repositório

* Código-fonte do projeto
* Documentação do hardware
* Diagramas e fluxogramas
* Arquitetura MQTT
* Artigo acadêmico
* Materiais de apoio

## Objetivo

Contribuir para a prevenção de enchentes por meio do monitoramento do nível da água e da emissão de alertas em tempo real, utilizando uma solução simples, acessível e baseada em IoT.
