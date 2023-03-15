---
layout: post
title:  "Série sobre projetos - Comandos elétricos"
date:   2023-03-15 08:00:00 -0300
categories: projeto automotiva
author: Paulo Royer
---
# Projeto Automotivo

## Automação

A automação em polos automotivos compreende várias disciplinas:

- Comandos Elétricos
- PLC
- Redes industriais
- Pneumática
- Mecânica
- Robótica

Cada disciplina é um universo inteiro de conhecimentos e não se costuma exigir o domínio em cada disciplina, pois seria algo impossível. É comum, por isso, contar com especialistas em cada uma das mesmas disciplinas.

### Comandos Elétricos

O domínio de comandos elétricos no campo da automação permite utilizar elementos discretos para controle e proteção dos equipamentos na área da máquina.

É comum o uso de contatores e relés que fazem a interface entre o PLC e o equipamento controlado, como um motor ou sistema de aquecimento.

Entretanto é relativamente comum utilizar comandos elétricos como ferramentas *stand alone* entre as técnicas disponíveis de controle. Assim, circuitos que controlam iluminação ou compressores e motobombas, possuem e permitem o controle direto e local do funcionamento.

A segurança e proteção de pessoas também é obtida através de contatores e relés de segurança, principalmente quando se fala em adequação aos padrões de segurança de máquinas, no Brasil e no exterior.

Sem o uso de PLC, é possível construir um sistema seguro com as técnicas para proteção de pessoas em CAT I, CAT II e até em CAT III e CAT IV, com o uso escalar de relés de segurança, de acordo com a análise de risco.

Toda a documentação do projeto elétrico deve ser desenhada e atualizada em algum software CAD, como *e-plan* ou *see* ou mesmo o *autocad electrical*. Mesmo o autocad padrão também permite desenhar circuitos simples. O desafio ao longo do projeto é manter os desenhos atualizados, um exercício constante.
### PLC

Do inglês *controlador lógico programável* foi a forma encontrada para tornar as linhas de montagem flexíveis e fáceis de diagnosticar quando houvesse um problema de manutenção, como uma simples falha em algum relé e que devia ser substituído.

Através de programas gravados em uma memória não volátil, o **PLC** é capaz de executar instruções e realizar cálculos, além de informar uma infinidade de dados relativos às condições atuais da linha de produção ou de controle de processo.

Simplificou em muito a construção de sistemas de automação, uma vez que a complexidade não está no hardware utilizado, muitas vezes apenas contatores e relés utilizados como *drivers* de potência, mas no software, especialmente escrito para controlar todos os elementos de uma linha.

### Redes Industriais

As redes industriais começaram junto com a eletrônica em circuitos de controle anteriores aos PLC, mas que precisavam comunicação a relativa longa distância. 

Utilizam um protocolo serial, hoje bem definido e com checagem de erros e qualidade de comunicação.

As comunicações podem ser bidirecionais ou unidirecionais, de acordo com a possibilidade de comunicação em reverso. Assim, dispositivos separados por muitos quilômetros podem ser operados de maneira segura e confiável com apenas uma linha de comunicação, e ainda informar as condições remotas do dispositivo.

Destacam-se hoje as redes:

- Ethernet-IP
- CAN
- MODBus
- ProfiNet, ProfiSafe
- Device-Net
