## Manipulação de Conteúdo com comandos Shell

`>>` permite redirecionar a saida para um arquivo, no nosso exemplo estamos denominando o arquivo de linhas.txt

![>>](img/topico03/01.png)


--------------

Comando `cat` permite visuliar o arquivo que criamos atenriormente

![cat](img/topico03/02.png)

--------------

Comando `more` permite visuliar arquivos página-a-página ou linha-a-linha utilizando respctivamente `Space` ou `Enter`

![more](img/topico03/03.png)

--------------

Comando `less` é o mais recomomentado dentre o que já foi mostrado, é um `more` melhorado pois permite utilizar a naveção de setas

![less](img/topico03/04.png)

No comando `less` utilizando a `/` é possível realizar pesquisas em um determinado arquivo

![less](img/topico03/05.png)


--------------

Comandos `tail` e `head` são uteis para visualização de logs, vendo respectivamente o fim e o início de um determinado arquivo de log

![tail-e-head](img/topico03/07.png)

![tail-e-head](img/topico03/06.png)

Utilizando o argumento `-n` especifico a quantilidade de linhas que quero visulizar no log

![tail-e-head](img/topico03/09.png)

--------------

## Redirecionadores

Para utilizar os redirecionadores basta utilizarmos "maior que" `>` ou "menor que" `<`

Redirecionando a saida do comando `ls -l` para o arquivo listagem-2.txt, utilizando `>` sobrescreve, já se utilizarmos `>>` adicionamos ao final do arquivo

![redirecionador](img/topico03/10.png)

--------------

Redirecionadores que tem a função de receber, menor que `<` ou `<<` 

Neste exemplo esteamos fazendo o comando `more` receber o conteúdo de linhas-2.txt

![redirecionador](img/topico03/13.png)


O redirecionador `<<` é utilizado para determinar o final de um "bloco" de dados

![redirecionador](img/topico03/16.png)