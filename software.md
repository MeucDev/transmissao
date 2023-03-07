# Software

- [Software](#software)
  - [Companion](#companion)
  - [OBS Studio](#obs-studio)
  - [ATEM Software Control](#atem-software-control)
    - [Saída de pre-visualização](#saída-de-pre-visualização)
    - [Croma Key](#croma-key)
      - [Configuração de cor do Croma](#configuração-de-cor-do-croma)
    - [Picture-in-Picture](#picture-in-picture)

## Companion

![Companion](imgs/companion-logo.png)

[Site oficial](https://bitfocus.io/companion)

O BitFocus Companion é um software que integra com a StreamDeck para configuração dos botões.

Ao ser inicializado, o software assume controle do Stream Deck e preenche as teclas com as imagens configuradas.  
Além disso, cada botão pode ser personalizado não só com imagem, mas funcionalidade, integrações, funcionamente, etc.

Hoje a principal funcionalidade dele é para controle da câmera PTZ, mas existem alguns botões que estão integrados a
funções do OBS, e ATEM.

## OBS Studio

![Logo OBS](imgs/obs-logo.png)

[Site oficial](https://obsproject.com/)

O OBS Studio é utilizado para transmissão de vídeo e áudio para stream no YouTube e opcionalmente seleção de cenas.

## ATEM Software Control

![Logo ATEM](imgs/atem-logo.jpg)

[Site oficial](https://www.blackmagicdesign.com/products/atemmini/software)

O ATEM Software Control é utilizado para configurações avançadas da ATEM Mini, como tamanho e posição do Picture-in-Picture e detalhes do Croma Key.

Para as funções dos botões na mesa, acesse a página da [ATEM Mini](atem-mini.md).

### Saída de pre-visualização

O monitor da esquerda está configurado para visualizar uma das entradas da ATEM.  
Por padrão o software vem com a opção "Program" selecionada, que seria a opção selecionada para envio (em vermelho). Porém, recomendamos que a opção "Preview" seja selecionada, para a imagem do monitor apresentar o conteúdo de prévia (em verde).

Essa seleção acontece no menu superior, item "Output".

![Output](imgs/atem-output.png)

### Croma Key

O Croma Key é utilizado para as legendas de letra das músicas no culto.

Essa configuração pode ser feita no menu lateral direito, aba "Croma".  
A imagem que deve ser jogada por cima deve ser sempre a "Projeção".

![Croma](imgs/atem-croma.png)]

> Para evitar uma sombra ou distorção verde, utiliza a configuração de "Borda".

#### Configuração de cor do Croma

Se ao ativar o Croma Key ouver alguma distorção de cor, é preciso configurar a cor
utilizada para o Croma.  
Para isso, desative o Croma Key e clique em "Amostra Croma". Ao ativar o Croma novamente
a aberração de cor deve estar corrigida.

### Picture-in-Picture

O Picture-in-Picture (PiP) é utilizado para ter uma entrada sobreposta a outra.

A configuração do PiP pode ser feita no menu lateral direito, aba "DVE".  
Certifique-se de ter a "Câmera esquerda" selecionada como Preenchimento.

![DVE](imgs/atem-dve.png)

> Recomendamos também deixar a "Opacidade da borda" em 0%.
