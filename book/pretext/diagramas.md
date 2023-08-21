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

[geral](https://mermaid.live/view#pako:eNpdVFtv2jAU_iuWJSZAQAnXkgckSkqhhcFS9jJSqW5yAtYSGzlOL4vyY6Y9TJq0p_2D8cfmxFzK8pTj7_vOzec4wS73AJu4Wq06TFIZgInGEFp0jUaChPDCxVeH5WihkFBGpYkSB_sBf3E3REgH5_ZGhsGUPEEQZQc-CSJIU5QWCg5z2JGMprbDkPoGSvJYLht_f6ERiaBcNtFCwJYIsvu5-8HRhFGXkuDRwakWXPWv6FNA-VoQn5IHpBJCAw0N-8tYckEJjdBifAZ96k_hmTCp6mCSIw-QDVseUbn7IyiPzrgDZfSRpRNrqMR8ndhQ7H5L6hLk8ehcfspulGtvtLb9rigbnmmUFQRoEav8XV3fSWnlyvHqYuCCeOaR4zy8ByariwmTIHziQoRuxO67r3ycWGP0AU2yKvroWkdvnqIPeQCSZFVbxHuf7nXu-zZJZgr3Miw9Q-5WRYtI5URGpX2gWxXoLgdHOk7rFGcpyLHDqkfeeTDdm2mSWOCr8dH3q3IiT1wQD9YQHoJPUbWmqPMkmQ_tqvXf8SJJ1pOQrMEGJRMHdJ6hyC4uBVB2uudQTXXAS5qz0B7uiza4nG3ApUfelLzxWKrrUf-uGj9XNRuivc7e67R1n0_LcqWGnbtiPzTT5Vz_yVe1Cg_HeEr2uTjkQoAueEZYTIJSDiw06yY3ZquimvxIXf5-9D2O9s0_9F4TPxaLFnfjLHPNLJVwBYcgQkI9tcBJRnaw3EAI2Q462AOfxIFKy2GpohK1JfdvzMWmFDFUcLz1iASLErVT4eFwS9gXzo8meFSt1kw_EflLkVOwmeBXbLYavZpRN-qtZrduGF2jV8Fv2Gz22rW6cdnpdrrt7qXRaKcV_C33Wa_1er1Go9nr1I1Wp9s1muk_OONtMw)


### Segunda fase
    
```mermaid
---
title: Segunda Fase
---
%%{init: {"flowchart": {"htmlLabels": false}} }%%

flowchart TB
    A{"`**Crítica dos Repositórios**`"}
    A --> B[/Acervos\]
    A --> C[/"Interfaces
    Gráficas"\]
    B --- H["Avaliação dos
    dados brutos"]
    H -.- D(HBD)
    H -.- E(BND-PT)
    H -.- F(HML)
    C --> G("Método
    impresso de avaliação
    de interfaces gráficas")
    G -.- D(HBD)
    G -.- E(BND-PT)
    G -.- F(HML)
```

### Terceira fase

```mermaid
---
title: Terceira Fase
---
%%{init: {"flowchart": {"htmlLabels": false}} }%%

flowchart TB
    A{"`**Coleta de Dados**`"}
    A --> E & F & D
    E(Scrapers) -.-> C[(Datasets)]
    E -.- F
    F(Organização) -.-> C
    D("Relatórios
    Metodológicos") -.-> B{{Metadados}}
```

## Pendências

Fazer diagramas específicos para cada fase do framework.