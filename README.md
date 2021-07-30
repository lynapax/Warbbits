# Warbbits-PC

## Descrição Resumida do Jogo

 É um jogo multiplayer de tabuleiro que o objetivo é chegar no coelho que esconde a bandeira goal e derrotá-lo. 
 Cada time possuirá um grupo de fighters com diferentes naturezas (fogo, gelo, agua, armadilha e bandeira) e poderá mover um fighter por vez, optando por batalhar com o fighter do time oponente ou só se deslocar pelo tabuleiro. As regras do jogo são melhores demonstradas abaixo. 

A imagem abaixo é apenas um primeiro rascunho do tabuleiro final. Futuramente cada fighter terá itens demonstrando sua natureza
![Rascunho da Imagem de Batalha](https://github.com/lynapax/Warbbits/blob/main/Data/Tabuleiro%20montado%203D%20-%20rascunho.png)
## Personagens 

![Idle](https://github.com/lynapax/Warbbits/blob/main/Data/Fighter%20modelo%203D%20-%20idle.gif)

![Modelo 3D do Fighter](https://github.com/lynapax/Warbbits/blob/main/Arquivos%20Blender/Concepts%20e%20modelos/Coelho%20-%20modelo%203D%20simplificado.png)

* Fogo  : (4 Personagens)
![Concept FireFighter - time Red](https://github.com/lynapax/Warbbits/blob/main/Arquivos%20Blender/Concepts%20e%20modelos/fire%20fighter%20red.png)

* Água  : (4 Personagens)
![Concept WaterFighter - time Blue](https://github.com/lynapax/Warbbits/blob/main/Arquivos%20Blender/Concepts%20e%20modelos/water%20fighter%20blue.png)

* Gelo   : (4 Personagens) 
![Concept IceFighter - time Red](https://github.com/lynapax/Warbbits/blob/main/Arquivos%20Blender/Concepts%20e%20modelos/ice%20fighter%20red.png)



* Armadilha (bait) (1 Personagem)

* Bandeira (goal/target) (1 Personagem) 


## Movimentos 

![Modelo 3D do tabuleiro](https://github.com/lynapax/Warbbits/blob/main/Arquivos%20Blender/Concepts%20e%20modelos/Tabuleiro%20-%20Modelo%203D.png)


#### Movimento dos personagens : 
Os Personagens podem se mover nas direções : Esquerda, Direita, Cima e Baixo 
Os Personagens sempre deverão se mover apenas uma casa por rodada 

#### Movimentos permitidos : 
Andar no Tabuleiro 
Batalhar com oponente 

#### Movimentos inválidos : 
Andar mais de uma casa por vez 
Batalhar com personagens de mesmo time 
Batalhar com mais do que um personagem 
Sobrescrever personagens seja de time amigo ou inimigo 
A Peça Armadilha não poderá se movimentar 
A Peça Bandeira não poderá se movimentar 


## Regras de Batalha 

A partir do movimento em que confronte um oponente, entrará no modo de batalha x1 
Os poderes do personagem que poderá ou não estar oculto serão revelados. 
A ordem de sucesso segue de forma cíclica : 
Fogo > Gelo > Agua. 
Fogo x Gelo : Fogo derrete o gelo, portanto Ganha 
Gelo x Agua : Gelo congela a agua, portanto Ganha 
Agua x Fogo : Agua apaga o fogo, portanto Ganha 
Todas as peças perdem para a Peça Armadilha 
Todas as peças ganham ao batalhar com a peça Bandeira  
Aquele que obtiver a vitória, irá ocupar a mesma posição do oponente derrotado.
O oponente derrotado sairá do jogo.

### Desempate 

Caso o oponente tenha a mesma habilidade que a do seu personagem, será permitido que troque a habilidade do personagem que estiver jogando e a habilidade do jogador oponente será escolhida de forma aleatória

O Objetivo do jogo é conquistar a Bandeira do Oponente primeiro. 

