# Game01--stage-cru--

#Game01--stage-crude--

#VERSION 0.0.1

O código Java apresenta a implementação de um jogo simples utilizando a biblioteca javax.swing e java.awt. Aqui estão algumas características principais do código:

Estrutura Geral do Jogo:
O jogo é baseado em um sistema de entidades, onde cada entidade representa um elemento no mundo do jogo.
A classe Game é a classe principal que gerencia o loop de jogo, a renderização e a lógica do jogo.
Elementos Principais:
Janela do Jogo (JFrame):

A classe Game inicializa uma janela do jogo usando JFrame.
Define propriedades como título, redimensionamento, posição e operação padrão de fechamento.
Canvas e Buffer de Imagem:

Utiliza um Canvas para desenhar gráficos.
Usa um BufferedImage para armazenar os gráficos antes de renderizá-los, evitando cintilação.
Entidades (Entity):

Define uma classe abstrata Entity que representa elementos no jogo.
Uma lista de entidades (entities) é gerenciada para atualizar e renderizar todos os elementos.
Spritesheet e Sprites:

Utiliza uma classe Spritesheet para carregar uma folha de sprites.
Cria o jogador (Player) usando sprites específicos da spritesheet.
Mundo (World):

Utiliza um objeto World para renderizar o ambiente de jogo.
O mapa é carregado a partir de um arquivo de imagem (map.png).
Loop de Jogo:

Implementa um loop de jogo utilizando Thread.
Mantém um controle de frames por segundo (FPS) para exibir no console.
Controle do Jogador:

Responde às teclas pressionadas e libera a movimentação do jogador.
Movimentos direcionais (cima, baixo, esquerda, direita) são controlados pelo teclado.
Como Executar o Jogo:
Instancie a classe Game.
Chame o método start para iniciar o jogo.
Use as teclas direcionais (W, A, S, D) para controlar o jogador no ambiente do jogo.
Observações:
O código utiliza conceitos básicos de renderização, controle de teclado e lógica de jogo.
A estrutura do jogo é modular, facilitando a adição de novos elementos e funcionalidades.
Requisitos:
Java instalado.
