# A Double-Edged Sword? Software Reuse and Potential Security Vulnerabilities

Gkortzis, A., Feitosa, D., and Spinellis, D. (2019). A double-edged sword? software reuse and potential security vulnerabilities. In Peng, X., Ampatzoglou, A., and Bhowmik, T., editors, _Reuse in the Big Data Era_, pages 187–203, Cham. Springer International Publishing. DOI: [10.1007/978-3-030-22888-0_13](https://doi.org/10.1007/978-3-030-22888-0_13)

## 1. Fichamento de Conteúdo

O artigo visa investigar a extensão em que a reutilização influencia a segurança de um projeto. Para isso, os autores usam análise estática para identificar possíveis vulnerabilidades e investigar como o código nativo desenvolvido pelo time do projeto e o código reutilizado de componentes de terceiros contribuem para o nível de segurança estimado. A fim de responder às questões de pesquisa, os autores projetaram um estudo de múltiplos casos holísticos, selecionando projetos de código aberto como casos e unidades de análise. Para abordar as questões de pesquisa, os autores construíram um conjunto de dados contendo dois grupos de variáveis para cada unidade de análise: informações do projeto e informações de vulnerabilidade. O conjunto de dados foi construído seguindo um procedimento de cinco etapas, que foi posteriormente automatizado em um conjunto de _scripts_ disponíveis no GitHub. Os resultados do estudo mostraram que os projetos com maior reutilização de código têm maior número de vulnerabilidades. Além disso, os projetos com maior reutilização de código têm maior número de vulnerabilidades de alto risco. Os autores concluíram que a reutilização de código pode ser uma espada de dois gumes, pois, embora ajude a acelerar o desenvolvimento, também pode aumentar o risco de segurança. Eles sugerem que os desenvolvedores devem ter cuidado ao reutilizar código de terceiros e que os estudos de extensão podem abranger o conjunto de dados atual e explorar questões de pesquisa mais aprofundadas relacionadas.

## 2. Fichamento Bibliográfico 

* Heartbleed foi uma vulnerabilidade de segurança grave em um protocolo de criptografia da Internet chamado OpenSSL (página 188).

* _Source Lines of Code_ (Linhas de código-fonte) é uma métrica de software que mede o tamanho de um programa de computador por meio do número de linhas de código-fonte (página 193).

* _Common Weakness Enumeration (CWE)_ é uma lista de fraquezas de software comumente encontradas em software e sistemas de hardware. O CWE é mantido pela MITRE Corporation (página 194).

* SpotBugs é uma ferramenta de análise estática de código-fonte para Java (página 192).

## 3. Fichamento de Citações 

* _"Unsurprisingly, the results suggest that larger projects are associated with more vulnerabilities in both native and reused code. However, they also show that higher reuse ratio is correlated with a lower overall vulnerability density"_

* _"On the other hand, the automation scripts shared through this study could be turned into a tool that could benefit both practitioners and researchers."_

* "_These findings are in line with those of Mohagheghi et al., who performed a comparable study but in a industrial setting and also found a lower defect density (which includes security vulnerabilities) in reused code when compared to native code._"

* _"In summary, we found that the amount of reused code is considerably larger compared to native code. However, the vulnerability density is higher in native code, i.e., it shows a higher count of vulnerabilities per sloc than reused code. These observations culminate in the fact that the amount of vulnerabilities is mostly associated with the reused code"_
