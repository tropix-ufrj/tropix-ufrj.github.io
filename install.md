      *******   *******  *******   *******    *    *     *
         *      *     *  *     *   *     *    *     *   *
         *      *     *  *     *   *     *    *      * *
         *      *******  *     *   *******    *       *
         *      *  *     *     *   *          *      * *
         *      *   *    *     *   *          *     *   *
         *      *    *   *******   *          *    *     *















                    TROPIX - Guia de INSTALAÃÃO


                           VersÃ£o 4.9.0




                               Guia
















                         Dezembro de 2008

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 2

                             CONTEÃDO





        Cap.  1 - IntroduÃ§Ã£o ...........................  4

        Cap.  2 - Novidades das VersÃµes ................  6

        Cap.  3 - CaracterÃ­sticas ...................... 11

        Cap.  4 - ConfiguraÃ§Ã£o do PC ................... 12

        Cap.  5 - CriaÃ§Ã£o do CDROM ..................... 13

        Cap.  6 - CriaÃ§Ã£o do disquete de BOOT .......... 14

        Cap.  7 - Algumas  ConvenÃ§Ãµes/caracterÃ­sticas do
                  TROPIX ............................... 16

        Cap.  8 - Executando  o  TROPIX  diretamente  do
                  CDROM ou disquete .................... 18

        Cap.  9 - PreparaÃ§Ã£o dos disquetes/arquivos
                  restantes ............................ 22

        Cap. 10 - Modos de instalaÃ§Ã£o do TROPIX no disco
                  rÃ­gido ............................... 23

        Cap. 11 - InstalaÃ§Ã£o  do  TROPIX  em arquivos do
                  MS-DOS/Windows ....................... 24

        Cap. 12 - Discos e partiÃ§Ãµes ................... 26

        Cap. 13 - O editor de partiÃ§Ãµes "fdisk" ........ 28

        Cap. 14 - Reduzindo  o  tamanho  de uma partiÃ§Ã£o
                  MS-DOS/Windows ....................... 32

        Cap. 15 - InstalaÃ§Ã£o   do  TROPIX  em  partiÃ§Ãµes
                  prÃ³prias ............................. 35

        Cap. 16 - ConfiguraÃ§Ã£o dos controladores USB.... 37

        Cap. 17 - E agora? ............................. 38

        Cap. 18 - CaracterÃ­sticas e UtilitÃ¡rios originais
                  do TROPIX ............................ 40

        Cap. 19 - IntroduÃ§Ã£o    Ã     Interface   GrÃ¡fica
                  X-Window ............................. 41

        Cap. 20 - CriaÃ§Ã£o e instalaÃ§Ã£o dos  disquetes/
                  arquivos da Interface GrÃ¡fica ........ 42

        Cap. 21 - ConfiguraÃ§Ã£o da interface GrÃ¡fica .... 43

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 3

        Cap. 22 - UtilizaÃ§Ã£o bÃ¡sica da interface GrÃ¡fica 45

        Cap. 23 - ObtenÃ§Ã£o e instalaÃ§Ã£o do  cÃ³digo fonte
                  do TROPIX ............................ 46

        Cap. 24 - CompilaÃ§Ã£o  do  nÃºcleo, bibliotecas  e
                  utilitÃ¡rios do TROPIX ................ 47

        Cap. 25 - O uso do editor de textos "vi" ....... 48

        Cap. 26 - Uma  lista  dos principais comandos do
                  TROPIX ............................... 49

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 4

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 1                       *
     *                                                       *
     *                      INTRODUÃÃO                       *
     *                                                       *
     *********************************************************

O TROPIX (pronuncia-se "trÃ³pix") Ã© um Sistema Operacional de 32 bits,
multiusuÃ¡rio e multitarefa, de filosofia UNIX Â®, desenvolvido no
NÃºcleo de ComputaÃ§Ã£o EletrÃ´nica da Universidade Federal do Rio de
Janeiro (NCE/UFRJ).

O TROPIX foi inicialmente concebido durantes os anos de 1982 a 1986 (na
Ã©poca com o nome PLURIX) para o computador PEGASUS. Este computador foi
construÃ­do tambÃ©m no NCE, e era baseado nos processadores MOTOROLA
68010/20. Desde seu inÃ­cio, o sistema foi concebido com
multiprocessamento simÃ©trico, funcionando em um PEGASUS que possuÃ­a 2
CPUs 68020.

O sistema foi transportado em 1987 para o computador ICARUS, baseado
nestes mesmos processadores, e acrescentada parte do suporte para tempo
real. Em 1994 foi iniciado o transporte para a linha INTEL de
processadores (386, 486, Pentium), e desde 1996 o TROPIX jÃ¡ estÃ¡
operacional em PCs, sendo utilizado em diversos computadores.

Nesta versÃ£o para PCs, ainda nÃ£o estÃ¡ concluÃ­da a deteÃ§Ã£o de
placas-mÃ£e com mais de uma CPU, o que Ã© necessÃ¡rio para o
multiprocessamento.

Em relaÃ§Ã£o ao tempo real, foi recentemente concluÃ­da uma tese de
mestrado na qual foi desenvolvida uma versÃ£o do nÃºcleo do TROPIX para
tempo real.

O TROPIX tem diversas utilidades, tais como o
estudo/aprendizado/utilizaÃ§Ã£o de um sistema operacional de filosofia
UNIX, o desenvolvimento de programas ("software") e a implementaÃ§Ã£o de
servidores para a INTERNET. AlÃ©m disto, Ã© ideal para a utilizaÃ§Ã£o em
cursos de sistemas operacionais, pois contÃ©m primitivas para processos
"leves" ("threads"), memÃ³ria compartilhada, semÃ¡foros a nÃ­vel de
usuÃ¡rio, dentre outros.

Este texto (que vocÃª estÃ¡ lendo) contÃ©m informaÃ§Ãµes introdutÃ³rias
sobre a distribuiÃ§Ã£o e instalaÃ§Ã£o do sistema TROPIX. Durante a
instalaÃ§Ã£o, ele pode ser consultado/impresso no seu PC (veja o final
do capÃ­tulo 8). AlÃ©m disto, contÃ©m as informaÃ§Ãµes para a
instalaÃ§Ã£o da Interface GrÃ¡fica X-Window (capÃ­tulos 19 a 22), e as
informaÃ§Ãµes para a instalaÃ§Ã£o/compilaÃ§Ã£o do cÃ³digo fonte do
TROPIX (capÃ­tulos 23 e 24).

O sistema operacional TROPIX Ã© um "software" livre, e vocÃª Ã©
bem-vindo para redistribuÃ­-lo sob certas condiÃ§Ãµes; para detalhes,
tecle "man licenÃ§a" (apÃ³s a sua instalaÃ§Ã£o).

Atualmente, o desenvolvimento e manutenÃ§Ã£o do TROPIX estÃ£o sendo
feitos por Pedro Salenbauch e Oswaldo Vernet. Para maiores

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 5

informaÃ§Ãµes, sugestÃµes, comunicaÃ§Ã£o de erros, ou em caso de
quaisquer dÃºvidas sobre a sua instalaÃ§Ã£o e utilizaÃ§Ã£o, use o
endereÃ§o eletrÃ´nico "tropix\@tropix.nce.ufrj.br".

Visite periodicamente a pÃ¡gina eletrÃ´nica do TROPIX, no endereÃ§o
"http://www.tropix.nce.ufrj.br" para informar-se sobre novas versÃµes do
sistema.

A continuaÃ§Ã£o deste trabalho Ã© uma homenagem pÃ³stuma a Newton
Faller, o grande idealizador dos projetos PEGASUS, PLURIX, TROPIX e de
tantos outros.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 6

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 2                       *
     *                                                       *
     *                 NOVIDADES DAS VERSÃES                 *
     *                                                       *
     *********************************************************

Novidades desta versÃ£o "4.9.0":

    1: Implementado o protocolo USB 2.0.

    2: Suporta a discos SATA.

    3: Nova versÃ£o da interface grÃ¡fica (baseada  na  versÃ£o  4.7.0
       distribuÃ­da pelo ConsÃ³rcio XFree86).

Para acompanhar a evoluÃ§Ã£o do TROPIX, incluÃ­mos as novidades das
versÃµes anteriores.

Novidades da versÃ£o "4.8.0":

    1: Sistema de Arquivos NFS (Network  File  System,  VersÃ£o  2),
       para a montagem de sistemas de arquivos remotos.

Novidades da versÃ£o "4.7.0":

    1: DistribuiÃ§Ã£o do cÃ³digo objeto em CDROM.

    2: Novo utilitÃ¡rio grÃ¡fico "xcpu", que desenha o grÃ¡fico de uso
       da CPU.

Novidades da versÃ£o "4.6.0":

    1: Suporte  a  discos  USB (simulados em memÃ³ria, "pen drive"),
       com anexaÃ§Ã£o/desanexaÃ§Ã£o dinÃ¢mica.

    2: Montagem (somente para  leituras)  do  sistema  de  arquivos
       NTFS.

    3: Montagem  de  imagens  de  sistemas de arquivos (em arquivos
       regulares).

    4: Nova versÃ£o da interface grÃ¡fica (baseada  na  versÃ£o  4.4.0
       distribuÃ­da pelo ConsÃ³rcio XFree86).

Novidades da versÃ£o "4.5.0":

    1: Reconhecimento de "mouse" USB.

    2: Novos utilitÃ¡rios grÃ¡ficos: o gerenciador de arquivos "xfm",

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 7

       o  programa  para acessar caixas postais remotas "xpop3" e o
       gerador de imagens fractais de Mandelbrot "xmandel".

    3: ExtensÃ£o do nÃºcleo  para  permitir  o  compartilhamento  das
       interrupÃ§Ãµes (IRQ) entre dispositivos.

    4: Acesso a sistemas de arquivos FAT-32 de mais de 4 GB.

Novidades da versÃ£o "4.4.0":

    1: Montagem de Sistemas de Arquivos EXT2 do Linux.

    2: Suporte ao "mouse" PS/2.

    3: Nova  versÃ£o  (XFree86  Version  4.3.0)  do  Sistema GrÃ¡fico
       X-Window, suportando os modelos  mais  recentes  das  placas
       grÃ¡ficas ATI, TRIDENT e S3.

    4: Novas  funÃ§Ãµes da biblioteca "stdio" com Ã¡reas de 4 KB, para
       compatibilizÃ¡-la com o novo sistema de arquivos T1.

    5: FunÃ§Ãµes aritmÃ©ticas de 64 bits para os valores  "long  long"
       da linguagem "C". Isto Ã© importante para o acesso a arquivos
       com mais de 4 GB.

    6: Acesso  ao  histÃ³rico  da  "sh"  atravÃ©s das teclas de setas
       tambÃ©m em modo texto.

    7: Novos  comandos:  O  desfragmentador   "xdefrag"   (programa
       grÃ¡fico)  permite melhorar a alocaÃ§Ã£o dos blocos de sistemas
       de arquivos T1; o  programa  conversor  "a2ps"  converte  um
       texto  ISO para PostScript, para ser impresso em impressoras
       que aceitam esta linguagem.

Novidades da versÃ£o "4.3.0":

    1: O novo sistema  de  arquivos  T1,  com  blocos  de  4  KB  e
       identificadores de atÃ© 255 caracteres, que tem um desempenho
       muito  superior  ao  sistema  de  arquivos  anterior (V7) de
       blocos de 512 bytes. A presente versÃ£o continua suportando o
       sistema de arquivos V7.

    2: CriaÃ§Ã£o do arquivo "/etc/fstab" para o  melhor  controle  da
       montagem de dispositivos.

    3: Nova   interface   para   reconhecimento   de   dispositivos
       IDE/ATA/ATAPI.

    4: Disquete de BOOT da distribuiÃ§Ã£o contendo  a  imagem  de  um
       sistema  de  arquivos  que  Ã©  descompactada  em  um RAMD (a
       simulaÃ§Ã£o de um disco na memÃ³ria principal). Isto facilita a
       instalaÃ§Ã£o do TROPIX.

Novidades da versÃ£o "4.2.0":

    1: Aumento do tamanho das Ã¡reas de entrada/saÃ­da do "cache"  de
       dispositivos  estruturadas de 512 para 4096 bytes. Com isto,
       possibilitamos a leitura/escrita de dispositivos que possuem
       blocos maiores do que 512 bytes (por exemplo o  CDROM,  cujo
       bloco  Ã©  de  2  KB)  alÃ©m  de  aumentarmos  a velocidade de
       processamento dos dispositivos jÃ¡ suportados.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 8

    2: CriaÃ§Ã£o da camada abstrata de "nÃ³s-Ã­ndice" para possibilitar
       a montagem de vÃ¡rios sistemas de arquivos.

    3: Montagem de sistemas de arquivos FAT12/16/32.

    4: Montagem de sistemas de arquivos de CDROM original, alÃ©m das
       extensÃµes "Rock Ridge" e "Joliet".

    5: ImplementaÃ§Ã£o dos elos simbÃ³licos.

Novidades da versÃ£o "4.1.0":

    1: Novo "driver" para  controladores  SCSI  da  Adaptec:  Agora
       suportando os novos controladores 29160, para 160 MB/s.

    2: Adicionados  os "chip"s da VIA e INTEL para o uso de DMA com
       o acesso a discos IDE.

    3: Estendido o sistema de  compilaÃ§Ã£o  da  linguagem  "C"  para
       aceitar identificadores sem limitaÃ§Ã£o de tamanho.

    4: Introduzidas  as  funÃ§Ãµes  da biblioteca "C" para leitura de
       diretÃ³rios  em  um  formato  independente  do   sistema   de
       arquivos: "opendir", "readdir", ...

    5: O  "boot"  do  TROPIX  foi  estendido, e jÃ¡ aceita os discos
       Iomega ZIP (100 MB) para carregar o  sistema,  em  todas  as
       suas etapas.

Novidades da versÃ£o "4.0.0":

    1: Melhorado  o  reconhecimento  e a avaliaÃ§Ã£o da velocidade do
       processador do computador durante o estÃ¡gio 2  da  carga  do
       sistema ("boot2").

    2: Suporte para discos IDE com mais de 8 GB.

    3: Reconhecimento de dispositivos PnP ("Plug and Play").

    4: UtilizaÃ§Ã£o  de  DMA  para  o acesso a discos IDE (no momento
       somente para o "chip" "Acer Aladdin").

    5: Comando "mail" inteiramente reescrito, agora podendo receber
       e enviar anexos.

