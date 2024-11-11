## Filtro de Conteúdo 

A utilização de filtros permite que informações que sejam enviadas para a saída padrão `stdout` apenas as informções relevantes. 

O comando ´grep´ pesquisa em arquivos ou em dua entrada padrão por uma sequência de caracteres informada 

![grep](img/topico04/01.png)

Utilizando o parâmetro `-v` imprime todas as linhas que não tenham a palavra informada

![grep](img/topico04/02.png)


Utilizando a expressão regular `^d` é possível filtrar todas as linhas que comecem com a letra d

![grep](img/topico04/03.png)

-----------------

Comando `wc` permite visulizar a quantidade de linhas, palavras e caracteres em um determinado arquivo

![wc](img/topico04/04.png)

Utilizando o parâmetro `nl` no comando `cat` visualizamos a quantidades de linhas  

![cat](img/topico04/05.png)

-----------------

O comando `cut` faz recorte em um determinado arquivo, sendo o `-d` o delimitador e o `-f` campo

 

![cut](img/topico04/06.png)

![cut](img/topico04/07.png)

-----------------

O comando `awk` é similar ao comando `cat` mostrado anteriormente, 

 ![awk](img/topico04/08.png)