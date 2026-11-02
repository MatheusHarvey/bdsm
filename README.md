# B.D.S.M. — Baralho Desgraçado Sem Moral 🃏 (+18)

Um jogo de cartas de humor ácido para jogar com a galera: a carta preta aparece na TV, cada um tem a sua mão **escondida no celular**, e vence quem completar a frase com a pior resposta possível.

**Jogar:** abra o link do GitHub Pages deste repositório na TV ou no notebook. Os jogadores entram pelo QR Code que aparece na tela.

> ⚠️ **Conteúdo adulto.** Humor sobre sexo, morte, religião, política, crime e desgraças do cotidiano. Feito para maiores de 18 anos e para amigos que topam a brincadeira.

## Como funciona

1. **Abra a sala na TV.** Ela mostra um QR Code e um código de 4 letras.
2. **Cada um entra pelo celular**, digita o nome e recebe **10 cartas brancas**, que só ele vê. São precisos pelo menos 3 jogadores.
3. **A carta preta aparece na TV**, com uma ou duas lacunas. Cada um escolhe a resposta no celular e vê a prévia da frase antes de jogar.
4. **As respostas aparecem na TV, embaralhadas e sem nome**, já encaixadas na frase.
5. **Escolhe-se a melhor**, de um destes jeitos:
   - **Juiz rotativo:** a cada rodada um jogador é o juiz. Ele não joga e escolhe a vencedora pelo celular.
   - **Voto popular:** todo mundo joga e todo mundo vota, menos na própria resposta. Empate dá ponto para todos os empatados.
6. **Ao fim de cada rodada, todo mundo compra cartas** para voltar a ter 10.

## Destaques

- **60 perguntas e 250 respostas**, escritas do zero em português com referências brasileiras: coach quântico, golpe do Pix, motorista de aplicativo filósofo, Orkut, Mercúrio retrógrado e mais.
- **Três níveis de acidez**, que ligam e desligam: Morno, Ácido e Sem perdão. O Sem perdão começa desligado.
- **Cartas da turma:** campos para escrever perguntas e respostas próprias, com as piadas internas do grupo. Elas ficam salvas só no aparelho que abriu a sala.
- **Modo de nomes:**
  - **Censurado:** ninguém sabe quem jogou o quê. Placar e autores só aparecem no fim, na tela de **Melhores momentos**.
  - **Não censurado:** a cada rodada aparece o dono da resposta vencedora.
- **Reciclagem:** a cada 5 rodadas, cada jogador pode trocar **até 7 das 10 cartas** da mão. As descartadas voltam para o fundo do monte.
- **Sem cartas repetidas:** o baralho é um monte único, e nenhuma carta aparece na mão de dois jogadores ao mesmo tempo.
- **Partida até 5, 7 ou 10 pontos**, ou sem limite.

## Requisitos

- **Um aparelho para a mesa:** TV, notebook ou tablet. Ele controla a partida e precisa ficar com a página aberta.
- **Um celular por jogador**, com internet.
- **Comunicação em tempo real:** é feita pelo Firebase Realtime Database. A configuração fica no começo do `index.html`, e as regras do banco precisam liberar o caminho `salas`.

## Arquivos

- `index.html`: o jogo inteiro, com o baralho embutido.

## Créditos

Inspirado no formato dos jogos de "complete a frase". Nome, cartas e código são originais deste projeto.

Feito por Matheus "Harvey" Jeronimo, com ajuda do Claude, para as noites com os amigos.
