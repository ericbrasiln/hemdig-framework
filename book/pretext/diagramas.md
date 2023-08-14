# Diagramas

Esboços de diagramas feitos com mermaid. Os diagramas estão sendo construídos utilizando o editor inline disponível [aqui](https://mermaid.live/).

## Geral (primeiro nível)

```mermaid
---
title: HemDig Framework
---
%%{init: {"flowchart": {"htmlLabels": false}} }%%

flowchart LR
    A{"`**1ª Fase**:
    Preparação Inicial`"} --> B{"`**2ª fase**:
    Crítica dos Repositórios`"} -->C{"`**3ª Fase**:
    Coleta de Dados`"} --> D{"`**4ª Fase**:
    Tratamento dos dados`"} --> E{"`**5ª Fase**:
    Revisão e Publicação`"}
```

## Geral completo

```mermaid
---
title: HemDig Framework
---
%%{init: {"flowchart": {"htmlLabels": false}} }%%

flowchart LR
    A{"`**1ª Fase**: Preparação Inicial`"}
    B>Bibliografia] --- A
    C>Tutoriais PH] --- A
    Q>Levantamento de Repositórios] --- A
    A --> D{"`**2ª fase**:Crítica dos Repositórios`"}
    F --> G{"`**5ª Fase**: Revisão e Publicação`"}
    D --> H[/Acervos\]
    D --> I[/Interfaces Gráficas\]
    H & I ---> E{"`**3ª Fase**:Coleta de Dados`"}
    E --> J{{Metadados}}
    E --> K[(Datasets)]
    J & K --> F{"`**4ª Fase:Tratamento dos dados`"}
    F --> L{{Definição de aboradegem}}
    L -.-> O{{OCR-D}}
    L -.-> P{{gImageReader}}
    O -.- R(Treinamento de modelo)
    P -.-> S(Reconhecimento de Layout e de caracteres)
    R -.-> S
    S --- T["hocr
    ALTO
    txt"]
    P --> U(Correção Manual) --> P
    G --> M[(Preservação do Dataset)]
    G --> N((Documentação))
```

## Pendências

Fazer diagramas específicos para cada fase do framework.