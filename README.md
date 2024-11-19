# Projeto de Monitoramento de Tensão dos LEDs

## Descrição do Funcionamento
Este projeto utiliza uma ESP32 para monitorar a tensão dos LEDs através de um sensor de corrente ACS712. Os dados são enviados para a plataforma Adafruit IO via protocolo MQTT, permitindo monitoramento remoto e controle do relé.

## Uso
1. **Montagem do Hardware**: Conecte a ESP32 ao sensor ACS712, relé, e LEDs conforme o diagrama fornecido.
2. **Configuração do Software**: Faça o upload do código fornecido para a ESP32 usando o Arduino IDE.
3. **Monitoramento e Controle**: Use o dashboard do Adafruit IO para visualizar a tensão dos LEDs e controlar o relé remotamente.

## Requisitos
- ESP32
- Sensor ACS712
- Relé de 5V
- LEDs
- Protoboard e jumpers
- Conta no Adafruit IO

## Instruções de Instalação
1. Clone este repositório: `git clone https://github.com/seu-usuario/Projeto-Monitoramento-LED`
2. Abra o projeto no Arduino IDE.
3. Configure as credenciais Wi-Fi e as credenciais do Adafruit IO no arquivo `config.h`.
4. Faça o upload do código para a ESP32.

