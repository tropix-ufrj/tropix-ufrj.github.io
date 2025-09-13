
<img src="tropix.gif" alt="tropix" width="400"/>

# O Sistema Operacional TROPIX

**Versão do sistema: 4.9.0, de 28.11.08 - Data da página: 15.12.08**

## Índice

-  **[Descrição do sistema](#descrição-do-sistema)**

-  **[Projeto em desenvolvimento](#projeto-em-desenvolvimento)**

- **[Características do sistema](#características-do-sistema)**

- **[Requisitos para a instalação](#requisitos-para-a-instalação)**

- **[Novidades desta Versão](#novidades-desta-versão)**

- **[Novidades da Versão Anterior](#novidades-da-versão-anterior)**

- **[Manual de instalação](#manual-de-instalação)**

- **[Imagem do CDROM](#imagem-do-cdrom)**

- **[Disquetes do TROPIX](#disquetes-do-tropix)**

- **[Disquetes do X-Window](#disquetes-do-x-window)**

- **[Código Fonte](#código-fonte)**

- **[Perguntas Freqüentes](/qfp.html)**

- **[Entrevista da \"GeekStore\"](/entre.html)**

- **[Estatísticas de acesso](#estatísticas-de-acesso)**

- **[Ajude no desenvolvimento](#ajude-no-desenvolvimento)**

- **[Visite os outros Projetos do NCE/UFRJ](http://www.nce.ufrj.br/pesquisa/projetos.asp)**

## Descrição do Sistema

O **TROPIX** (pronuncia-se \"Trópix\") é um Sistema Operacional
multiusuário e multitarefa, de filosofia UNIX ®, desenvolvido no Núcleo
de Computação Eletrônica da Universidade Federal do Rio de Janeiro
(NCE/UFRJ).

O TROPIX foi inicialmente concebido durantes os anos de 1982 a 1986 (na
época com o nome PLURIX) para o computador PEGASUS. Este computador foi
construído também no NCE, e era baseado nos processadores MOTOROLA
68010/20. O sistema foi transportado em 1987 para o computador ICARUS,
também baseado nestes mesmos processadores. Em 1994 foi iniciado o
transporte para a linha INTEL de processadores (386, 486, Pentium), e
desde 1996 o TROPIX já está operacional em PCs, sendo utilizado em
diversos computadores.

O TROPIX tem diversas utilidades, tais como o
estudo/aprendizado/utilização de um sistema operacional de filosofia
UNIX, o desenvolvimento de programas (\"software\") e a implementação de
servidores para a INTERNET (esta página que você está lendo está vindo
do servidor WWW de um computador rodando TROPIX). Além disto, é ideal
para a utilização em cursos de sistemas operacionais, pois contém
primitivas para processos \"leves\" (\"threads\"), memória
compartilhada, semáforos a nível de usuário, dentre outros.

A distribuição do TROPIX é gratuita, segundo a licença pública do GNU.

Atualmente, o desenvolvimento e manutenção do TROPIX estão sendo feitos
por Pedro Salenbauch e Oswaldo Vernet. Para maiores informações,
sugestões, comunicação de erros, ou em caso de quaisquer dúvidas sobre a
sua instalação e utilização, use o endereço eletrônico
<syspedrosal@gmail.com>.

A continuação deste trabalho é uma homenagem póstuma para **Newton
Faller**, o grande idealizador dos projetos PEGASUS, PLURIX, TROPIX e de
tantos outros.

**[Volta para o Índice](#índice)**

## Projeto em Desenvolvimento

O TROPIX é um projeto vivo, em contínuo desenvolvimento. Embora já
contenha diversas componentes importantes, tais como acesso à INTERNET e
uma interface gráfica simples, entre outros (veja abaixo), ainda NÃO é
um sistema completo.

Para completá-lo, ele conta com a sua colaboração. Veja a seção **[Ajude
o desenvolvimento do TROPIX](#ajude-no-desenvolvimento)**

Além disto, se você sentiu falta de algum aplicativo, linguagem, etc.
\... está automaticamente convidado(a) a desenvolve-lo ou transportá-lo.

**[Volta para o Índice](#índice)**

## Características do Sistema

O TROPIX é distribuído em 2 meios: disquetes ou CDROM. A distribuição
através de disquetes consiste da parte básica com 2 disquetes de 3½\" e
o Sistema Gráfico X-Window em 2 disquetes adicionais. O CDROM é
distribuído através de uma imagem, que deverá ser usada para gravar um
CDROM com o auxílio de um programa apropriado (tal como \"cdrecorder\",
\"Easy CD Creator\" ou \"Nero\").

A instalação em PCs pode ser feita de dois modos: em partições próprias
ou em arquivos de uma partição do MS-DOS/Windows (neste caso sem a
necessidade de alterar as partições dos discos). É incluído um
gerenciador de carga de sistemas operacionais (\"boot0\") para a
convivência amigável com outros sistemas operacionais.

Atualmente o TROPIX possui os utilitários básicos do UNIX (além de mais
alguns utilitários próprios), um sistema de desenvolvimento para a
linguagem ANSI \"C\", o suporte para a rede de computadores INTERNET com
protocolos TCP/IP, SLIP, PPP (para linha discada), e os
clientes/servidores \"telnet\", \"rlogin\", \"ftp\", \"www\", \"pop3\" e
outros.

Todo o TROPIX é baseado no código de caracteres ISO-8859-1 (Latim-1),
tendo toda a acentuação disponível em todos os modos (texto, gráfico) e
utilitários. Além disto, todos os manuais podem ser consultados na tela
(\"on-line\"), e são em português.

Os sistemas de arquivos FAT/NTFS do MS-DOS/Windows (tanto em disquetes
como em partições dos discos rígidos) assim como os CDROMs podem ser
montados diretamente (NTFS somente para leituras).

**[Volta para o Índice](#índice)**

## Requisitos para a instalação

O PC deve possuir um processador Intel 486/PENTIUM ou equivalente. O
mínimo razoável de memória principal é 8 MB. Com 4 MB é possível
utilizar o sistema, mas pode haver dificuldades em simultaneamente usar
a rede INTERNET e compilar programas. Para o Sistema Gráfico X-Window
são necessários pelo menos 16 MB.

São suportados disquetes de 3½\" e 5¼\", e discos rígidos IDE/ATA/SATA.
Também são suportados discos rígidos SCSI conectados através dos
controladores SCSI Adaptec 1542 (ISA) e 2940/29160 (PCI).

Os discos Iomega ZIP (100 MB) e CDROMs também são suportados, nas
versões de porta paralela (ZIP), IDE/ATAPI e SCSI (desde que conectados
a um dos controladores SCSI indicados acima).

Para a rede INTERNET, são suportados os controladores \"ethernet\"
Novell (NE1000, NE2000 ISA/PCI), 3Com 3c503 e Realtek RTL 8129/8139 Fast
Ethernet (10/100 Mbs), além de linhas seriais com protocolos SLIP ou
PPP.

São suportadas também as portas paralelas para o uso de impressoras.

São reconhecidos \"mouse\"s e \"pen drive\" USB, desde que conectados à
portas USB dos padrões UHCI, OHCI ou EHCI.

São aceitos os Fax-modems ISA e o Fax-modem U.S. Robotics 56K PCI.

É suportada a saída de áudio digital (DSP) das placas de som \"Sound
Blaster 16\" (ou sucessoras), para a execução de músicas PCM (arquivos
\"\*.wav\").

**[Volta para o Índice](#índice)**

## Novidades desta Versão

A presente versão (4.9.0), contém como novidades:

1.  O Protocolo DHCP para a obtenção de endereços IP dinâmicos.
2.  Implementado o protocolo USB 2.0.
3.  Suporte a discos SATA.
4.  Nova versão da interface gráfica (baseada na versão 4.7.0
    distribuída pelo Consórcio XFree86).

**[Volta para o Índice](#índice)**

## Novidades da Versão Anterior

A versão 4.8.0 continha como novidade:

1.  O Sistema de Arquivos NFS (Network File System, Versão 2), para a
    montagem de sistemas de arquivos remotos.

**[Volta para o Índice](#índice)**

## Manual de instalação

Tanto a coleção da [imagem do CDROM](#cd) do TROPIX, como a coleção dos
[disquetes do TROPIX básico](#disquetes) incluem este manual.

-   [Manual de instalação (versão 4.9.0, de dezembro de 2008, TXT, 108
    KB)](install.txt)
-   [Manual de instalação (versão 4.9.0, de dezembro de 2008, PDF, 176
    KB)](install.pdf)
-   [Manual de instalação (versão 4.9.0, de dezembro de 2008,
    HTML)](install.html)

Salve o arquivo \"install.txt\" com \"save as\", e em seguida leia o
texto com \"more\" (sistemas UNIX) ou com \"notepad\"/\"wordpad\"
(sistemas Windows).

>Repare que este manual é acentuado, usando o código de caracteres UTF-8:
>talvez seja necessário configurar o seu sistema.

**[Volta para o Índice](#índice)**

## Imagem do CDROM

Esta imagem contém o TROPIX objeto completo, inclusive o Sistema Gráfico
X-Window.

O servidor WWW do TROPIX já está permitindo a retomada das
transferências a partir do ponto em que foram interrompidas. É
necessária a utilização de uma ferramenta apropriada, como por exemplo
\"GetRight\".

-   [Imagem do CDROM do TROPIX (versão 4.9.0, de 10.12.08, 11
    MB)](cdrom.tgz)

Se você usa um sistema UNIX, use os utilitários \"gunzip\" e \"tar\"
para descomprimir a coleção, e leia o manual de instalação com \"more\".

Se você usa um sistema Windows, use o utilitário \"winzip\" para
descomprimir a coleção, e leia o manual de instalação com \"notepad\" ou
\"wordpad\".

É necessária a gravação do CDROM; leia o capítulo 5 do [manual de
instalação.](#manual-de-instalação)

**[Volta para o Índice](#índice)**

## Disquetes do TROPIX

Se você tiver uma partição MS-DOS/Windows FAT16/32 ou NTFS em seu
computador, só é necessária a criação de um único disquete para a
instalação.

-   [Disquetes do TROPIX básico (versão 4.9.0, de 10.12.08, 2221
    KB)](\tropix.tgz)

Se você usa um sistema UNIX, use os utilitários \"gunzip\" e \"tar\"
para descomprimir a coleção, e leia o manual de instalação com \"more\".

Se você usa um sistema Windows, use o utilitário \"winzip\" para
descomprimir a coleção, e leia o manual de instalação com \"notepad\" ou
\"wordpad\".

**[Volta para o Índice](#índice)**

## Disquetes do X-Window

-   [Disquetes do X-Window (versão 4.9.0, de 10.12.08, 2443
    KB)](\xwin.tgz)

Se você usa um sistema UNIX, use os utilitários \"gunzip\" e \"tar\"
para descomprimir a coleção.

Se você usa um sistema Windows, use o utilitário \"winzip\" para
descomprimir a coleção.

Se você tiver uma partição MS-DOS/Windows FAT16/32 ou NTFS em seu
computador, NÃO é necessária a criação de nenhum disquete para a
instalação.

Para detalhes de instalação, leia os capítulos 19 a 22 do [manual de
instalação.](#manual-de-instalação)

**[Volta para o Índice](#índice)**

## Código Fonte

Já estão disponíveis os Códigos Fonte do Núcleo do Sistema, bibliotecas,
comandos e o sistema gráfico X-Window do TROPIX:

-   [Código Fonte do Núcleo do TROPIX (versão 4.9.0, 1063
    KB)](\kernel.tgz)

-   [Código Fonte das Bibliotecas do TROPIX (versão 4.9.0, 562
    KB)](\lib.tgz)

-   [Código Fonte dos Comandos do TROPIX (versão 4.9.0, 3088
    KB)](\cmd.tgz)

-   [Código Fonte do sistema gráfico X-Window do TROPIX (versão 4.9.0,
    17254 KB)](\sxwin.tgz)

Se você está usando um sistema Windows e tem o TROPIX instalado, monte a
partição MS-DOS/Windows para copiar a coleção, use os utilitários
\"gunzip\" e \"gar\" para descomprimi-la e em seguida compile os
diversos módulos.

Se você está usando um sistema Windows, mas NÃO tem o TROPIX instalado,
use o utilitário \"Winzip\" para descomprimi-la.

Se você está usando um sistema UNIX, use os utilitários \"gunzip\" e
\"tar\" para descomprimi-la.

Para maiores detalhes, leia os capítulos 23 e 24 do [manual de
instalação.](#manual-de-instalação)

**[Volta para o Índice](#índice)**

## Estatísticas de acesso

No período de 21.06.99 a 30.09.06 houve:

38677 acessos a esta página;

5225 distribuições do TROPIX básico;

3708 distribuições da Interface Gráfica X-Window;

3616 distribuições do Código Fonte do Núcleo do TROPIX.

No período de 17.05.00 a 30.09.06 houve:

1749 distribuições do Código Fonte das Bibliotecas;

1619 distribuições do Código Fonte dos Comandos do TROPIX.

No período de 19.05.03 a 30.09.06 houve:

460 distribuições do Código Fonte da Interface Gráfica X-Window.

No período de 01.12.04 a 30.09.06 houve:

468 distribuições da imagem do CDROM do TROPIX.

**[Volta para o Índice](#índice)**

## Ajude no Desenvolvimento

Se você tem prazer em programar e gostaria de contribuir para a
continuação do desenvolvimento do TROPIX, seja bem-vindo! Dentre os
diversos projetos de desenvolvimento futuro para os quais necessitamos
de colaboradores estão:

1.  Transporte do Lynx para o TROPIX.
2.  Transporte do Netscape para o TROPIX.

Para maiores detalhes, entre em contato conosco no endereço eletrônico
<syspedrosal@gmail.com>.

**[Volta para o Índice](#índice)**

<hr>
  Data da Página: {{ "now" | date: "%Y-%m-%d %H:%M" }}  --- Projeto TROPIX
<hr>
