# Projeto-1
Trabalho de grupo para a disciplina de Técnicas de Desenvolvimento de Videojogos.

Realizado por / Daniel Guerra - 31478
              / Afonso Silva - 31485
              / Simão Baltar - 31464

MonoPingPong

Introdução
O projeto MonoPingPong é uma reinterpretação moderna do clássico jogo "Pong", desenvolvido utilizando a framework MonoGame e a linguagem C#.
O jogo foi criado como exercício prático no contexto da unidade curricular Técnicas de Desenvolvimento de Videojogos, focando-se no desenvolvimento de mecânicas básicas de interação, física de colisões e gestão de estados de jogo.

Objetivo do Jogo
O objetivo do MonoPingPong é simples: cada jogador controla uma raquete e deve impedir que a bola passe pela sua área.
Cada vez que o adversário falha a defesa, o jogador marca um ponto. O vencedor é o primeiro jogador a atingir o número de pontos definido como limite.

O jogo suporta modo multiplayer local, permitindo que dois jogadores compitam no mesmo dispositivo.

Desenvolvimento Técnico
O jogo foi desenvolvido com:

-Linguagem de Programação: C#
-Framework: MonoGame (uma framework de código aberto para criação de jogos 2D e 3D)
-Plataforma: Desktop (Windows)

MonoGame fornece as ferramentas necessárias para o controlo da janela de jogo, deteção de input, renderização de gráficos e atualização em tempo real.

Estrutura do Projeto
A estrutura do projeto é organizada da seguinte forma:

Game1.cs:
A classe principal do jogo. Esta classe gere o ciclo principal do jogo (Initialize, LoadContent, Update, Draw).

Content/:
Pasta que contém os recursos (assets) como imagens, sons e fontes de texto.

-Sprites/ (se existir):
Recursos visuais usados para representar as raquetes e a bola.

Program.cs:
Ponto de entrada da aplicação que inicia o ciclo do jogo.

Principais Componentes
-Initialize(): Inicializa variáveis e configura o estado inicial do jogo (posição das raquetes, bola, pontuação).
-LoadContent(): Carrega todos os recursos gráficos e fontes necessários.
-Update(GameTime gameTime): Atualiza a posição da bola e raquetes, verifica colisões e gere a lógica de pontuação.
-Draw(GameTime gameTime): Desenha todos os elementos visuais do jogo no ecrã (campo, raquetes, bola e pontuação).

Jogabilidade
-Jogador 1 controla a sua raquete usando as teclas W (cima) e S (baixo).
-Jogador 2 controla a sua raquete usando as teclas Up Arrow (cima) e Down Arrow (baixo).

A bola movimenta-se automaticamente e altera a sua direção ao colidir com as raquetes ou com as bordas superior e inferior do campo de jogo.



Conclusão
O MonoPingPong demonstra o desenvolvimento de um jogo multiplayer 2D simples usando práticas fundamentais da criação de videojogos:
gestão de ciclos de jogo, input de jogadores, deteção de colisões e renderização de objetos gráficos.

Este projeto serve como base sólida para a introdução a técnicas mais avançadas de desenvolvimento de videojogos, como física mais complexa, inteligência artificial e sistemas de menus.
