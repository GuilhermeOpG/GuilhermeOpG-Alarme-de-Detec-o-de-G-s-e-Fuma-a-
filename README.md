# Alarme Inteligente de Gás e Fumaça com ESP8266 e MQTT

Este projeto apresenta um sistema de detecção de gases inflamáveis e fumaça utilizando o sensor MQ-2, o microcontrolador ESP8266, e comunicação via protocolo MQTT. O sistema inclui notificações remotas em tempo real através do aplicativo Adafruit IO, além de alertas sonoros locais.

## Funcionalidades
- **Monitoramento de Gás**: Detecta metano, butano, GLP e fumaça.
- **Notificações em Tempo Real**: Envia alertas ao aplicativo móvel via MQTT.
- **Alerta Sonoro Local**: Aciona um buzzer e LED quando níveis críticos são detectados.

## Componentes Utilizados
- **Hardware**:
  - Sensor MQ-2
  - Placa ESP8266 NodeMCU
  - Protoboard e Jumpers
  - Buzzer Ativo 5V
- **Software**:
  - IDE Arduino
  - Plataforma Adafruit IO para monitoramento MQTT
  - Bibliotecas: `ESP8266WiFi.h`, `Adafruit_MQTT.h`, `Adafruit_MQTT_Client.h`


## Como Reproduzir
1. Monte o hardware conforme o diagrama.
2. Carregue o código na ESP8266 usando a IDE Arduino.
3. Configure o MQTT com o Adafruit IO.
4. Monitore os alertas no aplicativo.

## Resultados e Testes
O sistema foi testado para garantir estabilidade da conexão Wi-Fi, sensibilidade do sensor e envio de notificações em tempo real. 

---
Desenvolvido por Luiz G.

