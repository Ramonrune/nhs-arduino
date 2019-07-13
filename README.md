# NHS Arduino

Leitor de NFC utilizando Arduino Mega e NFC PN532.

## Componentes
Arduino Mega<br>
Kit módulo leitor RFID NFC PN532<br>
Kit Jumpers Macho-Macho x65 unidades<br>
Protoboard 830 Pontos<br>
Buzzer ativo 5V<br>

![alt text](https://github.com/Ramonrune/nhs-arduino/blob/master/circuit.png)

A Figura apresenta o circuito utilizado. Pode-se notar a presença do Arduino Mega, do módulo PN532 e de um Buzzer. O módulo PN532 é utilizado para obter o código de identificação do equipamento de acesso, e no momento que isto ocorrer, o buzzer irá alertar o usuário através do som.

## Ligações entre o Arduino e o módulo PN532
Arduino	  PN532<br>
GND	      GND<br>
5V	      VCC<br>
18 – TX1	SCL<br>
19 – RX1	SDA<br>

