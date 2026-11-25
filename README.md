# Olá, você — misty

Presente digital experimental em telas, com álbum interativo e um jardim para explorar no final. Sem jogo externo.

## Arquivos

`index.html` contém layout, ilustrações, interações e conteúdo editável em `CONTENT`. `assets/missing-someone.mp3` e `assets/cupido.png` são os arquivos escolhidos para a música e o easter egg. Veja `assets/README.md`.

## Experiência

Abertura “Clique para descobrir”: o toque chama `HTMLAudioElement.play()` diretamente, antes da transição. Também existe entrada sem som e controle de pausar/retomar. Reprodução não é garantida se o aparelho estiver sem som, o arquivo falhar ou houver alguma restrição externa.

O contador parte de 27/11/2025 às 22:36 no fuso de Brasília (-03:00), usando o relógio do dispositivo. As fotos viram ao toque; a flor abre; a carta é paginada; há bilhetes nas estrelas.

No final, sete pontos do cenário abrem mensagens sem ordem obrigatória: lua, céu, cavalo, flores, rio, árvore e estrela. O botão de pista destaca o próximo ponto não descoberto; há retorno ao álbum. O cupido é um segredo adicional, fora do contador normal, com a frase especificada pelo criador.

## Publicar e testar

GitHub Pages → Deploy from a branch → main → /(root). Atualizações no main publicam pelo mesmo endereço. Testar no Safari/iPhone: toque inicial e áudio, pausa, voltar da aba, todas as telas, exploração, modal e fechamento, paisagem e modo avião.

O download de HTML pelo app Arquivos do iPhone não equivale ao Safari. Prefira abrir por HTTPS, guardar a cópia offline no final e adicionar à Tela de Início. O cache inclui HTML, manifest e os dois arquivos de mídia; sem os arquivos o preparo offline falha. O iOS pode apagar cache; manter uma cópia do projeto. No computador a pasta completa funciona localmente. Sem fontes de terceiros, CDN, analytics ou coleta de dados.

## Conteúdo provisório

misty é o apelido solicitado. Fotos, bilhetes e carta ainda precisam do conteúdo definitivo do casal. Flores provisórias até confirmar a preferência. As frases de exemplo não descrevem acontecimentos reais. Referência de formato: https://www.dearyou.com.br/ ; desenho e implementação próprios.

Verificações automáticas: sintaxe, fluxo, toque inicial/entrada sem som, exploração de sete pontos e segredo, retorno ao álbum, contador e play/pause com áudio simulado. Testes automáticos não validam qualidade visual, som real ou Safari de um iPhone.
