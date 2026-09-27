# 🐍 A Cobra Vai Fumar!

Um jogo de cobrinha inspirado no clássico **Snake**, desenvolvido com **HTML, CSS e JavaScript**, trazendo algumas mecânicas extras para deixar a experiência mais divertida e desafiadora.

O jogador controla a cobra, coleta frutas, acumula pontos e tenta alcançar as maiores pontuações sem bater nas paredes ou no próprio corpo.

🔗 **[Jogue online agora](https://dcapulot.github.io/A-Cobra-vai-Fumar/)**

---

## 🎮 Sobre o projeto

**A Cobra Vai Fumar!** é um projeto desenvolvido para praticar conceitos de desenvolvimento web e lógica de programação.

Além da mecânica tradicional do Snake, o jogo possui:

- 🍎 Frutas com diferentes pontuações;
- ❤️ Sistema de vidas;
- 🏆 Sistema de recordes;
- 📊 Ranking com os 10 melhores resultados;
- 👤 Histórico de jogadores;
- 🔊 Efeitos sonoros;
- ⏱️ Contagem regressiva;
- 🐍 Aumento progressivo da velocidade;
- 🎯 Fruta com movimentação especial;
- 💾 Salvamento de dados utilizando `localStorage`.

---

## 🕹️ Como jogar

Ao abrir o jogo, digite seu nome no menu inicial e pressione **Enter** para começar.

O objetivo é simples:
> **Controle a cobra, coma as frutas, faça o máximo de pontos possível e tente sobreviver até o fim!**

### 🎯 Controles

| Tecla                 | Ação                            |
| --------------------- | ------------------------------- |
| ⬆️ Seta para cima     | Movimenta a cobra para cima     |
| ⬇️ Seta para baixo    | Movimenta a cobra para baixo    |
| ⬅️ Seta para esquerda | Movimenta a cobra para esquerda |
| ➡️ Seta para direita  | Movimenta a cobra para direita  |

O jogo também possui botões para:

- ▶️ Iniciar;
- ⏸️ Pausar;
- 🔄 Reiniciar.

---

## 🍎 Frutas

Existem três tipos de frutas no jogo.

| Fruta      | Pontuação |
| ---------- | --------- |
| 🔴 Vermelha | 10 pontos |
| 🟡 Amarela  | 20 pontos |
| 🔵 Azul     | 30 pontos |

As frutas aparecem em posições aleatórias do tabuleiro e o sistema evita que elas sejam colocadas sobre o corpo da cobra.

---

## 🐍 Mecânica especial

Depois que o jogador coleta **7 frutas**, uma mecânica especial é ativada.

A fruta passa a **se movimentar pelo tabuleiro**, aumentando o nível de dificuldade.

O jogador precisa acompanhar a posição da fruta enquanto continua controlando a cobra.

Além disso, a **velocidade da cobra aumenta conforme a pontuação cresce**, deixando a partida progressivamente mais desafiadora.

---

## ❤️ Sistema de vidas

O jogador começa a partida com:

**❤️ 3 vidas**

Uma vida é perdida quando a cobra:

- 🧱 Bate em uma parede;
- 🐍 Bate no próprio corpo.

Caso ainda existam vidas, a cobra é reposicionada e uma **contagem regressiva** acontece antes da partida continuar.

Quando todas as vidas acabam:
> 💀 **Fim de jogo!**

O resultado da partida é então salvo no histórico e pode aparecer no ranking.

---

## 🏆 Recorde e ranking

O jogo utiliza o **LocalStorage do navegador** para armazenar informações mesmo depois que a página é recarregada.

### 👤 Histórico de jogadores

O histórico registra informações das partidas realizadas, incluindo:

- Nome do jogador;
- Pontuação obtida.

### 🥇 Ranking Extra

O ranking organiza as pontuações da **maior para a menor** e mantém os **10 melhores resultados**.

Isso permite que diferentes jogadores tentem superar as melhores pontuações registradas no navegador.

---

## 🔊 Efeitos sonoros

O jogo possui efeitos sonoros para diferentes acontecimentos durante a partida.

Entre eles:

- ⏱️ Contagem regressiva;
- 🍎 Coleta de frutas;
- ❤️ Perda de vida;
- 💀 Derrota;
- ▶️ Início da partida.

Os efeitos sonoros são produzidos diretamente pelo JavaScript utilizando a **Web Audio API**, sem necessidade de bibliotecas externas de áudio.

---

## 🎨 Imagens

Para manter o projeto organizado, as imagens utilizadas pelo jogo ficam dentro da pasta:

```
Imagens/
```

### Exemplos

```
Imagens/Fundo4.png
Imagens/Fundo_do_tabulero.jpg
```

É importante manter os nomes e caminhos dos arquivos de imagem corretos para que o jogo consiga carregá-los.

---

## 📁 Estrutura do projeto

```
A-Cobra-vai-Fumar/
│
├── index.html
├── snake.css
├── snake.js
├── README.md
│
└── Imagens/
    ├── Fundo4.png
    └── Fundo_do_tabulero.jpg
```

---

## 🛠️ Tecnologias utilizadas

### HTML5

Utilizado para criar a estrutura da página e os elementos da interface.

### CSS3

Utilizado para estilização, layout, cores, elementos visuais e apresentação do jogo.

### JavaScript

Responsável pela lógica principal do jogo, incluindo movimentação da cobra, pontuação, vidas, frutas, controles e estados da partida.

### Canvas API

Utilizada para desenhar e atualizar o tabuleiro e os elementos do jogo.

### Web Audio API

Utilizada para gerar os efeitos sonoros da partida diretamente pelo navegador.

### LocalStorage

Utilizado para armazenar:

- Histórico de jogadores;
- Pontuações;
- Ranking.

---

## 🚀 Como executar

Não é necessário instalar bibliotecas ou frameworks.

### 1. Clone o repositório

```bash
git clone https://github.com/DCapulot/A-Cobra-vai-Fumar.git
```

### 2. Entre na pasta

```bash
cd A-Cobra-vai-Fumar
```

### 3. Verifique a estrutura

Certifique-se de que os arquivos estejam organizados desta forma:

```
A-Cobra-vai-Fumar/
├── index.html
├── snake.css
├── snake.js
├── README.md
└── Imagens/
```

### 4. Abra o jogo

Basta abrir o arquivo `index.html` diretamente no navegador (duplo clique ou "Abrir com" → seu navegador preferido).

Não é necessário nenhum servidor local — o jogo roda direto no navegador.

---

## 👤 Autor

**David Capulot Corrêa**

Projeto desenvolvido para fins de estudo e prática de desenvolvimento web.
