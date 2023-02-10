
# Variáveis

Aqui estão algumas anotações sobre variáveis e também os tipos no GoLang.

 ## :green_book: Declaração de variável
 Em GoLang, temos algumas formas de declarar variáveis:
 
 - Temos a declaração com o valores com inicializadores (valores já definidos para ela);
 - Temos a declaração sem atribuição, no qual declaramos o tipo da variável;
 - Temos a declaração curta de variáveis, porém esta só pode ser usada dentro de funções;

#### Para fazer a declaração de uma variável em GoLang com inicializador, fazemos da seguinte forma:

    var x = 10
    
Onde o 10 pode ser qualquer valor permitido para o GoLang, como uma string, um valor com ponto flutuante, boolean, etc.

#### Para fazer a declaração de uma variável em GoLang sem atribuição de valor, fazemos da seguinte forma:

    var x int

Podemos também atribuir mais de uma variável para o mesmo tipo, porém, o tipo da variável sem fica ao final da declaração:    

    var x, y, z int

#### Para fazer a declaração curta de uma variável em GoLang, fazemos da seguinte forma:

    x := "Brunno Alberto"

Lembramos que essa forma de declaração só é permitida dentro de funções.