Novidades da versÃ£o "3.2.3":

     Esta versÃ£o "continha como novidade principal  as  bibliotecas
     compartilhadas  (semelhantes  Ã s  DLLs  do  Windows). Todas as
     bibliotecas das versÃµes antigas ("libc", "libm", "libcurses" e
     "libxti")  estÃ£o  agora  reunidas  em  apenas  uma  biblioteca
     compartilhada "/lib/libt.o".

     O  mesmo ocorre tambÃ©m com as bibliotecas da interface grÃ¡fica
     X-Window:  todas  elas  estÃ£o  agora   integradas   nas   duas
     bibliotecas     compartilhadas     "/usr/xwin/lib/libx.o"    e
     "/usr/xwin/lib/liby.o".

     Com a utilizaÃ§Ã£o das bibliotecas compartilhadas, o tamanho dos
     mÃ³dulos   executÃ¡veis   diminuiu   drasticamente.   Com   isto
     reduziu-se  simultaneamente o tempo de carga e a quantidade de

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 9

     espaÃ§o ocupados (tanto no disco como  na  memÃ³ria  principal).
     Como  exemplo,  um utilitÃ¡rio tÃ­pico, o "cp" que ocupava 13704
     bytes, passou a ocupar apenas 4032, isto Ã©, caiu  a  menos  do
     terÃ§o  do  tamanho.  No  caso  dos  utilitÃ¡rios grÃ¡ficos, esta
     reduÃ§Ã£o  Ã©  muito  maior;  como  exemplo  citamos  o  programa
     "xedit", que passou de 612 KB para menos de 4KB!


     Esta  versÃ£o  inclui  tambÃ©m  alguns programas novos, entre os
     quais:

         1: "cdplay": toca CDs de Ã¡udio  em  unidades  IDE/ATAPI  e
            SCSI.

         2: "cdtowave":  extrai  faixas de Ã¡udio de CDs em unidades
            IDE/ATAPI e SCSI.

         3: "sbvol": controla o volume (mestre) das placas SB-16.

         4: "mkshlib" e "ldshlib": cria e  carrega  as  bibliotecas
            compartilhadas.

         5: "nohup": executa comandos imunes ao sinal SIGHUP.

         6: "paste": une linhas de vÃ¡rios arquivos.

         7: "fdc": pequeno calculador de mesa para nÃºmeros de ponto
            flutuante.

         8: "xcoremap":  programa  grÃ¡fico para desenhar um mapa de
            alocaÃ§Ã£o da memÃ³ria principal do computador.

         9: "xedit": programa grÃ¡fico para editar  textos  (similar
            ao "notepad" do Windows).

        10: "xpaint": agora jÃ¡ aceita o formato JPEG.


     Outros modificaÃ§Ãµes/aprimoramentos:

         1: "Drivers"  para dispositivos IDE-ATAPI: Estes "drivers"
            irÃ£o permitir ao TROPIX acessar dispositivos IDE-ATAPI,
            tais como CD-ROMs e acionadores de discos ZIP internos.
            No entanto, os sistemas de arquivos dos  CD-ROMs  ainda
            nÃ£o estÃ£o sendo reconhecidos.

         2: "Driver" para o controlador "Realtek RTL 8129/8139 Fast
            Ethernet" (10/100 Mbs).

         3: A  partiÃ§Ã£o  de  SWAP  nÃ£o  Ã©  mais  necessÃ¡ria  para a
            instalaÃ§Ã£o,  tanto  em  partiÃ§Ãµes  prÃ³prias,  como   em
            arquivos do MS-DOS/Windows.

         4: JÃ¡ Ã© reconhecido o Fax-modem U.S. Robotics 56K PCI.

         5: InauguraÃ§Ã£o   da   distribuiÃ§Ã£o  do  cÃ³digo  fonte  das
            bibliotecas e utilitÃ¡rios do TROPIX.

         6: O servidor WWW do TROPIX  jÃ¡  permite  a  retomada  das
            transferÃªncias   a   partir   do  ponto  em  que  foram
            interrompidas.

Novidades da versÃ£o "3.2.1":

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 10

     Inclui a primeira distribuiÃ§Ã£o do cÃ³digo fonte  do  nÃºcleo  do
     sistema,  recomendando-o  mais ainda para um curso de sistemas
     operacionais.

Novidades da versÃ£o "3.2.0":

     Continha como novidade principal o suporte  (parcial)  para  a
     placa de som "Sound Blaster".

Novidades da versÃ£o "3.1.8":

     Continha  como  novidades  a  Interface  GrÃ¡fica  X-Window e o
     suporte para sistemas de arquivos MS-DOS/Windows com FAT32.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 11

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 3                       *
     *                                                       *
     *                    CARACTERÃSTICAS                    *
     *                                                       *
     *********************************************************

A distribuiÃ§Ã£o do TROPIX Ã© gratuita, e ele pode ser instalado
atravÃ©s de um CDROM ou de disquetes.

1.  O CDROM Ã© distribuÃ­do atravÃ©s de uma imagem, e contÃ©m o TROPIX
    objeto completo (incluindo o Sistema GrÃ¡fico X-Window). Esta imagem
    deverÃ¡ ser usada para gravar um CDROM atravÃ©s de um programa
    apropriado: veja o capÃ­tulo 5.

2.  A distribuiÃ§Ã£o atravÃ©s de disquetes consiste da parte bÃ¡sica com
    2 disquetes de 3Â½\" e o Sistema GrÃ¡fico X-Window em 2 disquetes
    adicionais: veja os capÃ­tulos 19 a 22.

A instalaÃ§Ã£o em PCs pode ser realizada de dois modos: em partiÃ§Ãµes
prÃ³prias ou em arquivos de uma partiÃ§Ã£o FAT16 ou FAT32 do
MS-DOS/Windows (neste caso sem a necessidade de alterar as partiÃ§Ãµes
dos discos). Ã incluÃ­do um gerenciador de carga de sistemas
operacionais ("boot0"), para a convivÃªncia amigÃ¡vel com outros
sistemas operacionais.

Atualmente o TROPIX possui os comandos bÃ¡sicos do UNIX (alÃ©m de mais
alguns comandos prÃ³prios), um sistema de desenvolvimento para a
linguagem ANSI "C", o suporte para a rede de computadores INTERNET com
protocolos TCP/IP, SLIP, PPP (para linha discada) e os
clientes/servidores "telnet", "rlogin", "ftp", "mail", "pop3" e outros.

Todo o TROPIX Ã© baseado no cÃ³digo de caracteres ISO-8859-1 (Latim-1, o
mesmo do Windows 95/98/NT/2000/XP), tendo toda a acentuaÃ§Ã£o
disponÃ­vel em todos os modos (texto, grÃ¡fico) e comandos. AlÃ©m disto,
todos os manuais podem ser consultados na tela ("on-line"), e sÃ£o em
portuguÃªs.

Os sistemas de arquivos MS-DOS/Windows FAT-12/16/32/NTFS (tanto em
disquetes como em partiÃ§Ãµes dos discos rÃ­gidos) podem ser montados
(este Ãºltimo somente para leituras).

Para a montagem de sistemas de arquivos remotos temos disponÃ­vel o
protocolo NFS, versÃ£o 2.

TambÃ©m CD-ROMs podem ser montados em todas as suas variantes (ISO-9660,
Rock-Ridge e Joliet).

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 12

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 4                       *
     *                                                       *
     *                   CONFIGURAÃÃO DO PC                  *
     *                                                       *
     *********************************************************

O PC deve possuir um processador Intel 486/PENTIUM ou equivalente. O
mÃ­nimo razoÃ¡vel de memÃ³ria principal Ã© 8 MB. Com 4 MB Ã© possÃ­vel
utilizar o sistema, mas pode haver dificuldades em simultaneamente usar
a rede INTERNET e compilar programas. Para a Interface GrÃ¡fica X-Window
sÃ£o necessÃ¡rios pelo menos 16 MB.

SÃ£o aceitos os controladores USB, mas apenas dos padrÃµes UHCI e OHCI.

SÃ£o suportados disquetes de 3Â½\" e 5Â¼\" e discos rÃ­gidos IDE/EIDE.
TambÃ©m sÃ£o suportados discos rÃ­gidos SCSI conectados atravÃ©s dos
controladores SCSI Adaptec 1542 (ISA) e 2940/29160 (PCI).

A partir da versÃ£o 4.9.0 sÃ£o suportados dispositivos USB com protocolo
1.1 e 2.0 com anexaÃ§Ã£o/desanexaÃ§Ã£o dinÃ¢mica.

Os disquetes Iomega ZIP (100 MB) tambÃ©m sÃ£o suportados nas versÃµes de
porta paralela, IDE/ATAPI e SCSI (desde que conectados a um dos
controladores SCSI indicados acima).

Para a rede INTERNET, sÃ£o suportados os controladores "ethernet" Novell
(NE1000, NE2000 ISA/PCI), 3Com 3c503 e Realtek RTL 8129/8139 Fast
Ethernet (10/100 Mbs), alÃ©m de linhas seriais com protocolos SLIP ou
PPP.

SÃ£o suportadas tambÃ©m as portas paralelas para o uso de impressoras.

SÃ£o aceitos os Fax-modems ISA e o Fax-modem U.S. Robotics 56K PCI.

A partir da versÃ£o 3.2.0 Ã© tambÃ©m suportada a saÃ­da de som digital
PCM atravÃ©s das placas de som "Sound Blaster 16" (ou sucessoras). Com
isto, Ã© possÃ­vel tocar arquivos de som \"\*.wav\" no TROPIX.

JÃ¡ sÃ£o suportados "mouse"s USB.

Como jÃ¡ foi mencionado, hÃ¡ dois modos de instalaÃ§Ã£o do TROPIX nos
discos rÃ­gidos do PC (veja o capÃ­tulo 10). Em qualquer um destes modos
Ã© necessÃ¡rio alocar um certo espaÃ§o dos discos rÃ­gidos (tipicamente
128 MB).

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 13

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 5                       *
     *                                                       *
     *                  CRIAÃÃO DO CDROM                     *
     *                                                       *
     *********************************************************

Tendo obtido a coleÃ§Ã£o "cdrom.tgz" da distribuiÃ§Ã£o do CDROM do
TROPIX, Ã© necessÃ¡rio gravÃ¡-lo.

1.  Se vocÃª utiliza um sistema UNIX, deve descomprimir "cdrom.tgz"
    atravÃ©s de "gunzip" (gerando uma coleÃ§Ã£o "tar"), e em seguida
    usar o comando "tar" para obter os arquivos:

              install.txt
              tropix.iso

    O arquivo "install.txt" Ã© o guia de instalaÃ§Ã£o (que vocÃª estÃ¡
    lendo) e o arquivo "tropix.iso" Ã© a imagem do CDROM.

    O CDROM deve ser gravado atravÃ©s de um utilitÃ¡rio adequado (tal
    como o "cdrecorder").

2.  Se vocÃª utiliza WinXP/Win2000/WinNT/Win98/Win95/Win3.x, deve
    descomprimir a coleÃ§Ã£o "cdrom.tgz" atravÃ©s de "Winzip", obtendo
    os arquivos:

              install.txt
              tropix.iso

    O arquivo "install.txt" Ã© o guia de instalaÃ§Ã£o (que vocÃª estÃ¡
    lendo) e o arquivo "tropix.iso" Ã© a imagem do CDROM.

    O CDROM deve ser gravado atravÃ©s de um utilitÃ¡rio adequado (tal
    como o "Easy CD Creator" ou o "Nero").

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 14

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 6                       *
     *                                                       *
     *            CRIAÃÃO DO DISQUETE DE "BOOT"              *
     *                                                       *
     *********************************************************

Tendo obtido a coleÃ§Ã£o "tropix.tgz" da distribuiÃ§Ã£o do TROPIX
bÃ¡sico, Ã© necessÃ¡rio (pelo menos) criar o disquete de 3Â½\" chamado
de BOOT.

1.  Se vocÃª utiliza um sistema UNIX, deve descomprimir "tropix.tgz"
    atravÃ©s de "gunzip" (gerando uma coleÃ§Ã£o "tar"), e em seguida
    usar o comando "tar" para obter os arquivos:

              install.txt
              fdimage.exe
              boot.dsk
              gar1.dsk

    O arquivo "install.txt" Ã© o guia de instalaÃ§Ã£o (que vocÃª estÃ¡
    lendo), o arquivo "fdimage.exe" Ã© um utilitÃ¡rio de cÃ³pia para o
    MS-DOS/Windows (que neste caso nÃ£o serÃ¡ usado), e os arquivos
    restantes sÃ£o os conteÃºdos dos 2 disquetes chamados de BOOT e
    GAR1.

    O disquete de BOOT pode ser criado atravÃ©s de um comando do tipo:

              cat boot.dsk >/dev/fd0

    (o nome exato do dispositivo do disquete depende do sistema sendo
    usado).

    Pode tambÃ©m ser usado o comando "dd" na forma:

              dd if=boot.dsk of=/dev/fd0

2.  Se vocÃª utiliza WinXP/Win2000/WinNT/Win98/Win95/Win3.x, deve
    descomprimir a coleÃ§Ã£o "tropix.tgz" atravÃ©s de "Winzip", obtendo
    os arquivos:

              install.txt
              fdimage.exe
              boot.dsk
              gar1.dsk

    O arquivo "install.txt" Ã© o guia de instalaÃ§Ã£o (que vocÃª estÃ¡
    lendo), o programa "fdimage.exe" Ã© um utilitÃ¡rio de cÃ³pia e os
    arquivos restantes sÃ£o os conteÃºdos dos 2 disquetes. O disquete de
    BOOT deve ser criado atravÃ©s de um comando do tipo

              fdimage.exe -v boot.dsk A:

    No caso de WinXP/Win2000/WinNT, use a janela de comandos;

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 15

      para Win98/Win95/Win3.x  use  o  modo  DOS;  neste  caso  nÃ£o
      recomendamos  usar  a janela de comandos DOS, pois Ã s vezes a
      escrita Ã© realizada incorretamente.

Utilize um disquete novo, de boa qualidade. Muitos dos erros relatados
sÃ£o ocasionados por disquetes defeituosos.

ApÃ³s a geraÃ§Ã£o do disquete, recomendamos protegÃª-lo contra escritas.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 16

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 7                       *
     *                                                       *
     *      ALGUMAS CONVENÃÃES/CARACTERÃSTICAS DO TROPIX     *
     *                                                       *
     *********************************************************

Conceitualmente, o sistema operacional TROPIX Ã© semelhante aos sistemas
tipo UNIX, embora existam algumas diferenÃ§as. Para descrever de forma
nÃ£o ambÃ­gua o procedimento de instalaÃ§Ã£o e uso do TROPIX nos PCs,
usaremos as convenÃ§Ãµes descritas abaixo. Repare bem nestas
convenÃ§Ãµes, pois elas serÃ£o usadas no TROPIX como um todo, incluindo
o sistema depois de instalado.

