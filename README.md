# Estrutura Try-Catch

Estudando estrutura try-catch.

Especificando como funciona cada bloco: <br>
try - Execução de código que pode acarretar uma exceção. <br>
catch - Código a ser executado caso ocorra exceção. <br>

Exemplos: <br>

![exemplotrycatch1](https://user-images.githubusercontent.com/24979432/181860317-97e8fc7a-be54-43b6-9c82-f3d1fd213723.png)
<br>
No exemplo incluímos três registros em um array chamado vect sendo a posição 0 - Alex, 1 - Maria e 2 Bob.
Em seguida informamos a posição a ser lida e mostrada na tela pelo sysout vect na posição informada.
Aqui tudo funcionou normalmente. <br>


Neste segundo exemplo já se faz necessário o uso do tratamento de excessões, <br>
porque sem esse tratamento quando um erro acontece o programa termina de imediato. <br>
Olhe o exemplo: <br>

![exemplotrycatch4](https://user-images.githubusercontent.com/24979432/181861025-903fe954-23c0-4972-8ba1-3e671e74abbc.png)

<br>

A diferença aqui é que você consegue concluir o código mesmo quando um erro acontece <br>
repare que a linha 26 foi executada mesmo após o erro, diferente do exemplo anterior.
(O erro ocorre por conta da inserção de um caractere que não condiz com as posições de um array padrão.)
<br>
![exemplotrycatch2](https://user-images.githubusercontent.com/24979432/181860331-a79130f5-b473-48c5-bbc5-338426eb3e14.png)

<br>
E neste último exemplo tentamos acessar um posição que ainda não existe dentro do array, e ainda assim ele concluiu o código.
<br>

![exemplotrycatch3](https://user-images.githubusercontent.com/24979432/181860334-7c8e68b6-4a62-49ce-b7d6-27c1ac863d17.png)













