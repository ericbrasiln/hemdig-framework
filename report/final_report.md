---
title: Relatório Final da Pesquisa
subtitle: HEMDIG(pt) Framework - Métodos, ferramentas e hemerotecas digitais em português
author: Eric Brasil
date: 2023-10-11
lang: pt
toc: true
toc-own-page: true
numbersections: true
bibliography: ./data/bibliografia/hemdig_general.bib
biblio-style: abnt
link-citations: true
---

## Introdução

Nessa pesquisa, realizada em estágio de pós-doutoramento junto ao Instituto de História Contemporânea, Faculdade de Ciências Sociais e Humanas da Universidade NOVA de Lisboa / IN2PAST — Laboratório Associado para a Investigação e Inovação em Património, Artes, Sustentabilidade e Território[^ihc], busquei enfrentar o problema comum a todos/as que executam a operação historiográfica: o processo de selecionar, recolher, organizar as fontes primárias e realizar sua crítica – a chamada heurística das fontes. Agora, com um aspecto diferente, uma heurística em ambientes digitais, através de ferramentas e dados digitais. O foco aqui está na análise de repositórios e interfaces gráficas que permitem o acesso a periódicos em língua portuguesa digitalizados. 

[^ihc]: O IHC é financiado por fundos nacionais através da FCT — Fundação para a Ciência e a Tecnologia, I.P., no âmbito dos projectos UIDB/04209/2020, UIDP/04209/202o e LA/P/0132/2020.

Tomo como objeto de estudo a Hemeroteca Digital Brasileira, da Fundação Biblioteca Nacional, a coleção de periódicos da Biblioteca Nacional Digital de Portugal, e a Hemeroteca Digital da Hemeroteca Municipal de Lisboa. Analiso tanto as interfaces gráficas e possibilidades de acesso aos dados quanto os acervos disponibilizados. Busco subsidiar reflexões sobre as relações entre teoria, metodologia e epistemologia da História. Essa tarefa foi realizada através da aproximação entre "os saberes fundamentais da pesquisa em história com conhecimentos técnicos de programação, atuando em zonas de troca, interdisciplinares e colaborativas"(BRASIL, 2022, p.189), avançando em pesquisas que venho desenvolvendo e publicando nos anos recentes. Na prática, busquei exercer uma hermenêutica digital, como definidas por Fickers e Clavert:

>Tornar explícito como a produção de conhecimento histórico através de ferramentas e tecnologias digitais é o resultado de um processo complexo de interação humano-máquina, de co-construção do ‘objeto epistêmico’ da inquirição e investigação histórica. (FICKERS, CLAVERT, 2021, parágrafo 6, tradução minha)

Como afirmei anteriormente,

>as novas formas de realizar pesquisas em repositórios e interfaces digitais de buscas impactam, mediam e direcionam tanto a coleta e seleção das fontes quanto sua análise. Diante disso, é fundamental que o método histórico leve em consideração a aplicação de práticas de heurística digital coerentes tanto com as características das ferramentas e métodos utilizados, das fontes e dados trabalhados quanto com as reflexões teóricas básicas da disciplina histórica. (BRASIL, 2022, p. 189)

A partir destas análises e reflexões, desenvolvi um *framework* para pesquisa nos referidos repositórios, buscando encadear um fluxo de trabalho que atende os aspectos metodológicos específicos da disciplina História, contemplando desde a preparação computacional inicial, criação de um plano de gerenciamento dos dados, a pesquisa e análise dos acervos e interfaces gráficas, a coleta e organização dos dados, o tratamento e preservação dos dados.

O *HEMDIG(pt) framework*, portanto, é um enquadramento dos processos de pesquisa composto por uma biblioteca de referências bibliográficas sobre o temas – seus aspectos técnicos e teóricos –, a lista de repositórios de periódicos históricos em português digitalizados, uma documentação acerca de cada um dos repositórios e suas interfaces gráficas (apresentando as principais características, parâmetros possíveis de busca, opções de acesso e resultados); um conjunto de *Jupyter Notebooks* com ferramentas para registro metodológico das pesquisas e resultados, e ferramentas de coletas dos dados; indicação e manual de uso de programas de Reconhecimento Ótico de Caracteres (OCR) e análise de layout (OLR); indicações de estratégias e ferramentas para preservar, documentar e compartilhar os dados e resultados da pesquisa.