Teclar `<enter>`{=html} significa pressionar a tecla que tem este nome;
teclar `<sp>`{=html} (espaÃ§o em branco) significa teclar a barra de
espaÃ§o.

Teclar \<\^D\> significa comprimir simultaneamente as teclas "ctl" e
"D". Ao fazer isto, devemos comprimir inicialmente a tecla "ctl"
(segurando-a comprimida) e em seguida comprimir a tecla "D".
Analogamente, teclar \<\^A\>, \<\^B\>, ... significa comprimir a teclas
"ctl" juntamente com "A", "B", ... Em alguns teclados, podemos ter
"ctrl" ao invÃ©s de "ctl".

Teclar `<ctl-alt-del>`{=html} significa comprimir simultaneamente as
trÃªs teclas indicadas; teclar `<reset>`{=html} significa comprimir o
botÃ£o de "reset" do PC que, em geral, fica no gabinete do PC (e nÃ£o no
teclado).

Teclar "-fd0 tropix" significa teclar em sequÃªncia as teclas "-", "f",
"d", "0", `<sp>`{=html}, "t", "r", "o", "p", "i", "x" e
`<enter>`{=html}. Quando especificamos uma cadeia de caracteres para ser
teclada (como a dada acima) assumimos implicitamente que seja teclado um
`<enter>`{=html} ao final da cadeia (a nÃ£o ser que seja explicitamente
indicado o contrÃ¡rio).

Devemos nos lembrar que no TROPIX, assim como em todos os sistemas
operacionais similares ao UNIX, letras maiÃºsculas sÃ£o caracteres
DIFERENTES de letras minÃºsculas. No exemplo acima, portanto, nÃ£o
devemos comprimir a tecla `<shift>`{=html} pois as letras a serem
geradas sÃ£o todas minÃºsculas.

Alguns dos comandos do TROPIX podem pedir uma informaÃ§Ã£o/confirmaÃ§Ã£o
de aÃ§Ã£o. Este pedido Ã© identificado por um "prompt" que pode ser um
caracter ou uma cadeia de caracteres que o sistema escreve na tela.

No TROPIX, alguns do "prompt"s contÃªm uma cadeia de caracteres entre
parÃªnteses antes de um ":". Isto significa que teclar aquela cadeia ou
simplesmente teclar `<enter>`{=html} terÃ¡ o mesmo efeito. Essa cadeia
de caracteres Ã© chamada de "default", isto Ã©, aquilo que serÃ¡
interpretado pela falta de uma cadeia de caracteres explicitamente
teclada.

Assim, para a pergunta

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 17

     Carrega (fd0, tropix)? (s):

Ã© equivalente teclar "s" seguido de `<enter>`{=html} ou simplesmente
`<enter>`{=html}, o que significa "sim". Se desejarmos responder "nÃ£o",
temos de teclar "n" seguido de `<enter>`{=html}.

Em alguns comandos, uma resposta com letra maiÃºscula ("S" ou "N") faz
com que esta e todas as perguntas subseqÃ¼entes sejam respondidas
automaticamente (afirmativamente para "S" e negativamente para "N"). O
manual de cada comando (veja abaixo) informa se ele segue esta
convenÃ§Ã£o.

No TROPIX, usualmente, o sistema pÃ¡ra de escrever na tela ao completar
uma tela (24 linhas). Isto Ã© conveniente, pois o usuÃ¡rio tem tempo de
ler o texto sem que um novo texto substitua o texto atual que (talvez)
ainda nÃ£o tenha sido lido. Para continuar a escrita do texto basta
teclar \<\^Q\>. AlÃ©m disto, uma saÃ­da na tela pode ser parada a
qualquer momento, teclando \<\^S\>. Isto pode ser alterado atrÃ¡ves do
comando "stty" (ver adiante).

Ao entrar no modo "multiusuÃ¡rio" (veja abaixo) o TROPIX oferece 8 telas
virtuais independentes. O chaveamento entre as telas virtuais Ã© feito
teclando \<\^S\> (para parar a saÃ­da na tela virtual corrente), seguido
do nÃºmero da tela virtual para a qual desejamos ir (1 a 8), e
finalmente, \<\^Q\> (para ativarmos a saÃ­da na nova tela virtual).
Repare que o nÃºmero da tela virtual corrente Ã© mostrada no centro da
Ãºltima linha.

Com algumas combinaÃ§Ãµes de teclas, usadas seqÃ¼encialmente, podemos
gerar caracteres especiais. Assim, teclando-se "\~a" obtemos "Ã£" e com
",c" obtemos "Ã§". Com este mÃ©todo, podemos obter quase todas as vogais
acentuadas das linguas ocidentais. Se nÃ£o desejarmos esta composiÃ§Ã£o,
basta teclar "\" entre os caracteres. Assim, por exemplo, se
teclarmos"\~`\a`{=tex}\" obteremos "\~a".

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 18

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 8                       *
     *                                                       *
     *  EXECUTANDO O TROPIX DIRETAMENTE DO CDROM OU DISQUETE *
     *                                                       *
     *********************************************************

Tanto o CDROM do TROPIX (obtido no capÃ­tulo 5), como o disquete de BOOT
(obtido no capÃ­tulo 6), contÃ©m a imagem comprimida de um sistema de
arquivos TROPIX autÃ´nomo. Ambos podem ser executados inserindo-os na
unidade correspondente e teclando `<ctl-alt-del>`{=html} ou
`<reset>`{=html} (esta operaÃ§Ã£o, de carga do sistema operacional,
chamamos de "boot").

NÃ£o esqueÃ§a de verificar se a ordem dos vÃ¡rios dispositivos na
seqÃ¼Ãªncia de "boot" da BIOS do seu computador Ã© a desejada.

Isto Ã© Ãºtil para:

     1. Testar a compatibilidade do TROPIX com o seu computador. Se
        houver alguma incompatibilidade, comunique-nos (atravÃ©s  do
        endereÃ§o eletrÃ´nico do capÃ­tulo 1).

     2. Executar   o  TROPIX  experimentalmente,  para  conhecer  o
        sistema sem alterar os discos rÃ­gidos do seu computador.

     3. Ler este guia de instalaÃ§Ã£o  na  tela  do  computador  e/ou
        imprimi-lo na sua impressora (veja o final deste capÃ­tulo).

     4. Instalar  o  TROPIX  no  disco rÃ­gido do seu computador. HÃ¡
        dois modos de instalaÃ§Ã£o: veja o capÃ­tulo 10.

     5. Consertar  o  TROPIX  residente  no  disco   rÃ­gido,   caso
        apresente problemas.

ApÃ³s o "reset", o "boot1" (o primeiro estÃ¡gio da operaÃ§Ã£o de "boot")
serÃ¡ lido do CDROM ou disquete. Ã escrita a mensagem:

     TROPIX CD boot1, Versao: 4.9.0, de 17.06.06

     >

Teclando `<enter>`{=html}, serÃ¡ lido o "boot2" (o segundo estÃ¡gio) do
CDROM ou disquete; apÃ³s a leitura, teremos a mensagem

     TROPIX boot2, VersÃ£o: 4.9.0, de 17.11.08

     Copyright Â© 1988-2008 NCE/UFRJ

     Processador PENTIUM ................................
     ....................................................
     ........ (e outros dados do computador) ............
     ....................................................

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 19

     boot>

Neste ponto, o "boot2" estÃ¡ aguardando um comando. Ele Ã© um programa
versÃ¡til, que pode (entre outros) carregar e executar um programa,
editar/imprimir a tabela de partiÃ§Ãµes e listar o conteÃºdo da memÃ³ria
ou dispositivo. Se teclarmos "?", ele imprime a sua lista de comandos.

No nosso caso, devemos teclar "-i", para descomprimir a imagem do
sistema de arquivos da RAIZ do CDROM ou disquete para uma Ã¡rea no final
da memÃ³ria principal. Esta Ã¡rea serÃ¡ entÃ£o usado como um RAMD, ou
seja, a simulaÃ§Ã£o de um disco na memÃ³ria.

ApÃ³s a descompressÃ£o, Ã© escrita a mensagem

     TROPIX INTEL x86 - VersÃ£o 4.9.0 de 28.11.08 ...

     Copyright Â© 1988-2008 NCE/UFRJ

     O sistema operacional TROPIX Ã© distribuÃ­do ABSOLUTAMENTE
     SEM GARANTIA. Este Ã© um "software" livre, e vocÃª Ã© bem-vindo
     para redistribuÃ­-lo sob certas condiÃ§Ãµes; para detalhes,
     tecle "man licenÃ§a".

     Deseja modificar parÃ¢metros? (n):

Teclando `<enter>`{=html} mais uma vez, surje a mensagem

     TROPIX (meu_computador) mono [5]: 

Uma vez atingido este ponto, o sistema operacional TROPIX jÃ¡ assumiu o
controle em seu modo "monousuÃ¡rio", havendo apenas uma tela virtual
ativa (a que vocÃª estÃ¡ usando).

Tecle \<\^D\>, para entrar no modo "multiusuÃ¡rio", no qual vÃ¡rias
telas virtuais estarÃ£o disponÃ­veis. SerÃ£o escritas diversas
informaÃ§Ãµes na tela, atÃ© aparecer uma linha contendo:

     LOGIN:

Tecle "root" e serÃ¡ impressa a linha:

     Senha:

Tecle entÃ£o "tropix" (que nÃ£o serÃ¡ ecoado na tela) e finalmente serÃ¡
impressa a linha:

     root@meu_computador:[/home/root]# 

Pronto! Uma parte crÃ­tica foi vencida. O TROPIX jÃ¡ estÃ¡ rodando em
modo multiusuÃ¡rio em seu computador.

Durante a carga, o nÃºcleo do TROPIX escreve a mensagem

        Deseja modificar parÃ¢metros? (n):

apÃ³s a qual normalmente teclamos `<enter>`{=html}. Com isto, aceitamos
os

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 20

valores "default" dos parÃ¢metros, que em geral sÃ£o os desejados.
Podemos, no entanto modificar vÃ¡rios parÃ¢metros, sendo o mais comum o
"rootdev", isto Ã©, o dispositivo raiz do sistema. Este parÃ¢metro
contÃ©m o valor NODEV (isto Ã©, indefinido), e na inicializaÃ§Ã£o do
nÃºcleo, este procura uma raiz adequada. A ordem de busca Ã©:

1.  partiÃ§Ãµes TROPIX dos discos rÃ­gidos (por exemplo "hda2a");

2.  dispositivos simulando discos a partir de arquivos MS-DOS/Windows
    (por exemplo "md1");

3.  CDROMs (por exemplo "hdb" ou "sdb").

4.  disquetes (por exemplo "fd0").

Podemos alterar o valor "default", atribuindo uma
`<raiz  desejada>`{=html} atravÃ©s de

        rootdev=<raiz desejada>

e em seguida teclando \<\^D\>. Isto Ã© Ãºtil, por exemplo, quando jÃ¡
temos uma partiÃ§Ã£o ROOT em um disco rÃ­gido ou arquivo MS-DOS/Windows
e desejamos iniciar uma nova instalaÃ§Ã£o a partir do CDROM ou disquete.

Repare que o que foi teclado apÃ³s "LOGIN" Ã© o nome da conta ("root" no
caso), e o que o que foi teclado apÃ³s "Senha" Ã© a sua respectiva senha
("tropix" no caso). Isto significa que estamos utilizando a conta
"root", que Ã© a conta do superusuÃ¡rio, com poderes (quase) ilimitados.
Isto Ã© necessÃ¡rio durante a instalaÃ§Ã£o, mas nÃ£o Ã© recomendÃ¡vel
para o uso normal.

Para consultar este guia de distribuiÃ§Ã£o/instalaÃ§Ã£o na tela do
computador, tecle "man install". Para avanÃ§ar/retroceder pelas vÃ¡rias
pÃ¡ginas do guia, use os comandos \<\^D\>, \<\^U\>. Para ler o
conteÃºdo, use "2p"; para ir diretamente para a pÃ¡gina `<n>`{=html}
(obtida atravÃ©s do conteÃºdo), use "`<n>`{=html}p". Para encerrar a
execuÃ§Ã£o de "man", tecle "q".

Para imprimir este guia, use o comando

     cat /usr/man/ref/install >/dev/lp

(isto sÃ³ Ã© possÃ­vel se o seu PC tiver a impressora na porta/IRQ
padrÃ£o). Lembre-se de que o guia utiliza o cÃ³digo ISO-8859-1 (Latim-1)
de caracteres; se a sua impressora nÃ£o aceita este cÃ³digo de
caracteres, use o comando

     stty ascii 2>/dev/lp

antes do "cat", para retirar os acentos dos caracteres.

Se a sua impressora for uma HP, aceitando a linguagem PCL, vocÃª pode
usar o comando "hpprint".

Uma outra possibilidade Ã© a impressÃ£o deste guia atravÃ©s do
MS-DOS/Windows, usando a seqÃ¼Ãªncia de comandos:

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 21

     mount /dev/hda1 /mnt
     cp /usr/man/ref/install /mnt
     umount /dev/hda1

onde "/dev/hda1" deve ser substituÃ­do por uma partiÃ§Ã£o DOS/Windows
FAT 16/32 adequada (em geral pode ser usado o prÃ³prio "/dev/hda1", pois
provavelmente corresponde Ã  unidade "C:"). Para obter os nomes das
partiÃ§Ãµes correspondentes Ã s partiÃ§Ãµes MS-DOS/Windows, use o
comando "prdisktb".

ApÃ³s estes comandos, imprima o arquivo "install" atravÃ©s do
MS-DOS/Windows; Ã© melhor utilizar o Windows, em virtude do cÃ³digo de
caracteres usado (ISO-8859-1 (Latim-1)).

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 22

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 9                       *
     *                                                       *
     *     PREPARAÃÃO DOS DISQUETES/ARQUIVOS RESTANTES       *
     *                                                       *
     *********************************************************

Este capÃ­tulo contÃ©m informaÃ§Ãµes apenas para a instalaÃ§Ã£o atravÃ©s
de disquetes. Se vocÃª estÃ¡ instalando atravÃ©s de um CDROM, pode
pulÃ¡-lo.

Repare que a coleÃ§Ã£o "tropix.tgz" contÃ©m a imagem de 2 disquetes,
BOOT e GAR1. O disquete de BOOT jÃ¡ foi criado no capÃ­tulo 6.

