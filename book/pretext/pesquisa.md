# Histórico, versionamento, repositório

## Breve histórico da pesquisa

Essa pesquisa teve início em 2022, como parte uma parceria entre os Laboratórios 
de humanidades digitais da Universidade Federal da Bahia e da Universidade Nova
de Lisboa. Os laboratórios firmaram parceria institucional para desenvolver 
formação, publicações e pesquisas. A primeira etapa da parceria se concretizou
com a participação no corpo editorial da revista *The Programming Historian*.
Em seguida, realizei um período de atuação direta na revista, como parte de uma
licença para capacitação, o que gerou uma série de produtos ligados ao processo
editorial e a publicação de uma lição inédita em português (ver {cite:ts}`brasil_git_2023`).

A partir de outubro de 2022, iniciei a pesquisa sobre as Hemerotecas digitais
de jornais históricos em língua portuguesa.

O projeto inicialmente aprovado por ser acessado [aqui](https://github.com/ericbrasiln/hemdig-framework/tree/main/projeto-aprovado).

O cronograma da pesquisa está disponível [aqui](https://github.com/ericbrasiln/hemdig-framework/blob/main/cronograma.md)

## Licença

Toda a pesquisa utiliza ferramentas gratuitas e de código aberto. Os dados, códigos, visualizações estão licenciadas sob [Creative Commons Atribuição 4.0 Internacional CC BY-NC-SA 4.0 Deed ](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.pt-br), o que permite sua reutilização, cópia, alteração, expansão desde que os seguintes termos sejam seguidos:

>Atribuição - Você deve dar o crédito apropriado, prover um link para a licença e indicar se mudanças foram feitas . Você deve fazê-lo em qualquer circunstância razoável, mas de nenhuma maneira que sugira que o licenciante apoia você ou o seu uso. 
>
>Não Comercial - Você não pode usar o material para fins comerciais . 
>
> Compartilha Igual - Se você remixar, transformar, ou criar a partir do material, tem de distribuir as suas contribuições sob a mesma licença que o original.
>
>Sem restrições adicionais - Você não pode aplicar termos jurídicos ou medidas de caráter tecnológico que restrinjam legalmente outros de fazerem algo que a licença permita. 

Para saber mais sobre a licença, veja o [link](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.pt-br).

## Versionamento

Para controle das alterações e registro metodológico sistemático, foi utilizado o sistema de controle de versões Git. Desde o início da pesquisa, cada alteração foi registrada e devidamente comentada, sendo inserida no histórico de versões do Git. Isso permitiu além do controle e registro das mudanças, possibilitou maior capacidade de recuperação de dados, correção e experimentação ao longo do processo. 

Utilizei como repositório remoto o GitHub, funcionando como backup em nuvem e também como gerenciador de tarefas da pesquisa. O site produzido com *Jupyter book* também está hospedado no Github e sua publicação on-line acontece via Github actions, a partir do branch `gh-pages`.

Para acessar todo o histórico de mudanças (todas as mensagens de *commit* e o trabalho com *branches*), acesse o arquivo `csv` nesse [link](https://github.com/ericbrasiln/hemdig-framework/blob/main/log_main.csv).

Para acessar o projeto organizado no Github Projects, [clique aqui](https://github.com/users/ericbrasiln/projects/6).

### O Repositório da pesquisa

Como dito anteriormente, o diretório local da pesquisa foi controlado através do Git e foi criado um repositório remoto no Github. Esse repositório reúne os dados brutos da pesquisa, os códigos e resultados, licença, cronograma, etc. Nele também consta o diretório que estrutura esse livro, `book/`. Em seu interior estão organizados todos os elementos necessários para que esse material fosse renderizado e publicado corretamente on-line.

Portanto, é possível acessar o repositório remoto no Github e percorrer as pastas de cada etapa da pesquisa, assim como visualizar os *commits*, *issues* e *pull requests* realizados ao longo do tempo.

Esse repositório será armazenado no *Zenodo*, e será gerado um DOI. Assim, o material fica preservado em um repositório confiável com previsão de armazenamento de longa duração.
