# 1.1. Levantamento bibliográfico na base Scopus

No exemplo utilizado aqui, realizei levantamento bibliográfico na base Scopus[^1] e Web of Science, buscando trabalhos específicos sobre reconhecimento de caracteres e layout, assim como trabalhos sobre jornais históricos e interfaces de usuário.

O acesso a ambos os repositórios foi feito a partir da plataforma [Periódicos Capes](https://www-periodicos-capes-gov-br.ez373.periodicos.capes.gov.br), logado em minha conta institucional da Universidade da Integração Internacional da Lusofonia Afro-Brasileira (UNILAB).

## Busca na base Scopus

A busca foi realizada no dia 04/11/2020 para cada um dos parâmetros listados no item {ref}`par-scopus`.

A opção foi buscar cada combinação de termos específicos nas categorias *Title*, *Abstract* e *Keywords* (*TITLE-ABS-KEY*). Utilizei o operador lógico *OR* para combinar termos similares e o operador *AND* para combinar termos de categorias diferentes. Em alguns casos utilizei o caractere * para buscar termos que poderiam ter pequenas variações, como o caso de *historical newspaper* e *historical newspapers*: ao utilizar o caractere * no final da palavra, a busca retornaria resultados que contivessem a palavra *newspaper* ou *newspapers*.

Em seguida, os resultados foram exportados no formato RIS. Esse formato poder ser importado diretamente no Zotero, como veremos a seguir.

O Scopus possui inúmeras possibilidades de filtros e opções de exportação. Para mais informações, consulte a [página de ajuda](https://service.elsevier.com/app/answers/detail/a_id/11423/c/10546/supporthub/scopus/kw/search/).

(par-scopus)=
### Parâmetros utilizados no Scopus

Listo abaixo os parâmetros utilizados para cada busca, assim como o número de resultados e a data da busca.

1. TITLE-ABS-KEY ( "layout recognition"  OR  "layout segmentation"  OR  "layout parsing" ) 
   - 98 resultados 
   - Data da busca: 04/11/2022
2. TITLE-ABS-KEY ( "historical newspapers"  OR  "historical newspaper"  AND  "OCR"  OR  "character recognition" )
   - 69 resultados
   - Data da busca: 04/11/2022
3. TITLE-ABS-KEY ( "historical newspaper*"  AND  "interface*" ) 
   - 19 resultados
   - Data da busca: 04/11/2022


## Busca no Web of Science

A busca no Web of Science foi realizada no dia 01/09/2023 para cada um dos parâmetros listados no item {ref}`par-wos`. Utilizamos a ferramenta de construção de busca avançada -- *Advanced Search Query Builder* -- e, para as três buscas realizadas, utilizamos nos campos *Title*, *Abstract* e *Author Keywords* os mesmo termos e expressões da busca realizada no Scopus.

Os resultados de cada busca foram exportados no formato RIS, com a opção *Full Record* e posteriormente importados no Zotero.

Assim como no Scopus, o WoS possuir variados filtros, parâmetros e opções de busca, exportação e análise dos resultados. Para mais informações sobre o Advanced Search Query Builder, consulte a [página de ajuda](https://webofscience.help.clarivate.com/Content/advanced-search.html).

(par-wos)=
### Parâmetros utilizados no Web of Science

Listo abaixo os parâmetros utilizados para cada busca, assim como o número de resultados e a data da busca.

1. TI=("layout recognition"  OR  "layout segmentation"  OR  "layout parsing") OR AB=("layout recognition"  OR  "layout segmentation"  OR  "layout parsing") OR AK=("layout recognition"  OR  "layout segmentation"  OR  "layout parsing")
   - 71 resultados
   - Data da busca: 01/09/2023
2. TI=("historical newspaper*"  AND  "character recognition") OR AB=("historical newspaper*"  AND  "character recognition") OR AK=("historical newspaper*"  AND  "character recognition")
   - 17 resultados
   - Data da busca: 01/09/2023
3. TI=("historical newspaper*"  AND  "interface*") OR AB=("historical newspaper*"  AND  "interface*") OR KP=("historical newspaper*"  AND  "interface*")
   - 7 resultados
   - Data da busca: 01/09/2023

## Organização dos dados no Zotero

Após as buscas, os dados foram exportados e inseridos no Zotero. Então foram organizados e categorizados de acordo com os temas da busca. Esse processo foi feito através da criação de uma coleção principal chamada **HEMDIG(pt)**, para armazenamento e organização das referências gerais da pesquisa. Uma subcoleção chamada **SCOPUS** e outra **WEB OF SCIENCE** foram criadas. Dentro dessas subcoleções, foram criadas subcoleções para cada tema da busca, *Historical newspapers and digital interfaces*, *Historical newspapers and OCR*, *Layout recognition, segmentation and parser*.

Após a conclusão dessa etapa, que contou também com a revisão dos metadados para cada referência, a coleção *HEMDIG(pt)* foi adicionada à biblioteca pública de referências *História Digital*.[^2]

Essa biblioteca foi criada por Ana Carolina Veloso, Priscila Silveira Valverde e Eric Brasil, e está disponível em [https://www.zotero.org/groups/2216280/histria_digital](https://www.zotero.org/groups/2216280/histria_digital). 

Ao acessar a biblioteca, você poderá encontrar a pasta **HEMDIG(pt)** com os resultados da busca, organizados pelos parâmetros utilizados, conforme a {numref}`Figura {number}: {name} <zot-01>`.

```{figure} ../../assets/images/print_bib_zot.png
:name: zot-01
:align: center

Print da biblioteca *História Digital* no Zotero.
```

Também foram gerados ficheiros `.bib`, `.ris` e `.csv` com os dados de cada resultado de busca, disponíveis na pasta [`bibliografia/SCOPUS/`](../../../data/bibliografia/SCOPUS/README.md) e [`bibliografia/WoS/`](../../../data/bibliografia/WOS/README.md) do repositório da pesquisa.

Os ficheiros `.bib` e `.ris` podem ser importados diretamente no Zotero, enquanto o `.csv` pode ser aberto em programas de tratamento e visualização de dados tabulares, como o *LibreOffice Calc* e *Excel*, e organizado de acordo com as necessidades do pesquisador.

Além da busca nas bases Scopus e WoS, foram incorporadas à lista de referências trabalhos utilizados como referências mais gerais sobre o tema, e podem ser acessados na pasta [`bibliografia/`](../../../data/bibliografia/README.md) do repositório da pesquisa.


[^1]: Ver [Issue #9](https://github.com/ericbrasiln/hemdig-framework/issues/9) no repositório da pesquisa.

[^2]: Ver [Issue #3](https://github.com/ericbrasiln/hemdig-framework/issues/3) no repositório da pesquisa.