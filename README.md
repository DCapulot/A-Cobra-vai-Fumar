🐍 A Cobra Vai Fumar!

📌 Sobre o projeto

A Cobra Vai Fumar! é um jogo de cobrinha desenvolvido com HTML, CSS e JavaScript, inspirado no clássico jogo Snake.

A ideia é simples: o jogador controla a cobra usando as setas do teclado, coleta as frutas espalhadas pelo tabuleiro e tenta conseguir a maior pontuação possível sem bater nas paredes ou no próprio corpo.

O jogo também possui sistema de vidas, recorde, histórico de jogadores, ranking, efeitos sonoros e frutas com diferentes valores de pontuação.

🎮 Como jogar

Digite seu nome no menu inicial e pressione Enter para começar.

Controles

⬆️ Seta para cima — movimenta a cobra para cima

⬇️ Seta para baixo — movimenta a cobra para baixo

⬅️ Seta para esquerda — movimenta a cobra para a esquerda

➡️ Seta para direita — movimenta a cobra para a direita

Também existem botões para iniciar, pausar e reiniciar o jogo.

🍎 Frutas

Fruta

Pontuação

🔴 Vermelha

10 pontos

🟡 Amarela

20 pontos

🔵 Azul

30 pontos

As frutas aparecem em posições aleatórias e não são colocadas sobre a cobra.

🐍 Mecânica especial

Depois que o jogador come 7 frutas, o alimento começa a se movimentar pelo tabuleiro.

Isso aumenta a dificuldade, pois o jogador precisa acompanhar uma fruta que pode mudar de posição enquanto controla a cobra.

A velocidade da cobra também aumenta conforme a pontuação cresce.

❤️ Sistema de vidas

O jogador começa com 3 vidas.

Quando a cobra bate em uma parede ou no próprio corpo, uma vida é perdida.

Se ainda houver vidas, a cobra é reposicionada e uma contagem regressiva acontece antes da partida continuar.

Quando todas as vidas acabam, o jogo termina e o resultado é salvo.

🏆 Recorde e rankings

O projeto utiliza o localStorage do navegador para guardar as informações.

Histórico de jogadores

Registra o nome e a pontuação das partidas realizadas.

Ranking Extra

Organiza as pontuações da maior para a menor e mantém os 10 melhores resultados.

🔊 Efeitos sonoros

O jogo possui sons para diferentes acontecimentos:

Contagem regressiva;

Coleta de frutas;

Perda de vida;

Derrota;

Início da partida.

Os efeitos são produzidos pelo JavaScript utilizando a Web Audio API.

🎨 Imagens

Para manter o projeto organizado, todas as imagens devem ficar dentro da pasta:

imagem/

Exemplo:

imagem/Fundo4.png
imagem/Fundo_do_tabulero.jpg

📁 Estrutura do projeto

A-Cobra-vai-Fumar/
│
├── index.html
├── snake.css
├── snake.js
├── README.md
│
└── imagem/
    ├── Fundo4.png
    └── Fundo_do_tabulero.jpg

🛠️ Tecnologias utilizadas

HTML5

CSS3

JavaScript

Canvas API

Web Audio API

LocalStorage

🚀 Como executar

Não é necessário instalar nenhuma biblioteca.

Baixe ou clone o projeto.

Mantenha os arquivos na estrutura indicada acima.

Abra o index.html no navegador.

Digite seu nome.

Pressione Enter.

Use as setas para controlar a cobra.

🌐 Link do projeto

Site: [adicione aqui o link do seu site]

📚 Objetivo do projeto

O projeto foi desenvolvido para praticar conceitos de desenvolvimento web e lógica de programação, incluindo manipulação do DOM, eventos de teclado, funções JavaScript, Canvas, armazenamento com localStorage e reprodução de sons.

📞 Contato

E-mail: davidcapulot2025@gmail.com

Celular: 21965201025

⭐ A Cobra Vai Fumar! — um projeto simples inspirado no clássico Snake, com algumas mecânicas extras para deixar a partida mais divertida.
