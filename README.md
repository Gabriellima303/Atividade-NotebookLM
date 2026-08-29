Link do NotebookLM : https://notebook.google.com/notebook/1dddf72f-2bd2-4906-bb47-4b4fc9e00e4a
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

Como saber qual é cada peça, pois não conheço os sinais

Resposta : 

Identificar as peças do Shogi sem conhecer os caracteres japoneses (Kanjis) é um dos maiores desafios para quem está começando, mas existem padrões visuais simples e alternativas modernas que tornam essa tarefa muito fácil
.
Abaixo, veja um guia prático para reconhecer cada peça pelos seus "sinais" visuais no modelo tradicional:
1. As Peças Principais (Ataque e Defesa Especial)
A Torre (飛 - Hisha): É uma das peças mais fáceis de identificar
. O caractere 飛 (que significa "voar") é muito complexo e cheio de traços simétricos nas laterais, lembrando as asas abertas de um pássaro ou de um inseto
. Quando promovida a Rei Dragão, ela revela o caractere de dragão (龍 ou 竜)
.
O Bispo (角 - Kaku): O caractere 角 (que significa "ângulo" ou "chifre") parece uma caixa quadrada dividida ao meio por uma linha vertical, com duas perninhas pontiagudas saindo por baixo
. Quando promovido a Cavalo de Dragão, ele revela o caractere 馬 (cavalo), marcado por quatro pontinhos na base que parecem as patas de um animal
.
2. Os Generais (O Coração da Defesa)
O General de Ouro (金 - Kin): O caractere 金 (ouro) é largo na base e muito simétrico
. A melhor forma de identificá-lo é pelo "chapéu" triangular no topo (que se parece com o telhado de uma casa: 𠆢) e linhas horizontais logo abaixo
. Ele nunca se promove
.
O General de Prata (銀 - Gin): Como também é feito de metal, a metade esquerda do seu caractere é idêntica à do General de Ouro (sendo uma versão espremida do caractere de metal)
. No entanto, a sua metade direita (艮) parece uma caixinha com uma perna inclinada
. Quando promovido, ele ganha um caractere vermelho (全) que se assemelha a um telhado com o caractere de rei ("王") embaixo
.
3. As Peças da Linha de Frente e Suporte
O Peão (歩 - Fu): É a menor peça do tabuleiro e a mais comum (você terá nove delas)
. Seu caractere 歩 é muito simples e lembra uma pessoa caminhando, com duas perninhas abertas embaixo
. Quando o Peão é promovido (Tokin), ele é virado e revela um caractere vermelho muito simples que se parece com a letra "t" cursiva ou um "y" de cabeça para baixo (と)
.
O Cavaleiro (桂 - Keima): O caractere 桂 possui uma nítida cruz do lado esquerdo (que representa o radical de madeira: 木) e dois traços horizontais paralelos sobrepostos do lado direito (圭)
.
A Lança (香 - Kyousha): O caractere 香 (que significa "fragrância") parece uma pequena planta ou ramos brotando no topo de uma base quadrada (o caractere de sol: 日)
.
O Rei (玉 ou 王 - Gyoku/O): É a peça central e imponente
. O caractere do Rei defensor (玉) possui um pequeno ponto ou pingo no canto inferior direito, enquanto o caractere do Rei desafiante (王) não possui esse ponto
.

Alternativas para Facilitar o seu Aprendizado

Se você estiver jogando online ou comprando seu primeiro tabuleiro físico, não precisa sofrer decorando os Kanjis tradicionais de imediato. Existem ótimas opções adaptadas para iniciantes:
Peças de 1 Kanji (Simplificadas): Em vez de trazer dois caracteres empilhados (comuns em conjuntos profissionais), essas peças trazem apenas o caractere principal em tamanho grande, o que torna a associação visual muito mais rápida e limpa
.
Peças com Setas Direcionais: Muitos conjuntos didáticos trazem pequenas setas desenhadas nas bordas da peça indicando exatamente para quais direções ela pode se mover no momento
. Ao virar a peça para o lado promovido, as setas mudam para mostrar a nova movimentação
.
Peças Ocidentalizadas: Algumas plataformas e tabuleiros utilizam a letra inicial do nome da peça em inglês (como P para Pawn/Peão, R para Rook/Torre, B para Bishop/Bispo) ou pequenos ícones idênticos aos do xadrez ocidental
.

