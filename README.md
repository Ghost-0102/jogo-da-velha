# Jogo da velha - Linguagem C
Pedro Gulherme Cardoso Silva Lima
## ➡️Estrutura Fundamental do Jogo

-> Tabuleiro: Uma matriz 3x3 que representará as casas do jogo.

-> Exibição do Tabuleiro: Uma função para mostrar o estado atual do jogo no console.

-> Lógica de Jogada: Mecanismos para que os jogadores 'X' and 'O' possam inserir suas jogadas.

-> Verificação de Vitória e Empate: Lógica para determinar se um jogador venceu a partida ou se o jogo terminou em empate.

-> Laço Principal do Jogo: A estrutura que manterá o jogo em execução até que haja um vencedor ou um empate.

<hr>

## 📌 Avaliação da linguagem

### Sistema de tipos: sistema de tipagem estática
### Forma de execução: compilação

<hr>

## 📌 Justificativa das Escolhas de Fluxo de Controle

###  - Laço principal do jogo (while)

Justificativa: Número de Iterações Indeterminado: A principal razão para usar um while é que o número total de turnos do jogo não é fixo. 
<img width="523" height="332" alt="image" src="https://github.com/user-attachments/assets/d8b17283-4610-4b45-85d4-0b9717b80616" />


### - Laços de inicialização e Exibição do tabuleiro (for)

Justifiva: Número de Iterações Conhecido: O tabuleiro do jogo da velha tem um tamanho fixo e conhecido: 3x3.
<img width="411" height="231" alt="image" src="https://github.com/user-attachments/assets/3692910e-0f62-43a1-acdb-e7b0509c4117" />

### - Validação da jogada do usuário (while)

Justificativa: Garantir a execução pelo menos uma vez.
<img width="1286" height="434" alt="image" src="https://github.com/user-attachments/assets/ae24b0fc-8f9b-47d7-8834-cfa948ca9812" />


### -  Estruturas de Decisão (if / else)
Justificativa: São usados para alternar o jogador e para determinar o resultado final do jogo.
<img width="521" height="325" alt="image" src="https://github.com/user-attachments/assets/95718620-f575-4db4-bff0-6b228c9e4d44" />



## 📌 Modularização

### - O Laço Principal do Jogo (A Função main)

Criei a função main que orquestrará todo o jogo, alternando entre os jogadores e verificando as condições de término a cada rodada.

<img width="518" height="565" alt="image" src="https://github.com/user-attachments/assets/556b72a8-8145-485f-8dfb-584c4c706226" />


