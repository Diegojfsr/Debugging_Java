Apresentação e Visão Geral


Erros de programacao sao denominados de bugs e o processo de encontrar e corrigir
bugs e chamado de depuracao ou debugging.
De forma geral a depuracao e uma tarefa dificil e trabalhosa e a dificuldade varia de
acordo com o ambiente de desenvolvimento o que inclui a linguagem de programacao e as
ferramentas disponiveis como depuradores.

Existem duas grandes categorias que englobam a natureza do erro:

Erros de Sintaxe:

E um erro nas regras estabelecidas da linguagem:
- Parenteses, chaves, colchetes que abrem mas nao fecham.
- Duas instrucoes sem ponto e virgula entre elas.
- Uma palavra chave sendo usada numa posicao inesperada.


Erros de Semantica:

E um erro na logica do codigo em sua semantica, o codigo esta sintaticamente correto
porem nao faz o que se esperava dele.
- Tentar dividir um numero por uma String ou por Zero.
- Atribuir um valor incoerente a um tipo de dado. Ex: int n = "Camila";
- tentar fechar um arquivo que nao foi aberto.


Depuracao / Debugging

Linguagem de alto nivel tornam a depuracao mais facil pois fornecem mais ferramentas
para identificar erros como o tratamento de execoes.
Os depuradores funcionam assumindo o controle de tempo de exeucao de um programa
e permitindo que voce o observe e controle.
Para fazer isso ele mostra a pilha do programa e permite que voce a atravesse em
qualquer direcao. Qunado voce esta em um depurador obtem uma imagem mais completa
de um quadro de pilha do que quando olha os rastreamentos de pilha em uma mensagem de log.

Pilha de execucao de um programa Java/Stack Trace

Pilha de Execucao.
Toda invocao de metodo e empilhada em uma estrutura de dados que isola a
area de memoria de cada um. Quando um metodo termina(retorna) ele volta
para o metodo que o invocou.

Stack Trace.
E a matriz onde encontramos a pilha de excecucao da excecao.
Em outras palavras, podemos dizer que o rastreamento dapilha
busca(rastreio) para a proxima linha onde a excecao pode surgir.