Temos o seguinte cenário:  O rei inimigo esta na posição 51 duas casas a frente tem um peão inimigo, já você tem o rei na posição 59 e duas casas a frente uma torre a aliada. Como você ganha esse jogo em até 10 jogadas?

Resposta :

Aqui está o passo a passo para alcançar o xeque-mate (Tsumi)
:
Jogada 1: Rx53+ (Torre captura Peão em 53 e promove a Dragão)
Sua Torre avança da casa 57, captura o peão inimigo em 53 e entra na zona de promoção (as três primeiras linhas do oponente)
. Ao fazer isso, você promove a Torre a Dragão (Ryuo), virando a peça
.
O Dragão em 53 agora ataca em linha reta e também uma casa em qualquer diagonal
. Ele coloca o Rei inimigo em 51 imediatamente em xeque pela coluna 5
.
Como o Dragão também controla as diagonais de uma casa (42 e 62) e a coluna vertical (52)
, o Rei inimigo é forçado a fugir para os lados: 41 ou 61
.
Resposta do oponente: Rei move-se para 41 (1... K-41)
.
Jogada 2: P*42 (Reposição de Peão em 42)
Como você acabou de capturar o peão inimigo na primeira jogada, ele agora é seu e está na sua mão
. Você usa seu turno para repor o Peão diretamente na casa 42
.
O Peão em 42 ataca uma casa diretamente à frente (41), colocando o Rei oponente em xeque de novo
.
Esta jogada é 100% legal: A regra proíbe dar xeque-mate imediato ao repor um peão, mas aqui o rei oponente ainda tem casas de fuga, então é um xeque válido
. Além disso, o Peão está protegido pelo seu Dragão em 53 (que alcança a diagonal 42)
, logo o Rei inimigo não pode capturá-lo
.
O Rei inimigo em 41 não pode voltar para a coluna 5 (pois 51 e 52 continuam sob a mira vertical do Dragão em 53)
. Portanto, ele é obrigado a fugir para a coluna 3, movendo-se para 31 ou 32
.
A partir daqui, o jogo se divide em dois caminhos fáceis para a sua vitória:
Caminho A: Se o Rei fugir para 31 (2... K-31)
3. D-33 (Dragão para 33): Você move seu Dragão de 53 para 33
. Isso coloca o Rei em xeque pela coluna 3
. O Rei não pode ir para 32 (na mira do Dragão), nem para 41 (na mira do peão em 42)
. A única fuga do oponente é ir para 21
.
3... K-21 (Fuga forçada do oponente)
.
4. D-23 (Dragão para 23): O seu Dragão move-se para 23, aplicando xeque na coluna 2
. Ele também controla as casas diagonais adjacentes (32 e 12)
. O Rei oponente é obrigado a se espremer no canto, fugindo para 11
.
4... K-11 (Fuga forçada do oponente)
.
5. D-13 (Dragão para 13 - XEQUE-MATE!): Você move o Dragão para 13
. O Rei inimigo em 11 está em xeque e não tem mais nenhuma casa segura para onde ir (todas as adjacentes, 12, 22 e 21, estão na mira do Dragão)
. Como o Dragão está a duas casas de distância, o Rei também não pode capturá-lo
. Vitória em 5 rodadas suas (9 movimentos no total)!
Caminho B: Se o Rei fugir para 32 (2... K-32)
3. D-52 (Dragão para 52): Você recua seu Dragão para 52
. Isso coloca o Rei em xeque pela linha horizontal 2
. O rei não pode capturar seu Dragão pois está a duas casas de distância
. O Rei oponente é empurrado para trás, sendo obrigado a ir para 31
.
3... K-31 (Fuga do oponente)
.
4. P-41+ (Peão move-se para 41 e promove a Tokin): Você avança seu peão de 42 para 41 e o promove a Tokin (+P), que agora se move de forma idêntica a um General de Ouro
. O Tokin em 41 coloca o Rei em xeque
. O Tokin está protegido pelo Dragão em 52 (diagonal de uma casa)
, então o Rei não pode capturá-lo
. O Rei é obrigado a ir para 21
.
4... K-21 (Fuga forçada do oponente)
.
5. D-32 (Dragão para 32): Você move o Dragão para 32
. Ele coloca o Rei em xeque pela diagonal
 e está defendido pelo Tokin em 41 (que, agindo como General de Ouro, protege a casa 32)