Se vocÃª possui uma partiÃ§Ã£o DOS/Windows FAT16/32 ou NTFS em seu
computador, a criaÃ§Ã£o do disquete GAR1 pode ser dispensada. A idÃ©ia
consiste em copiar a imagem para um diretÃ³rio "`\TROPIX`{=tex}" da
partiÃ§Ã£o DOS/Windows.

1.  Se vocÃª utiliza um sistema UNIX, deve utilizar comandos do tipo:
    mount /dev/hda1 /mnt mkdir /mnt/TROPIX cp gar1.dsk /mnt/TROPIX
    umount /dev/hda1

    onde "/dev/hda1" pode ser substituÃ­do por uma outra partiÃ§Ã£o
    DOS/Windows desejada.

    Se a sua partiÃ§Ã£o Ã© NTFS, informe-se se o seu sistema UNIX
    suporta a escrita nestes sistemas de arquivos; muitos sistemas UNIX
    (inclusive o LINUX) suportam em geral apenas a leitura).

2.  Se vocÃª utiliza WinXP/Win2000/WinNT/Win98/Win95/Win3.x, deve
    utilizar o "Windows Explorer" para criar o diretÃ³rio
    "C:`\TROPIX`{=tex}" e em seguida copiar o arquivo "gar1.dsk" para o
    diretÃ³rio criado. Ao invÃ©s de "C:", pode ser usada uma outra
    partiÃ§Ã£o desejada.

Se vocÃª NÃO possui uma partiÃ§Ã£o DOS/Windows FAT16/32 ou NTFS em seu
computador, ou estÃ¡ querendo instalar o TROPIX em outro computador, o
disquete GAR1 terÃ¡ de ser criado.

Isto deverÃ¡ ser feito do modo jÃ¡ visto no capÃ­tulo 6, naturalmente
susbtituindo-se "boot.dsk" por "gar1.dsk".

Utilize disquetes novos, de boa qualidade. Muitos dos erros relatados
sÃ£o ocasionados por disquetes defeituosos.

ApÃ³s a criaÃ§Ã£o, recomendamos proteger o disquete contra escritas.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 23

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 10                      *
     *                                                       *
     *     MODOS DE INSTALAÃÃO DO TROPIX NO DISCO RÃGIDO     *
     *                                                       *
     *********************************************************

HÃ¡ dois modos de instalar o TROPIX no disco rÃ­gido:

1.  Em particÃµes prÃ³prias do TROPIX. Este modo oferece o melhor
    desempenho, mas a instalaÃ§Ã£o exige um certo cuidado. Opcionalmente
    pode ser instalado um gerenciador de "boot", para permitir a escolha
    do sistema operacional a carregar. Siga a seqÃ¼Ãªncia de capÃ­tulos
    12, 13, 14, 15, 16 e 17.

2.  Em arquivos do MS-DOS/Windows. Este modo nÃ£o oferece um desempenho
    tÃ£o bom e o "boot" do TROPIX terÃ¡ de ser sempre atravÃ©s de CDROM
    ou disquete, mas a instalaÃ§Ã£o Ã© mais simples. Veja os capÃ­tulos
    11, 16 e 17.

Sugerimos que vocÃª leia este guia atÃ© o final, antes de iniciar a
instalaÃ§Ã£o; assim vocÃª terÃ¡ uma visÃ£o geral melhor e poderÃ¡
avaliar adequadamente as diversas opÃ§Ãµes.

Os procedimentos para a instalaÃ§Ã£o do TROPIX aqui descritos foram
feitos para que a instalaÃ§Ã£o se processe sem contratempos. No entanto,
Ã© possÃ­vel que (por descuido do usuÃ¡rio) haja a perda de arquivos
existentes no computador e/ou o sistema operacional original (por
exemplo MS-DOS/Windows) nÃ£o possa mais ser executado. Isto pode ocorrer
principalmente em virtude do uso incorreto do editor de partiÃ§Ãµes
"fdisk" (capÃ­tulo 13).

Mesmo durante o uso normal do sistema (apÃ³s uma instalaÃ§Ã£o correta),
Ã© possÃ­vel remover acidentalmente arquivos do MS-DOS/Windows durante o
uso com partiÃ§Ãµes FAT montadas, ou usando o utilitÃ¡rio "dosmp".

Embora tenhamos testado o funcionamento do sistema, acreditando que ele
nÃ£o contenha nenhum erro grave, sempre existe teoricamente a
possibilidade de que, atravÃ©s de algum erro ainda desconhecido, seja
afetado algum outro sistema operacional.

NÃS NÃO NOS RESPONSABILIZAMOS POR ESTES POSSÃVEIS ACIDENTES! VOCÃ
ESTÃ INSTALANDO/UTILIZANDO O TROPIX SOB SUA PRÃPRIA RESPONSABILIDADE E
RISCO!

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 24

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 11                      *
     *                                                       *
     *  INSTALAÃÃO DO TROPIX EM ARQUIVOS DO MS-DOS/Windows   *
     *                                                       *
     *********************************************************

Este modo nÃ£o oferece um desempenho tÃ£o bom quanto a instalaÃ§Ã£o do
TROPIX em partiÃ§Ãµes prÃ³prias; em compensaÃ§Ã£o, a instalaÃ§Ã£o Ã©
mais simples, pois nÃ£o Ã© necessÃ¡rio reorganizar as partiÃ§Ãµes do
disco. Este mÃ©todo sÃ³ Ã© possÃ­vel com sistemas de arquivos FAT-16 ou
FAT-32; ainda NÃO Ã© possÃ­vel com NTFS.

A idÃ©ia consiste em utilizar uma partiÃ§Ã£o jÃ¡ existente do
MS-DOS/Windows e nela criar o diretÃ³rio "`\TROPIX`{=tex}" contendo 2
arquivos: "ROOT" e "HOME". Estes arquivos irÃ£o conter os sistemas de
arquivos TROPIX e a carga do sistema serÃ¡ feita atravÃ©s de CDROM ou
disquete.

As etapas da instalaÃ§Ã£o sÃ£o as seguintes:

1.  Inicialmente Ã© interessante verificar a integridade da partiÃ§Ã£o
    MS-DOS/Windows escolhida. Para isto use os utilitÃ¡rios CHKDSK ou
    SCANDISK (do MS-DOS ou do Windows).

    Uma outra opÃ§Ã£o Ã© usar o NDD (Norton Disk Doctor) dos "NORTON
    Utilities". Repare o tamanho do espaÃ§o livre disponÃ­vel da
    partiÃ§Ã£o escolhida: para uma instalaÃ§Ã£o normal sÃ£o necessÃ¡rios
    128 MB.

2.  Como segundo passo, recomendamos desfragmentar a partiÃ§Ã£o
    escolhida. Isto significa compactar todos os arquivos MS-DOS/Windows
    no inÃ­cio da partiÃ§Ã£o, de tal modo que fique apenas uma Ã¡rea
    livre ao seu final, onde serÃ£o criados os 2 arquivos do diretÃ³rio
    "`\TROPIX`{=tex}". Isto pode ser feito pelo utilitÃ¡rio DEFRAG (do
    MS-DOS ou do Windows), ou o SPEED DISK dos "NORTON Utilities".

3.  Insira o CDROM ou disquete de BOOT do TROPIX e carregue o sistema
    (conforme o capÃ­tulo 8). Entre no modo multiusuÃ¡rio.

