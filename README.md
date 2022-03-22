# Monty Hall: solução simples

Código em C++ que simula o jogo de [Monty Hall](https://pt.wikipedia.org/wiki/Problema_de_Monty_Hall)

*fonte: Wikipedia*

O jogo consistia no seguinte: Monty Hall, o apresentador, apresentava três portas aos concorrentes. Atrás de uma delas estava um prêmio (um carro) e, atrás das outras duas, dois bodes.

* Na 1.ª etapa o concorrente escolhe uma das três portas (que ainda não é aberta);

* Na 2.ª etapa, Monty abre uma das outras duas portas que o concorrente não escolheu, revelando que o carro não se encontra nessa porta e revelando um dos bodes;

* Na 3.ª etapa Monty pergunta ao concorrente se quer decidir permanecer com a porta que escolheu no início do jogo ou se ele pretende mudar para a outra porta que ainda está fechada para então a abrir. Agora, com duas portas apenas para escolher — pois uma delas já se viu, na 2.ª etapa, que não tinha o prêmio — e sabendo que o carro está atrás de uma das restantes duas, o concorrente tem que tomar a decisão.

# Requisitos

* C / C++

# Exemplo de saída

Após o jogo rodar 1000 vezes:
```
Porcentagem de vitória após mudar de porta: 68%
Porcentagem permanecendo com a mesma porta: 31%
```
