# The Extent of Orphan Vulnerabilities from Code Reuse in Open Source Software

Reid, D., Jahanshahi, M., and Mockus, A. (2022). The extent of orphan vulnerabilities from code reuse in open source software. In 2022 _IEEE/ACM 44th International Conference on Software Engineering (ICSE)_, pages 2104–2115. DOI: [10.1145/3510003.3510216](https:/doi.org/10.1145/3510003.3510216)

## 1. Fichamento de Conteúdo

Esse artigo examina o problema da propagação de vulnerabilidades de segurança de software causadas pelo reuso de trechos de código de software de código aberto. O objetivo deste estudo é gerar ideias para mitigar essas vulnerabilidades e estimular pesquisas acadêmicas adicionais. Para isso, foi realizado um estudo de caso exploratório para melhor compreender o problema. O estudo de caso permitiu que os autores olhassem de perto para um pequeno número de projetos amplamente reutilizados e dentro de seu contexto real. A metodologia do estudo incluiu a seleção de um conjunto de vulnerabilidades conhecidas, identificação de todas as versões afetadas dos arquivos nos repositórios primários e uso da base do World of Code (WoC) para identificar todos os outros projetos de software de código aberto que têm versões do código que precedem a versão afetada ou que são modificadas após ela sem aplicar a correção. O algoritmo foi codificado como uma ferramenta que pode ser usada para qualquer vulnerabilidade ou qualquer outro tipo de defeito. Os autores examinaram em detalhe quatro casos específicos de vulnerabilidades de software conhecidas, incluindo uma vulnerabilidade no libpng, uma vulnerabilidade nova e antiga no OpenSSL e o pacote xz escrito na linguagem Go para contrastar com os outros projetos que eram todos projetos de linguagem C. Os autores examinaram esses quatro casos no contexto, olhando para projetos de código aberto específicos que reutilizam código vulnerável e que são hospedados em plataformas de hospedagem públicas, incluindo GitHub, Bitbucket, SourceForge e outros. Os autores usaram artefatos, observações e contato direto com os mantenedores do projeto (através de _pull requests_ e _issues_), permitindo que eles coletassem mais _insights_ do que usando apenas um método. O contato com os mantenedores do projeto fornece mais insights sobre sua disposição para abordar problemas uma vez que eles estejam cientes das vulnerabilidades. Os resultados do estudo mostraram que as vulnerabilidades mais antigas são mais propensas a serem corrigidas e que os projetos ainda vulneráveis tendem a ser menos ativos do que os projetos corrigidos. Além disso, os autores concluíram que a ferramenta VDiOS desenvolvida para este projeto de pesquisa é capaz de identificar projetos com vulnerabilidades órfãs.

## 2. Fichamento Bibliográfico 

* _Orphan Vulnerabilities_ (vulnerabilidades orfãs) são vulnerabilidades em código não corrigidas mesmo após a correção da vulnerabilidade em uma versão mais recente do código de origem (página 2104).

* _Common Vulnerabilities and Exposures database_ (Banco de Dados de Vulnerabilidades e Exposições Comuns) é uma lista de vulnerabilidades de software conhecidas, mantida pela MITRE Corporation e patrocinada pelo Departamento de Segurança Interna dos Estados Unidos e pela Agência de Segurança Cibernética e Infraestrutura, também dos Estados Unidos (página 2106).

* World of Code é uma base de dados de versionamento de código que permite analisar, rastrear proveniência e medir relacionamentos entre projetos de software de código aberto (página 2106).

## 3. Fichamento de Citações 

* _"Even apparently inactive projects are still publicly available for others to use and spread the vulnerability further. The often long delay in fixing orphan vulnerabilities even in highly popular projects increases the chances of it spreading to new projects"_

* _"Using VDiOS, we find very extensive white-box reuse of vulnerable code with a large number of projects that do not appear to fix the upstream vulnerability. These are cases where reused code contains known vulnerabilities or other bugs that persist in open source projects even though they have been fixed in other projects."_

* _"By using our VDiOS tool layered on top of WoC’s nearly complete collection of OSS in any language, we are able to find a significantly larger number of projects that reuse vulnerable code."_

* _"Overall, we may conclude that extensive code copying in OSS results in an extensive spread of vulnerable code that may take years to fix and that affects not only inactive, but also highly active and popular projects. We also found that many of the projects may not be willing to patch the vulnerabilities even after being provided a fix."_
