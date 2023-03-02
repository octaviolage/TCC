# InspectJS: leveraging code similarity and user-feedback for effective taint specification inference for JavaScript

Dutta, S., Garbervetsky, D., Lahiri, S. K., and Sch ̈afer, M. (2022). Inspectjs: Leveraging code similarity and user-feedback for effective taint specification inference for javascript. In _2022 IEEE/ACM 44th International Conference on Software Engineering: Software Engineering in Practice (ICSE-SEIP)_, pages 165–174. [DOI: 10.1145/3510457.3513048](https://ieeexplore.ieee.org/document/9794015)

## 1. Fichamento de Conteúdo

O artigo descreve o trabalho de pesquisa realizado para melhorar a análise de segurança de código JavaScript usando uma ferramenta própria baseada no _framework_ CodeQL. O objetivo é usar uma abordagem de aprendizado de máquina para vulnerabilidades de segurança em bibliotecas JavaScript a partir de dados de fluxo de dados estáticos. Para isso, foi desenvolvida uma ferramenta chamada InspectJS. A metodologia usada foi a combinação de uma abordagem probabilística para prever características de possíveis vulnerabilidades a partir de informações de fluxo de dados estáticos com um mecanismo de refinamento baseado na similaridade de código para ajustar a pontuação de previsão com base na sua similaridade com as vulnerabilidades conhecidas. Além disso, três técnicas foram usadas para organizar as previsões de contaminação com base em sua pontuação, generalidade e similaridade entre si. Um experimento foi realizado para avaliar a qualidade das previsões produzidas por InspectJS em códigos reais. Os resultados mostraram que a ferramenta conseguiu encontrar vulnerabilidades adicionais que não estavam presentes nos modelos manualmente escritos. Em suma, o trabalho contribuiu com uma combinação inovadora de abordagens de aprendizado de máquina e refinamento de código para identificar código malicioso em bibliotecas JavaScript.

## 2. Fichamento Bibliográfico 

* _Security vulnerabilities_ (Vulnerabilidades de segurança) são trechos de código que podem ser usados para comprometer a segurança de um sistema (página 168).

* CodeQL é um _framework_ de análise de código estático desenvolvida pela GitHub para encontrar vulnerabilidades de segurança em código  (página 166).

* InspectJS é a ferramenta desenvolvida pelos autores para melhorar a análise de segurança de código JavaScript baseada no _framework_ CodeQL (página 166).

* _Taint analysis_ (Análise de contaminação) é uma técnica de análise estática de código que identifica a propagação de dados sensíveis em um programa (página 165).

* _Machine Learning_ (Aprendizado de máquina) é uma técnica de aprendizado de padrões que permite que os sistemas aprendam com dados, sem serem explicitamente programados (página 165).

## 3. Fichamento de Citações 

* _We have implemented our approach in a tool called InspectJS, which is based on the CodeQL analysis framework._

* _We propose three criteria for organizing predictions: by score as determined by the probabilistic inference and refined using code similarity; by generality; and by syntactic similarity._

* _We show that the machine-learning component can successfully infer many new taint sinks that either are not part of the manual modelling or are not detected due to analysis incompleteness._

* _We have, however, provided evidence that InspectJS finds additional sinks missing from manually-written models that have been maintained by domain experts over many years, thereby showing the advantages of complementing manual modeling with automated techniques._
