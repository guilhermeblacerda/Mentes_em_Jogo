# Mentes em jogo  (*/ω＼*)


## Descrição✍️
O projeto "Mentes em Jogo" tem como o objetivo desenvolver um jogo para as pessoas com o espectro autista,  para promover um momento de lazer a esses indivíduos.


E assim, desenvolvemos o nosso jogo! Havendo uma grande inspiração vindo dos jogos de tabuleiro, assim conseguindo promover o desenvolvimento de soft-skills como a paciência e as habilidades sociais.


## O que é necessário para que o jogo aconteça? ⁉️


1. É necessário uma pessoa adulta para mediar a partida e dar as devidas orientações aos jogadores;


2. Tenha a parte física do produto (tutorial de montagem do hardware spós a descrição do Hardware);


## Descrição do Hardware 📫


No tabuleiro, há 4 botões colados nela, o que representa cada jogador individualmente. Cada clique no botão irá mandar o comando ao Arduino que irá rolar um número aleatório de 1 até 6 na tela LCD.


Após o rolamento, as LEDS da casa onde o indivíduo será realocado irão ascender.


Um desafio já pré-salvo dentro do código será escolhido e projetado na tela LCD, e o indivíduo precisará realizar o desafio proposto sem um tempo limite.


## Tutorial de instalação do Hardware 🛠️


### Materiais necessários:


> 1 Arduino Uno;  
> 40 Fios jumpers macho-macho;  
> 8 Fios de cobre;  
> 2 quadrados de acrílico 40cmx40cm;  
> 4 rectángulos de acrílico 6cmx40cm;  
> 8 cabo elétrico;  
> 1 fonte transformador de 5V;  
> Fita LED endereçável de 5V;  
> Tela LCD 20cmx4cm i2c;  
> 4 push buttons;
> Cola específica para acrílico;  
> Fio com Plugue


### 1 Passo: Instalação dos botões


Corte o fio jumper macho-macho no meio.


Desencape os fios dos jumpers e os  dois lados dos cabos elétricos, solde uma ponta de cada cabo com um jumper, pois o fio jumper não possui comprimento suficiente para conectar o arduino com os botões devido a distância.


E o outro lado do cabo elétrico, solde ele com o botão pull-up. Mas tenha atenção em soldá-los na diagonal.


### 2 passo: Conexão dos fios


Já que o botão está soldado em cada ponta com um fio elétrico, conecte uma delas nos respectivos portões digitais e o outro no fio terra (GND).


Portões digitais na qual serão conectados: (A ser colocado).


### Passo 3: Motobomba time.


Agora precisamos conectar tudo, o LED, a fonte (motobomba) e o arduino!


Desencape o fio com o plugue, a única obrigação é conectar o fio verde na parte de aterramento (regra universal, todo fio de aterramento é verde nos cabos com plugue!).


Conecte os fios do LED com as entradas positivas e negativas.


Conecte o fio de LED e a tela LCD com o Arduino.


### Passo 4: O grande final.


Agora que tudo está montado, coloque tudo menos a fonte (grande demais) dentro da caixa de acrílico, cole os botões em cada espaço, parafuse a tela LCD no lugar demarcado.


E pronto! a parte física do nosso projeto está pronto para ser utilizado!


## Tutorial em como instalar o programa ao Arduino 🤖


### O que vai ser necessário:


> Ter o Arduino IDE instalado na máquina;
> Ter o VScode ou algum editor de código na sua máquina;


## Passo 1: Importar o código.


Agora salve o código na qual está dentro do repositório no Github e importe-o dentro do Arduino IDE.


### Passo 2: Conexão.


Tenha o Python instalado na sua máquina, abra o prompt da sua máquina e insira o código "pip install pyserial".


Use o cabo USB e conecte ele ao Arduino e a sua máquina.


Agora mande o código do computador ao Arduino.


### Pronto! agora tudo já foi instalado!















