---
layout: post
title:  "Série sobre projetos - Automotivo"
date:   2023-03-14 08:00:00 -0300
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
### Pneumática

A pneumática é a forma mais barata de obter movimentos e travamentos seguros nos diversos dispositivos do setor automotivo. São grampos, cilindros e pinos guia que permitem que as peças sejam presas corretamente e com força adequada até que haja a solda a ponto ou algum tipo de aparafusamento.

Os dispositivos são controlados por PLC ou por lógica de relés através de ilhas de válvulas pneumáticas e sensores acoplados aos cilindros.

Todos esses comandos passam por módulos de entrada e de saída conectados ao PLC da linha. Alguns dispositivos contam com PLC integrado, inclusive de segurança, tornado totalmente ************stand-alone************ e independente.

### Mecânica

A mecânica é responsável pelo leiaute completo da linha de montagem, além dos cálculos de esforço que cada componente sofre. Transportadores, mesas de elevação, janelas de inspeção, pinças de solda, enfim, todos os equipamentos e todos os elementos de fixação necessários aos equipamentos.

Sempre com a estreita relação entre o controle e o comando feito pelos PLCs ou pelos comandos elétricos, é o que garante a rigidez da montagem dos carros, bem como a precisão e a repetibilidade.

Na Ford e em muitas montadoras americanas, as normas que se devem seguir são as ********NAMS******** e asseguram inclusive uma compatibilidade de estruturas entre as fábricas. No caso de fabricantes europeias, as normas são as ******DIN****** ou **ISO** que norteiam as especificações de construção.

### Robótica

A robótica, tema de filmes, livros e séries de ficção científica durante muito tempo, está presente na indústria automotiva de maneira firme desde meados da década de 1970.

A possibilidade de repetibilidade e precisão ao longo do tempo de operação de um robô é algo que não se alcança com o ser humano, que se cansa, esquece de dar algum ponto de solda ou aplicar algum trecho de cola, e o carro passa com um defeito que afeta a sua estrutura ou a sua qualidade.

Diversos tipos de robôs hoje em dia permitem as mais variadas aplicações na linha de montagem automotiva, com destaque para:

- Movimentação de peças
- Aplicação de cola
- Solda a ponto
- Solda mig
- Solda e corte a Laser
- Aplicação de pinos Stud e tackwelds

Também começam a aparecer aplicações de inspeção de qualidade, validação dimensional e de quantidade de pontos de solda, além dos COBOTS, capazes de trabalhar ao lado de pessoas de maneira segura e confiável.

Os robôs são escolhidos de acordo com sua aplicação, o peso da ferramenta, o alcance que devem ter e o tipo de peça. São controlados em sua maioria por meio de um PLC central que passa os comandos aos diversos robôs e dispositivos da linha de montagem.

Isso não impede que operem de maneira isolada, pois o controlador de cada robô é capaz de ser programado como um PLC e inclusive controlar os outros robôs da célula de montagem, de uma maneira integrada e totalmente descentralizada.

A comunicação entre robôs e PLC é feita via redes industriais, como vimos anteriormente, o que diminui a passagem de fios e cabos, uma vez que a estrutura de rede é ponto a ponto muitas vezes redundante, ao romper um cabo, a comunicação chega ao robô através de um caminho alternativo.
