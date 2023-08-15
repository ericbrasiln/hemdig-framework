# Os casos de estudo: HDB, BND-PT e HML

Nesse documento, estão listados e brevemente explicados, os repositórios e interfaces gráficas avaliados e selecionados para o projeto.

Em coerência com os objetivos da pesquisa, a análise foi realizada a partir das interfaces gráficas que permitem busca e consulta aos acervos digitalizados de periódicos de língua portuguesa, sendo eles: Hemeroteca Digital Brasileira, da Fundação Biblioteca Nacional do Brasil (doravante HDB), a Biblioteca Nacional Digital, da Biblioteca Nacional de Portugal (doravante BND-PT) e a Hemeroteca Digital da Hemeroteca Municipal de Lisboa (doravante HML).

## Dados abertos e avaliação geral dos acervos

Primeiramente, busquei coletar e tratar dados gerais sobre cada acervo. Essa tarefa se mostrou complexa, visto que cada uma das três interfaces apresentar diferentes níveis de detalhamento e de acesso aos dados. No caso da BND-PT, encontramos dados abertos organizados para todo o acervo digitalizado e disponibilizado pela interface. Os dados estão organizados e disponíveis em múltiplos formatos, e contém informações detalhadas sobre as características do acervo, inclusive detalhando as licenças de acesso, ano, autoria, editora, local, entre outros.

Dessa forma, foi possível desenvolver análises mais profundas e apresentar visualizações mais robustas sobre o acervo da BND-PT, como pode ser visto [aqui](sec42)

No caso da HDB, os dados abertos disponibilizados pela interface atualmente são referentes apenas aos periódicos digitalizados e incorporados ao acervo da BNDigital nos anos de 2019 e 2020. Os dados estão disponíveis em formato `csv`, e contém informações sucintas: título, material, código do título, números de chamada local e código do objeto digital.

Com esse conjunto de dados, foi possível apenas contabilizar o número de periódicos incorporados ao acervo da BNDigital nos anos de 2019 e 2020, como pode ser visto [aqui](sec41).

Buscando uma compreensão mais detalhada do escopo do acervo da HDB, realizei levantamento manual dos dados relativos à quantidade de periódicos por década disponíveis na interface, os organizei em formato `csv` e os analisei, como pode ser visto [aqui](sec41).    

Em relação à HML, não foi possível encontrar dados abertos disponibilizados pela interface. Portanto, desenvolvi um programa para coletar os dados relativos ao escopo do acervo da HML, como pode ser visto [aqui](). Com esse programa, foi possível gerar um documento `csv` com os seguintes dados, te todos os periódicos disponíveis na interface: título, anos, local, fichas históricas, quantidade de pdfs, lista de links de pdfs. A apresentação e análise desses dados pode ser vista [aqui](sec43).

Por conseguinte, não foi possível realizar análises detalhadas de forma isonômica entre os três acervos. A ausência de uma política de dados abertos no padrão adotado pela BND-PT, por parte da HDB e da HML impõe limites à análise e à visualização dos dados. Ao mesmo tempo que explicita a necessidade urgente sobre o debate e implementação de políticas de dados abertos por parte das instituições responsáveis pelos acervos.


## Avaliação crítica das Interfaces

Realizei uma avaliação crítica de aspectos variados das interfaces gráficas de cada um dos acervos, a partir de metodologia de proposto por Ehrmann, Bunout e Düring[^1]. Foi desenvolvido um formulário amplo, com seis critérios de avaliação subdividido em 125 itens.

O formulário foi aplicado a cada uma das interfaces, e os resultados foram organizados em formato `csv`.

Os documentos relativos à avaliação de cada interface podem ser vistos a seguir:

- [Documentação sobre a criação do formulário](/AVA_INTERFACES/criterios_ava.md)
- [Formulário de avaliação](/AVA_INTERFACES/form_criterios.csv)
- [Análise geral dos dados](/AVA_INTERFACES/interfaces_analise.ipynb)

[^1]: Ehrmann, Maud, Estelle Bunout, e Marten Düring. “Historical Newspaper User Interfaces: A Review”. Em Libraries: Dialogue for Change. Athens, Greece, 2017. http://library.ifla.org/id/eprint/2578/.