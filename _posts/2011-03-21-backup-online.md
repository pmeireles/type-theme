---
title: Soluções de backup online
categories:
  - Base
tags:
  - backup
featured: no
status: live
summary:
---

Já pensaram o que seria se perdessem todas as vossas fotografias digitais? E todos os vídeos? E todas as músicas? Era mau não era? Pois bem, **a má notícia é que a probabilidade de isso acontecer não é nada baixa**. A boa notícia é que existem soluções para evitar que isso aconteça.

Passo a explicar. Grande parte das nossos fotografias, vídeos e músicas (já para não falar de documentos) residem hoje nos nosso computadores, armazenadas no disco rígido. Acontece que a probabilidade de um disco rígido avariar é elevada e é fácil perceber isso, basta olhar para o [funcionamento](http://pt.wikipedia.org/wiki/Disco_r%C3%ADgido/) de um disco. Estranho é que eles não avariem mais vezes! Pois bem, quem tem todos os seus ficheiros armazenados apenas num computador deveria preocupar-se…e muito! É que eles não estão mesmo nada seguros.

**Precisamos então de backups**. A forma mais fácil de o fazer é utilizando um disco rígido externo e copiando para lá todos os nossos ficheiros importantes. Este processo poderá ser mais ou menos automático, mas regra geral é eficaz. Passamos a ter todos os nossos ficheiros em dois sítios diferentes. Óptimo, então já não nos precisamos de preocupar, certo? Errado. Em primeiro lugar, apesar de a probabilidade ser infinitamente mais baixa, podemos ter o azar de nos avariar o disco do computador e o disco externo. Mas mais preocupante do que isso, podem-nos assaltar a casa e levar o computador e o disco externo e lá se vão as nossas memórias. Ou pior do que isso, podemos ter um incêndio em casa e de nada adianta ter os dados em dois sítios diferentes se esses dois sítios forem debaixo do mesmo tecto e este arder.

Se calhar estou a ser um pouco dramático, mas tratando-se das nossas valiosas memórias pessoais, todo o cuidado é pouco. Pelo menos eu sei que ficaria muito chateado, para não dizer furioso, se perdesse todas aquelas fotografias dos meus filhos bebés, a darem os primeiros passos, a comerem as primeiras papas, a dizerem as primeiras palavras! Para mim seria impensável perder estas preciosidades.

Pois bem, preocupado com esta situação pus mão à obra e fui à procura de uma solução. A primeira solução que me ocorreu foi armazenar um disco externo em casa de familiares ou amigos, aumentando assim a segurança. Mas isso obrigar-me-ia a estar constantemente a ir lá buscar o disco para fazer novo backup, voltar a deixá-lo lá e repetir este processo vezes sem conta. Nada prático. Para além de que os meus dados pessoais ficavam à mercê de outras pessoas. E se eu até confio nos meus amigos, sei lá o que é que poderiam fazer os amigos dos meus amigos. Sinceramente sinto-me mais seguro se for eu a ter o controlo dos meus dados.

Chegamos então ao tópico deste post e que me parece ser a solução ideal para este problema: **fazer os backups para um serviço on-line**. Vantagens? Os nossos dados ficam alojados do outro lado do atlântico, em datacenters com todas as medidas de segurança possíveis e imaginárias e temos uma quantidade ilimitada de espaço. Desvantagens? O serviço tem um custo (que acaba por não ser assim tão alto) e os nossos dados, apesar de tudo, estão num lugar que nós não controlamos e isso pode criar algumas desconfianças. Mas bem vistas as coisas parece ser a solução mais eficaz para esta problemática das cópias de segurança.

**Vamos então às soluções existentes.**

Depois de pesquisar um pouco pela web reduzi a escolha a três serviços que pareciam ser os mais bem cotados:

* [Backblaze](http://www.backblaze.com/)
* [Carbonite](http://www.carbonite.com/)
* [Mozy](http://www.mozy.com/)

Os três pareciam muito similares e a escolha parecia difícil. Eliminar o Mozy foi fácil. Mal abri o site deparei-me com esta imagem:

![Mozy](http://pedromeireles.pt/images/mozy.png)

Foi o suficiente para afastar logo este serviço da minha lista. Porquê? Já reparam bem na ridícula fotografia do homem de óculos escuros? Se estivéssemos a falar de um site de download de filmes piratas ou coisa do género ainda se compreendia, agora num serviço que se quer credível e a quem vamos confiar os nossos dados pessoais? Não, os meus dados aí não ficam!

Restava-me então o Carbonite e o Backblaze. Pareciam ambos boas alternativas e muito competentes, mas então li algures relatos de utilizadores que tinham perdido os dados todos que tinham guardados no Carbonite. Bem sei que isto pode acontecer a qualquer um dos outros serviços, mas deixou-me logo desconfiado. Sendo assim, estava encontrado o vencedor:

![Backblaze](http://pedromeireles.pt/images/backblaze.jpg)

Escolhi então o Backblaze e posso dizer que para já estou satisfeito. É possível testar o serviço durante 15 dias, coisa que eu fiz, mas acabei por aderir ao serviço por um ano. Os preços podem ser de $5/mês ou $50/ano e depois vão variando consoante se opte por subscrever mais anos de uma só vez. Eu optei pelos $50/ano, poupando assim $10 face aos $5/mês, o que se traduziu em aproximadamente 36€. Nada mau para um serviço que nos permite fazer upload ilimitado de informação.

O funcionamento do Backblaze é muito simples. É necessário instalar o software no nosso computador (existe para PC e Mac) e na primeira utilização será feito um inventário de toda a informação existente no nosso disco para salvaguardar. O principio é de que toda a informação vai ser salvaguardada, excepto ficheiros temporários, de sistema, etc. Podemos depois excluir determinadas pastas ou ficheiros. **Ou seja, em vez de indicarmos que dados queremos salvaguardar, indicamos apenas aqueles que não queremos salvaguardar, o que faz sentido**. A ideia é que o software seja simples de utilizar, mesmo pelos mais leigos nestas matérias.

Depois de seleccionarmos a informação a salvaguardar, o software começa a fazer o nosso primeiro backup que, dependendo da quantidade de informação e da velocidade da nossa ligação, poderá demorar entre uns dias e umas semanas. No meu caso, que tenho 120 GB de dados para salvaguardar, já lá vai mais de uma semana e o backup ainda não acabou. É pois recomendável deixar o computador sempre ligado durante uns dias, enquanto é feito o backup inicial.

Terminado o backup inicial, será feito apenas backup dos ficheiros novos ou de ficheiros que tenham sido alterados. **Caso um ficheiro seja apagado do computador, o mesmo ficará disponível durante 30 dias**, no fim dos quais será também apagado do Backblaze. Isto pode dar jeito no caso de acidentalmente apagarmos algum ficheiro.

Resta falar das possibilidades que temos de recuperar a nossa informação em caso de perda. Existem três possibilidades: fazer download dos ficheiros a partir do próprio site, receber em casa um DVD, ou receber um disco externo USB com os nossos dados. A primeira opção não tem custos, mas caso tenhamos perdido todos os nossos ficheiros não é prática, já que demoraríamos multo tempo a fazer download de todos os dados. A segunda opção já tem custos mas também só faz sentido se tivermos muito pouca informação. A terceira opção é a mais cara, mas em caso de perda total dos nossos dados será a ideal, pois enviam-nos um disco com toda a nossa informação.

Pelo preço pedido, cerca de 36€ por ano, penso que esta solução é relativamente económica. Não nos podemos esquecer que muita da nossa informação digital não tem preço. São memórias que queremos guardar para a vida. Sendo assim, recomendo vivamente uma solução deste género.