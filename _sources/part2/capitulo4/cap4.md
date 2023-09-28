# 4. Os casos de estudo: Hemeroteca Digital Brasileira, Biblioteca Nacional Digital de Portugal e Hemeroteca Digital da Hemeroteca Municipal de Lisboa

Neste documento, estão listados e brevemente explicados, os repositórios e interfaces gráficas  selecionados e avaliados na pesquisa.

Em coerência com os objetivos gerais, a análise foi realizada a partir das interfaces gráficas que permitem busca e consulta aos acervos digitalizados de periódicos de língua portuguesa, sendo eles: *Hemeroteca Digital Brasileira*, da Fundação Biblioteca Nacional do Brasil (doravante HDB), a *Biblioteca Nacional Digital*, da Biblioteca Nacional de Portugal (doravante BND-PT) e a *Hemeroteca Digital* da Hemeroteca Municipal de Lisboa (doravante HML).

## Dados abertos e avaliação geral dos acervos

### BND-PT

Primeiramente, busquei coletar e tratar dados gerais sobre cada acervo. Essa tarefa se mostrou complexa, visto que cada uma das três interfaces apresentar diferentes níveis de detalhamento e de acesso aos dados. No caso da *BND-PT*, encontramos dados abertos organizados para todo o acervo digitalizado e disponibilizado publicamente. Os dados estão organizados e disponíveis em múltiplos formatos, e contém informações detalhadas sobre as características do acervo, inclusive com detalhamento sobre as licenças de acesso, ano, autoria, editora, local, entre outros.

Dessa forma, foi possível desenvolver análises mais profundas e apresentar visualizações mais robustas sobre o acervo da *BND-PT*, como pode ser visto [aqui](sec42.ipynb)

### HDB

No caso da *HDB*, os dados abertos disponibilizados pela interface atualmente são referentes apenas aos periódicos digitalizados e incorporados ao acervo da BNDigital nos anos de 2019 e 2020. Os dados estão disponíveis em formato `csv`, e contém informações sucintas: título, material, código do título, números de chamada local e código do objeto digital.

Com esse conjunto de dados, não seria possível uma análise aprofundada e muito menos uma comparação com os dados da *BND-PT*.

Buscando uma compreensão mais detalhada do escopo do acervo da *HDB*, solicitei via email junto ao Setor de Gestão de Programas e Inovação (SGPI) da BNDigital os dados referentes aos periódicos digitalizados disponibilizados na *HDB*. Em resposta, o setor disponibilizou um ficheiro `xml` completo, exportado internamente no sistema da BNDigital. A partir da análise desse ficheiro `xml` foi possível produzir reflexões e visualizações próximas daquelas realizadas com os dados da *BND-PT*, e serão apresentados no tópico [4.1](sec41.ipynb). 

### HML

Em relação à *HML*, não foi possível encontrar dados abertos disponibilizados pela interface e não consegui contato por email. Portanto, desenvolvi um programa para coletar os dados relativos ao escopo do acervo da *HML*, como pode ser visto [aqui](../../../data/hml/hemeroteca_lisboa.csv). Com esse programa, foi possível gerar um documento `csv` com os seguintes dados, te todos os periódicos disponíveis na interface: título, anos, local, fichas históricas, quantidade de pdfs, lista de links de pdfs. A apresentação e análise desses dados pode ser vista [aqui](sec43.ipynb).

Por conseguinte, não foi possível realizar análises detalhadas de forma isonômica entre os três acervos. A ausência de uma política de dados abertos no padrão adotado pela BND-PT, por parte da HDB e da HML acabou demandando o desenvolvimento de estratégias distintas na coleta de dados. Sem dúvida, isto impõe limites à análise e à visualização dos dados. Ao mesmo tempo que explicita a necessidade urgente sobre o debate e implementação de políticas de dados abertos por parte das instituições responsáveis pelos acervos.