4.  VÃ¡ para o diretÃ³rio "/usr/etc/install" (use o comando "cd
    /usr/etc/install"). A instalaÃ§Ã£o normal irÃ¡ ocupar 128 MB da sua
    partiÃ§Ã£o MS-DOS/Windows (64 MB para o ROOT, 64 MB para HOME), o
    que jÃ¡ Ã© suficiente para a interface grÃ¡fica X-Window. Se vocÃª
    tem este espaÃ§o disponÃ­vel e estÃ¡ satisfeito com ele, vÃ¡ para a
    etapa 5.

    Para mudar o tamanho da instalaÃ§Ã£o, basta editar o arquivo
    "install.dos" (veja o capÃ­tulo 25, para uma introduÃ§Ã£o ao uso do
    editor de texto "vi"). Para alterar o tamanho de um arquivo, basta
    mudar o nÃºmero apÃ³s a respectiva linha que comeÃ§a por "mkfile".

5.  Inicie a instalaÃ§Ã£o, teclando o comando "install.dos".

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 25

      Repare que com "C:" estamos nos referindo Ã  primeira partiÃ§Ã£o
      regular do primeiro disco;  idem  com  "D:"  para  o  segundo
      disco.

      Esta  etapa  cria  os  2  arquivos na partiÃ§Ã£o MS-DOS/Windows
      escolhida, gera  sistemas  de  arquivos  TROPIX  e  copia  os
      arquivos  do TROPIX para o disco rÃ­gido. Durante a instalaÃ§Ã£o
      (se  vocÃª  estÃ¡  instalando  a  partir  de  disquetes),  serÃ¡
      necessÃ¡rio um disquete adicional (cujo conteÃºdo serÃ¡ perdido)
      para ser usado para a carga do TROPIX. Siga as instruÃ§Ãµes.

      Se  vocÃª  deseja  conservar  uma  versÃ£o antiga do sistema de
      arquivos HOME,  NÃO  apague  o  arquivo  MS-DOS/Windows  HOME
      (desconsidere  a  mensagem  "O  arquivo  "home" jÃ¡ existe") e
      responda  afirmativamente  Ã   pergunta  "Deseja  conservar  a
      versÃ£o antiga de HOME?".

6.  ParabÃ©ns! O TROPIX jÃ¡ estÃ¡ instalado e operacional em seu disco
    rÃ­gido.

    Sempre que quiser executar o TROPIX, basta recarregar o sistema
    (teclando `<ctl-alt-del>`{=html} ou `<reset>`{=html}) com o CDROM ou
    o disquete DOS inserido. No caso do CDROM, Ã© necessÃ¡rio modificar
    a raiz do sistema para "md1" durante a carga do nÃºcleo (isto Ã©,
    tecle "rootdev=md1").

    Se o CDROM e o disquete nÃ£o estiverem inseridos, serÃ¡ carregado o
    sistema operacional normal (por exemplo MS-DOS/Windows). Para sair
    do TROPIX, use o comando "shutdown".

7.  Para desinstalar o TROPIX da sua partiÃ§Ã£o MS-DOS/Windows, basta
    remover o diretÃ³rio "`\TROPIX`{=tex}" (juntamente com os seus 2
    arquivos).

Para facilitar a instalaÃ§Ã£o futura de uma nova versÃ£o do TROPIX,
recomendamos colocar seus arquivos particulares apenas no seu diretÃ³rio
"home" (nome de arquivos comeÃ§ando por "/home/...").

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 26

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 12                      *
     *                                                       *
     *                  DISCOS E PARTIÃÃES                   *
     *                                                       *
     *********************************************************

Para instalar o TROPIX em partiÃ§Ãµes prÃ³prias (que possibilita o
melhor desempenho), Ã© necessÃ¡rio possuir uma noÃ§Ã£o bÃ¡sica de como
sÃ£o organizados os discos rÃ­gidos no PC.

Cada disco Ã© dividido em uma ou mais seÃ§Ãµes denominadas
"partiÃ§Ãµes". Cada uma destas partiÃ§Ãµes Ã© criada para ser usada por
um sistema operacional (em certos casos algumas das partiÃ§Ãµes podem
ser compartilhadas por dois ou mais sistemas operacionais).

Podemos ter atÃ© 4 partiÃ§Ãµes "regulares" (ou "primÃ¡rias") em cada
disco. Se este nÃºmero nÃ£o for suficiente, podemos definir uma das
partiÃ§Ãµes como sendo do tipo "estendida", que pode conter vÃ¡rias
outras (sub-)partiÃ§Ãµes chamadas de partiÃ§Ãµes "lÃ³gicas".

Os usuÃ¡rios dos MS-DOS/Windows certamente jÃ¡ tiveram contato com
partiÃ§Ãµes, pois nestes sistemas cada partiÃ§Ã£o recebe uma letra,
comeÃ§ando de "C". Assim, temos as partiÃ§Ãµes "C:", "D:", "E:", ...

A nomenclatura usada no TROPIX Ã© bem distinta das letras indicadas
acima. Vamos considerar um computador com apenas um disco IDE. As quatro
partiÃ§Ãµes sÃ£o denominadas de "hda1", "hda2", "hda3" e "hda4". Se uma
delas for "estendida", por exemplo "hda3", ela conterÃ¡ as
(sub-)partiÃ§Ãµes "lÃ³gicas" "hda3a", "hda3b", ... AlÃ©m disto, temos
"hda" para representar o disco como um todo.

Se o computador tiver mais de um disco IDE, o segundo serÃ¡ o "hdb..."
ao invÃ©s de "hda..." (bastando trocar o "a" por "b" no exemplo acima).
Se o computador tiver discos SCSI, os nomes serÃ£o "sda...", "sdb...",
... (bastando trocar o "h" por "s" no exemplo acima).

Como jÃ¡ foi dito, podemos ter apenas uma partiÃ§Ã£o estendida. Por este
motivo, no TROPIX foi criado um novo tipo de partiÃ§Ã£o estendida (a
partiÃ§Ã£o estendida de tipo TROPIX), estruturalmente idÃªntica Ã 
original, mas com um outro cÃ³digo de identificaÃ§Ã£o. O objetivo Ã©
possibilitar o agrupamento de todas as (sub-)partiÃ§Ãµes TROPIX
desejadas em apenas uma partiÃ§Ã£o (estendida) isolada, mesmo que jÃ¡
exista uma partiÃ§Ã£o estendida tradicional (que chamaremos de tipo
DOS).

Ao escolher a distribuiÃ§Ã£o das vÃ¡rias partiÃ§Ãµes pelos seus (um ou
mais) discos rÃ­gidos, deve ser levado em conta quantos discos estÃ£o
presentes, quantas partiÃ§Ãµes sÃ£o necessÃ¡rias/jÃ¡ estÃ£o alocadas,
...

No exemplo do capÃ­tulo seguinte, criamos uma (nova) partiÃ§Ã£o
estendida (de tipo TROPIX) para conter todas as partiÃ§Ãµes TROPIX. Isto
Ã© uma soluÃ§Ã£o simples e elegante, pois somente necessitamos de uma
partiÃ§Ã£o vaga.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 27

Naturalmente, podemos tambÃ©m criar uma partiÃ§Ã£o regular para cada
partiÃ§Ã£o TROPIX desejada, ou ainda acrescentar novas partiÃ§Ãµes
lÃ³gicas TROPIX a uma partiÃ§Ã£o estendida DOS jÃ¡ existente.

Para efeito de "boot", o sistema de arquivos ROOT do TROPIX pode ser
alocado em qualquer tipo de partiÃ§Ã£o de qualquer disco.

Se houver espaÃ§o disponÃ­vel em mais de um disco rÃ­gido, aconselhamos
fortemente a distribuir as partiÃ§Ãµes entre os vÃ¡rios discos.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 28

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 13                      *
     *                                                       *
     *             O EDITOR DE PARTIÃÃES "fdisk"             *
     *                                                       *
     *********************************************************

Assim como os outros sistemas operacionais, o TROPIX tambÃ©m possui o
seu editor de partiÃ§Ãµes, que (como Ã© usual) tambÃ©m Ã© chamado de
"fdisk". No entanto, no TROPIX o "fdisk" estÃ¡ incorporado ao "boot2", e
sÃ³ pode ser executado durante a carga do sistema (e nÃ£o com o sistema
jÃ¡ executando). A idÃ©ia Ã© ressaltar a impossibilidade de alterar as
partiÃ§Ãµes com o sistema em funcionamento.

Para executar o "fdisk", insira o CDROM ou o disquete de BOOT do TROPIX,
e recarregue o sistema (conforme o capÃ­tulo 8). Quando surgir o
"prompt" "boot\>" do "boot2", tecle "-f":

boot\> -f

Entrando no editor de tabelas de partiÃ§Ãµes "fdisk"

Tecle "?" para uma lista de comandos

Disco "hda": 6149.88 MB (12594960 blocos), geo = (784, 255, 63, L)

IND. -DEV- A D -INÃCIO- --FINAL- -BLOCOs- TAM (MB) TIPO

     1  hda1   *         63  4209029  4208967  2055.16  0C DOS FAT32 (L)

A geometria do disco ("geo") Ã© dada atravÃ©s do nÃºmero de cilindros
(784), nÃºmero de cabeÃ§as (255) e o nÃºmero de setores por trilha (63).
A letra "L" ao final indica que para este disco, as extensÃµes da INT 13
da BIOS estÃ£o ativas (em caso contrÃ¡rio, a letra indicada seria "G").

Uma vez com o "prompt" do "fdisk", teclando "?" obtemos uma lista dos
comandos disponiveis:

fdisk\> ?

Editor de tabelas de partiÃ§Ãµes

comandos: -: Imprime a tabela de partiÃ§Ãµes p: Idem, com Ã¡reas vagas
c: Troca o dispositivo (disco) n: Cria uma partiÃ§Ã£o nova d: Remove uma
partiÃ§Ã£o m: Altera o tamanho de uma partiÃ§Ã£o a: Troca o estado
(ativo/nÃ£o ativo) da partiÃ§Ã£o l: Imprime os tipos das partiÃ§Ãµes

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 29

         t: Troca o tipo da partiÃ§Ã£o
         s: Imprime as Ã¡reas vagas do disco
         u: Liga/desliga o alinhamento (comeÃ§a ligado)
         w: Reescreve (atualiza) a tabela de partiÃ§Ãµes no disco
         q: Termina a execuÃ§Ã£o do editor de partiÃ§Ãµes

Obs.: Para qualquer dado pedido, "n" cancela o comando

Inicialmente vamos criar uma partiÃ§Ã£o estendida para conter os 2
sistemas de arquivos (tradicionais) do TROPIX. Tecle "n", e siga o
seguinte diÃ¡logo (repare na opÃ§Ã£o do tipo da partiÃ§Ã£o estendida):

fdisk\> n

DÃª o tipo desejado: regular (r), estendida (e) ou lÃ³gica (l): e

NÃºmero da partiÃ§Ã£o = 2? (s):

DÃª o tipo de partiÃ§Ã£o estendida: DOS (d) ou TROPIX (x): x

Bloco inicial = 4209030? (s):

Bloco final = 12402179 (4000.56 MB)? (s): n

DÃª o tamanho desejado (MB): 128

Disco "hda": 6149.88 MB (12594960 blocos), geo = (784, 255, 63, L)

IND. -DEV- A D -INÃCIO- --FINAL- -BLOCOs- TAM (MB) TIPO

     1  hda1   *         63  4209029  4208967  2055.16  0C DOS FAT32 (L)
     2  hda2        4209030  4482134   273105   133.35  AE TROPIX Extended

Neste ponto podemos (opcionalmente) usar o comando "u" para nÃ£o alinhar
as partiÃ§Ãµes seguintes (veja abaixo). O exemplo continua supondo que
NÃO demos o comando "u".

Em seguida, vamos criar a partiÃ§Ã£o lÃ³gica para o ROOT. Tecle "n", e
siga o seguinte diÃ¡logo:

fdisk\> n

DÃª o tipo desejado: regular (r), estendida (e) ou lÃ³gica (l): l

PartiÃ§Ã£o estendida "hda2":

Bloco inicial = 4209093? (s):

Bloco final = 4482134 (133.32 MB)? (s): n

DÃª o tamanho desejado (MB): 64

Disco "hda": 6149.88 MB (12594960 blocos), geo = (784, 255, 63, L)

IND. -DEV- A D -INÃCIO- --FINAL- -BLOCOs- TAM (MB) TIPO

     1  hda1   *         63  4209029  4208967  2055.16  0C DOS FAT32 (L)
     2  hda2        4209030  4482134   273105   133.35  AE TROPIX Extended
     3  hda2a       4209093  4353614   144522    70.57  A9 TROPIX T1

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 30

Em seguida, vamos criar a partiÃ§Ã£o lÃ³gica para o HOME. Tecle "n", e
siga o seguinte diÃ¡logo:

fdisk\> n

DÃª o tipo desejado: regular (r), estendida (e) ou lÃ³gica (l): l

PartiÃ§Ã£o estendida "hda2":

Bloco inicial = 4353678? (s):

Bloco final = 4482134 (62.72 MB)? (s):

Disco "hda": 6149.88 MB (12594960 blocos), geo = (784, 255, 63, L)

IND. -DEV- A D -INÃCIO- --FINAL- -BLOCOs- TAM (MB) TIPO

     1  hda1   *         63  4209029  4208967  2055.16  0C DOS FAT32 (L)
     2  hda2        4209030  4482134   273105   133.35  AE TROPIX Extended
     3  hda2a       4209093  4353614   144522    70.57  A9 TROPIX T1
     4  hda2b       4353678  4482134   128457    62.72  A9 TROPIX T1

Finalmente, vamos ativar a partiÃ§Ã£o ROOT, para possibilitar a carga do
sistema ("boot") atravÃ©s do gerenciador de carga (o "boot0"). Tecle
"a", e siga o seguinte diÃ¡logo:

fdisk\> a

Ãndice da partiÃ§Ã£o: 3

Disco "hda": 6149.88 MB (12594960 blocos), geo = (784, 255, 63, L)

IND. -DEV- A D -INÃCIO- --FINAL- -BLOCOs- TAM (MB) TIPO

     1  hda1   *         63  4209029  4208967  2055.16  0C DOS FAT32 (L)
     2  hda2        4209030  4482134   273105   133.35  AE TROPIX Extended
     3  hda2a  *    4209093  4353614   144522    70.57  A9 TROPIX T1
     4  hda2b       4353678  4482134   128457    62.72  A9 TROPIX T1

Uma vez conferida a tabela de partiÃ§Ãµes, podemos escrevÃª-la no disco
rÃ­gido atravÃ©s dos seguintes comandos:

fdisk\> w

Reescreve a tabela de partiÃ§Ãµes? (n): s

fdisk\> q

Saindo do editor de tabelas de partiÃ§Ãµes

boot\>

O Ãºnico comando "perigoso" Ã© o "w" (com a respectiva confirmaÃ§Ã£o),
pois todos os outros comandos apenas modificam a tabela de partiÃ§Ãµes
na memÃ³ria principal, sem atualizÃ¡-la no disco rÃ­gido.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 31

Portanto, vocÃª pode "brincar" Ã  vontade, criando e removendo
partiÃ§Ãµes, atÃ© que esteja satisfeito com a sua configuraÃ§Ã£o, dando
entÃ£o o "w" final.

Repare que os tamanhos dados (128 MB, 64 MB e 64 MB) nÃ£o foram
obedecidos exatamente; na realidade eles foram arredondados para
mÃºltiplos do tamanho do cilindro do disco. Como este disco tem um
cilindro razoavelmente grande (255 \* 63 = 16065 blocos \~= 7.8 MB), as
diferenÃ§as sÃ£o significativas. Um modo de evitar isto, Ã© usar o
comando "u", que impede o arredondamento.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 32

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 14                      *
     *                                                       *
     *  REDUZINDO O TAMANHO DE UMA PARTIÃÃO MS-DOS/Windows   *
     *                                                       *
     *********************************************************

Um dos casos mais freqÃ¼entes Ã© o de PCs que possuem apenas um disco
rÃ­gido totalmente ocupado com apenas uma partiÃ§Ã£o MS-DOS/Windows,
correspondente a "C:".

Neste caso, Ã  primeira vista, existem apenas 2 possibilidades para
obter espaÃ§o para partiÃ§Ãµes TROPIX: instalar um novo disco rÃ­gido,
ou entÃ£o salvar os seus arquivos MS-DOS/Windows e reinstalar o
MS-DOS/Windows em uma partiÃ§Ã£o de tamanho menor.

Uma terceira possibilidade consiste na reduÃ§Ã£o da partiÃ§Ã£o
MS-DOS/Windows em sua prÃ³pria localizaÃ§Ã£o (isto Ã©, sem destruir o
seu conteÃºdo). Isto pode ser realizado pelo comando "chsize" do
utilitÃ¡rio "dosmp". TambÃ©m Ã© possÃ­vel usar o programa "fips" do
LINUX, ou ainda o programa PARTITION MAGIC, da firma PowerQuest, se
vocÃª por acaso o possui.

Antes do uso do comando "chsize", para a reduÃ§Ã£o do tamanho da
partiÃ§Ã£o MS-DOS/Windows, Ã© essencial verificar a sua integridade e
desfragmentÃ¡-la. A verificaÃ§Ã£o da integridade pode ser feita pelos
utilitÃ¡rios CHKDSK ou SCANDISK (do MS-DOS/Windows) ou ainda NDD (Norton
Disk Doctor) dos "NORTON Utilities". A defragmentaÃ§Ã£o pode ser feita
pelo utilitÃ¡rio DEFRAG (do MS-DOS/Windows), ou o SPEED DISK dos "NORTON
Utilities".

Lembre-se de que os programas de desfragmentaÃ§Ã£o possivelmente NÃO
movem o arquivo de "swap" do MS-DOS/Windows. VocÃª deve removÃª-lo
(usando o "Control Panel") e posteriormente reinstalÃ¡-lo.

Se vocÃª usa IMAGE ou MIRROR, o Ãºltimo setor da partiÃ§Ã£o contÃ©m um
arquivo "oculto" de nome "`\image`{=tex}.idx" ou
"`\mirorsav`{=tex}.fil". VocÃª deve remover este arquivo (usando
"attrib" e "del"). Ele serÃ¡ recriado na prÃ³xima vez que vocÃª executar
IMAGE ou MIRROR (assim esperamos, nÃ£o testamos).

Outra fonte de problemas sÃ£o arquivos de nome "*`\desktop`{=tex}.*", os
quais o Windows nÃ£o move: eles devem ser salvos e posteriormente
restaurados.

Se vocÃª usa um sistema de arquivos comprimido com "Stacker",
"SuperStor", "Doublespace", ..., possivelmente (?) "chsize" nÃ£o irÃ¡
funcionar. NÃ£o testamos "chsize" nestes casos (nem sabemos se PARTITION
MAGIC os suporta).

ApÃ³s a desfragmentaÃ§Ã£o, insira o CDROM ou o disquete de BOOT do
TROPIX e carregue o sistema (conforme o capÃ­tulo 8), entrando no modo
multiusuÃ¡rio.

Retire o disquete de BOOT (se vocÃª estÃ¡ instalando atravÃ©s de
disquete) e insira um disquete (por exemplo MS-DOS/Windows), e

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 33

monte-o atravÃ©s de

     mount /dev/fd0 /fd0

Este disquete destina-se para armazenar o superbloco original do sistema
de arquivos MS-DOS/Windows para o caso de eventuais problemas.

Em seguida, tecle

     cd /fd0
     dosmp /dev/hda1

onde "/dev/hda1" deve ser substituÃ­do pela partiÃ§Ã£o correspondente ao
sistema de arquivos MS-DOS/Windows em questÃ£o (em geral serÃ¡ o
prÃ³prio "/dev/hda1", que corresponde Ã  unidade "C:").

Teclando

     chsize

obtemos (por exemplo):

     Tamanho atual da partiÃ§Ã£o DOS            = 511.84 MB
     Tamanho atual do sistema de arquivos DOS = 511.84 MB
     EspaÃ§o livre disponÃ­vel ao final         = 427.26 MB

Verifique se o espaÃ§o livre disponÃ­vel Ã© suficiente para a nova
partiÃ§Ã£o desejada. No nosso exemplo, temos espaÃ§o suficiente para o
caso tÃ­pico de 128 MB (427.26 \> 128). Lembre-se naturalmente de deixar
algum espaÃ§o para futuros (novos) arquivos DOS.

Para liberarmos 128 MB (que serÃ£o usados para a nova partiÃ§Ã£o a ser
criada para o TROPIX), devemos teclar

     rw
     chsize -s 128

e obteremos (por exemplo):

     Tamanho atual da partiÃ§Ã£o DOS            = 511.84 MB
     Tamanho atual do sistema de arquivos DOS = 511.84 MB
     EspaÃ§o livre disponÃ­vel ao final         = 427.26 MB

     Tamanho novo da partiÃ§Ã£o DOS             = 382.03 MB
                                                (782401 blocos)
     Tamanho novo do sistema de arquivos DOS  = 382.03 MB
     Tamanho da nova partiÃ§Ã£o (a ser criada)  = 129.81 MB
                                                (265856 blocos)

     Continua? (n):

Repare que os valores nÃ£o sÃ£o exatamentos os pedidos, em virtude de
arredondamentos para cilindros inteiros.

Se concordarmos com os valores dados, devemos teclar "s" e anotar os
valores dados: tamanho novo da partiÃ§Ã£o DOS = 382.03 MB, 782401 blocos
e tamanho da nova partiÃ§Ã£o (a ser criada) = 129.81 MB, 265856 blocos.

O comando "dosmp" guarda o superbloco original do sistema de arquivos
DOS no arquivo "dos\_sb" do diretÃ³rio corrente (no caso, no disquete
montado), para o caso de eventuais problemas.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 34

Em seguida, saÃ­mos do "dosmp" (com "q") e do TROPIX (com "reboot").

Entre novamente no sistema MS-DOS/Windows, e assegure-se de que ele
continua funcionando corretamente. Verifique a integridade do sistema de
arquivos (normalmente "C:") e se todos os seus arquivos continuam
acessÃ­veis.

Se surgir ALGUM PROBLEMA com o sistema MS-DOS/Windows, restaure o
sistema de arquivos original, recarregando o TROPIX e executando os
comandos

     mount /dev/fd0 /fd0
     cd /fd0
     dd if=dos_sb of=/dev/hda1

com o disquete no qual foi armazenado o superbloco original do sistema
DOS. Neste caso, comunique-nos (atravÃ©s do endereÃ§o eletrÃ´nico do
capÃ­tulo 1) a falha do "chsize".

Uma vez constatado que o sistema MS-DOS/Windows estÃ¡ funcionando
corretamente, utilize o utilitÃ¡rio "fdisk" do TROPIX (conforme o
capÃ­tulo 13), para alterar a tabela de partiÃ§Ãµes.

Inicialmente, altere o tamanho da partiÃ§Ã£o DOS (utilizando o comando
"m"). O novo tamanho (valor em blocos) deve corresponder exatamente ao
tamanho anotado acima (no caso, 382.03 MB, 782401 blocos).

Finalmente, crie a partiÃ§Ã£o TROPIX no espaÃ§o liberado, conforme o
exemplo do capÃ­tulo 13 (no caso, 129.81 MB, 265856 blocos).

Pronto! JÃ¡ Ã© hora de instalar o TROPIX nas novas partiÃ§Ãµes, conforme
o capÃ­tulo 15.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 35

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 15                      *
     *                                                       *
     *     INSTALAÃÃO DO TROPIX EM PARTIÃÃES PRÃPRIAS        *
     *                                                       *
     *********************************************************

Este Ã© o melhor modo, pois oferece o melhor desempenho e possibilita a
instalaÃ§Ã£o do "boot0", um gerenciador de "boot". Este gerenciador
permite a escolha do sistema operacional a carregar (de modo que TROPIX
possa ser carregado sem a utilizaÃ§Ã£o de CDROM ou disquete). Ele jÃ¡
foi testado com LINUX, FreeBSD e
DOS/WinXP/Win2000/WinNT/Win98/Win95/Win3.x.

Se vocÃª estÃ¡ lendo este capÃ­tulo, supomos que jÃ¡ possua espaÃ§o em
disco para partiÃ§Ãµes TROPIX e jÃ¡ saiba como utilizar o editor de
partiÃ§Ãµes "fdisk".

A idÃ©ia consiste em criar duas ou mais partiÃ§Ãµes para o TROPIX. O
mÃ­nimo Ã© a criaÃ§Ã£o de uma partiÃ§Ã£o ROOT. Recomendamos, no entanto,
criar pelo menos mais uma, HOME, para conter os arquivos particulares
dos usuÃ¡rios.

Se vocÃª tiver 128 MB disponÃ­veis, sugerimos 64 MB para ROOT e 64 MB
para HOME; estes tamanhos serÃ£o suficientes inclusive para a interface
grÃ¡fica X-Window. Caso tenha mais espaÃ§o disponÃ­vel, pode aumentar os
tamanhos das partiÃ§Ãµes, ou atÃ© criar partiÃ§Ãµes adicionais.

As etapas da instalaÃ§Ã£o sÃ£o as seguintes:

1.  Crie as partiÃ§Ãµes para o TROPIX atravÃ©s do editor de partiÃ§Ãµes
    "fdisk" (veja o capÃ­tulo 13). NÃO esqueÃ§a de "ativar" a
    partiÃ§Ã£o ROOT. NÃO Ã© necessÃ¡rio que a partiÃ§Ã£o ROOT (na qual
    serÃ¡ dado o "boot") fique no primeiro disco.

    Sugerimos criar uma partiÃ§Ã£o estendida do tipo TROPIX para conter
    as diversas partiÃ§Ãµes necessÃ¡rias/desejadas; isto no entanto nÃ£o
    Ã© necessÃ¡rio: se for mais conveniente para o seu caso, as
    partiÃ§Ãµes TROPIX podem tambÃ©m ser do tipo "regular"
    ("primÃ¡ria"), ou entÃ£o partiÃ§Ãµes lÃ³gicas dentro de uma
    partiÃ§Ã£o estendida do tipo DOS. Se vocÃª tiver mais de um disco,
    Ã© interessante distribuir as vÃ¡rias partiÃ§Ãµes pelos vÃ¡rios
    discos.

2.  Insira o CDROM ou disquete de BOOT do TROPIX e carregue o sistema
    (conforme o capÃ­tulo 8). Entre no modo multiusuÃ¡rio.

3.  VÃ¡ para o diretÃ³rio "/usr/etc/install" (use o comando "cd
    /usr/etc/install"). Inicie a instalaÃ§Ã£o, atravÃ©s do comando
    "install". Esta etapa gera sistemas de arquivos TROPIX nas
    partiÃ§Ãµes escolhidas e copia os arquivos fundamentais do TROPIX
    para o disco rÃ­gido. Siga as instruÃ§Ãµes.

    Se vocÃª deseja conservar uma versÃ£o antiga do sistema de arquivos
    HOME, responda afirmativamente a pergunta \"Deseja

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 36

      conservar a versÃ£o antiga de HOME?", e durante  a  cÃ³pia  dos
      arquivos nÃ£o permita a reescrita dos arquivos ".profile".

ParabÃ©ns! O TROPIX jÃ¡ estÃ¡ instalado e operacional em seu disco
rÃ­gido.

Se vocÃª NÃO instalou o gerenciador de "boot": para executar o TROPIX,
recarregue o sistema com o CDROM ou disquete BOOT inserido, e no
"prompt"

     boot>

tecle `<enter>`{=html}. Se o sistema for recarregado sem o CDROM nem
disquete serÃ¡ carregado o sistema operacional "normal" (por exemplo
Windows 95/98).

Se vocÃª INSTALOU o gerenciador: apÃ³s a recarga do sistema o
gerenciador imprime uma lista de partiÃ§Ãµes "ativas" dos seus diversos
discos rÃ­gidos, e espera vocÃª teclar o Ã­ndice da partiÃ§Ã£o desejada.
A partiÃ§Ã£o "default" pode ser modificada atravÃ©s do comando "edboot".

Para sair do sistema TROPIX, use "shutdown".

Se o gerenciador de "boot" NÃO funcionar, recarregue o TROPIX atravÃ©s
do CDROM ou disquete BOOT (entrando no modo multiusuÃ¡rio) e restaure o
gerenciador original, executando o comando do tipo

             cat /etc/boot/mbr >/dev/hda

e comunique-nos (atravÃ©s do endereÃ§o eletrÃ´nico do capÃ­tulo 1) a
falha do "boot0".

Para facilitar a instalaÃ§Ã£o futura de uma nova versÃ£o do TROPIX,
recomendamos colocar seus arquivos particulares apenas no seu diretÃ³rio
"home" (nome de arquivos comeÃ§ando por "/home/...").

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 37

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 16                      *
     *                                                       *
     *          CONFIGURAÃÃO DOS CONTROLADORES USB           *
     *                                                       *
     *********************************************************

O TROPIX (na versÃ£o atual) suporta controladores USB dos padrÃµes UHCI,
OHCI e EHCI.

HÃ¡ previsÃ£o de atÃ© 8 controladores ("usb0" a "usb7"); o sistema vem
configurado com os controladores "usb0" a "usb3" habilitados e os demais
desabilitados.

Isto pode ser alterado (somente para esta execuÃ§Ã£o do sistema)
atravÃ©s da modificaÃ§Ã£o de parÃ¢metros durante a carga do sistema;
responda afirmativamente Ã  pergunta

        Deseja modificar parÃ¢metros? (n):

tal como mencionado no capÃ­tulo 8, e altere os valores de "usb0" a
"usb7" para 0 ou 1.

Para a habilitaÃ§Ã£o/desabilitaÃ§Ã£o dos controladores (de modo
permamente) use o comando "edscb" (Use "man scb" e "man edscb").

Para verificar se o controlador USB estÃ¡ sendo reconhecido
corretamente, acompanhe as mensagens durante a carga do sistema (ou
entÃ£o use o comando "dmesg" posteriormente).

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 38

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 17                      *
     *                                                       *
     *                      E AGORA ...?                     *
     *                                                       *
     *********************************************************

Uma vez com o sistema implantado e em funcionamento, temos todos os
manuais do TROPIX (em portuguÃªs) Ã  disposiÃ§Ã£o atravÃ©s do
utilitÃ¡rio "man". AlÃ©m disto, todos os comandos fornecem um pequeno
resumo de sua utilizaÃ§Ã£o atravÃ©s da opÃ§Ã£o "-H" (por exemplo "passwd
-H").

Para consultar o manual do utilitÃ¡rio "passwd" (por exemplo), tecle
"man passwd". Para avanÃ§ar/retroceder pelas vÃ¡rias pÃ¡ginas dos
manuais, temos os comandos \<\^D\>, \<\^U\>. Para encerrar a execuÃ§Ã£o
de "man", use "q". Experimente "man man".

Recomendamos inicialmente a modificaÃ§Ã£o da senha da conta "root" e a
criaÃ§Ã£o de contas regulares (isto Ã©, NÃO superusuÃ¡rios). Para a
modificaÃ§Ã£o de senhas, utilize o comando "passwd"; para a
criaÃ§Ã£o/gerÃªncia de contas, use o comando "edusr".

TambÃ©m uma tarefa importante Ã© a atualizaÃ§Ã£o do arquivo
"/etc/fstab", que contÃ©m informaÃ§Ãµes dos sistemas de arquivos a
montar. Leia o manual de "fstab" (fmt), "getmntent" (libc) e "mount"
(cmd). Em particular, se vocÃª nÃ£o tiver a partiÃ§Ã£o HOME, remova a
linha correspondente de "/etc/fstab".

De vez em quando (digamos, uma vez por semana) Ã© interessante verificar
a integridade dos sistemas de arquivos. Para tanto, apÃ³s a carga do
sistema (ainda em modo "monousuÃ¡rio"), utilize o comando "fsck". Repare
que o arquivo "/etc/fstab" tambÃ©m controla os sistemas de arquivos
examinados por "fsck" (convÃ©m colocar o "/dev/root" como o Ãºltimo da
lista). Para obter uma lista de todas as partiÃ§Ãµes presentes nos
diversos discos do seu computador, use "prdisktb".

AtravÃ©s do comando "edscb" vocÃª pode alterar o nome do computador
("nodename") e acertar as portas/IRQs dos seus dispositivos (portas
seriais, paralelas, "ethernet", ...). Use "man scb" e "man edscb".

O TROPIX Ã© distribuÃ­do com o DMA dos controladores IDE desligados,
pois com certos controladores podem surgir problemas. Experimente
ligÃ¡-lo atravÃ©s de "dmaenable=1", inicialmente durante o "boot" para
testar, e se funcionar adequadamente, no arquivo "/tropix" atravÃ©s do
utilitÃ¡rio "edscb". Com isto, vocÃª aumentarÃ¡ a performance dos seus
discos rÃ­gidos IDE.

Leia o capÃ­tulo 26, onde Ã© dada uma lista dos principais comandos do
TROPIX.

Aprenda a usar o "histÃ³rico" do "sh". Ele permite reexecutar comandos,
inclusive com modificaÃ§Ãµes (cada linha do histÃ³rico pode ser editada
com os mesmos comandos do "vi", antes de ser reexecutada).

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 39

Esta versÃ£o do TROPIX jÃ¡ possui o utilitÃ¡rio "sbwave" para tocar
mÃºsicas PCM atravÃ©s de placas "Sound Blaster" ISA, veja o manual.

Durante a instalaÃ§Ã£o, a INTERNET jÃ¡ Ã© configurada para funcionar no
modo interno ("loopback"), o que Ã© necessÃ¡rio pela Interface GrÃ¡fica
X-Window. Para configurar a INTERNET para o uso com outros dispositivos,
use "man internet".

Para a montagem de sistemas de arquivos remotos atravÃ©s do Sistema de
Arquivos NFS (Network File System), use "man nfs".

Leia o capÃ­tulo 18: ele menciona caracterÃ­sticas nÃ£o convencionais do
TROPIX, as quais incluÃ­mos no sistema por considerÃ¡-las Ãºteis.

Para instalar a Interface GrÃ¡fica X-Window, consulte os capÃ­tulos 19 a
22.

Para obter/compilar o cÃ³digo fonte do TROPIX, consulte os capÃ­tulos 23
e 24.

Naturalmente, este capÃ­tulo dÃ¡ apenas o resumo de uma direÃ§Ã£o geral
a tomar. O ideal Ã© consultar um livro de introduÃ§Ã£o ao UNIX.

Esperamos que o TROPIX lhe seja Ãºtil, tanto no aprendizado de sistemas
de filosofia UNIX, como na utilizaÃ§Ã£o de mais um sistema operacional.
Em caso de dÃºvidas ou relatos de erros, utilize o endereÃ§o eletrÃ´nico
do capÃ­tulo 1.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 40

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 18                      *
     *                                                       *
     *  CARACTERÃSTICAS E UTILITÃRIOS ORIGINAIS DO TROPIX    *
     *                                                       *
     *********************************************************

Embora o TROPIX seja um sistema de filosofia UNIX, hÃ¡ algumas
caracterÃ­sticas originais que nÃ£o sÃ£o encontradas em outros sistemas
deste tipo. A seguir sÃ£o dadas algumas destas originalidades:

1.  Na maioria dos sistemas UNIX, quando listamos um arquivo de vÃ¡rias
    pÃ¡ginas no vÃ­deo, ele "rola" fora da tela antes que possamos
    le-lo. Temos entÃ£o de usar o comando "more" na forma

              cat texto.txt | more

    ou entÃ£o,

              more texto.txt

    Isto Ã© o caso, tambÃ©m, se usamos o comando "ls -l" com diretÃ³rios
    contendo muitos arquivos.

    No TROPIX, isto nÃ£o Ã© necessÃ¡rio; a saÃ­da do vÃ­deo Ã© pausada
    quando ela completa o nÃºmero de linhas visÃ­veis. Para continuar a
    saÃ­da no vÃ­deo, basta teclar \<\^Q\>.

    Isto pode ser alterado atravÃ©s do comando "stty" (veja o respectivo
    manual).

2.  O utilitÃ¡rio "show": permite visualizar um arquivo de texto de
    forma conveniente no vÃ­deo, podendo avanÃ§ar/retroceder sobre o
    texto com comandos semelhantes ao do editor de textos "vi". Ã
    especialmente Ãºtil para examinar a saÃ­da de um programa, usando um
    "pipe" (veja o manual).

3.  O comando "gar": este utilitÃ¡rio Ã© uma extensÃ£o do "tar", padrÃ£o
    do mundo UNIX. O "gar", alÃ©m de criar/extrair coleÃ§Ãµes do formato
    "tar", extrair coleÃ§Ãµes do formato "cpio", ele
    cria/extrai/compara/adiciona coleÃ§Ãµes do formato prÃ³prio ("gar")
    com/sem compactaÃ§Ã£o. VocÃª certamente jÃ¡ utilizou o "gar" ao
    instalar o TROPIX (veja o manual).

4.  Os utilitÃ¡rios "cmptree/cptree"; permitem copiar/comparar/atualizar
    Ã¡rvores do sistema de arquivos locais ao prÃ³prio computadores
    (veja o manual).

5.  A famÃ­lia de utilitÃ¡rios "tcmpto": permite
    copiar/comparar/atualizar Ã¡rvores do sistema de arquivos de/entre o
    computador local e um computador remoto, atravÃ©s de protocolo
    prÃ³prio TCP/IP (veja o manual).

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 41

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 19                      *
     *                                                       *
     *       INTRODUÃÃO Ã INTERFACE GRÃFICA X-WINDOW         *
     *                                                       *
     *********************************************************

O sistema X-Window para o TROPIX Ã© uma interface grÃ¡fica baseada na
versÃ£o 4.7.0 distribuÃ­da pelo ConsÃ³rcio XFree86.

A presente versÃ£o inclui servidores especÃ­ficos para algumas das
placas grÃ¡ficas mais usuais. AlÃ©m disto, sÃ£o distribuÃ­dos os
clientes indispensÃ¡veis para o funcionamento mÃ­nimo do sistema.

Apesar de os monitores modernos possuÃ­rem circuitos de proteÃ§Ã£o
contra o uso com freqÃ¼Ãªncias horizontal e/ou vertical indevidas,
sempre existe teoricamente a possibilidade de danificar o seu monitor.

NÃS NÃO NOS RESPONSABILIZAMOS POR ESTES POSSÃVEIS DANOS AO SEU
MONITOR. VOCÃ ESTÃ INSTALANDO/UTILIZANDO A INTERFACE GRÃFICA DO
TROPIX SOB SUA PRÃPRIA RESPONSABILIDADE E RISCO!

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 42

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 20                      *
     *                                                       *
     *       CRIAÃÃO E INSTALAÃÃO DOS DISQUETES/ARQUIVOS     *
     *                 DA INTERFACE GRÃFICA                  *
     *                                                       *
     *********************************************************

Este capÃ­tulo contÃ©m informaÃ§Ãµes apenas para a instalaÃ§Ã£o atravÃ©s
de disquetes. Se vocÃª estÃ¡ instalando atravÃ©s de um CDROM, pode
pulÃ¡-lo.

A distribuiÃ§Ã£o da Interface GrÃ¡fica X-Window Ã© feita atravÃ©s da
coleÃ§Ã£o "xwin.tgz": obtenha-a na pÃ¡gina do TROPIX
("http://tropix.nce.ufrj.br").

Uma vez tendo obtida esta coleÃ§Ã£o, Ã© necessÃ¡rio preparar os 2
arquivos ou criar os 2 disquetes de 3Â½\". Ela contÃ©m os seguintes
arquivos:

                fdimage.exe
                xwin1.dsk
                xwin2.dsk

O arquivo "fdimage.exe" Ã© um utilitÃ¡rio de cÃ³pia para os Windows
(vocÃª provavelmente jÃ¡ o tem, obtido durante a instalaÃ§Ã£o do TROPIX
bÃ¡sico), e os arquivos restantes sÃ£o os conteÃºdos dos 2 disquetes.

Assim como no caso do TROPIX bÃ¡sico, se vocÃª possui uma partiÃ§Ã£o
DOS/Windows FAT16/32 ou NTFS em seu computador, a criaÃ§Ã£o dos
disquetes XWIN1 e XWIN2 pode ser dispensada. Siga o roteiro do capÃ­tulo
9 (substituindo "gar1" por "xwin1" e "xwin2").

Uma vez com os disquetes ou arquivos preparados, entre no sistema TROPIX
(como superusuÃ¡rio), vÃ¡ para o diretÃ³rio "/usr/etc/install", e
execute o comando

                install.xwin

e siga as suas instruÃ§Ãµes. O sistema necessita de cerca de 10 MB no
disco.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 43

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 21                      *
     *                                                       *
     *            CONFIGURAÃÃO DA INTERFACE GRÃFICA          *
     *                                                       *
     *********************************************************

Uma vez instalados todos os arquivos da Interface GrÃ¡fica X-Window (se
vocÃª estÃ¡ instalando atravÃ©s do CDROM isto Ã© automÃ¡tico, para o
caso de disquetes veja o capÃ­tulo anterior), vamos dar a seguir o
mÃ©todo passo a passo para a configuraÃ§Ã£o do sistema. Isto deve ser
feito como superusuÃ¡rio.

1.  ConfiguraÃ§Ã£o da "internet": Ela deverÃ¡ estÃ¡ ativa, pelo menos
    para acessos internos ("loopback"); isto normalmente, a instalaÃ§Ã£o
    do TROPIX jÃ¡ realiza. Para maiores detalhes, veja o manual
    "internet" (atravÃ©s do comando "man").

2.  EspecificaÃ§Ã£o do "mouse": O sistema vem configurado para o "mouse"
    PS/2.

    Para outros tipos de "mouse, o arquivo"/usr/xwin/conf/xconfig\"
    deverÃ¡ ser editado. Se o seu "mouse" for serial (COM1, COM2) ou
    USB, mova os dois caracteres "\#" das linhas do seu tipo de "mouse"
    para as duas linhas do "mouse" PS/2.

    Use o utilitÃ¡rio "dmesg" para verificar se, durante a carga do
    sistema, o seu "mouse" estÃ¡ sendo reconhecido.

3.  ExecuÃ§Ã£o do servidor no modo de 16 cores (4 bits). Inicialmente o
    arquivo de configuraÃ§Ã£o "/usr/xwin/conf/xconfig" estÃ¡ preparado
    para executar o servidor no modo grÃ¡fico do padrÃ£o VGA, de 16
    cores e resoluÃ§Ã£o de 640x480 e 800x600. Este modo deve funcionar
    com qualquer placa grÃ¡fica, e serÃ¡ sua (Ãºnica) opÃ§Ã£o caso a sua
    placa nÃ£o tenha sucesso nas tentativas abaixo.

    Para tanto, basta teclar o comando "startx" (sem ter alterado o
    arquivo de configuraÃ§Ã£o). O sistema iniciarÃ¡ com o fundo padrÃ£o
    do TROPIX, duas janelas "xterm", um relÃ³gio e um selecionador de
    "desktops". Em cada janela "xterm" Ã© executado o interpretador de
    comandos padrÃ£o "sh".

    Para voltar ao modo texto, a maneira mais simples Ã© teclar
    simultaneamente `<ctl-alt-bs>`{=html}.

    Este Ã© o modo mais bÃ¡sico de funcionamento do sistema X-Window; se
    ele nÃ£o funcionar envie-nos os arquivos "/var/log/xwin/xserver.log"
    e "/var/log/xwin/xclients.log" para o endereÃ§o eletrÃ´nico do
    capÃ­tulo 1.

4.  DeterminaÃ§Ã£o da placa grÃ¡fica: Uma vez funcionando no modo de 16
    cores, podemos verificar se existe a possibilidade de utilizar um
    servidor especÃ­fico para a sua placa grÃ¡fica. Isto proporcionarÃ¡
    a possibilidade de usar uma gama maior de

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 44

      cores,  e  outras  resoluÃ§Ãµes  (800x600, 1024x768, 1280x1024,
      ...).

      Dependendo da sua placa grÃ¡fica, podemos editar o arquivo  de
      configuraÃ§Ã£o  "/usr/xwin/conf/xconfig". Se for uma placa ATI,
      coloque em comentÃ¡rio as linhas:

                Driver          "svga"
                Device          "Generic VGA"

      colocando um "#" no inÃ­cio da linha, e tire o comentÃ¡rio  das
      linhas:

                Driver          "accel"
                Device          "ati"

      AlÃ©m  disto,  altere  o  nÃºmero  de bits por cor comentando a
      linha:

                DefaultColorDepth       4

      e tirando o "#" de uma das linhas (experimente):

                DefaultColorDepth       8
                DefaultColorDepth       16
                DefaultColorDepth       24

      Para cada tentativa, entre no modo grÃ¡fico teclando "startx",
      e  para  voltar  ao  modo  de  texto,  tecle  simultaneamente
      <ctl-alt-bs>.  Obtenha  infomaÃ§Ãµes  de  sucesso/insucesso  no
      arquivo "/var/log/xwin/xserver.log".

      As instruÃ§Ãµes sÃ£o semelhantes, se a sua placa for uma  NVIDIA
      ou TRIDENT, usando-se

                Device          "nv"
      ou
                Device          "trident"

5.  Se a sua placa grÃ¡fica nÃ£o for uma das acima, ou as tentativas
    acima nÃ£o tiveram sucesso, vocÃª poderÃ¡ apenas (na presente
    versÃ£o) usar o modo de 16 cores (4 bits).

6.  Para alterar de resoluÃ§Ã£o, tecle \<ctl-alt-+\> ou
    `<ctl-alt-->`{=html} ("+" e "-" do teclado numÃ©rico).

Uma vez funcionando, vocÃª poderÃ¡ tentar alterar o nÃºmero de cores e o
tamanho do seu "desktop". Em caso de nÃ£o conseguir, envie-nos os dois
arquivos do diretÃ³rio "/var/log/xwin", conforme acima.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 45

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 22                      *
     *                                                       *
     *          UTILIZAÃÃO BÃSICA DA INTERFACE GRÃFICA       *
     *                                                       *
     *********************************************************

Uma vez com o sistema em funcionamento, teremos (com jÃ¡ foi citado
acima), duas janelas "xterm", um relÃ³gio e um selecionador de
"desktops".

A pequena janela "xterm" superior Ã© a da "console", e nÃ£o deve ser
usada normalmente, pois nela serÃ£o escritas as mensagens de erro do
sistema operacional.

Para movimentar uma janela, clique e arraste o botÃ£o da esquerda do
"mouse" na moldura da janela.

Para alterar o tamanho de uma janela, clique e arraste o botÃ£o da
esquerda do "mouse" em um dos 4 cantos da janela (nem todas as janelas
admitem isto).

Para promover uma janela (isto Ã©, colocÃ¡-la na frente das demais),
clique o botÃ£o da esquerda na moldura da janela. Para rebaixÃ¡-la (isto
Ã©, colocÃ¡-la atrÃ¡s das demais), clique o botÃ£o da direita na moldura
da janela. Se vocÃª tiver um "mouse" de 3 botÃµes, pode tambÃ©m promover
uma janela com o botÃ£o do meio.

O botÃ£o da esquerda, clicado fora de qualquer janela, apresenta um
"menu" de utilitÃ¡rios, alÃ©m da opÃ§Ã£o para sair do modo grÃ¡fico
(retornando ao modo de texto). O botÃ£o da direita, clicado fora de
qualquer janela, apresenta uma lista das janelas ativas.

Tudo o que foi descrito atÃ© agora refere-se ao "desktop" 0. Clicando em
um outro selecionador de "desktop" (no canto inferior direito), vocÃª
terÃ¡ um novo espaÃ§o independente para a criaÃ§Ã£o de janelas. VocÃª
dispÃµe (na presente configuraÃ§Ã£o), de 6 "desktops".

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 46

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 23                      *
     *                                                       *
     *   OBTENÃÃO E INSTALAÃÃO DO CÃDIGO FONTE DO TROPIX     *
     *                                                       *
     *********************************************************

O cÃ³digo fonte do TROPIX Ã© distribuÃ­do atravÃ©s dos 3 arquivos
"kernel.tgz" (o nÃºcleo do sistema), "lib.tgz" (as bibliotecas) e
"cmd.tgz" (os utilitÃ¡rios). Tratam-se de coleÃ§Ãµes TAR comprimidas
atravÃ©s do utilitÃ¡rio "gzip".

Uma vez obtida uma coleÃ§Ã£o \"\*.tgz\" atravÃ©s de um navegador,
devemos descomprimi-la. Isto pode ser feito de diversos modos:

1.  Se vocÃª armazenou a coleÃ§Ã£o \"\*.tgz\" em um sistema de arquivos
    DOS/Windows FAT16/32, e estÃ¡ com o TROPIX instalado, pode
    acessÃ¡-la diretamente atravÃ©s do TROPIX, montando a partiÃ§Ã£o com
    um comando da forma

         mount /dev/hda1 /mnt

    Em seguida, descomprima-a com:

         cd /mnt/...                  (DiretÃ³rio do TROPIX)
         gunzip *.tgz                 (Nome da coleÃ§Ã£o)
         gar -ixv <*.tar              (Nome da coleÃ§Ã£o TAR obtida)
         rm *.tar                     (Remove a coleÃ§Ã£o TAR)

2.  Se a sua partiÃ§Ã£o DOS/Windows for NTFS (como ela Ã© somente de
    leitura), o procedimento acima deverÃ¡ ser efetuado apÃ³s a cÃ³pia
    do arquivo \"\*.tgz\" para uma partiÃ§Ã£o TROPIX.

3.  Se vocÃª estÃ¡ usando um sistema UNIX, deverÃ¡ usar os utilitÃ¡rios
    "gunzip" e "tar". Verifique os detalhes no seu sistema UNIX.

4.  Se vocÃª estÃ¡ apenas com Windows, pode descomprimir a coleÃ§Ã£o com
    o utilitÃ¡rio "Winzip" e ler cada um dos programas atravÃ©s dos
    utilitÃ¡rios "Notepad", "Wordpad" ou "Word", entre outros.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 47

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 24                      *
     *                                                       *
     *           COMPILAÃÃO DO NÃCLEO, BIBLIOTECAS           *
     *                E UTILITÃRIOS DO TROPIX                *
     *                                                       *
     *********************************************************

Abaixo damos orientaÃ§Ãµes para compilar os diversos componentes da
distribuiÃ§Ã£o do cÃ³digo fonte do TROPIX:

1.  NÃCLEO DO SISTEMA: Uma vez com a Ã¡rvore do nÃºcleo instalada no
    TROPIX, vocÃª poderÃ¡ compilar os diversos mÃ³dulos que a integram:
    "boot/boot0", "boot/boot1", "boot/boot2" e "kernel".

    Em cada um dos diretÃ³rios hÃ¡ o "Makefile" para controlar a
    respectiva compilaÃ§Ã£o.

    Repare que no diretÃ³rio "kernel" hÃ¡ o arquivo "scbfile.v" que
    contÃ©m parÃ¢metros para configurar o seu nÃºcleo em particular
    (veja "edscb" (cmd)).

2.  BIBLIOTECAS: Na raiz da Ã¡rvore hÃ¡ um "Makefile" para a
    compilaÃ§Ã£o de todas as 4 bibliotecas. Se for desejado, pode ser
    compilada cada uma delas separadamente (indo para o diretÃ³rio
    correspondente).

3.  UTILITÃRIOS: Na raiz da Ã¡rvore hÃ¡ um "Makefile" para a
    compilaÃ§Ã£o de todos os utilitÃ¡rios. Se for desejado, pode ser
    compilado cada um deles separadamente (indo para o diretÃ³rio
    correspondente).

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 48

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 25                      *
     *                                                       *
     *              O USO DO EDITOR DE TEXTOS "VI"           *
     *                                                       *
     *********************************************************

O utilitÃ¡rio "vi" Ã© o editor de textos "padrÃ£o" dos sistemas
operacionais de filosofia UNIX. Neste capÃ­tulo serÃ¡ dada uma pequena
introduÃ§Ã£o ao seu uso, suficiente para realizar alteraÃ§Ãµes nos
arquivos de configuraÃ§Ã£o (que eventualmente sejam necessÃ¡rias),
durante a instalaÃ§Ã£o do TROPIX.

Maiores detalhes poderÃ£o ser vistos (posteriormente com o sistema em
funcionamento regular), atrÃ¡ves de "man vi" ou ainda "man -g vi".

Para editar um arquivo (por exemplo, de nome "abc"), teclamos "vi abc",
e o "vi" inicia o seu funcionamento mostrando a primeira pÃ¡gina do
arquivo "abc", com o cursor no primeiro caractere da primeira linha.

Podemos entÃ£o utilizar os seguintes comandos (repare que o cursor
indica onde o comando serÃ¡ executado):

     <sp>       AvanÃ§a (o cursor de) um caractere na linha.
     <bs>       Retrocede um caractere na linha.
     "-"        Retrocede uma linha no arquivo.
     <enter>    AvanÃ§a uma linha no arquivo.
     <^D>       AvanÃ§a meia pÃ¡gina no arquivo.
     <^U>       Retrocede meia pÃ¡gina no arquivo.
     "1g"       Retrocede para o inÃ­cio do arquivo.
     "g"        AvanÃ§a para o final do arquivo.

     "i"        Insere texto antes do cursor (atÃ© um <esc>).
     "a"        Insere texto apÃ³s o cursor (atÃ© um <esc>).
     "o"        Cria novas linhas e insere texto (atÃ© um <esc>).
     "x"        Remove o caractere indicado pelo cursor.
     "dd"       Remove uma linha.
     "yyp"      Copia uma linha.

     "/..."     Procura a cadeia "..."
     "n"        Procura a ocorrÃªncia seguinte da cadeia.
     "N"        Procura a ocorrÃªncia anterior da cadeia.

     "."        Repete o Ãºltimo comando de ediÃ§Ã£o.
     "u"        Desfaz o Ãºltimo comando de ediÃ§Ã£o.

     ":w"       Atualiza o arquivo.
     ":q"       Sai do "vi" (somente se o arquivo estÃ¡ atualizado).
     ":q!"      Sai do "vi", sem atualizar o arquivo.

Repare que o arquivo sendo editado ("abc" no caso) sÃ³ serÃ¡ atualizado
quando for dado o comando ":w". Se foi feita acidentalmente alguma
modificaÃ§Ã£o indesejada, podemos sair do "vi" com o comando ":q!",
conservando o arquivo em sua forma original.

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 49

     *********************************************************
     *                                                       *
     *                      CapÃ­tulo 26                      *
     *                                                       *
     *     UMA LISTA DOS PRINCIPAIS COMANDOS DOS TROPIX      *
     *                                                       *
     *********************************************************

Para a sua comodidade, damos abaixo uma lista alfabÃ©tica dos principais
comandos do TROPIX, juntamente com uma breve descriÃ§Ã£o de cada um.
Para obter mais informaÃ§Ãµes sobre um comando "x" (por exemplo), use
"man x".

     a2ps      - conversor de arquivos texto em PostScript
     as        - montador para INTEL-80386/486/PENTIUM
     bison     - gerador de analisadores sintÃ¡ticos do GNU
     c         - escreve as linhas de um arquivo em vÃ¡rias colunas
     cat       - concatena e copia arquivos
     cc        - compilador para a linguagem "C"
     cdplay    - reproduz faixas de CDs
     cdtowave  - extrai faixas de CDs
     chgrp     - troca a identificaÃ§Ã£o do grupo de arquivos
     chmod     - modifica a permissÃ£o de acesso de arquivos
     chown     - troca a identificaÃ§Ã£o do dono (UID) de arquivos
     clear     - limpa a tela do terminal
     clr       - limpa a tela do terminal
     cls       - limpa a tela do terminal
     cmp       - compara pares de arquivos
     cmpobj    - compara pares de mÃ³dulos objeto
     cmptree   - compara Ã¡rvores
     comm      - seleciona ou rejeita linhas comuns a dois arquivos
                 ordenados
     coremap   - imprime um mapa de alocaÃ§Ã£o da memÃ³ria
     cp        - copia arquivos
     cpfs      - copia sistemas de arquivos
     cptree    - copia uma Ã¡rvore
     crypt     - codifica/decodifica arquivos
     data      - mostra/atualiza a data/hora corrente do sistema
     dc        - calculador de mesa com aritmÃ©tica inteira
     dd        - copia e converte arquivos
     df        - informa sobre o espaÃ§o disponÃ­vel de sistemas de
                 arquivos
     diff      - comparador diferencial de arquivos
     dmesg     - imprime as mensagens iniciais de carga do nÃºcleo
     dosmp     - monta/processa um sistema de arquivos no formato
                 MS-DOS/Windows
     du        - informa sobre o uso de disco
     echo      - ecoa os arqumentos
     ed        - editor de textos orientado por linhas
     edboot    - gerencia "boot0" e "boot2"
     editscb   - edita/imprime o bloco de controle da INTERNET
     edobj     - editor de mÃ³dulos objeto
     edscb     - imprime/edita o bloco de controle do nÃºcleo do
                 TROPIX
     edusr     - gerencia as contas/senhas
     eject     - ejeta o meio removÃ­vel de um dispositivo

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 50

     ex        - editor visual de textos
     exportfs  - lista/atualiza a tabela "exports" do NFS
     fdc       - calculador de mesa com aritmÃ©tica flutuante
     fdisk     - imprime e/ou modifica a tabela de partiÃ§Ãµes
                 de um disco
     fdformat  - formata disquetes
     file      - tenta identificar o conteÃºdo de um arquivo
     finger    - obtÃ©m informaÃ§Ãµes sobre usuÃ¡rios remotos
     fsck      - verifica a consistÃªncia de sistemas de arquivos
     fsdefrag  - melhora a alocaÃ§Ã£o dos blocos de um sistema de
                 arquivos
     fsname    - consulta/atualiza nomes/volumes de sistemas de
                 arquivos
     ftp       - programa de cÃ³pia remota de arquivos da INTERNET
     gar       - utilitÃ¡rio para a criaÃ§Ã£o/atualizaÃ§Ã£o de coleÃ§Ãµes
                 de arquivos
     grep      - busca de padrÃµes em arquivos
     gunzip    - comprime ou expande arquivos
     gzip      - comprime ou expande arquivos
     help      - imprime resumos de utilizaÃ§Ã£o de comandos
     hpprint   - impressor para HP DeskJet (PCL)
     ifdef     - realiza prÃ©processamentos parciais
     includes  - descobre arquivos incluÃ­dos
     kill      - envia sinais a processos
     lasttime  - lista os nomes de arquivos modificados recentemente
     lc        - lista o conteÃºdo de diretÃ³rios
     ld        - link-editor de mÃ³dulos objeto
     ldshlib   - carrega/descarrega uma biblioteca compartilhada
     linkoptim - substitui arquivos duplicados por elos fÃ­sicos
     ln        - cria elos fÃ­sicos ou simbÃ³licos para arquivos
     ls        - lista caracterÃ­sticas de arquivos e conteÃºdos de
                 diretÃ³rios
     mail      - recebe ou envia cartas do correio eletrÃ´nico
     make      - gerenciador de manutenÃ§Ã£o de programas
     man       - mostra um manual na tela do terminal/vÃ­deo/janela
     mkdev     - cria/atualiza os dispositivos de "/dev"
     mkdir     - cria diretÃ³rios
     mkfifo    - cria FIFOs
     mkfs      - gera um sistema de arquivos
     mklib     - cria/atualiza bibliotecas de mÃ³dulos objeto
     mknod     - cria um arquivo especial
     mount     - monta um sistema de arquivos
     mv        - move (troca o nome de) arquivos
     mvtree    - move (troca o nome) de uma Ã¡rvore/diretÃ³rio
     nettime   - obtÃ©m a data/hora corrente de um nÃ³ remoto
     nice      - executa um comando com prioridade modificada
     nm        - imprime a tabela de sÃ­mbolos de mÃ³dulos objeto
     nohup     - executa um comando imune ao sinal SIGHUP
     pallwd    - imprime todos os diretÃ³rios correntes
     passwd    - altera a senha do usuÃ¡rio
     paste     - une linhas de vÃ¡rios arquivos
     ping      - teste de acesso a um nÃ³ remoto
     pop3      - acessa uma caixa postal remota atravÃ©s do
                 protocolo POP3
     pr        - imprime arquivos
     prdisktb  - Imprime a tabela de discos/partiÃ§Ãµes
     prsync    - imprime o estado da sincronizaÃ§Ã£o dos processos
     ps        - imprime informaÃ§Ãµes sobre processos
     pwd       - imprime o diretÃ³rio corrente
     reboot    - Encerra o uso do TROPIX, e recarrega o computador
     rlogin    - entra em sessÃ£o em um nÃ³ remoto
     rm        - Remove arquivos
     rmdir     - remove diretÃ³rios
     rmtree    - remove Ã¡rvores

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 51

     sbvol     - controla o volume da placa de som SB-16
     sbwave    - Toca mÃºsica PCM atravÃ©s da placa de som SB-16
     semafree  - libera o semÃ¡foro pelo qual o processo estÃ¡
                 esperando
     setmode   - atribui as proteÃ§Ãµes corretas aos arquivos do
                 sistema
     sh        - interpretador de comandos
     show      - mostra um arquivo na tela do terminal
     shutdown  - reinicializa o computador apÃ³s um certo tempo
     size      - imprime tamanhos e caracterÃ­sticas de mÃ³dulos
                 objeto
     sleep     - suspende a execuÃ§Ã£o por um intervalo de tempo
     sort      - ordena e/ou intercala arquivos
     sroff     - formatador de textos
     strip     - remove as tabelas de sÃ­mbolos de mÃ³dulos-objeto
     stty      - consulta/altera parÃ¢metros de terminais/vÃ­deos
     su        - muda de conta temporariamente
     subst     - busca/substitui cadeias em vÃ¡rios arquivos
     sync      - Atualiza os blocos do cache nos discos
     sysmap    - desenha um mapa de uso de alguns recursos do
                 sistema (programa grÃ¡fico)
     tac       - descompila a descriÃ§Ã£o instalada de um terminal/
                 vÃ­deo
     tail      - obtÃ©m a parte final de um arquivo
     tcmpfrom  - comparaÃ§Ã£o/atualizaÃ§Ã£o remota de Ã¡rvores
                 (caminhando Ã¡rvores remotas)
     tcmpto    - comparaÃ§Ã£o/atualizaÃ§Ã£o remota de Ã¡rvores
                 (caminhando Ã¡rvores locais)
     tcpfrom   - cÃ³pia remota de Ã¡rvores (caminhando Ã¡rvores
                 remotas)
     tcpto     - cÃ³pia remota de Ã¡rvores (caminhando Ã¡rvores
                 locais)
     tee       - copia a entrada padrÃ£o para diversos arquivos e a
                 saida padrÃ£o
     telnet    - comunica com um nÃ³ remoto utilizando o protocolo
                 TELNET
     test      - testa propriedades de arquivos
     textmap   - imprime uma tabela de programas reentrantes em uso
     tic       - compila e instala a descriÃ§Ã£o de um terminal/vÃ­deo
     touch     - Modifica os tempos de arquivos
     tpipe     - escreve arquivos remotos na saÃ­da padrÃ£o
     tr        - traduz caracteres
     tty       - imprime o nome do terminal/vÃ­deo
     umount    - desmonta sistemas de arquivos
     uname     - imprime a identificaÃ§Ã£o do sistema
     uniq      - indica linhas repetidas de um arquivo
     untext    - libera os recursos de programas reentrantes
     uptime    - fornece o tempo decorrido desde o Ãºltimo "boot"
     vi        - editor visual de textos
     walk      - caminha em Ã¡rvores do sistema de arquivos
     wc        - contador de pÃ¡ginas, linhas, palavras e caracteres
     who       - informa quem estÃ¡ no sistema
     write     - escreve mensagens para um outro usuÃ¡rio
     xcoremap  - desenha um mapa de alocaÃ§Ã£o da memÃ³ria
                 (programa grÃ¡fico)
     xclock    - relÃ³gio analÃ³gico (programa grÃ¡fico)
     xcpu      - desenha o grÃ¡fico de uso da CPU
     xd        - "dump" em hexadecimal e ISO
     xdefrag   - Melhora a alocaÃ§Ã£o dos blocos de um sistema
                 de arquivos T1
     xedit     - editor de textos simples para o sistema X-Window
     xfm       - gerenciador grÃ¡fico de arquivos
     xmandel   - desenha as imagens fractais de Mandelbrot
     xpop3     - acessa uma caixa postal remota atravÃ©s do

Atualizado em 10.12.08 VersÃ£o 4.9.0

INSTALL (ref) TROPIX: Guia de InstalaÃ§Ã£o Pag. 52

                 protocolo POP3
     xpaint    - mostra uma imagem (gif, jpeg, bmp ou xpm) em uma
                 janela (programa grÃ¡fico)
     xterm     - Emulador de terminal ANSI para X-Window
     ziptool   - ferramenta para dispositivos Iomega ZIP

Atualizado em 10.12.08 VersÃ£o 4.9.0
