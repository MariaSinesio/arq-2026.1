# Projeto de Arquitetura de Computadores - Mega 2560

## Sobre o Projeto
Este projeto implementa um interpretador de instruções baseado na arquitetura de Von Neumann, utilizando um Arduino Mega 2560 e outros materiais. O sistema é capaz de receber comandos via teclado matricial, decodificar e executá-los, interagindo com periféricos conforme o ensinado (E/S), por exemplo, sensores de distância, LEDs, buzzer e display de 7 segmentos.

## Operação
O sistema possui dois estados isolados de funcionamento:
1.  **Modo LOAD:** Permite a inserção de instruções mnemônicas via teclado matricial, convertendo-as para opcodes e armazenando-as sequencialmente na memória.
2.  **Modo EXECUTE:** Inicia o ciclo de máquina contínuo, buscando os opcodes na memória, decodificando e acionando a ULA e as portas de I/O.

## Hardware
- **Placa:** Arduino Mega 2560
- **Entrada:** Teclado Matricial 4x4, Sensor de Distância (Ultrassônico)
- **Saída:** Display de 7 Segmentos, LEDs indicadores, Buzzer, Serial Monitor

## Como Executar
1. Clone o repositório
2. Monte o circuito conforme o diagrama, desenho.
3. Faça o upload do código `main.ino` para o Arduino Mega.
4. Abra o Serial Monitor
5. Se divirta!

## Tecnologias Utilizadas
* C (Linguagem)

## 👥 Equipe
- [MariaSinesio]
- [Henrique]

## LICENSE

[MIT](LICENSE)
