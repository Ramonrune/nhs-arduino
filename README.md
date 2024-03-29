# NHS Arduino


```
Projeto de Conclusão de Curso apresentado
como requisito parcial para obtenção do grau
Tecnólogo em Análise e Desenvolvimento de
Sistemas, pela Faculdade de Tecnologia de
Americana.
Time: 
RAMON LACAVA GUTIERREZ GONÇALES
LEONARDO MARTINS DE OLIVEIRA
NATÁLIA AKINA UESUGI
Orientador: Prof. Dr. Kleber de Oliveira Andrade
Área de concentração: Engenharia de Software

Americana, SP
2018


Este trabalho se trata de uma plataforma de saúde digital unificada, que permite melhor gestão de informações de saúde e processos inteligentes. 
A plataforma visa auxiliar o dia a dia das instituições de saúde e pacientes, buscando diminuir a quantidade de erros na área médica através de uma coleção consistente de dados do paciente, possibilitando que o sistema atue em qualquer instituição de saúde, e que tenha uma melhor eficiência e eficácia em atendimentos, sejam estes comuns ou de urgência e emergência.
O trabalho foi realizado em colaboração com a universidade de Durban, na África do Sul. 
A metodologia empregada durante o decorrer do trabalho foi o SCRUM, que visa a transparência, dinamicidade e agrega valor ao produto final. 
Foram desenvolvidos dois aplicativos para dispositivos móveis e um para computador, que realizam gestão de exames, diagnósticos, dados de saúde, medicamentos, instituições, médicos(as), dentre outros. 
Diversos requisitos foram coletados de forma dinâmica com as equipes sul africanas para possibilitar a integração dos sistemas tanto no Brasil quanto na África do Sul.
Todo o desenvolvimento do sistema se voltou para agregar valor aos processos e interfaces de usuário (se focando em facilidade de uso e experiencia de usuário).
Os resultados foram dois aplicativos publicados na Google Play e um sistema computadorizado, sendo que os três estão em fase de testes na África do Sul.
Conclui-se que o sistema poderá auxiliar muito no ambiente da saúde, facilitando a gestão, fornecendo processos inteligentes e uma maior agilidade no atendimento, permitindo com que pacientes possuam acesso a seus dados de saúde, e com que funcionários de saúde possuam uma maior facilidade e uma maior quantidade de dados relevantes para análise durante os atendimentos.
```
<br>
Leitor de NFC utilizando Arduino Mega e NFC PN532 utilizado no projeto NHS.

## Componentes
<p>&nbsp;</p>
<p>Tabela - Componentes utilizados</p>
<table width="100%">
<tbody>
<tr>
<td width="519">
<p><strong>Nome do componente</strong></p>
</td>
<td width="85">
<p><strong>Pre&ccedil;o (R$)</strong></p>
</td>
</tr>
<tr>
<td width="519">
<p>Arduino Mega</p>
</td>
<td width="85">
<p>R$ 94,90</p>
</td>
</tr>
<tr>
<td width="519">
<p>Kit m&oacute;dulo leitor RFID NFC PN532</p>
</td>
<td width="85">
<p>R$ 117,90</p>
</td>
</tr>
<tr>
<td width="519">
<p>Kit Jumpers Macho-Macho x65 unidades</p>
</td>
<td width="85">
<p>R$ 12,90</p>
</td>
</tr>
<tr>
<td width="519">
<p>Protoboard 830 Pontos</p>
</td>
<td width="85">
<p>R$ 16,90</p>
</td>
</tr>
<tr>
<td width="519">
<p>Buzzer ativo 5V</p>
</td>
<td width="85">
<p>R$ 3,40</p>
</td>
</tr>
</tbody>
</table>

## Circuito
![alt text](https://github.com/Ramonrune/nhs-arduino/blob/master/circuit.png)

A Figura apresenta o circuito utilizado. Pode-se notar a presença do Arduino Mega, do módulo PN532 e de um Buzzer. O módulo PN532 é utilizado para obter o código de identificação do equipamento de acesso, e no momento que isto ocorrer, o buzzer irá alertar o usuário através do som.

## Ligações entre o Arduino e o módulo PN532
<p><a name="_Toc530233522"></a>Tabela - Liga&ccedil;&otilde;es entre o Arduino e o m&oacute;dulo PN532</p>
<table>
<tbody>
<tr>
<td width="302">
<p><strong>Arduino</strong></p>
</td>
<td width="302">
<p><strong>PN532</strong></p>
</td>
</tr>
<tr>
<td width="302">
<p>GND</p>
</td>
<td width="302">
<p>GND</p>
</td>
</tr>
<tr>
<td width="302">
<p>5V</p>
</td>
<td width="302">
<p>VCC</p>
</td>
</tr>
<tr>
<td width="302">
<p>18 &ndash; TX1</p>
</td>
<td width="302">
<p>SCL</p>
</td>
</tr>
<tr>
<td width="302">
<p>19 &ndash; RX1</p>
</td>
<td width="302">
<p>SDA</p>
</td>
</tr>
</tbody>
</table>

## Diagrama para leitura do NFC
![alt text](https://github.com/Ramonrune/nhs-arduino/blob/master/reader.png)



## Licença

    Copyright 2019 
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.