. O Rei não pode capturar o Dragão
 e é forçado a ir para a última casa de escape em 11
.
5... K-11 (Fuga forçada do oponente)
.
6. D-21 ou 6. +P-31 (XEQUE-MATE!): Qualquer um dos movimentos tira a última chance do Rei, prendendo-o sem escapatória na parede do tabuleiro. Vitória em 6 rodadas suas (11 movimentos no total)!

Nesse prompt a IA demorou um bom tempo para gerar uma resposta e ela nem sempre imagina que o oponente pode fazer uma jogada tão inteligente.

Testei fazer algumas modificações nesse cenário e percebi que tive cada vez mais respostas mais rápidas.

O rei inimigo joga primeiro e ele fica atras a esquerda do peão casa 42

Resposta :
Nesse caso, o Rei inimigo tentou se abrigar diagonalmente. Você pode alcançar o xeque-mate (Tsumi) em apenas 5 jogadas suas (9 movimentos no total) usando uma estratégia de ataque à distância:
Jogada 1 (Inimigo): O Rei inimigo move-se para 42
.
Jogada 1 (Sua): R-47 (Torre para 47)
Sua Torre avança pela coluna 4 e coloca o Rei inimigo em xeque à distância
.
Como a torre está longe, o Rei não pode capturá-la
. O Rei é obrigado a fugir para o lado.
Resposta do oponente: Rei foge para 31 (1... K-31).
Jogada 2 (Sua): Rx53+ (Torre captura Peão em 53 e promove a Dragão)
Sua torre limpa o peão do tabuleiro, entra na zona de promoção e vira um poderoso Dragão
. Além disso, você agora tem um Peão na sua mão para usar quando quiser
.
Resposta do oponente: O oponente tenta afastar o Rei do perigo e move-se para 21 (2... K-21).
Jogada 3 (Sua): D-51 (Dragão para 51)
Seu Dragão recua para a primeira fileira, aplicando um xeque horizontal de longa distância
.
O Rei inimigo não pode subir para a fileira 2 porque o Dragão também controla essa área
. Ele é obrigado a ir para o canto do tabuleiro.
Resposta do oponente: Rei move-se para 11 (3... K-11).
Jogada 4 (Sua): P*12 (Reposição de Peão em 12)
Você repõe o peão capturado diretamente na casa 12
. Isso coloca o Rei em xeque
.
Esta reposição é permitida por lei porque o rei ainda tem uma casa de fuga (não é um mate imediato de peão)
.
Resposta do oponente: Como o peão está protegido pelo Dragão (que ataca diagonalmente a uma casa de distância)
, o Rei não pode capturá-lo e é forçado a fugir para 21 (4... K-21).
Jogada 5 (Sua): D-21 (Dragão para 21 - XEQUE-MATE!)
Seu Dragão captura a casa 21
. O Rei inimigo está encurralado na borda do tabuleiro e não tem mais nenhuma jogada legal de fuga
. Vitória garantida!

Aqui percebi que a ia pula algumas jogadas como foi a captura do peão.

Expliquei os erros da IA mas ela continuava apresentando alguns erros, mas percebi que foi diminuindo a quantidade de erros


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
