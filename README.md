# Atividade-NotebookLM

Atividade sobre IA Generativa e Machine Learn, onde foi ensinado a IA sobre regras do Shogi.

O Notebook tem o intuito de ensinar as regras, estratégias, fundamentos, jogadas e solucionar desafios de shogi.

Base de dados:

https://www.youtube.com/watch?v=OKycHqHpufM

https://www.youtube.com/watch?v=PivqpWs5BRc

https://shogi.cz/en/game-rules/

https://bostonshogi.com/files/IntroToShogi.pdf

https://www.youtube.com/watch?v=FKPMuNx8v60

Prompts testados:

Me explique as regras de shogi, como se eu não soubesse o que é o jogo. 

Resposta :

O Shogi, também conhecido popularmente como xadrez japonês, é um jogo de tabuleiro tradicional de estratégia muito dinâmico, desafiador e divertido
. Embora tenha semelhanças com o xadrez ocidental, ele possui regras revolucionárias que tornam as partidas únicas e muito movimentadas.
Para compreender o Shogi do zero, o funcionamento do jogo pode ser dividido nos seguintes pilares:
1. O Tabuleiro e as Peças
O jogo é disputado em um tabuleiro de 9 por 9 casas
. Diferente do xadrez que conhecemos, existem duas grandes particularidades visuais no Shogi:
Sem diferença de cor: As peças de ambos os jogadores têm o mesmo formato (pentágonos de madeira) e cor
.
Direção das pontas: Para saber de quem é a peça, basta olhar para onde ela está apontando
. As suas peças sempre apontam para a frente (em direção ao seu oponente), enquanto as dele apontam na sua direção
.
Kanjis: As peças possuem caracteres japoneses gravados em preto na parte superior para indicar sua identidade
. Quando são viradas ao contrário, revelam caracteres geralmente em vermelho que representam seu estado promovido
.
2. O Objetivo do Jogo
O objetivo principal é capturar o Rei do seu oponente, aplicando o xeque-mate (chamado de Tsumi em japonês)
.
Cheque (Oute): Ocorre quando o Rei está sob ameaça direta de captura no próximo turno
. O jogador ameaçado deve obrigatoriamente defender o Rei ou movê-lo para um local seguro
.
Xeque-mate (Tsumi): Se o Rei for atacado e não houver nenhuma jogada possível para salvá-lo, o jogo termina com a vitória de quem realizou o ataque
.
3. A Dinâmica do Turno (Mover ou Repor)
Os jogadores jogam alternadamente e nunca podem passar a vez
. Em cada turno, você deve obrigatoriamente escolher realizar uma destas duas ações:
Mover uma peça sua que já está no tabuleiro
.
Repor uma peça que você capturou anteriormente de volta ao jogo (essa mecânica especial é chamada de Drop)
.
A Incrível Regra de Reposição (Drops)
No Shogi, as peças que você captura do seu oponente não são eliminadas do jogo; elas passam a ser suas!
. Elas ficam guardadas ao seu lado (no campo de visão de ambos)
. No seu turno, em vez de mover, você pode "reciclar" uma dessas peças colocando-a em qualquer casa vazia do tabuleiro para lutar sob o seu comando
.
Existem apenas algumas poucas restrições para fazer essa reposição:
As peças capturadas sempre retornam ao tabuleiro com seu lado não promovido voltado para cima
.
Você não pode colocar uma peça em uma casa onde ela fique presa sem poder se mover no futuro (como posicionar um Peão ou Lança na última fileira, ou um Cavalo nas duas últimas fileiras)
.
Regra do Peão Duplo (Nifu): Você não pode repor um Peão em uma coluna vertical que já possua outro peão seu que não esteja promovido
.
Xeque-mate com Peão: Você não pode dar xeque-mate imediato ao oponente colocando um Peão diretamente do lado de fora
. No entanto, você pode dar xeque-mate repondo qualquer outra peça, e os peões que já estavam no tabuleiro podem dar mate normalmente
.
4. A Promoção das Peças
As três linhas horizontais mais distantes do seu lado (onde as peças do oponente começam) são a zona de promoção
.
Quando uma peça sua entra, sai ou se move dentro dessa área de três linhas, você pode escolher promovê-la no final do seu movimento
. Para promovê-la, você simplesmente vira a peça ao contrário para revelar o caractere gravado em vermelho
. A peça promovida ganha novas e mais poderosas movimentações
. A promoção é opcional na maioria dos casos, mas torna-se obrigatória caso a peça chegue a uma linha onde não teria mais nenhum movimento legal nos turnos seguintes
. As peças permanecem promovidas até que o oponente as capture; quando capturadas, elas voltam ao estado original não promovido
.
5. Como as Peças se Movem
Nenhuma peça (exceto o Cavalo) pode pular sobre outras peças que estejam bloqueando seu caminho
.
Rei: Move-se uma casa em qualquer direção (horizontal, vertical ou diagonal)
.
Peão: Anda apenas uma casa diretamente para a frente
. Ao ser promovido, move-se como um General de Ouro
.
Torre: Move-se quantas casas livres quiser em linha reta (frente, trás, esquerda ou direita)
. Quando promovida, além de manter seu movimento original, também ganha a habilidade de mover uma casa em qualquer diagonal (como o Rei)
.
Bispo: Move-se quantas casas livres quiser em qualquer uma das quatro direções diagonais
. Quando promovido, além do movimento original, também ganha a habilidade de mover uma casa na horizontal ou vertical (como o Rei)
.
General de Ouro: Move-se uma casa em qualquer direção, exceto nas diagonais traseiras (esquerda/direita para trás)
. Essa peça não se promove
.
General de Prata: Move-se uma casa na diagonal (em qualquer direção) ou uma casa diretamente para a frente
. Ao ser promovido, passa a se mover exatamente como um General de Ouro
.
Cavaleiro (ou Cavalo): Move-se em um formato de "L" longo (uma casa para a frente e uma na diagonal para a frente)
. É a única peça do jogo que pode saltar sobre outras
. Só pode mover-se para a frente
. Ao ser promovido, move-se como um General de Ouro
.
Lança: Move-se qualquer número de casas livres apenas diretamente para a frente (não recua e não anda para os lados)
. Ao ser promovida, move-se como um General de Ouro
.
 Guia de Estudo
 
