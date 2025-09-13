---
layout: default 
title: Entrevista 
permalink: /entre/
---
# O Sistema Operacional TROPIX

![Tropix](tropix.gif)

## Entrevista da \"GeekStore\" 

Abaixo reproduzimos a entrevista de Andrei de Oliveira Mosman da
\"GeekStore\" [www.geekstore.com.br](http://www.geekstore.com.br) com a
equipe do TROPIX (Setembro de 2000):

**GS:** A febre LINUX e a GPL alavancaram inúmeros projetos de sistemas
operacionais alternativos ao redor do mundo. Isso de alguma forma
incentivou, ajudou ou atrapalhou o desenvolvimento do projeto TROPIX ?

**TROPIX:** Antes de passar a responder às perguntas, gostaríamos de
fazer um esclarecimento. O objetivo de distribuir o TROPIX através de
uma página eletrônica, foi o de tornar público os resultados de um
projeto de pesquisa com 17 anos de duração, a fim de que os seus
usuários e a comunidade científica possam também participar do projeto.
É a mesma idéia do LINUX, em que Linus Torvalds construiu apenas o
núcleo do sistema operacional, e a comunidade colaborou, programando os
diversos outros componentes do sistema.

A sua afirmação inicial, de que o LINUX e GPL alavancaram inúmeros
projetos de sistemas operacionais não se aplica ao TROPIX, pelo simples
fato de ser um projeto iniciado quase 10 anos antes do LINUX. Quem sabe
se não foi o inverso, com o TROPIX alavancando o LINUX?

Em relação à sua pergunta sobre a influência do LINUX e GPL sobre o
TROPIX: na realidade ajudou, pois em primeiro lugar conscientizou a
comunidade de que existem outros sistemas operacionais além dos da
Microsoft, e em segundo lugar, possibilitou-nos (principalmente através
do FreeBSD), obter informações sobre diversos dispositivos do PC (no
código fonte dos \"drivers\"), às quais não teríamos acesso de outra
forma.

**GS:** A geekstore testou o sistema operacional TROPIX em seu
laboratório e pôde observar várias diferenças conceituais do TROPIX em
relação à outros UNIXes, tal como a configuração de placas de rede, e a
compatibilidade dos aplicativos. Linus Torvalds conseguiu popularizar o
LINUX compatibilizando o sistema com outros UNIXes e alavancou o projeto
quando conseguiu rodar em seus sistemas aplicativos desenvolvidos pela
GNU. Existe algum projeto para compatibilizar o TROPIX a um ponto onde
ele consiga rodar binários do LINUX e até mesmo de alguns UNIXes ?

**TROPIX:** Não é bem assim; cada UNIX tem a sua configuração dos
diversos dispositivos/rede e os aplicativos não são idênticos entre as
diversas variantes de UNIXes. Além disto, o LINUX não é compatível com
outros UNIXes, simplesmente porque estes outros UNIXes são distintos
entre si.

Repare que a \"compatibilidade\" no mundo UNIX é a nível de código fonte
(em geral na linguagem \"C\") e não código objeto. A compatibilidade a
nível de código objeto é possível para o mundo Windows pelo fato de
estes sistemas operacionais serem produtos de um monopólio (a
Microsoft), a qual mantém o código fonte no mais absoluto sigilo. Aliás,
ficamos admirados como empresas e órgãos governamentais colocam os seus
dados confidenciais em computadores com o Windows, quando existe a
possibilidade de este código secreto conter funções para \"espionar\" os
dados e remetê-los através da INTERNET para qualquer destino desejado
(coisa que não pode ocorrer quando o código fonte é público).

Em relação aos aplicativos do GNU, como o código fonte é público, eles
foram compilados para o LINUX, o que também podemos fazer para o TROPIX.
No nosso caso, isto foi feito apenas para o compilador \"C\", pois em
relação aos demais aplicativos, preferimos os nossos, que já foram
feitos há mais de 10 anos, quando o projeto ainda se chamava PLURIX.

A execução de programas objeto do LINUX no TROPIX, é uma possibilidade
que pode ser feita apenas em um futuro a longo prazo, pois faltam no
TROPIX ainda coisas muito mais básicas, tais como a leitura do sistema
de arquivos do CD-ROM e navegadores para a INTERNET (tal como o
NETSCAPE).

**GS:** A corrida pelos softwares GPL por parte de empresas, ONGs e até
mesmo de organizações governamentais tem direcionado o LINUX, o BSD e o
até mesmo o HURD para um segmento mais profissional do mercado. Apesar
de muitas vezes trabalharem com uma visão relativamente não-comercial,
distribuições como o RedHat e o SlackWare, o OpenBSD, o FreeBSD e o
NetBSD têm conquistado respeito por parte do mercado devido à
aplicabilidade desses sistemas em um contexto extremante comercial. O
TROPIX tende a seguir um rumo comercial, acadêmico ou vocês ainda nem
pensaram muito nisso ?

**TROPIX:** O Projeto TROPIX possui atualmente apenas 2 pesquisadores
fixos, o que não possibilita a competição com os outros UNIXes em termos
de número de aplicativos e linguagens. Justamente a disponibilidade
pública do código objeto e fonte possibilita a colaboração da comunidade
(conforme o esclarecimento acima) e após esta etapa podemos decidir
sobre o rumo comercial e/ou acadêmico.

**GS:** Qual o incentivo que a UFRJ tem dado ao TROPIX ? Existe a
ideia/pretensão/visão/incentivo por parte da UFRJ para fazer do TROPIX
um modelo de tecnologia de ponta nacional, uma vez que o TROPIX é o
primeiro projeto 100% nacional de desenvolvimento de um sistema
operacional de filosofia UNIX ?

**TROPIX:** Atualmente, o NCE/UFRJ dedica 2 pesquisadores para o
projeto, além de um estagiário e alguns PCs. Na parte acadêmica, o
TROPIX é assunto para várias teses de mestrado.

Acreditamos que o objetivo de fazer do TROPIX um modelo de tecnologia de
ponta nacional teria de ser um empreendimento conjunto do NCE/UFRJ e a
iniciativa privada.

Aliás, não podemos esquecer de mencionar o sistema operacional SOX, da
empresa estatal COBRA, desenvolvimento também nacional, dos anos 80.

**GS:** A comunidade de desenvolvedores para ambientes UNIX tem
colaborado para o desenvolvimento do TROPIX ? Qual a representatividade
desta colaboração ?

**TROPIX:** A colaboração até agora foi bastante pequena; na realidade
ela resume-se em apenas uma: a adaptação do núcleo para teclados ABNT.

**GS:** Vocês acreditam que em alguns anos o TROPIX possa conseguir um
nível de aceitação no brasil comparável à aceitação conseguida pelo
LINUX ?

**TROPIX:** Talvez, mas em primeiro lugar, precisamos desenvolvê-lo
mais.

**GS:** Para terminar: Existe incentivo da iniciativa privada para o
desenvolvimento do TROPIX ? Este incentivo seria/é importante?

**TROPIX:** No momento não temos nenhum contato com a iniciativa
privada. Qualquer incentivo, naturalmente, seria bem vindo, desde que
respeite a idéia do código fonte público.

**[Volta para o Índice](index.md)**

<hr>
  Data da Página: {{ "now" | date: "%Y-%m-%d %H:%M" }}  --- Projeto TROPIX
<hr>
