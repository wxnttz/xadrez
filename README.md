# ♟️ Movimentos de Xadrez - Simulação em C

Este projeto simula os **movimentos básicos das peças de xadrez** utilizando estruturas de repetição (`for`, `while`, `do-while`) e recursividade em linguagem C. Ele visa treinar a lógica de programação por meio da visualização dos possíveis movimentos das peças em um tabuleiro 8x8.

## 📌 Níveis de Complexidade

### 🏅 Nível Novato
- Simula os movimentos de:
  - **Torre** (linhas e colunas)
  - **Bispo** (diagonais)
  - **Rainha** (combinação de torre + bispo)
- Utiliza estruturas de repetição simples para imprimir os movimentos no terminal.

### ⚔️ Nível Aventureiro
- Simula o movimento do **Cavalo** em "L".
- Utiliza **loops aninhados** para encontrar todas as 8 possibilidades válidas do cavalo.
- Verifica se os movimentos estão dentro dos limites do tabuleiro (0 a 7).

### 🧠 Nível Mestre
- Apresenta uma **simulação recursiva** dos movimentos do Rei.
- A recursão verifica todas as casas adjacentes ao Rei, mantendo controle de profundidade e posição anterior para evitar repetições.
- Permite visualizar a progressão da função recursiva no console.

## 📥 Entrada de Dados
- Coordenadas iniciais de cada peça são inseridas manualmente no código.
- As posições variam de 0 a 7 (sistema de coordenadas baseado em matriz 8x8).

## 📤 Saída de Dados
- O terminal exibirá todas as casas que a peça escolhida pode se mover a partir da posição inicial informada.

## 🛠️ Como Executar

1. Compile o código com um compilador C:
   ```bash
   gcc xadrez_movimentos.c -o xadrez

2. Execute
   ```bash
   ./"nome do projeto"

3. O terminal exibirá os posicionamentos dos navios ou as áreas afetadas pelas habilidades, dependendo do nível implementado.
