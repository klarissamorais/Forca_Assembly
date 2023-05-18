# Projeto de Forca em Assembly x86

Este projeto é um jogo de forca implementado em assembly x86 para a disciplina de Infraestrutura de Software. O objetivo é adivinhar a palavra oculta antes de ser enforcado. O jogo utiliza a interação com o teclado para adivinhar letras e exibe a evolução da forca na tela.

## Funcionalidades

- Tela de menu com opções para iniciar o jogo ou sair
- Seleção de palavras ocultas aleatórias
- Exibição da forca e das letras corretas adivinhadas
- Contagem de erros e pontuação do jogador
- Tela de vitória e derrota com opção de continuar ou retornar ao menu
- Transições suaves entre as telas

## Instruções de Uso

1. Execute o programa no ambiente de desenvolvimento ou monte o código em um ambiente compatível com o processador x86.
2. Na tela de menu, pressione a tecla 'space' para iniciar o jogo ou a tecla 'backspace' para sair.
3. No jogo, tente adivinhar a palavra oculta digitando letras no teclado.
4. Se a letra estiver correta, ela será exibida na palavra oculta.
5. Caso a letra esteja incorreta, a forca será desenhada gradualmente.
6. Se acertar todas as letras antes de ser enforcado, você vence o jogo.
7. Caso seja enforcado antes de adivinhar a palavra, você perde o jogo.
8. Na tela de vitória ou derrota, pressione a tecla 'space' para continuar jogando ou a tecla 'backspace' para retornar ao menu.
9. Repita os passos 3 a 8 para jogar novamente ou sair do jogo.

## Requisitos de Sistema

- Processador compatível com x86
- Ambiente de desenvolvimento ou montagem de código Assembly x86

## Limitações

- O jogo suporta apenas palavras de até 10 letras
- O número máximo de erros permitidos é 6
- A interface gráfica é baseada em texto, sem suporte a elementos visuais avançados
