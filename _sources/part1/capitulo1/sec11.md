# 1.1. Levantamento bibliográfico na base Scopus

No exemplo utilizado aqui, realizei levantamento bibliográfico na base Scopus[^1], buscando trabalhos específicos sobre reconhecimento de caracteres e layout, assim como trabalhos sobre jornais históricos e interfaces de usuário.

## Busca na base Scopus

A busca foi realizada na base Scopus enquanto logado em minha conta institucional da Universidade da integração Internacional da Lusofonia Afro-Brasileira (UNILAB). A busca foi realizada no dia 04/11/2020 para cada um dos parâmetros listados no item {ref}`par-scopus`.

A opção foi buscar cada combinação de termos específicos nas categorias *Title*, *Abstract* e *Keywords* (*TITLE-ABS-KEY*). Utilizei o operador lógico *OR* para combinar termos similares e o operador *AND* para combinar termos de categorias diferentes. Em alguns casos utilizei o caractere * para buscar termos que poderiam ter pequenas variações, como o caso de *historical newspaper* e *historical newspapers*: ao utilizar o caractere * no final da palavra, a busca retornaria resultados que contivessem a palavra *newspaper* ou *newspapers*.

Em seguida, os resultados foram exportados no formato RIS. Esse formato poder ser importado diretamente no Zotero, como veremos a seguir.

O Scopus possui inúmeras possibilidades de filtros e opções de exportação. Para mais informações, consulte a [página de ajuda](https://service.elsevier.com/app/answers/detail/a_id/11423/c/10546/supporthub/scopus/kw/search/).

## Organização dos dados no Zotero

Após a busca, os dados foram exportados e inseridos no Zotero. Então foram organizados e categorizados de acordo com os temas da busca. Esse processo foi feito através da criação de uma coleção principal chamada **HEMDIG(pt)**. Nela seria armazenas as referências gerais da pesquisa. Um subcoleção chamada **SCOPUS** foi criada para armazenar os resultados da busca na base Scopus. Dentro dessa subcoleção, foram criadas subcoleções para cada tema da busca, *Historical newspapers and digital iterfaces*, *Historical newspapers and OCR*, *Layout recognition, segmentation and parser*.

Após a conclusão dessa etapa, que contou também com a revisão dos metadados para cada referência, a coleção *HEMDIG(pt)* foi adicionada à biblioteca pública de referências *História Digital*.

Essa biblioteca foi criada por Ana Carolina Veloso, Priscila Silveira Valverde e Eric Brasil, e está disponível em [https://www.zotero.org/groups/2216280/histria_digital](https://www.zotero.org/groups/2216280/histria_digital). 

Ao acessar a biblioteca, você poderá encontrar a pasta **HEMDIG(pt)** com os resultados da busca, organizados pelos parâmetros utilizados[^2], conforme a {numref}`Figura {number}: {name} <zot-01>`.

```{figure} ../../assets/images/print_bib_zot.png
:name: zot-01
:align: center

Print da biblioteca *História Digital* no Zotero.
```

Também foram gerados ficheiros `.bib`, `.ris` e `.csv` com os dados de cada resultado de busca, disponíveis na pasta [`bibliografia/SCOPUS/`](https://github.com/ericbrasiln/hemdig-framework/tree/main/bibliografia/SCOPUS) do repositório da pesquisa.

Os ficheiros `.bib` e `.ris` podem ser importados diretamente no Zotero, enquanto o `.csv` pode ser aberto em programas de tratamento e visualização de dados tabulares, como o *LibreOffice Calc* e *Excel*, e organizado de acordo com as necessidades do pesquisador.

Além da busca na base Scopus, foram incorporadas à lista de referências trabalhos utilizados como referências mais gerais sobre o tema, e podem ser acessados na pasta [`bibliografia/`](../../../data/bibliografia/) do repositório da pesquisa.

(par-scopus)=
## Parâmetros utilizados no Scopus

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


[^1]: Ver [Issue #9](https://github.com/ericbrasiln/hemdig-framework/issues/9) no repositório da pesquisa.

[^2]: Ver [Issue #3](https://github.com/ericbrasiln/hemdig-framework/issues/3) no repositório da pesquisa.