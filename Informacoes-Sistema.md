## Comandos para Gerenciamento do Sistema Operacional

Neste módulo aprederemos alguns comandos básicos para coletar informções do sistema 

Comando `uname -a` exibe informções sobre o sistema instalado, incluindo a versão do Kernel

![zip](img/topico06/01.png)

No comando `uname` não é possivel ver a distribuição, para isso existe o caminho `/etc/debian_version ` onde podemos ver qual é a distribuição do Linux

![zip](img/topico06/02.png)

-------------


Comando ` uptime ` através dele podemos ver a hora atual assim como o tempo que o sistema está em execução

![zip](img/topico06/03.png)

-------------

Comando ` top ` além de exibir quanto tempo a máquina está ligada, exibe também a quantidade de usuários que estão logados e o load average 

![zip](img/topico06/04.png)

-------------

Comando `free -m` exibe informações sobre a utilização de memória RAM e SWAP

![zip](img/topico06/05.png)

Podemos executar o comando `free -s 2` para atulizar o status a cada 2 segundos

![zip](img/topico06/06.png)


Para obter mais informações sobre o uso de memória, podemos acessar o arquivo `/proc/meminfo `

![zip](img/topico06/07.png)

-------------

Comando `df -h` exibe informações sobre o espaço livre/utilizado em disco


![zip](img/topico06/08.png)

O comando `du` exibe o tamanho ocupado em disco de arquivos e diretórios 

![zip](img/topico06/09.png)


![zip](img/topico06/10.png)

-------------

Comando `file` exibe o tipo de um determinado arquivo

![zip](img/topico06/11.png)

![zip](img/topico06/12.png)

-------------

Comandos `whoami`, `who` e `w` exibe informações de logons

![zip](img/topico06/13.png)