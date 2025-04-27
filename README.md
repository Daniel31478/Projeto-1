# Projeto-1
Trabalho de grupo para a disciplina de Técnicas de Desenvolvimento de Videojogos

Realizado por / Daniel Guerra - 31478
              / Afonso Silva - 31485
              / Simão Baltar - 31464

Introdução - 

Este documento apresenta a análise de um projeto de jogo desenvolvido utilizando o framework MonoGame em C#.
O projeto foi obtido a partir de um repositório no GitHub e insere-se no âmbito da disciplina de Programação e Técnicas de Desenvolvimento de Videojogos.
Serão abordados a descrição do funcionamento do jogo e uma explicação técnica da sua implementação.

Descrição do Jogo - 

O jogo é um projeto simples baseado no ciclo tradicional de desenvolvimento de videojogos:

- Inicialização;
- Carregamento de conteúdos;
- Atualização da lógica do jogo;
- Desenho dos elementos no ecrã.

Apesar da simplicidade gráfica e de jogabilidade, o projeto serve como uma excelente base para aprendizagem de conceitos fundamentais de desenvolvimento de jogos 2D.
Este projeto foi pensado para reforçar os conhecimentos práticos na criação de um motor de jogo básico.

Explicação Técnica do Código -

O projeto está organizado da seguinte forma:

- Program.cs: Ponto de entrada da aplicação. É aqui que a classe Game1 é instanciada e o jogo começa a correr;
- Game1.cs: Contém toda a lógica principal do jogo;
- Initialize: Prepara o ambiente inicial (ex.: definição de variáveis iniciais);
- LoadContent: Carrega todos os recursos necessários, como imagens e sons;
- Update: Atualiza o estado do jogo, processando entradas do utilizador e lógica de movimento/colisão;
- Draw: Desenha os elementos visuais na janela de jogo;
- Content: Pasta onde estão armazenados os conteúdos (assets) que o jogo utiliza;
- TDD.csproj: Ficheiro de configuração do projeto para o Visual Studio.

Estrutura do Ciclo de Vida do Jogo -

O projeto implementa o Game Loop, um padrão central no desenvolvimento de videojogos:

- Inicializar o ambiente do jogo;
- Carregar conteúdos gráficos e sonoros;
- Atualizar a lógica interna de forma contínua (input, colisões, movimento);
- Desenhar os objetos no ecrã de acordo com o estado atual.

Este ciclo repete-se dezenas ou centenas de vezes por segundo.

Tecnologias Utilizadas:

- Linguagem C#;
- Framework MonoGame;
- .NET SDK;
- Ambiente de desenvolvimento como o Visual Studio.

Conclusão -

O projeto TDD desenvolvido em MonoGame é um exemplo claro e simples de como estruturar um jogo básico em C#.
A sua organização permite compreender a lógica de desenvolvimento de videojogos desde o carregamento de conteúdos até ao desenho final.
É uma excelente base para futuras expansões e para o aprofundamento dos conhecimentos na área de programação de jogos.
