---
title: Autenticação em dois passos
categories:
  - Base
tags:
  - security
featured: no
status: live
summary:
---
Se o prezado leitor está de alguma forma preocupado com a privacidade e segurança dos seus perfis on-line e da informação que coloca nos diversos serviços *cloud* (Dropbox, Google Drive, etc.), **não há nenhuma razão para não utilizar a autenticação em dois passos**. Se não sabe do que se trata, então continue a ler.

A [autenticação em dois passos](http://en.wikipedia.org/wiki/Multi-factor_authentication) é uma camada de segurança adicional que nos permite proteger de uma forma mais eficaz os serviços on-line que utilizamos, sejam as redes sociais como o Facebook ou o Twitter, sejam outros serviços como o Gmail, Dropbox ou outros. O princípio é simples: em vez de nos ser pedido apenas o utilizador e a palavra-passe quando fazemos login num desses serviços, vai-nos ser pedido um código de segurança adicional (o tal segundo passo) para verificar a nossa identidade. Isto significa que se por alguma razão a nossa password for "roubada" por alguém, essa pessoa nunca conseguirá fazer login sem o código de segurança. **Este simples processo aumenta de uma forma muito significativa a segurança da utilização destes serviços**.

Serviços como os referidos Facebook, Twitter, Gmail e Dropbox já suportam a autenticação em dois passos, mas a lista continua a crescer e já inclui também a Microsoft, Apple e LinkedIn, entre outros. Alguns destes serviços estão a disponibilizar esta funcionalidade apenas em alguns países e vão gradualmente expandindo para outros, pelo que alguns serviços poderão já permitir a autenticação em dois passos mas ainda não em Portugal.

O processo é basicamente o mesmo em todos os serviços. Acedemos ao URL do serviço no nosso browser, introduzimos o utilizador e palavra-passe e a seguir é-nos pedido o tal código de segurança adicional que nos é enviado por SMS para o nº de telemóvel configurado no serviço. Aqui fica um exemplo do ecrã de autenticação em dois passos do Dropbox:

![](https://31.media.tumblr.com/3f20cd3f689f1b6e6a5d9b149db8ec26/tumblr_inline_nd6mg8US921smkfgf.png)

Para maior comodidade temos a hipótese de dizer que confiarmos no computador que estamos a utilizar e nesse computador específico não nos voltará a ser pedido o código. Isto é útil, por exemplo, quando acedemos a um serviço várias vezes no mesmo computador e este é seguro (por exemplo o nosso computador de casa).

Agora coloca-se uma questão: e se quisermos fazer login num sítio onde não temos cobertura de rede móvel (e portanto não podemos receber o SMS)? Neste caso alguns dos serviços suportam também a utilização de uma aplicação de autenticação que gera códigos baseados no tempo, à semelhança dos *[security tokens](http://en.wikipedia.org/wiki/Security_token)* utilizados nas redes corporativas. Uma dessas aplicações é o [Google Authenticator](https://code.google.com/p/google-authenticator/), que eu já utilizo para gerar códigos para entrar no Gmail, Dropbox, Facebook e serviços da Microsoft (Outlook.com, por exemplo). Aqui fica um ecrã do Google Authenticator:

![](https://31.media.tumblr.com/fe1d603a15a704f1c960224b58717a13/tumblr_inline_nd6mgi9I711smkfgf.jpg)

Mas mesmo os serviços que não suportam a utilização de uma aplicação de autenticação, permitem normalmente gerar alguns códigos para utilização off-line que poderemos utilizar mesmo sem rede de telemóvel. Por exemplo, a Google permite gerar um folha com 10 códigos de segurança de utilização única, que eu gerei e guardei em casa. Cada um destes códigos, como o nome indica, só pode ser utilizado uma vez.

Depois de ouvir histórias como [esta](http://www.wired.com/gadgetlab/2012/08/apple-amazon-mat-honan-hacking/), que circulou pela internet o ano passado, penso que toda a gente deveria considerar utilizar a autenticação em dois passos. É certo que torna o processo de login um bocado mais complicado, o que pode ser frustrante se tivermos em casa de um amigo e quisermos apenas mostrar alguma coisa que temos na nossa conta do Facebook ou Twitter, mas a segurança acrescida compensa largamente face a este incómodo adicional.

Para finalizar deixo aqui alguns links que explicam como activar a autenticação em dois passos nos serviços mais populares:

* **Apple:** [Frequently asked questions about two-step verification for Apple ID](http://support.apple.com/kb/HT5570)
* **Dropbox:** [How do I enable two-step verification on my account?](https://www.dropbox.com/help/363)
* **Evernote:** [Evernote’s Three New Security Features](http://blog.evernote.com/blog/2013/05/30/evernotes-three-new-security-features/)
* **Facebook:** [Introducing Login Approvals](https://www.facebook.com/note.php?note_id=10150172618258920)
* **Gmail:** [Google 2-Step Verification](http://www.google.com/landing/2step/)
* **LinkedIn:** [Protecting your LinkedIn Account with Two-Step Verification](http://blog.linkedin.com/2013/05/31/protecting-your-linkedin-account-with-two-step-verification/)
* **Twitter:** [Getting started with login verification](https://blog.twitter.com/2013/getting-started-login-verification)