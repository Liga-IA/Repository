# Teoria de Algoritmos Genéticos (Computação Evolucionária)

Você já ouviu falar dos **algoritmos genéticos**? Eles são como uma versão high-tech do processo de evolução biológica! Imagine uma galera de soluções candidatas para um problema, cada uma representada por um indivíduo. Esses indivíduos são como cromossomos cheios de genes, que podem ser características, parâmetros ou qualquer informação importante.

Aí vem a parte divertida! Esses indivíduos passam por uma verdadeira competição para se destacarem. 
A **seleção** entra em ação e escolhe os mais aptos, aqueles que têm uma performance melhor. Mas olha só, a diversidade genética é importante, então até os menos aptos têm chance de serem escolhidos. É tipo um reality show onde até o azarão pode ganhar uma chance!

<p align="center">
  <img src="https://media.giphy.com/media/Th49xtsrSFJVsIGtkB/giphy.gif" alt="GIF Neymar e Paquetá">
</p>
E aí temos o  **cruzamento**, um verdadeiro encontro genético! Aqui, partes dos cromossomos dos pais se misturam, criando uma nova geração. É como se o talento dos pais se unisse para formar descendentes ainda melhores. É como se Neymar e Paquetá se juntassem em campo para criar uma super jogada!

E não podemos esquecer da **mutação**! É quando uma pequena dose de loucura aleatória é adicionada aos genes dos indivíduos. Isso aumenta a diversidade genética e ajuda a explorar novos caminhos no problema. É como se de repente um gene resolvesse dançar o tango enquanto os outros estavam todos no samba!

<p align="center">
  <img src="https://media.giphy.com/media/3o6Mb9DvVlkBSiLToI/giphy.gif" alt="GIF Mutação">
</p>
Toda essa dança genética acontece por várias gerações até que o algoritmo encontre uma solução satisfatória ou atinja um limite de gerações. É como um jogo de tentativa e erro, mas com uma galera evoluindo junto!

A chance de um indivíduo da população ser selecionado para a próxima geração depende da função de aptidão ou fitness desse indivíduo

A ideia por trás desses algoritmos é bem legal: ao longo do tempo, a população evolui e encontra soluções cada vez melhores. É tipo uma turma de amigos que vai se superando em cada desafio, graças à combinação dos mais talentosos e a algumas surpresas aleatórias pelo caminho.

![image](https://github.com/Liga-IA/Repository/assets/93664169/bdac6c78-1b8d-4b92-be53-80e93c24e10a)

## População de Indivíduos
A cada geração, a população de indivíduos é representada por uma estrutura de dados S, onde cada solução xi é avaliada e recebe uma medida de aptidão (fitness). Essa medida de aptidão reflete o quão bem a solução se adapta ao problema em questão.

## Operador de Cruzamento
O operador de cruzamento, também conhecido como recombinação, desempenha um papel importante na criação de novos indivíduos. Ele transfere características entre dois ou mais indivíduos, criando uma mistura de informações genéticas. É como se estivéssemos misturando o melhor dos pais para criar filhos ainda melhores!

![image](https://github.com/Liga-IA/Repository/assets/93664169/a22200f4-9030-4281-9861-3ace67bbd15c)

O **cruzamento** é o operador responsável pela recombinação de características dos pais durante a reprodução, permitindo que as próximas gerações herdem essas características. Ele é considerado o operador genético predominante, por isso é aplicado com probabilidade dada pela taxa de crossover Pc, que deve ser maior que a taxa de mutação.

Este operador pode, ainda, ser utilizado de várias maneiras; as mais utilizadas são:

um-ponto: um ponto de cruzamento é escolhido e a partir deste ponto as informações genéticas dos pais serão trocadas. As informações anteriores a este ponto em um dos pais são ligadas às informações posteriores à este ponto no outro pai, como é mostrado no exemplo da figura abaixo:

multi-pontos: é uma generalização desta idéia de troca de material genético através de pontos, onde muitos pontos de cruzamento podem ser utilizados.

uniforme: não utiliza pontos de cruzamento, mas determina, através de um parâmetro global, qual a probabilidade de cada variável ser trocada entre os pais.

![cross_an](https://github.com/Liga-IA/Repository/assets/93664169/466760a7-0101-49ec-ad4e-a4fa49fe93d3)


Um exemplo de crossover de um ponto.
(a) dois indivíduos são escolhidos.
(b) um ponto (4) de crossover é escolhido.
(c) são recombinadas as características, gerando dois novos indivíduos.


## Operador de Mutação
A mutação é outro operador fundamental nos algoritmos evolutivos. Ele é responsável por introduzir mudanças aleatórias nos atributos de um indivíduo. Essas alterações podem ajudar os indivíduos a se adaptarem a novas condições do ambiente. É como se estivéssemos permitindo algumas surpresas inesperadas no processo evolutivo.


![image](https://github.com/Liga-IA/Repository/assets/93664169/52c664c0-b832-4d6d-8ad0-1dcd67d2cca0)


## Reprodução
O operador genético de reprodução é responsável por copiar indivíduos de uma população para outra. É como se estivéssemos passando adiante os genes dos indivíduos mais aptos para as gerações futuras.

## Seleção
A seleção é um processo que emula os princípios da reprodução assexuada e seleção natural. Geralmente, é criada uma população temporária de N indivíduos, selecionados com base na probabilidade proporcional à sua aptidão relativa. Ou seja, quanto mais apto o indivíduo, maior a probabilidade de ser selecionado. É como um concurso de talentos, onde os melhores têm mais chances de avançar. 
Em geral, gera-se uma população temporária de N indivíduos extraídos com probabilidade proporcional ao fitness relativo de cada indivíduo no população.


![image](https://github.com/Liga-IA/Repository/assets/93664169/a94e8ae6-1016-41fb-bad7-46109942a035)

A probabilidade de seleção de um cromossomo S é determinada por um cálculo específico que leva em consideração sua aptidão em relação aos outros indivíduos da população.

Com todos esses ingredientes combinados, os algoritmos evolutivos buscam encontrar soluções cada vez melhores ao longo do tempo. 

E o mais incrível é que esses algoritmos genéticos têm uma galera de aplicações legais! Eles ajudam a resolver problemas complexos, como o do caixeiro-viajante (aquele que precisa visitar várias cidades), projetos de circuitos, programação e até aprendizado de máquina. Eles são como os super-heróis da otimização!

Agora você já conhece a teoria por trás dos algoritmos genéticos. Prontinho para embarcar nessa aventura genética e solucionar problemas de forma superdivertida? Vamos lá!
