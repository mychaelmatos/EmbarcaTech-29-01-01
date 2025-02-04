# Projeto TAREFA 1 - Atividade 29/01

Este projeto é uma tarefa da residência do CEPEDI de Sistemas Embarcados. Ele demonstra como controlar LEDs usando a Raspberry Pi Pico. O código faz com que três LEDs (vermelho, amarelo e verde) alternem seu estado simulando um semáforo. O projeto utiliza a placa Raspberry Pi Pico e o simulador Wokwi para testar a funcionalidade durante o desenvolvimento.

## Descrição

O projeto utiliza um microcontrolador para controlar LEDs que simulam um semáforo. Os LEDs alternam entre vermelho, amarelo e verde em intervalos de 3 segundos.

## Estrutura do Projeto

- `blink.c`: Contém a lógica principal para controlar o display de LEDs.
- `diagram.json`: Arquivo JSON usado para visualizar os testes com as funcionalidades do Wokwi.
- `CMakeLists.txt`: Arquivo de configuração do CMake para compilar o projeto.

## Funcionalidades

- Alternar três LEDs (vermelho, amarelo e verde) simulando um semáforo.
- Alternar o estado dos LEDs a cada 3 segundos.

## Como usar o projeto

1. Clone o repositório.
2. Importe o projeto com a extensão Raspberry Pi Pico.
3. Coloque a placa Raspberry Pi Pico no modo BOOTSEL, compile e rode o arquivo blink.c.
4. Acesse o arquivo "diagram.json" e abrirá uma tela onde será simulado a placa e os LEDs.  

## Requisitos

- Placa BitDogLab
- Computador Pessoal

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).

---

Residência do CEPEDI de Sistemas Embarcados, Embarcatech.
