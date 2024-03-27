# Snake Game

Este é um simples jogo da cobrinha (Snake Game) desenvolvido em JavaScript usando a biblioteca Canvas HTML5.

## Como Jogar

1. Clone este repositório ou baixe os arquivos diretamente.
2. Abra o arquivo `index.html` em seu navegador da web.
3. Use as teclas de seta do teclado para mover a cobrinha e tente pegar a comida para aumentar sua pontuação.

## Estrutura do Código

O código está dividido em três principais partes:

- **Keyboard**: Gerencia as entradas do teclado para controlar a direção da cobrinha.
- **Component**: Define a estrutura do jogo, incluindo o palco (stage) e a cobrinha (snake).
- **Game**: Responsável por desenhar o jogo no canvas e lidar com as interações do usuário.

## Personalização

Você pode personalizar alguns aspectos do jogo, como a velocidade (fps) e o tamanho inicial da cobrinha, modificando os parâmetros passados para o construtor `Snake` na função `addEventListener` no final do código.


```var snake = new Component.Snake(canvas, {fps: 100, size: 4});```



## Créditos

Este README fornece uma breve visão geral do jogo, como jogar, a estrutura do código e como personalizar algumas configurações básicas. Você pode expandir este README adicionando informações adicionais, como créditos para recursos utilizados, instruções mais detalhadas sobre como modificar o jogo ou até mesmo capturas de tela para ilustrar o jogo em ação.
