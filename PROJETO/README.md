
# Projeto jogo "SAVE THE FRIEND"

Projeto de jogo da aula do curso técnico senac


## Objetivo do Jogo

Pegar a chave protegida pelo inimigo, salvar o companheiro aprisionado, abrir a porta e pegar o helicoptero e sair terminando a fase.


## Documentação do Jogador



| Heroi   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `Bina` | `Atirador` | `possui uma vida` - `Leva hitkill do inimigo` `possui 5 tiros na arma`  |

## Documentação do inimigo


| inimigos (classes)   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `Zumbis Comuns`      | `level 1` | `Morre com um tiro` |
| `Zumbis TANKS`      | `level 5` | `Morre com um 5 TIROS` - `Leva hitkill de barril`


# Documentação do Ambiente

A fase possui cerca elétricas que matam de hitkill o jogador se estiver em frente da cerca.
Possui uma chave mestra para terminar a fase e pegar o helicóptero.
Possui um especial que solta um barril explosivo que da dano em área e da hitkill no jogador ou no zumbis em geral.

## Tamanho da fase
`Tabuleiro 7x5`

## Peças que Move o Jogador

| Peças    | Tipo       | Cor                                   |

| `5 CORINGAS`      | `Tiro` | `PRETO E BRANCO` |

|  `1 BARRIL`      | `Especial` | `PRETO E BRANCO` |

| `1 dado`       | `Move o jogador 1`  | 


## Documentação Geral do Jogo

Este jogo é uma experiência interativa multiplayer em que o Player 1 enfrenta uma horda de zumbis controlada pelo Player 2. O objetivo principal do Player 1 é coletar itens essenciais e finalmente escapar em um helicóptero. O jogo combina elementos de estratégia, sorte e ação, criando uma dinâmica desafiadora.

O Player 1 rola os dados para determinar quantos espaços pode se mover, e essa rolagem é crucial para o planejamento estratégico das ações subsequentes. Em combate, o Player 1 pode atacar os zumbis a curta e longa distância, desde que esteja em linha reta em relação a eles. O jogo conta com 8 zumbis, classificados de nível 1 a nível 5, cada um apresentando diferentes níveis de vida.

Os objetivos do Player 1 no tabuleiro incluem: coletar um item de ataque especial (Barril), obter uma chave, resgatar um companheiro aprisionado, abrir uma porta trancada utilizando a chave e, finalmente, alcançar o helicóptero que aguarda na saída da fase para a fuga.

Os zumbis, controlados pelo Player 2, se movem um espaço por turno e podem eliminar o Player 1 se este estiver diretamente em sua frente ou no mesmo espaço. Isso adiciona um elemento de risco significativo ao movimento do Player 1, exigindo uma abordagem cuidadosa e estratégica.

O sistema de vidas é limitado; se o Player 1 perder uma vida, ele deve reiniciar a fase desde o início, o que reforça a importância do planejamento e da estratégia. O jogo, portanto, combina mecânicas de rolagem de dados com combate tático e coleta de itens, criando uma experiência envolvente. O Player 1 deve usar suas habilidades estratégicas para navegar em um ambiente hostil e completar seus objetivos, enquanto o Player 2 deve empregar táticas para impedir seu avanço.



