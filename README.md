# TrabalhoPratico2TDVJ
Repositório do Trabalho Pratico 2 - Técnicas De Desenvolvimento de Videojogos - 18816(José Oliveira) &amp; 25955(David Cruz)
Conceito:
O jogo consiste no jogador (o carro) precorrer o mapa e coletar combustível. Quanto mais combustível recolher, mais pontuação ganha.

- Program.cs
Vai ser com este código que premitirá o programa correr o jogo.

- Game1.cs
Uma class publica, que irá, primeiramente, defenir um valor random, introduzir os valores da dimensão da tela, e criar estados de jogo.

- Entity
Entity.cs: Esta Classe serve para controlar todas as entidades do jogo, quanto à sua textura, posição, rotação ou escala. Controla a posição do combustível que aparece no mapa, e desaparece com contacto com o jogador.

-Player.cs: Subclasse da Classe Entity e server para controlar o jogador, quanto à sua textura, posição, rotação ou escala. Quando este entra em contacto com uma unidade de combustível, a pontuação aumenta, o combustível desaparece e aparece um novo em outra posição.

- ScoreManager
Score.cs: Classe que deteta e retem o valor da pontuação do jogador.

-ScoreManager: Classe que deteta a pontuação obtida no Score.cs e organiza numa lista em ficheiro .xml com os melhores resultados até ao momento.

Processo:
Primeiramente pensamos em algo para fazer, algo funcional e simples. Fomos pesquisando vários jogos monogames para recolhermos informação de que tipo de jogo iriamos fazer e, chegamos a uma conclusão. Um jogo do estilo snake, mas com um carro. Recolhemos informação através de tutoriais e outras formas que resultaram em mecânicas de de score e entities. Através de tentativas e chegamos a este resultado.
