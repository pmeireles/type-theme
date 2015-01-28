---
title: Instalar o OS X num PC
categories:
  - Base
tags:
  - apple
  - geek stuff
  - osx
  - windows
featured: no
status: hidden
summary:
---
Desde há uns tempos que andava com vontade de experimentar instalar o OS X no meu PC de casa. Para quem não sabe é possível fazer isto desde que se tenha hardware minimamente compatível, alguns conhecimentos a nível de computadores, instalação de sistemas operativos, etc. e uma boa dose de paciência. O resultado final pode ser frustrante, ou pode ser tão bom que o OS X passa a ser o nosso sistema operativo por defeito. Foi o meu caso.

Mas voltemos um pouco atrás. O que é que me levou a querer instalar o OS X no meu computador? Bom, em primeiro lugar o facto de cada vez mais admirar a Apple e os seus produtos e de já ter um iPhone e de um iPad há bastante tempo. Para "fechar o ciclo" só me faltava mesmo ter um Mac, ou à falta de melhor o sistema operativo que corre nos Macs.

Por outro lado confesso que estou um bocado farto do Windows e penso que a Microsoft já perdeu o encanto há muito tempo (se é que alguma vez o teve), para além de que estrategicamente anda completamente perdida. O falhanço do Windows 8 e dos tablets baseados nele são prova disso, assim como o facto de a Microsoft ter perdido a guerra dos smartphones [^1]. Depois de usar o Windows 8 durante uns meses fiquei mesmo com a sensação que a era Microsoft já era, passando a redundância, e fiquei com vontade de experimentar outras opções.

Acresce a isto o facto de grande parte dos blogs que acompanho serem escritos por utilizadores do OS X, que muitas vezes falam das vantagens deste sistema operativo e da qualidade das aplicações existentes para o mesmo [^2].

Decidi portanto avançar com esta ideia. O primeiro passo foi arranjar um disco rígido que pudesse formatar à vontade para fazer as experiências necessárias sem mexer no meu disco principal do Windows. O segundo passo foi verificar se o hardware do meu computador era compatível com o OS X, o que se veio a verificar. A lista de componentes utilizada foi a seguinte:

* **Motherboard:** Asus P8H67-M Evo
* **Processador:** Intel Core i5 2500K
* **Memória:** 8Gb DDR3
* **Placa gráfica:** Intel HD3000 (integrada no CPU)
* **Disco rígido:** Samsung HD103SJ

A única duvida residia na placa gráfica, pois até há pouco tempo não era possível instalar o OS X com uma placa integrada, mas desde que o Mac Mini passou a utilizar esta mesma placa gráfica isso deixou de ser um problema.

O processo de instalação é relativamente simples mas requer o acesso a um computadpor Mac ou a uma máquina virtual com o OS X [^3]. O processo é o seguinte:

* Comprar uma licença do OS X Mountain Lion através da Mac App Store
* Criar uma pen drive de arranque utilizando o [Unibeast](http://www.unibeast.com)
* Arrancar o computador e fazer boot a partir da pen drive que criamos para iniciar a instalação
* Após a instalação correr o [Multibeast](http://www.multibeast.com) para instalar os drivers necessários e configurar o sistema para arrancar pelo disco

E pronto, temos o OS X a funcionar no nosso computador! Bom, obviamente não é assim tão linear e podem surgir problemas. No meu caso da primeira vez que arranquei fui brindado com um *kernel panic*, que é o equivalente ao *blue screen of death* do Windows. Mas rapidamente descobri que o problema estava na porta FireWire, que não é compatível com o Mountain Lion, e desactivei-a na BIOS. A partir daí já consegui arrancar sem problemas.

No primeiro arranque estava tudo funcional excepto a placa gráfica e a placa de som. Mas tudo isto é normal e faz parte do processo. Bastou correr o Multibeast e instalar os drivers de áudio Realtek ALC892 e as definições do Mac Mini que estes dois problemas ficaram resolvidos.

A partir daí foi uma questão de ir afinando uns pormenores e o sistema foi ficando totalmente operacional. Por exemplo, descobri que o teclado não funcionava a 100% com a língua portugesa, mesmo estando definido o português como língua do sistema. Para corrigir este problema tive que instalar um novo ficheiro com o layout do teclado que descobri por acaso num fórum.

Descobri também que a minha drive de DVD não funcionava (não era sequer reconhecida pelo sistema). Depois de ler uns artigos fiquei a saber que o problema era o facto desta ser IDE e o OS X não se dar muito bem com drives IDE. Substitui-a então por uma drive SATA e esta já foi reconhecida pelo sistema operativo. Apenas persistiu um problema, que é o facto de a drive de 5 em 5 minutos "acordar". Aparentemente as drives utilizadas nos Macs são da Sony (modelos Optiarc) ou Pioneer e apenas estas funcionam sem qualquer tipo de problema. A solução, para não gastar dinheiro numa drive nova, é ter sempre um CD ou DVD dentro da drive.

Para finalizar, aqui ficam como referência alguns dos sites que utilizei para levar esta ideia a bom porto:

* <http://www.tonymacx86.com/home.php>
* <http://wiki.osx86project.org/wiki/index.php/Main_Page>
* <http://www.macbreaker.com/2012/08/multibeast-5-mountain-lion-guide.html>
* <http://www.hackintosh.com/>
* <http://www.macbreaker.com/2012/11/how-to-set-up-asus-hackintosh.html>
* <http://hackintoshworld.info/p8h67-m-evo-hackintosh/>
* <http://www.macbreaker.com/2012/03/intel-hd-3000-on-your-hackintosh.html>

[^1]: Apesar disso considero o Windows Phone um execelente sistema operativo, tal como escrevi [aqui](http://www.pedromeireles.pt/blog/breve-analise-ao-windows-phone), que só peca por ter chegado muito tarde ao mercado. Inclusivamente considero-o um melhor sistema operativo que o Android.

[^2]: <a href="http://www.marco.org/2008/02/14/why-you-should-consider-os-x">Why you should consider OS X</a> (Marco Arment)

[^3]: [Nesta](http://www.souldevteam.net/blog/downloads/) página é possível encontrar máquinas virtuais das várias versões do OS X, incluindo a versão Developer Preview do Mavericks. 	