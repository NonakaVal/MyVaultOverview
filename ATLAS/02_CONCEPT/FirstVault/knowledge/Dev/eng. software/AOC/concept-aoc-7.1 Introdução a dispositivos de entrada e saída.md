---
tags:
  - learning
  - oldVoult
HUB:
  - "[[hub-aoc]]"
---
### 7.1 Introdução a dispositivos de entrada e saída

De acordo com o modelo previsto por [[1.2-modelo-de-von-neumann|Von-Neumann]] e apresentado ao longo das seções anteriores, um computador deve ser capaz de armazenar dados e instruções necessários para a execução de uma tarefa, na memória e no formato binário. Para que possam ser executados, esses dados e instruções são buscados pela [[1.13-organizacao-do-processador|UCP]]  diretamente na memória. É na memória também que o resultado desse processamento será disponibilizado. Como esses dados e instruções chegaram à memória? Como o resultado do processamento desse conteúdo mantido na memória é retornado ao usuário?

A resposta para essas perguntas é que são necessários elementos que permitam a interface do usuário com o computador, tanto para dar a entrada de dados e instruções quanto para proporcionar a saída de resultados ao usuário, no formato adequado, tal qual foi solicitado.

:ril_information:
 *Interface: é a fronteira ou canal de comunicação que define a forma de comunicação entre duas entidades (ex.: usuário, computador)
 
Esses elementos de interface podem ser chamados de dispositivos (ou periféricos) de entrada e saída (E/S). São considerados um subsistema de memória, pois fazem parte do sistema maior que é o sistema computacional, onde os dispositivos de E/S compõem o chamado subsistema de E/S, o qual, segundo Monteiro (2007), deve ser capaz de realizar duas funções:

a) receber ou enviar informações ao meio exterior;
b) converter as informações (de entrada e saída) em uma forma inteligível para a máquina (se estiver recebendo) ou para o programador ou usuário (se estiver enviando).


Dentre os diversos dispositivos de E/S podemos citar: teclado, mouse, monitor de vídeo, impressora, webcam, modem, dispositivos de armazenamento (ex.: disco rígido, CD/DVD – ROM, pen-drive). Esses dispositivos se interligam à UCP e memória principal através do barramento de expansão (apresentado na Aula 5) e podem ser classificados em duas categorias: entrada (teclado, mouse, webcam, modem, disco rígido) e saída (impressoras, disco rígido, monitor de vídeo). Sublinhamos que o disco rígido, assim como outros meios de armazenamento, são dispositivos tanto de entrada quanto de saída.

Monteiro (2007) destaca algumas observações relevantes que influenciam na comunicação dos dispositivos com a UCP e memória principal. São elas:

Lembramos que todos os estímulos gerados pelos dispositivos de E/S, por exemplo - a pressão de uma tecla, são convertidos em vários sinais elétricos, com diferentes intensidades, podendo representar os valores 0 ou 1

Comunicar diretamente UCP e periféricos seria complicado devido às diferenças de velocidade entre eles. A tabela 7.1 mostra exemplos de dispositivos de E/S e suas velocidades de transmissão de dados.

tabela-entrada-e-saida-image
Além da velocidade, outro aspecto que diferencia os dispositivos de E/S é a sua forma de comunicação. A comunicação entre o núcleo do computador e os dispositivos de E/S poderia ser classificada em (MONTEIRO, 2007):
![[concept-aoc-1.23-barramento-de-controle]]
 conforme a Figura 7.1.



b) Comunicação paralela: a informação pode ser transmitida/recebida em grupos de bits de cada vez, isto é, um grupo de bits é transmitido simultaneamente de cada vez, conforme apresenta a Figura 7.2.




Devido às diferenças elétricas entre UCP e periféricos, dispositivos intermediários realizam a "tradução" e compatibilização de sinais, além de outras tarefas de controle, permitindo a comunicação entre eles.

Os dispositivos possuem algumas denominações. A mais comum seria interface de E/S, mas comercialmente podem ser encontrados como controlador ou adaptador, adicionando-se o nome do dispositivo (ex.: controlador de vídeo, controlador de disco). A função de todos é sempre a mesma: compatibilizar as diferentes características de um periférico e da UCP/memória principal, permitindo um fluxo correto de dados em uma velocidade adequada a ambos os elementos que estão sendo interconectados. A Figura 7.3 apresenta exemplos de interfaces.

Os dispositivos intermediários que realizam a compatibilização de sinais entre UCP e periféricos podem ser chamados de interface de E/S, controlador ou adaptador. Sua função é permitir o fluxo correto de dados entre os elementos interconectados. Exemplos de interfaces podem ser vistos na Figura 7.3.


![[concept-aoc-1.34-ucp-e-dispositivos-de-es]]