O objetivo do seu trabalho é fazer uma árvore de jogo para selecionar a melhor opção 
para jogar o jogo da velha.

Você pode fazer a interface de jogo em terminal. Pode colocar jogador contra máquina
ou máquina contra máquina.

Para simplificar sua vida existe um jogo similar ao jogo da velha, porém jogados 
com números de 1 a 9.
Dois jogadores se revezam em turnos escolhendo números de 1 a 9 sem repetição.
O primeiro jogador que conseguir uma combinação entre seus números que dê soma
15 ganha o jogo.

Esse jogo na verdade é equivalente ao jogo da velha pensado no seguinte tabuleiro:

    2|7|6
    9|5|1
    4|3|8

Observe que a soma entre quaisquer linha, coluna ou diagonal é 15.

Algumas outras referências você pode encontrar em
Jogo da velha: https://en.wikipedia.org/wiki/Tic-tac-toe
Árvores de Jogo: https://en.wikipedia.org/wiki/Game_tree

Obs: você não precisa implementar o minimax, basta criar a árvore de jogos 
e depois fazer a busca pelo ramo que dá a máquina a vitória em menos passos.
