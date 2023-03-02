# An empirical evaluation of GitHub copilot's code suggestions


Nguyen, N. and Nadi, S. (2022). An empirical evaluation of github copilot’s code suggestions. In _2022 IEEE/ACM 19th International Conference on Mining Software Repositories (MSR)_, pages 1–5. DOI: [10.1145/3524842.3528470](https://ieeexplore.ieee.org/document/9796235)


## 1. Fichamento de Conteúdo

Nesse estudo empírico, os autores avaliam a corretude e entendimento do código gerado com a ferramenta GitHub Copilot. Os autores, então, utilizaram um conjunto de 33 questões de uma plataforma de desafios para desenvolvedores, LeetCode, e assim gerar sugestões do Copilot em quatro linguagens de programação diferentes. A corretude do código gerado foi avaliada pela própria bateria de testes fornecida para cada questão do LeetCode. O entendimento do código gerado foi avaliado utilizando uma ferramenta de análise estática de código, SonarQube, que mediu a complexidade ciclomática e cognitiva. Os resultados mostraram que a corretude do código gerado pelo Copilot pode variar entre 61% e 91%, dependendo da linguagem de programação. Ainda sobre a corretude, destaque positivo para a linguagem de programação Java, onde 57% das primeiras sugestões oferecidas já atendiam a todos os casos de testes da plataforma. Para o entendimento de código, os autores observaram que os códigos gerados apresentaram as medianas 5 e 6, para complexidade ciclomática e complexidade cognitiva respectivamente, não havendo diferenças significativas entre as linguagens de programação. Os autores concluem que o Copilot pode ser uma ferramenta útil para desenvolvedores economizarem tempo, mas ainda há espaço para melhorias, como uma geração de código mais simplificada ou compacta e de código que dependa de outras funções já existentes.


## 2. Fichamento Bibliográfico 

* GitHub Copilot é uma ferramenta de inteligência artificial que gera código para desenvolvedores diretamente no editor de código. O código gerado é baseado no contexto do código existente e em exemplos de código de outros desenvolvedores em repositórios de código aberto (página 1).

* LeetCode é uma plataforma de desafios para desenvolvedores que os ajudam a melhorar suas habilidades de programação, expandir seus conhecimentos e se preparar para entrevistas de emprego (página 1).

* SonarQube é uma ferramenta de análise de código estático para a detecção de bugs, vulnerabilidades e código mal escrito em mais de 20 linguagens de programação (página 1).

* _Correctness_ (corretude) é a qualidade de ser correto, de acordo com um padrão ou padrão (página 1).

* _Cyclomatic complexity_ (complexidade cíclica) é uma medida de complexidade de código que mede o número de caminhos lineares independentes em um grafo de fluxo de controle (página 1).

* _Cognitive complexity_ (complexidade cognitiva) é uma medida de complexidade de código que mede a dificuldade de entender o código (página 1).

## 3. Fichamento de Citações 


* _"Overall, we find that Copilot’s Java suggestions have the highest correctness score (57%) while JavaScript is lowest (27%). Copilot’s suggestions also have low complexity with no statistically significant differences between the complexity scores of the same solution in different languages"_

* _"We also find some potential Copilot shortcomings, such as generating code that can be further simplified/compacted and code that relies on undefined helper methods."_

* _"Copilot generally produces understandable code. The median complexity values of Copilot’s solutions are well below the 15-25 thresholds typically used in static analysis tools"_

* _"Copilot will help the developer completely solve their programming task (accepted) or provide them with a useful starting point (partially correct) in 61%-91% of the time, depending on the language."_