Fundamentos Estritos e Movimentação: Uma revisão detalhada do tabuleiro de 9x9 casas
, da diferenciação das peças pela orientação de suas pontas
 e do objetivo supremo de aplicar o xeque-mate (Tsumi) ao Rei adversário
. O guia traz um resumo visual de como cada peça se move e como elas se transformam ao serem promovidas nas três últimas fileiras.

A Arte do Drop (Reposição) e Suas Restrições: 

Explicação completa de como recrutar peças capturadas para o seu próprio exército
, detalhando as regras cruciais que evitam jogadas ilegais, como a proibição de ter dois peões não promovidos na mesma coluna (Nifu)
 e a impossibilidade de aplicar xeque-mate imediato repondo um peão.

Princípios Estratégicos de um Mestre 5-Dan:

Os três pilares fundamentais para vencer qualquer jogo:
Abertura: Planejar o jogo e consolidar uma estrutura defensiva segura para o Rei, como o Crab Castle (Castelo Caranguejo)
 ou o Mino Castle.

Meio de Jogo:

Ser consistente com o plano inicial, focando na atividade e valor de troca das peças.

Fim de Jogo:

Concentrar as forças e focar unicamente em ameaçar o Rei oponente de forma implacável.

Táticas Avançadas de Peões e Garfos: 

O guia traz técnicas essenciais usadas por jogadores experientes para criar fraquezas na defesa inimiga, incluindo o Bottom Pawn (Peão de Base) para criar defesas sólidas conectando-se a um General de Ouro
, o Striking Pawn (Peão de Ataque) para desestabilizar as forças inimigas
 e o Dangling Pawn (Peão Suspenso) para preparar uma promoção vitoriosa no turno seguinte
.
