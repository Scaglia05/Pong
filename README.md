README - Jogo de Ping Pong em p5.js
Este é um jogo simples de ping pong desenvolvido utilizando a biblioteca p5.js. O jogo consiste em rebater uma bola com uma raquete, controlada pelo jogador, de modo a evitar que a bola ultrapasse a raquete e marcar pontos ao fazer com que a bola ultrapasse a raquete do oponente.

Funcionalidades Principais
Variáveis e Configurações Iniciais
Variáveis da Bola:
xbolinha, ybolinha: Coordenadas da bola na tela.
diametro, raio: Dimensões da bola.
Velocidade da Bola:
xvelocidade, yvelocidade: Determinam a velocidade da bola nos eixos x e y.
Variáveis da Raquete do Oponente:
xraqueteoponente, yraqueteoponente: Coordenadas da raquete do oponente.
comprimentoraqueteop, raquetealturaop: Dimensões da raquete do oponente.
velocidadeyoponente, chancedeerrar: Parâmetros para o movimento automático e probabilidade de erro do oponente.
Variáveis da Raquete do Jogador:
xraquete, yraquete: Coordenadas da raquete controlada pelo jogador.
comprimentoraquete, raquetealtura: Dimensões da raquete do jogador.
Placar do Jogo:
meuspontos, pontosdooponente: Armazenam os pontos do jogador e do oponente.
Sons
Sons Carregados:
raquetada: Som reproduzido quando a bola colide com uma raquete.
ponto: Som reproduzido ao marcar um ponto.
trilha: Trilha sonora de fundo durante o jogo.
Funções Principais
Setup:

Configura o ambiente do jogo, define o tamanho da tela e inicia a trilha sonora.
Loop Principal (Draw):

Desenha e atualiza os elementos do jogo (bola, raquetes, placar).
Detecta colisões e atualiza a posição dos elementos.
Movimentação:

Permite ao jogador mover sua raquete para cima e para baixo.
Colisão:

Verifica se a bola colide com as raquetes do jogador e do oponente.
Pontuação:

Atualiza o placar quando um ponto é marcado.
Limitação de Movimento:

Impede que as raquetes saiam da tela.
Como Jogar
Use as setas do teclado para mover a raquete para cima e para baixo.
Rebata a bola com a raquete para evitar que ela ultrapasse a raquete.
Marque pontos ao fazer com que a bola ultrapasse a raquete do oponente.
Ganha quem marcar mais pontos.
Divirta-se jogando ping pong!

Instalação e Execução
Clone ou faça o download deste repositório.
Abra o arquivo index.html em um navegador web compatível com a biblioteca p5.js.
Desfrute do jogo!
