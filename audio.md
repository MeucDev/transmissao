# Áudio

> **IMPORTANTE:** para melhor qualidade e isolamento do som do computador, recomendamos levar seu próprio fone de ouvido. Um cabo mais longo também pode ser útil.

## Mesa de som

A regulagem individual dos instrumentos deve ser feita pelo mesário.

Em resumo:

- O som da mesa é enviado para um canal estéreo de retorno (9/10)
- O canal é capturado pela FastTrack Ultra que recebe via USB
- Os canais são considerados como um microfone pelo computador
- No [OBS Studio](./software.md#obs-studio), esse microfone fica aberto e envia o áudio também para os fones de ouvido

## Perguntas frequentes

### Como faço para ouvir o que está sendo transmitido?

O [OBS Studio](./software.md#obs-studio) está configurado para transmitir uma entrada de áudio.
Por padrão, o computador deve estar configurado para ouvir essa mesma entrada de áudio.  
Se isso não estiver acontecendo, você pode seguir os seguintes passos:

- No OBS, vá até o canal de áudio que recebe sinal da mesa de som
- Clique na engrenagem
- Selecione "Propriedades de Áudio Avançadas"
- Certifique-se de que o canal esteja marcado como "Enviar e Receber"
  > Se já estiver, desmarque e marque novamente
- Clique em "Aplicar"
