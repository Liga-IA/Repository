# Teoria

Os algoritmos genéticos são uma classe de algoritmos de otimização inspirados no processo de seleção natural e evolução biológica. Eles foram propostos por John Holland e seus colaboradores na década de 1970 e são amplamente utilizados para resolver problemas de otimização e busca em várias áreas.


A ideia básica por trás dos algoritmos genéticos é simular a evolução de uma população de indivíduos, onde cada indivíduo representa uma solução candidata para o problema em questão. Esses indivíduos são codificados como cromossomos, que consistem em uma sequência de genes. Os genes podem representar características, parâmetros ou qualquer informação relevante para o problema.

A evolução ocorre por meio de um processo iterativo que envolve três principais operadores genéticos:

1. Seleção: A seleção determina quais indivíduos têm uma maior probabilidade de serem escolhidos para reprodução com base em sua aptidão, que é uma medida de quão bom é um indivíduo em relação ao problema. Indivíduos com maior aptidão têm maior probabilidade de serem selecionados, mas a seleção também permite que indivíduos menos aptos sejam escolhidos para manter a diversidade genética.

2. Cruzamento (Crossover): O cruzamento é um operador que combina informações genéticas de dois indivíduos para criar descendentes. Em um ponto de corte aleatório, as partes dos cromossomos dos pais são trocadas para gerar novos cromossomos filhos. O cruzamento permite a criação de novas soluções combinando características favoráveis ​​dos pais.

3. Mutação: A mutação é um operador que introduz pequenas alterações aleatórias nos cromossomos dos indivíduos para aumentar a diversidade genética. Isso permite explorar o espaço de busca de forma mais ampla, evitando que o algoritmo fique preso em ótimos locais subótimos. A taxa de mutação controla a probabilidade de ocorrer mutação em um determinado gene.

Após a aplicação desses operadores genéticos, uma nova geração de indivíduos é formada. Esse processo é repetido por várias gerações até que uma condição de parada seja alcançada, como um número máximo de gerações ou a convergência para uma solução satisfatória.

A principal intuição por trás dos algoritmos genéticos é que, ao longo das iterações, a população evolui para soluções melhores, devido à seleção dos indivíduos mais aptos e à combinação e mutação de seus genes. Esse processo de busca baseado em evolução permite explorar eficientemente o espaço de busca em problemas complexos.

Os algoritmos genéticos possuem uma ampla variedade de aplicações, incluindo problemas de otimização combinatória, como o problema do caixeiro-viajante, problemas de programação, projeto de circuitos, aprendizado de máquina, entre outros.