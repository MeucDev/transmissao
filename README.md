# Transmissão

Guia e orientações para a transmissão ao vivo do culto em Blumenau.

Este guia segue um passo a passo de como executar a transmissão ao vivo de um culto.
Para ver mais detalhes sobre alguma área da transmissão, veja os guias específicos abaixo:

- [ATEM Mini](./atem-mini.md)
- [Áudio](./audio.md)
- [Câmeras](./cameras.md)
- [Luzes](./luzes.md)
- [Slides e Projeção](./slides.md)
- [Softwares](./software.md)
- [Sonoplastia](./sonoplastia.md)
- [Problemas e Soluções](./problemas.md)

## Preparação

1. Verificar as questões de energia:
   - Ligar a régua que alimenta o computador - dentro do móvel;
   - Conectar a energia na [BlackMagic ATEM Mini](./atem-mini.md).

2. Ligar a máquina:
   - Ligue o computador;
   - Ligue os monitores;
   - Digite a senha.

3. Ligar as câmeras:
   - Para ligar a câmera PTZ, abra a caixa acrílica utilizando o bastão e conecte a fonte;
   - Para ligar a câmera Sony, conecte o mini-HDMI na lateral esquerda e cabo de energia na lateral direita;
   - É interessante verificar se a lentes estão limpas. Você pode usar um pano de tecido ou um pedaço de papel higiênico para limpá-las.

4. Ligar as [luzes do palco](./luzes.md)

5. Equipamentos ligados! É hora de configurar os programas...

## Configuração

> Para regulagens de áudio, veja mais detalhes [aqui](./audio.md).

1. Seleção de cenas:
   - Toda a parte de seleção de câmeras e projetor acontece na [ATEM Mini](./atem-mini.md);
   - Demais cenas no OBS são utilizadas somente para vídeos de contagem regressiva e fim.

2. Abrir o [OBS Studio](./software.md#obs-studio):
   - Para enviar imagem para o projetor, clique com o botão direito sob a imagem sendo enviada (programa):
     - `Projetor em tela inteira (programa)` > `Monitor 2`
       > No caso de um conteúdo diferenciado, enviar o conteúdo da cena ATEM em vez de programa
   - Verificar que o sinal das câmeras está chegando
   - Verificar que o sinal do projetor está chegando
   - Para regulagem avançada de cenas e transmissão, veja [Software - OBS Studio](./software.md#obs-studio)

3. Abrir o [ATEM Software Control](./software.md#atem-software-control) (opcional)

4. Abrir o Google Chrome / YouTube:
   - A página de transmissão pode ser acessada [aqui](https://studio.youtube.com/channel/UCD9zslKV3jrJb3pslWe32Bw/livestreaming/dashboard)
   - Se houver a opção, clonar a configuração de um culto anterior
   - Verificar agendamento para o dia
   - Configurar título, horário, imagem
   - **IMPORTANTE**: O culto deve ser marcado como "Não é para crianças" e em avançado para "Não restringir conteúdo"
     ![YouTube](imgs/youtube-detalhes-transmissao.png)

## Iniciando

- No [OBS Studio](./software.md#obs-studio), clicar em `Iniciar transmissão` e selecionar a transmissão configurada no passo anterior;
  ![Iniciar transmissão](imgs/obs-iniciar-transmissao.png)
  > **IMPORTANTE:** essa etapa já pode ser iniciada minutos antes, pois somente com o próximo passo que a transmissão realmente inicia no YouTube.
- No [YouTube](https://studio.youtube.com/channel/UCD9zslKV3jrJb3pslWe32Bw/livestreaming/dashboard), clicar em `Transmitir ao vivo`.
  ![Transmitir ao Vivo](imgs/youtube-transmitir-ao-vivo.png)
