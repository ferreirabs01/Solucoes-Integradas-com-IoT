#Padroes em eletrônica
---
>Led polo positivo / polo negativo 

![alt text](image-10.png)

A haste (perna) maior do LED é o lado positivo e a menor é o lado negativo. Você pode ver também pelo lado mais achatado, que é o lado negativo enquanto o lado arredondado é o positivo.


>cores fios 


>Entradas 
>Portas Digitais:

As portas digitais podem ser configuradas para serem usadas como entradas ou saídas.
Como entradas, elas só podem detectar dois estados distintos: HIGH (alto) ou LOW (baixo), representados por níveis de tensão específicos (geralmente 5V para HIGH e 0V para LOW).
Como saídas, elas podem fornecer um sinal digital para controlar componentes externos, como LEDs, motores ou outros dispositivos, em que o controle é binário (ligado/desligado, verdadeiro/falso).
As portas digitais não podem medir valores analógicos diretamente.

>Portas Analógicas:

As portas analógicas são usadas para medir valores de tensão em uma faixa contínua de valores.
Elas podem ser utilizadas para ler sinais analógicos de sensores, como potenciômetros, sensores de temperatura, sensores de luz, entre outros.
As portas analógicas têm uma resolução limitada, o que significa que elas podem representar apenas um número finito de valores dentro da faixa de leitura.
No Arduino Uno, por exemplo, as portas analógicas têm uma resolução de 10 bits, o que significa que elas podem representar valores de 0 a 1023 (2^10 - 1).

#Em resumo, enquanto as portas digitais lidam com sinais binários (ligado/desligado), as portas analógicas lidam com sinais analógicos que variam continuamente dentro de uma faixa de valores. Essa diferença fundamental permite uma variedade de aplicações diferentes em projetos eletrônicos.