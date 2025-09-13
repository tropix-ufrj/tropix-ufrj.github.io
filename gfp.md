---
layout: default 
title: Perguntas Frequentes 
permalink: /gfp/
---

# O Sistema Operacional TROPIX

![Tropix](./tropix.gif)

Perguntas Frequentes
==================== 
**Versão 4.0.0, de 17.11.00**

------------------------------------------------------------------------
## 1. Tamanho dos disquetes

**Pergunta:** Ao tentar gravar os disquetes do TROPIX, verifiquei que o
arquivos não cabem nos disquetes.

**Resposta:** Você provavelmente tentou copiar os arquivos do TROPIX
para os disquetes diretamente através do Windows, \"arrastando\" o ícone
do arquivo. O correto é realizar a cópia através do utilitário
\"fdimage.exe\".

## 2. Documentação do TROPIX

**Pergunta:** O TROPIX tem documentação?

**Resposta:** Sim; o TROPIX contém centenas de manuais, com um total de
mais de mil páginas. Após a instalação do TROPIX, eles estão todos
disponíveis através do comando \"man\".

O principal manual é o de instalação, que pode ser obtido diretamente na
[página principal do TROPIX](index.html#manual), ou consultado (com o
sistema já instalado) através de \"man install\".

Leia o capítulo 16 do manual de instalação: (\"E agora \...?\").

## 3. Travamento da tela

**Pergunta:** Após imprimir algumas linhas na tela (tanto no modo texto
quanto no modo gráfico, com \"xterm\", o sistema \"trava\".

**Resposta:** Normalmente, a saída pára ao final de 24 linhas, evitando
um \"rolamento\" da tela que faria com que linhas (possivelmente ainda
não lidas) saíssem da tela. Para continuar, basta teclar \<\^Q\>. Isto
pode ser alterado através do comando \"stty\". Leia o capítulo 6 do
manual de instalação.


## 4. Programas executáveis do LINUX/FreeBSD

**Pergunta:** Os programas executáveis do LINUX/FreeBSD rodam no TROPIX?

**Resposta:** Não; no mundo UNIX (com raras exceções), os programas
executáveis de um sistema não rodam em outro. Normalmente, o transporte
é realizado através dos programas fontes.

------------------------------------------------------------------------

## 5. Instalação simultânea de várias Sistemas Operacionais

**Pergunta:** Como instalar em um mesmo PC vários Sistemas Operacionais,
tais como TROPIX, LINUX, FreeBSD, Win95/Win98/WinNT, \...

**Resposta:** Provavelmente há várias soluções para isto. Uma delas, a
que usamos, é utilizar o \"boot0\", o gerenciador de carga do TROPIX.
Para isto, é necessário que todas as partições contendo os sistemas
carregáveis estejam \"ativas\". Isto pode ser feito através do \"fdisk\"
do TROPIX, que é parte do \"boot2\" (veja no manual de instalação). Para
instalar o \"boot0\", use o comando \"edboot\" (leia o seu manual).

Detalhes: Ao instalar o LINUX, deve-se instalar o LILO no início da
partição raiz do LINUX, e NÃO no MBR (\"master boot record\"). Se você
tiver mais de um disco, pode instalar o TROPIX inteiramente no segundo
(ou terceiro, \...), pois \"boot0\" carrega um sistema operacional em
qualquer partição de todos os discos (desde que o programa de carga
colocado no início da partição raiz do sistema operacional suporte
isto).

**[Volta para o Índice](index.html)**

------------------------------------------------------------------------

  ----------------------------------- -----------------------------------
  Data: 30.05.2000                    Projeto TROPIX\

  ----------------------------------- -----------------------------------
