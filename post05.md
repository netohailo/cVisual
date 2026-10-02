# Computação Visual: Como um computador "enxerga" uma imagem

## Introdução

Quando olhamos uma foto na tela, vemos pessoas, cores e formas. Para o computador, porém, aquilo é apenas um conjunto organizado de números. Entender essa ideia é um dos primeiros passos da Computação Visual.

## A imagem como uma grade de pixels

Uma imagem digital funciona como uma grade (ou matriz) de pequenos quadrados chamados **pixels**. Cada pixel guarda a informação de uma cor, e a combinação de todos eles forma a imagem completa. Quanto mais pixels, maior a **resolução** e mais detalhes cabem na imagem.

## Como a cor é representada

Na maioria das telas, a cor de cada pixel é descrita por três valores: vermelho, verde e azul (modelo **RGB**). Normalmente, cada um desses canais vai de 0 a 255. Assim:

- (0, 0, 0) é preto;
- (255, 255, 255) é branco;
- (255, 0, 0) é vermelho puro.

## Por que isso importa

Se a imagem é só uma matriz de números, então podemos **processá-la com código**: deixar a imagem em tons de cinza, ajustar o brilho, detectar bordas ou aplicar filtros. Todas essas operações são, no fundo, cálculos sobre os valores dos pixels.

## Conclusão

Perceber que uma imagem é, no fundo, dados que podem ser lidos e transformados mudou a minha visão da disciplina. Computação Visual não é só desenhar na tela, mas também entender e manipular a informação visual por trás do que vemos.
