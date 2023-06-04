# Problema da Mochila

O problema da mochila envolve um ladrão que deve escolher itens de um conjunto disponível para colocar em sua mochila, com o objetivo de maximizar o valor total dos itens, respeitando a capacidade máxima da mochila.

Formalmente, o problema é definido da seguinte maneira:

Dado um conjunto de n itens, cada um com um valor e um peso associado, e uma mochila com uma capacidade máxima, o objetivo é determinar a melhor combinação de itens a serem colocados na mochila, de forma que o valor total seja maximizado e o peso total não exceda a capacidade da mochila.

Existem diferentes variantes do problema da mochila, mas a mais comum é a chamada "mochila 0/1". Nessa variante, cada item pode ser colocado na mochila apenas uma vez, ou seja, não é permitido dividir os itens. O item está ou não está presente na mochila.

Para resolver esse problema usando algoritmos genéticos, cada indivíduo da população é uma possível solução, representada como um vetor binário de tamanho n, onde n é o número de itens disponíveis. Cada posição do vetor indica se o item correspondente está ou não na mochila.

A função de aptidão (fitness function) avalia a qualidade de cada solução, levando em consideração o valor total dos itens na mochila e verificando se o peso total não excede a capacidade máxima.

Durante o processo evolutivo, o algoritmo genético utiliza os operadores genéticos (seleção, cruzamento e mutação) para criar novas soluções, combinando características favoráveis dos indivíduos mais aptos e explorando o espaço de busca.

O algoritmo continua a evoluir a população por várias gerações até atingir um critério de parada, como um número máximo de gerações ou a convergência para uma solução satisfatória.