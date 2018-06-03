# O Projeto

> A criação desse shield foi feita a partir necessidade de otimizar o processo de gravação do bootloader
nos microcontroladores para placas baseadas em Arduino (como, por exemplo, a [Franzininho](https://github.com/Franzininho)). 

## Descrição

Este shield foi projetado para a gravação de bootloader. Ele pode ser utilizado com placas compatíveis com a pinagem de um Arduino Uno.
Neste Arduino, deve conter o firmware para utilizá-lo como um gravador ISP, podendo assim, realizar a queima do bootloader nos novos microcontroladores que serão utilizados nas placadas desenvolvidas na oficina :) Veja mais sobre essas oficinas [aqui](http://www.oficinasculturais.org.br/). 

## Funcionalidades

Este shield foi projetado para a gravação de bootloader em alguns microcontroladores AVR da linha Atmel, por exemplo 
- Atmega 
  - 328/168
  - 88/48/8
- ATtiny
  - 25/45/85
 O bootloader deve ser escolhido de acordo com o microcontrolador compatível com a placa.
 |Microcontrolador   | Bootloader  | Placas Compatíveis |
|---|---|---|
 
 
 Por exemplo, deve se utilizar o bootloader do Arduino Uno para o microcontrolador Atmega 328/168. Já 

## 
