# Ferramentas de coleta de dados

Diretório com ferramentas de coletas de dados para pesquisa nos repositórios e interfaces gráficas analisadas.

## Ferramentas

- [scraper_hml](./HML/scraper_hml.ipynb): Esse raspador coletas dados básicos da Hemeroteca Municipal de Lisboa e os salva em um arquivo CSV. Essa ferramenta coleta apenas metadados a partir da lista de periódicos organizados por título na página da HML. A ferramenta foi desenvolvida em Python e utiliza a biblioteca [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/) para fazer o scraping.
- [pyHDB](./pyHDB/README.md): Ferramenta de coleta de metadados e download de arquivos de imagens da Hemeroteca Digital Brasileira da FUndação Biblioteca Nacional. A ferramenta foi desenvolvida em Python e utiliza a biblioteca Selenium para fazer o scraping e Pandas para organizar os dados. A pyHDB foi criada por [Eric Brasil](ericbrasiln.github.io) e sua documentação pode ser encontrada [aqui](https://ericbrasiln.github.io/pyHDB/). Ela possui licença MIT e pode ser utilizada livremente.
- BND-PT: Em relação à Biblioteca Digital de Portugal, não foi necessário criar uma ferramenta específica para coleta de metadados, pois a instituição disponibiliza os dados na plataforma [OpenData BNPORTUGAL.PT](https://opendata.bnportugal.gov.pt/index.htm). Para ver esses dados, acesse o notebook de [análise dos dados da BND-PT](../../repositorios/BND-PT/escopo.ipynb).