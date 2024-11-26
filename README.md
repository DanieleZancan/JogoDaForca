# Jogo da Forca - Versão 1 (SIMPLES)

Este é um jogo simples de Forca desenvolvido em Python. O objetivo do jogo é adivinhar a palavra secreta antes que o número de tentativas se esgote. A cada erro, uma parte do corpo de um boneco é desenhada, e o jogo termina quando o jogador adivinha a palavra ou perde todas as tentativas.

## Funcionalidades

- **Palavras Aleatórias**: O jogo escolhe uma palavra aleatória de uma lista.
- **Tentativas do Jogador**: O jogador tenta adivinhar a palavra, digitando uma letra por vez.
- **Desenho da Forca**: O boneco é desenhado conforme o jogador erra.
- **Verificação de Letras**: O jogo verifica se a letra inserida está na palavra e atualiza o estado da palavra oculta.
- **Número de Chances**: O jogador tem 6 chances para adivinhar a palavra corretamente.

## Requisitos

- **Python 3.x** instalado na sua máquina.

## Como Jogar

1. O jogo escolhe uma palavra aleatória da lista.
2. Você deve tentar adivinhar a palavra, digitando uma letra por vez.
3. Cada erro resulta em uma parte do boneco da forca sendo desenhada.
4. O jogo termina quando você adivinhar a palavra ou se esgotarem as tentativas.

### Regras

- Você tem 6 chances para errar.
- O objetivo é adivinhar a palavra secreta antes de perder todas as chances.

## Como Rodar o Jogo

1. Certifique-se de ter o **Python 3.x** instalado em sua máquina.
   - Você pode verificar se o Python está instalado executando o comando `python --version` ou `python3 --version` no terminal.

2. Baixe ou clone este repositório.

3. Execute o arquivo Python:

   ```bash
   python jogo_da_forca.py
