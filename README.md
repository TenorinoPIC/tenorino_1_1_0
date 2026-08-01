# Tenorino 1.1.0

Placa de estudo e testes baseada no microcontrolador **PIC18F4550** (clock 20 MHz).

## Sobre

O Tenorino é uma plataforma didática para aprendizado, prototipagem e experimentos com microcontroladores. Serve para exercitar programação embarcada, comunicação serial e uso de pinos de entrada/saída.

## Características

| Recurso | Descrição |
|---------|-----------|
| **MCU** | PIC18F4550 |
| **Clock** | 20 MHz |
| **Serial** | Interface serial para comunicação com PC ou outros dispositivos |
| **Pinos I/O** | Pinos de entrada/saída acessíveis para sensores, atuadores e circuitos externos |
| **Alimentação** | USB **ou** fonte externa **12 V** |

## Alimentação

A placa pode ser alimentada de duas formas:

- **USB** — conveniente para desenvolvimento e testes no computador
- **Fonte 12 V** — para uso autônomo ou quando a carga exige mais corrente

Não alimente pelas duas entradas ao mesmo tempo, salvo se o circuito da placa estiver preparado para isso.

## Uso típico

1. Conectar a alimentação (USB ou 12 V)
2. Usar a serial para debug, comandos ou troca de dados
3. Ligar sensores, LEDs, relés ou outros módulos nos pinos I/O

## Projeto de software

Este repositório contém o firmware de exemplo em **mikroC PRO for PIC**:

- `Tenorino001.c` — código principal
- `Tenorino001.mcppi` — projeto mikroC
- `Tenorino001.cfg` — configuração do dispositivo (PIC18F4550)
