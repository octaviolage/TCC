# Interpretation-Enabled Software Reuse Detection Based on a Multi-level Birthmark Model

Xu, X., Zheng, Q., Yan, Z., Fan, M., Jia, A., and Liu, T. (2021). Interpretation-enabled software reuse detection based on a multi-level birthmark model. In _2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE)_, pages 873–884. DOI: [10.1109/ICSE43902.2021.00084](https://doi.org/10.1109/ICSE43902.2021.00084)

## 1. Fichamento de Conteúdo

O artigo propõe uma abordagem de detecção de reutilização de código de software chamada Interpretable Software Reuse Detection (ISRD). O objetivo desta abordagem é fornecer uma interpretação detalhada dos resultados de detecção de reutilização de código, além de resistir à ofuscação de semântica e acelerar a detecção. Para alcançar esses objetivos, o ISRD propõe um modelo de marca de nascença multi-nível de granularidade para caracterizar um programa. O modelo envolve três níveis de granularidade para formar uma marca de nascença hierárquica, desde o nível da função, até o nível do bloco básico e, finalmente, o nível da instrução. Além disso, o ISRD também usa reconhecimento de ancoragem para reduzir o número de comparações e acelerar a detecção. Para avaliar o desempenho do ISRD, os autores realizaram experimentos em dois conjuntos de dados diferentes. O primeiro conjunto de dados foi construído a partir de projetos de código aberto, enquanto o segundo conjunto de dados foi fornecido por Bingo e αDiff, que também são ferramentas de analisa a similaridade de código. Os resultados dos experimentos mostraram que o ISRD é interpretável, pode detectar eficaz e eficientemente a reutilização parcial e é resistente à compilação cruzada, superando os melhores métodos existentes. O ISRD obteve um _recall_ de 76,4%, enquanto os melhores métodos existentes obtiveram um _recall_ de 39,9%. Além disso, o ISRD também obteve uma precisão de 94,2% com uma taxa de falsos positivos de 0,1%. Os resultados dos experimentos mostraram que o ISRD é uma abordagem eficaz e eficiente para detectar reutilização de código de software. Além disso, o ISRD também é interpretável, o que significa que os resultados de detecção podem ser facilmente compreendidos.

## 2. Fichamento Bibliográfico 

* _Interpretation-enabled Software Reuse Detection_ (Detecção de reutilização de software habilitada para interpretação) é uma abordagem de detecção de reutilização de software baseado em um modelo de marca de nascença multinível que contém nível de função, nível de bloco básico e nível de instrução arbodagem (página 873).

* _Minimum Branch Path_ (Caminho Mínimo de Ramificação) é o caminho de ramificação mínimo que conecta dois nós de um grafo (página 874).

* _Function Call Graph_ (Grafo de Chamada de Função) é um grafo direcionado, que consiste em um conjunto de nós que representam funções e um conjunto de arestas que representam as relações entre as funções (página 874).

* _Bithmark_ (Marca de Nascença) é um conjunto de características extraídas de um programa que reflete seus comportamentos semânticos, que pode ser usado para identificar exclusivamente um programa e é resiliente à semântica que preserva as transformações do código (página 873).

## 3. Fichamento de Citações 

* _"Through comparison on recall, we can see that ISRD outperforms the three baseline approaches by 27.0% on average, especially outperforms BinGo by 36. 5% on average."_

* _"The results reveal that ISRD is interpretable, can effectively and efficiently detect partial reuse. It is also resilient to cross-compilation, outperforming the state-of-the-art approaches."_

* _"The existing approaches cannot interpret detection results, although they can resist obfuscation caused by cross-compilation to some extent."_

* _"None existing approach can comprehensively overcome the aforementioned limitations except for ISRD, which shows the novelty and advantages of ISRD."_

* _"The ability to comprehensively interpreting the detection results is extremely important since it can provide the details or reasons to make the detection results acceptable or easy to be understood."_
