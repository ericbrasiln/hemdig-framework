# Ferramentas de coleta de dados

Diretório com ferramentas de coletas de dados para pesquisa nos repositórios e interfaces gráficas analisadas.

## Ferramentas

- [scraper_hml](./HML/scraper_hml.ipynb): Esse raspador coletas dados básicos da Hemeroteca Municipal de Lisboa e os salva em um arquivo CSV. Essa ferramenta coleta apenas metadados a partir da lista de periódicos organizados por título na página da HML. A ferramenta foi desenvolvida em Python e utiliza a biblioteca [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/) para fazer o scraping.
- [pyHDB](./pyHDB/README.md): Ferramenta de coleta de metadados e download de arquivos de imagens da Hemeroteca Digital Brasileira da Fundação Biblioteca Nacional. A ferramenta foi desenvolvida em Python e utiliza a biblioteca Selenium para fazer o scraping e Pandas para organizar os dados. A pyHDB foi criada por [Eric Brasil](ericbrasiln.github.io) e sua documentação pode ser encontrada [aqui](https://ericbrasiln.github.io/pyHDB/). Ela possui licença MIT e pode ser utilizada livremente.
- BND-PT: Apesar da Biblioteca Digital de Portugal, disponibilizar os seus dados na plataforma [OpenData BNPORTUGAL.PT](https://opendata.bnportugal.gov.pt/index.htm)[^1], desenvolvi um programa para coletar dados específicos de buscas realizadas na interface. A ferramenta utiliza o Selenium e pode ser acessada e utilizada [aqui](./BND_PT/scraper_bndpt.ipynb). 

[^1]: Para ver esses dados, acesse o notebook de [análise dos dados da BND-PT](../../repositorios/BND-PT/escopo.ipynb).
