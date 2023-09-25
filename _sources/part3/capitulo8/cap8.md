# 8. Scrapers de dados

Para o desenvolvimento de pesquisas com métodos digitais, é necessário possuirmos formas eficientes, precisas e controladas de coletar dados remotamente. Para isso dependemos de fatores estruturais e políticos que muitas vezes escapam do controle do pesquisador individual.

Primeiramente, é importante conhecer as políticas de dados abertos dos governos e instituições, para avaliar quais dados já estão disponíveis e como estão organizados, assim como conhecer as formas de acessá-los.

Caso o repositório pesquisado possua uma página específica para download de dados em massa, o trabalho de pesquisa é sobremaneira otimizado. 

Outra forma de coletar dados é através de APIs, que são application programming interfaces, ou seja, interfaces de programação de aplicativos. As APIs representam uma forma automatizada de acessar dados de plataformas baseadas na web através de conjuntos de padrões de programação. Elas representam a forma mais eficiente para coletar dados, porém ainda são uma raridade nos repositórios dos arquivos públicos brasileiros e portugueses.

Caso não tenhamos acesso aos dados através de APIs ou páginas para o download, precisamos desenvolver ferramentas de coleta específicas para cada repositório. Essas ferramentas são chamadas de scrapers, que são programas de computador que automatizam a coleta de dados de páginas da web. Ou seja, criar um programa para raspar os dados que precisamos diretamente da página da web pesquisada.

>A raspagem, dito de maneira bastante formal, é uma técnica importante para a coleta automatizada de dados on-line. É uma das práticas mais distintas associadas às formas atuais de pesquisa social digital, aquelas que são marcadas pelo surgimento da Internet e a nova onipresença dos dados digitais na vida social. Scrapers, para dizer de forma mais informal, são bits de código de software que possibilitam o download automático de dados da Web e a captura de algumas das grandes quantidades de dados sobre a vida social que estão disponíveis em plataformas on-line como Google, Twitter e Wikipédia. {cite:p}`marres_scraping_2013`

Esta empreitada requer bastante conhecimento técnico e, por isso, vou apresentar nesse capítulo ferramentas específicas para os três repositórios que fazem parte desta pesquisa.

É importante atentar para o seguinte:

>o web scraping não deve ser entendido apenas como uma técnica, mas também como uma maneira particular de lidar com a informação e o conhecimento. [...] As escolhas e perguntas, interesses e abordagens do/a pesquisador/a determinam os critérios de coleta que serão implementados pelo programa. {cite:p}`brasil_pyhdb_2022`

---

## Referências

```{bibliography}
:filter: docname in docnames
:style: alpha
```