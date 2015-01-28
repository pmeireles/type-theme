---
title: Como eu ouço música em casa
categories:
  - Base
tags:
  - música
  - readynas
  - squeezebox
featured: no
status: live
summary:
---
A música é uma parte importante da minha vida. Além de ouvir muita música (sobretudo jazz, mas cada vez mais música clássica), comecei também há cerca de 3 anos a aprender a tocar piano, o meu instrumento de eleição.

Sendo eu uma pessoa ligada às novas tecnologias, desde cedo que explorei alternativas ao tradicional sistema de som composto por amplificador + leitor de CD + colunas, sobretudo numa era em que cada vez mais a música é distribuída de forma digital.

Pois bem, o meu sistema de som em casa, para além do tradicional leitor de CD (NAD), amplificador (também NAD) e colunas (Castle Trent II), tem também uma componente digital, que é composta pelo seguinte:

### [1 – ReadyNAS DUO](http://www.readynas.com/?cat=3/)


![ReadyNAS Duo](http://www.pedromeireles.pt/images/readynas.jpg)

O ReadyNAS DUO, como o próprio nome indica, é um dispositivo NAS (Network Attached Storage). Basicamente trata-se de um mini-servidor que corre uma versão modificada do Linux e que suporta até dois discos (neste momento o meu tem apenas um disco de 500GB).

O **ReadyNAS DUO** tem dois papéis fundamentais no meu sistema de som: primeiro serve como armazenamento central da minha biblioteca de música e depois serve para correr o _**Squeezebox Server**_, que é o servidor de música que vai interagir com o _**Squeezebox Receiver**_ (ver ponto 2).

Em termos de formato dos ficheiros de música, grande parte dos meus ficheiros está comprimido no formato [FLAC](http://flac.sourceforge.net/) (Free Lossless Audio Codec), que é um formato de compressão sem perda, com qualidade bastante superior ao MP3. A grande desvantagem deste formato é que os ficheiros ocupam em norma cerca de dez vezes mais do que um MP3 equivalente.

É também possível utilizar um computador em vez do ReadyNAS, já que o Squeezebox Server existe para várias plataformas. A grande vantagem de utilizar um dispositivo como o ReadyNAS é que não só consome muito menos energia, como é mais silencioso. Mesmo assim, acabei por substituir a ventoinha do meu ReadyNAS por [uma](http://fractal-design.com/?view=product&category=4&prod=15) ainda mais silenciosa que a de origem, tornando-o praticamente inaudível. Fiz-lhe também um upgrade de memória, passando dos 256MB que vêm de origem para 512MB (o ReadyNAS utiliza SODIMMs idênticos aos que se utilizam nos portáteis).

### [2 – Squeezebox Receiver](http://www.logitech.com/en-us/support/4098?crid=409/)


![Squeezebox Duet](http://www.pedromeireles.pt/images/squeezebox_controller_cradle.jpg)

O _**Squeezebox Receiver**_ faz parte do conjunto _**Squeezebox Duet**_, que é composto pelo *Receiver* e pelo *Controller* (comando Wi-Fi). Foi-me oferecido um *Duet* cujo *Controller* estava avariado e, graças às intrucções que encontrei [nesta](http://forums.anandtech.com/showthread.php?t=210916/) página, consegui colocá-lo a funcionar sem o dito *Controller*! Então sem o comando como é que eu controlo que música é que quero ouvir? É simples, utilizo o meu iPad! (ver ponto 3)

O *Squeezebox Receiver* liga-se à rede doméstica via Wi-Fi ou cabo Ethernet (que é o que eu uso) e liga-se também via saídas RCA ou ópticas a um amplificador.

![Squeezebox Receiver](http://www.pedromeireles.pt/images/squeezebox_receiver_back.jpg)

A ligação à rede doméstica permite que o *Receiver* comunique com o *Squeezebox Server* que está a correr no ReadyNAS para ir buscar as músicas e depois envia o áudio para o amplificador.

### 3 – iPad / [Squeezepad](http://www.squeezepad.com/)


![Squeezepad](http://www.pedromeireles.pt/images/squeezepad.png)

O **Squeezepad** é uma aplicação para iPad que permite aceder à música existente no *Squeezebox Server* e controlar o *Squeezebox Receiver*. O funcionamento é em tudo idêntico ao do *Squeezebox Controller*, com a grande vantagem de que o ecrã do iPad é muito maior, permitindo ver as capas dos álbuns em tamanho grande.

Parece um bocado complicado, não é? Claro que este género de instalação não é recomendada a quem não tenha já alguns conhecimentos de informática e redes, mas no fundo acaba por ser relativamente simples e os resultados são muito bons. Uma vez que é possível ter vários *Receivers* espalhados pela casa, conseguimos com esta solução criar um sistema de som *multi-room* a um preço bem mais acessível do que os sistemas completos que se vendem por aí.