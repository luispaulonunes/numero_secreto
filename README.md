# Jogo do Número Secreto 🎲

Este é um jogo interativo desenvolvido com **HTML**, **CSS** e **JavaScript**, no qual o jogador precisa adivinhar um número secreto gerado aleatoriamente. O jogo utiliza efeitos de voz para melhorar a experiência do usuário.

---

## 🎯 Objetivo do Jogo

Adivinhe o número secreto escolhido aleatoriamente entre 1 e 50. A cada tentativa, você receberá dicas se o número secreto é maior ou menor do que o número chutado.

---

## 🛠️ Funcionalidades

- **Número secreto aleatório:** Gerado automaticamente para cada nova partida.
- **Dicas interativas:** Mostra se o número secreto é maior ou menor que o chute.
- **Feedback em áudio:** Utiliza a biblioteca [ResponsiveVoice](https://responsivevoice.org/) para leitura de mensagens.
- **Sistema de tentativas:** Exibe o número de tentativas realizadas para acertar o número.
- **Botão de reiniciar:** Inicia uma nova partida facilmente.

---

## 📋 Tecnologias Utilizadas

- **HTML5:** Estrutura do jogo.
- **CSS3:** Estilização e responsividade.
- **JavaScript:** Lógica do jogo.
- **ResponsiveVoice.js:** Integração de feedback em áudio.

---

## 🚀 Como Jogar

1. Escolha um número entre 1 e 50 no campo de entrada.
2. Clique no botão **"Chutar"** para submeter sua tentativa.
3. O jogo dará dicas sobre se o número secreto é maior ou menor.
4. Continue tentando até acertar o número secreto.
5. Após acertar, clique no botão **"Novo jogo"** para reiniciar.

---

## 📂 Estrutura do Projeto

```plaintext
.
├── index.html       # Estrutura do HTML
├── style.css        # Estilização do jogo
├── app.js           # Lógica do jogo em JavaScript
├── img/             # Imagens utilizadas no projeto
└── README.md        # Documentação do projeto
