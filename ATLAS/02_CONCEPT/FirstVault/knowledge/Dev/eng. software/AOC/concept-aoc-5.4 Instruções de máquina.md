---
tags:
  - learning
  - oldVoult
HUB:
  - "[[hub-aoc]]"
---
### 5.4 Instruções de máquina

A instrução de máquina é uma ordem que a Unidade Central de Processamento (UCP) recebe para realizar uma operação específica, como somar, subtrair ou transferir dados. As instruções e dados dos programas são armazenados na memória, e a UCP é responsável por executá-los. Em resumo, a instrução de máquina é a base da linguagem de programação, permitindo que os programadores escrevam códigos que possam ser executados pelos computadores.

Para que um computador possa entender e executar instruções, é necessário detalhá-las em pequenas etapas. Isso acontece porque os computadores são projetados para executar pequenas operações básicas, como soma e subtração. As pequenas etapas de uma instrução dependem do conjunto de instruções que o computador possui.

Assim, uma instrução de máquina pode ser definida pela formalização de uma operação básica que o hardware é capaz de realizar diretamente (MONTEIRO, 2007). Em outras palavras, consiste em transformar instruções mais complexas em uma sequência de instruções básicas e compreensíveis pelo processador.


Para exemplificar, vamos considerar um processador com uma ULA capaz de executar a soma ou a multiplicação de dois números (operações básicas), mas não as duas coisas ao mesmo tempo. Agora imaginem que esse processador precisa executar: X = A + B .C de uma só vez. Isso irá gerar a necessidade de transformar essa instrução, considerada complexa para esse processador, em uma sequência de instruções mais básicas, da seguinte forma:

– Executar primeiro: T = B.C (sendo que T é um registrador ou memória temporária) – Em seguida realizar a operação: X = A + T

O projeto de um processador é centrado no conjunto de instruções de máquina que se deseja que ele execute, ou seja, do conjunto de operações primitivas que ele poderá executar. Quanto menor e mais simples for o conjunto de instruções, mais rápido é o ciclo de tempo do processador

Um processador precisa dispor de instruções para: movimentação de dados; aritméticas; lógicas; edição; deslocamento; manipulação de registros de índice; desvio; modificação de memória; formais de ligação à sub-rotina; manipulação de pilha; entrada e saída e de controle.

Atualmente, há duas tecnologias de projeto de processadores empregadas pelos fabricantes de computadores

– Sistemas com conjunto de instruções complexo (Complex Instruction Set Computers – CISC), e
– Sistemas com conjunto de instruções reduzido (Reduced Instruction Set Computers – RISC).

[[concept-aoc-1.27-arquiteturas-risc-e-cisc]]



![[concept-aoc-1.25-formato-das-instrucoes]]