Tudo isso está organizado e disponível online em um livro digital, publicado em formato de Jupyter Book, disponível em [https://ericbrasiln.github.io/hemdig-framework/](https://ericbrasiln.github.io/hemdig-framework/), com licença Creative Commons Atribuição-NãoComercial-CompartilhaIgual 4.0 Internacional.

## Cronograma de atividades

| Atividades                                                                                         | 10/22 | 11/22 | 12/22 | 01/23 | 02/23 | 03/23 | 04/23 | 05/23 | 06/23 | 07/23 | 08/23 | 09/23 | 10/23 |
|----------------------------------------------------------------------------------------------------|:------:|:------:|:------:|:------:|:------:|:------:|--------|--------|--------|--------|--------|--------| ------ |
| Levantamento Bibliográfico e organização de biblioteca de referências no Zotero                    | X      | X      |        |        |        |        |        |        |        |        |        |        |        |
| Mapeamento dos repositórios e interfaces gráficas                                                  |        | X      | X      |        |        |        |        |        |        |        |        |        |        |
| Curso de Python Avançado                                                                           |        |        |        | X      | X      | X      | X      |        |        |        |        |        |        |
| Criação do formulário com os critérios de avaliação                                                |        |        |        | X      |        |        | X      |        |        |        |        |        |        |
| Pesquisa e avaliação de ferramentas de código aberto para OCR e OLR                                |        |        |        |        |        | X      |        | X      | X      | X      |        |        |        |
| Criação de jupyter notebooks com passo a passo para criação de relatórios de registro metodológico |        |        |        |        |        | X      | X      |        |        |        |        |        |        |
| Avaliação das interfaces e repositórios                                                            |        |        |        |        |        |        | X      | X      | X      |        |        |        |        |
| Workshop para o LAB_HD                                                                             |        |        |        |        |        |        |        | X      |        |        |        |        |        |
| Criação de jupyter notebooks com scripts para organização e tabulação de dados e metadados         |        |        |        |        |        |        |        |        | X      | X      |        |        |        |
| Escrita de artigo                                                                                  |        |        |        |        |        |        |        |        |        |        | X      | X      | X      |
| Organização do Workflow e finalização do projeto                                                   |        |        |        |        |        |        |        |        |        |        | X      | X      | X      |

## Metodologia

A pesquisa foi desenvolvida no Laboratório de Humanidades Digitais da Universidade Nova de Lisboa, e contou com a supervisão do professor Daniel Alves. A pesquisa foi organizada conforme o cronograma apresentado acima e suas etapas serão descritas a seguir. Mas antes, é importante ressaltar que toda a pesquisa foi realizada utilizando ferramentas e programas de código aberto e livres e todos os dados, resultados e produtos foram disponibilizados online, com licença [Creative Commons Atribuição-NãoComercial-CompartilhaIgual 4.0 Internacional](https://github.com/ericbrasiln/hemdig-framework/blob/main/LICENSE.md).

### Git e Github

As etapas de realização da pesquisa foram controladas e registradas através do sistema de controle de versões Git e utilizei o Github como repositório remoto para armazenamento do histórico de alterações e compartilhamento dos dados e resultados. É possível acessar todos os dados de alterações da pesquisa através do arquivo [log_main.csv](https://github.com/ericbrasiln/hemdig-framework/blob/main/log_main.csv).

Para gerenciar as tarefas e atividades da pesquisa, utilizei a funcionalidade *Projects* do Github, criando quadros *Kanban* para organizar as tarefas em listas de pendências, em andamento e concluídas. É possível acessar a página da pesquisa através do link [https://github.com/users/ericbrasiln/projects/6](https://github.com/users/ericbrasiln/projects/6). A utilização do Github para esse gerenciamento possibilitou o registro de todas as atividades, o acompanhamento do progresso ao longo do tempo e visualizações gráficas do andamento da pesquisa. Foram criados *milestones* para etapas chave, que reuniram conjuntos de *issues* e *pull requests* relacionados a cada uma delas. É possível acessar a lista de *milestones* [aqui](https://github.com/ericbrasiln/hemdig-framework/milestones?state=closed) e todas as *issues* [aqui](https://github.com/ericbrasiln/hemdig-framework/issues). Para melhor organização, foram criadas *labels* para identificar as tarefas relacionadas a cada etapa da pesquisa. É possível acessar a lista de *labels* [aqui](https://github.com/ericbrasiln/hemdig-framework/labels).

No repositório remoto no Github, [https://github.com/ericbrasiln/hemdig-framework](https://github.com/ericbrasiln/hemdig-framework), portanto, estão disponíveis todos os dados, o histórico de mudanças e também a organização geral da pesquisa. Nele também está armazenado o código fonte do Jupyter Book, que foi utilizado para publicar o livro digital da pesquisa, disponível em [https://ericbrasiln.github.io/hemdig-framework/](https://ericbrasiln.github.io/hemdig-framework/). Os arquivos necessários para publicação do livro no Github Pages estão disponíveis no branch `gh-pages` e o código fonte do Jupyter Book está disponível no branch `main`, na pasta `book/`.

### Etapas da pesquisa

A) Organização geral da pesquisa: nessa etapa foi criada a estrutura geral da pesquisa e o plano de gerenciamento de dados, assim como a listagem de repositórios e ferramentas a serem utilizadas. Ver o *milestone* [Organização geral do repo](https://github.com/ericbrasiln/hemdig-framework/milestone/1).

B) Levantamento bibliográfico: aqui foi desenvolvida a estratégia de levantamento bibliográfico,sua implementação, organização e tratamento dos dados. Também foi realizada a inserção dos dados na biblioteca de referências bibliográficas. Ver o *milestone* [Levantamento bibliográfico](https://github.com/ericbrasiln/hemdig-framework/milestone/2).

C) Análise dos acervos dos repositórios: nessa etapa, foi empreendida uma detalhada análise dos conjuntos de dados disponibilizados nas plataformas dos acervos digitais. Ver o *milestone* [Repositórios - Análise dos Dados](https://github.com/ericbrasiln/hemdig-framework/milestone/4).

D) Análise das interfaces gráficas dos acervos: a partir do método *impresso Review*, analisei amplamente as interfaces gráficas dos repositórios, buscando identificar as principais características, parâmetros possíveis de busca, opções de acesso e resultados. Ver o *milestone* [Repositórios e Interfaces Gráficas](https://github.com/ericbrasiln/hemdig-framework/milestone/3).

E) Ferramentas de suporte metodológico: criação e teste de ferramentas de suporte metodológico. Foram criadas ferramentas de raspagem e ferramentas de geração de relatórios de pesquisas. Ver o *milestone* [Ferramentas de suporte metodológico](https://github.com/ericbrasiln/hemdig-framework/milestone/6)

F) Análise e teste de ferramentas de linha de comando para OCR: nessa etapa foram testadas e avaliadas ferramentas de reconhecimento ótico de caracteres (OCR) de linha de comando. Ver o *milestone* [Análise de OCR e OLR](https://github.com/ericbrasiln/hemdig-framework/milestone/5).

G) Análise e teste de programa com interface gráfica para OCR: teste e avaliação do gImageReader, um programa com interface gráfica para reconhecimento ótico de caracteres. Ver o *milestone* [GUI para OCR](https://github.com/ericbrasiln/hemdig-framework/milestone/8).

H) Revisão final e publicação: nessa etapa foram realizadas as revisões finais do livro e do repositório, e a publicação do livro digital. Ver o *milestone* [Publicação](https://github.com/ericbrasiln/hemdig-framework/milestone/7).

## Resultados

Todos os resultados da pesquisa estão organizados, documentados e disponibilizados online. O livro digital da pesquisa está disponível em [https://ericbrasiln.github.io/hemdig-framework/](https://ericbrasiln.github.io/hemdig-framework/). O código fonte do livro está disponível no repositório remoto no Github, [https://github.com/ericbrasiln/hemdig-framework/tree/main/book](https://github.com/ericbrasiln/hemdig-framework/tree/main/book).

O *HEMDIG(pt) framework* representa o resultado mais explícito da pesquisa e reúne um conjunto de dados, tutoriais, indicações e reflexões que podem subsidiar inúmeras pesquisa futuras. As análises dos dados dos acervos da Hemeroteca Digital Brasileira e da coleção de periódicos da Biblioteca Digital Nacional de Portugal, assim como as análises das suas respectivas interfaces gráficas, abrem possibilidades muito amplas para novas pesquisas e publicações.

Além disso, os testes e comparações entre diferentes ferramentas de OCR, tanto de linhas de comando quanto de interface gráfica, geraram resultados substanciais para a elaboração de novas publicações.

O *HEMFIG(pt)* também oferece ferramentas de coleta de dados e geradores de relatórios de busca que favorecerão a realização de pesquisa mais eficientes e com maior qualidade metodológica.

Por fim, a pesquisa também gerou uma série de indicações sobre registro e preservação dos dados assim como a criação de uma bibliografia especializada bastante atualizada e bem organizada para acesso público.

Todo esse material foi armazenado no Zenodo, através da funcionalidade de conectar um repositório do Github, e um DOI foi gerado: [10.5281/zenodo.8397782](https://doi.org/10.5281/zenodo.8397782).

Assim, o produto final da pesquisa se mostra rico para todos e todas que tem interesse em pesquisar jornais históricos digitalizadas em língua portuguesa. Mas não apenas isso, pois possibilita reflexões sobre o próprio caráter da pesquisa histórica em ambientes digitais, suas possibilidades e limites.

Nos aspectos profissionais, esse período de estágio de pós-doutoramento possibilitou a ampliação de um rede de colaborações no campo d história Digital, permitiu que eu avançasse na formação técnica, sobretudo com a linguagem de programação Python; realizasse eventos, palestra e oficinas e gerasse novas publicações e aprofundasse minha atuação como editor do *Programming Historian* em português.

### Dados dos acervos

Lista com os dados dos acervos utilizados no projeto (com links para os diretórios).

#### Hemeroteca Digital Brasileira

- [XML dos dados brutos](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/bndbr/exp_per_marcxml.xml)
- [CSV com dados de periódicos digitalizados em 2019](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/bndbr/bnd-br_periodicos_2019.csv) - também disponível na página da BND-BR.
- [CSV com dados de periódicos digitalizados em 2020](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/bndbr/bnd-br_periodicos_2020.csv) - também disponível na página da BND-BR.
- [CSV dos dados filtrados, contendo as colunas "title", "subtitle", "place", "period", "publisher", "periodicity", "language"](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/bndbr/complete_data.csv)
- [CSV do dataframe final tratado](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/bndbr/dataframe_hdb.csv)
- [CSV de periódicos por décadas](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/bndbr/periodicos_dec.csv)

#### Biblioteca Nacional Digital de Portugal

- [CSV bruto com dados gerais](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/bndpt/bnd-pt.csv) - também disponível na página da BND-PT.
- [CSV bruto apenas com dados de obras em domínio público](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/bndpt/bnd-pt_livre.csv) - também disponível na página da BND-PT.


#### Hemeroteca Digital da Hemeroteca Municipal de Lisboa

- [CSV bruto com os dados coletados da HML](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/hml/hemeroteca_lisboa.csv)
- [CSV com dados de localidades bruto](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/hml/locais_hemeroteca_lisboa_raw.csv)
- [CSV com dados de localidades tratado](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/hml/locais_hemeroteca_lisboa.csv)

### Dados das interfaces

Lista com os dados das interfaces dos acervos utilizados no projeto (com links para os diretórios).

- [Formulário geral de dados básicos](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/avaliacao_interfaces/form_geral.csv)
- [Formulário de revisão das interfaces - modelo *impresso Review*](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/avaliacao_interfaces/InterfaceReview-pt-2023.csv)
- [Formulário de mapeamento geral com base dos critérios de alto nível - modelo *impresso Review*](https://github.com/ericbrasiln/hemdig-framework/blob/main/data/avaliacao_interfaces/InterfaceReview-pt-2023-mapping.tsv)

### Gráficos, visualizações e imagens

Lista dos gráficos e visualizações gerados no projeto.

#### Hemeroteca Digital Brasileira

Acesse [aqui o diretório](https://github.com/ericbrasiln/hemdig-framework/tree/main/repositorios/BND-BR/charts)

#### Biblioteca Nacional Digital de Portugal

Acesse [aqui o diretório](https://github.com/ericbrasiln/hemdig-framework/tree/main/repositorios/BND-PT/charts).

#### Visualizações  das análises das interfaces gráficas - método *impresso Review*

Acesse [aqui o diretório](https://github.com/ericbrasiln/hemdig-framework/tree/main/repositorios/AVA_INTERFACES/impresso_review_method/charts)

#### Imagens utilizadas nos testes de OCR

Acesse [aqui o diretório](https://github.com/ericbrasiln/hemdig-framework/tree/main/ocr_olr/imgs)

### Imagens utilizadas no livro

#### Diagramas

- [Diagrama geral](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/full-diagram.png)
- [Diagrama da 1ª fase](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/1fase_mermaid-diagram-2023-08-21-171600.png)
- [Diagrama da 2ª fase](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/2fase_mermaid-diagram-2023-08-21-172523.png)
- [Diagrama da 3ª fase](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/3fase_mermaid-diagram-2023-08-21-173800.png)
- [Diagrama da 4ª fase](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/4fase_mermaid-diagram-2023-08-21-225902.png)
- [Diagrama da 5ª fase](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/5fase_mermaid-diagram-2023-08-21-225829.png)

#### Logos

- [PNG, Grande, fundo branco](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/logos/logo-lg-white.png)
- [PNG, Grande, fundo preto](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/logos/logo-lg-black.png)
- [PNG, Pequeno, fundo branco](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/logos/logo-sm-white.png)
- [PNG, Pequeno, fundo preto](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/logos/logo-sm-black.png)
- [SVG, Grande, fundo transparente](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/logos/logo-lg.svg)
- [SVG, Pequeno, fundo transparente](https://github.com/ericbrasiln/hemdig-framework/blob/main/book/assets/images/logos/logo-sm.svg)

#### Outras imagens

Acesse [aqui o diretório](https://github.com/ericbrasiln/hemdig-framework/tree/main/book/assets/images)

### Ferramentas

- [Relatórios Metodológicos para Pesquisa em Interfaces Gráficas de Periódicos Digitalizados](https://ericbrasiln.github.io/hemdig-framework/part3/capitulo7/cap7.html)
- [Scraper para a Biblioteca Digital de Portugal.](https://ericbrasiln.github.io/hemdig-framework/part3/capitulo8/sec82.html).
- [Scraper para o site da Hemeroteca Digital de Lisboa](https://ericbrasiln.github.io/hemdig-framework/part3/capitulo8/sec83.html).
- [pyHDB - Coleta de metadados e acervos da HDB](https://ericbrasiln.github.io/hemdig-framework/part3/capitulo8/sec81.html).

### Tutoriais e testes de OCR

- [OCR-D](https://ericbrasiln.github.io/hemdig-framework/part4/capitulo12/sec121.html).
- [Kraken](https://ericbrasiln.github.io/hemdig-framework/part4/capitulo12/sec122.html).
- [gImageReader](https://ericbrasiln.github.io/hemdig-framework/part4/capitulo13/cap13.html).
- [Tutoriais do Programming Historian](https://ericbrasiln.github.io/hemdig-framework/part4/capitulo11/cap11.html).
