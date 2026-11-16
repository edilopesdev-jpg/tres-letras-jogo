# Três Letras

Jogo de navegador para três pessoas. Uma pessoa cria a sala, compartilha o link com as outras duas e todos correm para resolver oito anagramas.

## Publicação

Este projeto é um site estático: `index.html` é a página inicial. O multiplayer usa PeerJS para estabelecer a conexão entre navegadores. Para publicar no GitHub Pages, configure a publicação a partir da branch `main`, pasta `/root`.

## Como jogar

1. Abra a página publicada.
2. Uma pessoa cria a sala e compartilha o convite gerado.
3. As outras duas entram pelo convite.
4. O anfitrião inicia quando houver três jogadores.

Cada rodada tem uma tentativa por jogador e dura até 40 segundos. Acertos valem 3, 2 e 1 ponto, conforme a ordem de chegada.
