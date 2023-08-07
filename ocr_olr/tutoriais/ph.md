# Lições do Programming Historian

Essas lições são úteis para a compreensão de técnicas e funcionamento geral de OCR e OLR, assim como a implementação de limpeza de dados com expressões regulares. Por isso, esse é um bom ponto de partida para quem está começando a trabalhar com OCR e OLR.

Indicamos que, antes de começar a trabalhar com os programas e ferramentas listadas nesse diretório, você leia e pratique as lições abaixo.

## OCR

### [Working with batches of PDF files](https://programminghistorian.org/en/lessons/working-with-batches-of-pdf-files), Moritz Mähr.

Estão lição possui apenas versão em inglês. Ela ensina a trabalhar com arquivos PDF em lote, ou seja, com vários arquivos PDF ao mesmo tempo. Ela é útil para quem precisa trabalhar com muitos arquivos PDF, mas não quer ter que abrir um por um.

>"Learn how to perform OCR and text extraction with free command line tools like Tesseract and Poppler>> and how to get an overview of large numbers of PDF documents using topic modeling."

#### Uso da lição dentro do Hemdig framework

Essa lição é útil para:

- Reconhecimento de caracteres em massa de arquivos pdf (com ou sem OCR prévio).
- Transformação desses dados em texto simples (txt);
- Coleta de imagens de PDFs;
- Reunir PDFs;

É uma lição simples e útil principalmente para *datasets* de pdfs com qualidade alta, sem layouts complexos. É uma boa introdução para compreender o funcionamento de OCR com ferramentas de linha de comando.

A lição também apresenta como aplicar técnicas de modelagem de tópicos, mas que não serão utilizadas nessa pesquisa.

### [Generating an Ordered Data Set from an OCR Text File](https://programminghistorian.org/en/lessons/generating-an-ordered-data-set-from-an-OCR-text-file), Jon Crump.

Esta lição possui versões em inglês (original) e francês. Nela você aprenderá a criar um dicionário pythonpara ordenar os dados de um arquivo de texto gerado por OCR.

>"This tutorial illustrates strategies for taking raw OCR output from a scanned text, parsing it to isolate and correct essential elements of metadata, and generating an ordered data set (a python dictionary) from it."

#### Uso da lição dentro do Hemdig framework

- A lição fornece uma boa lista de exemplos úteis para a limpeza do texto gerado por OCR.
- Tutorial de criação e aplicação de uma função de distância de Levenshtein para correção de erros de OCR (útil para  limpar cabeçalhos e rodapés de páginas).
- Separação das páginas em grupos (chunks) e iteração sobre elas.
- Normalização de padrões.
- Criação de um dicionário python para armazenar os dados.


### [Cleaning OCR’d text with Regular Expressions](https://programminghistorian.org/en/lessons/cleaning-ocrd-text-with-regular-expressions), Laura Turner O'Hara.

Lição importante para aplicação de expressões regulares para limpeza de dados. A lição possui versão apenas em inglês (original).

>"Optical Character Recognition (OCR)—the conversion of scanned images to machine-encoded text—has proven a godsend for historical research. This lesson will help you clean up OCR’d text to make it more usable."

#### Uso da lição dentro do Hemdig framework

- Uso de expressões regulares para limpeza de dados.

### [Understanding Regular Expressions](https://programminghistorian.org/en/lessons/understanding-regular-expressions), Doug Knox.

Lição que apresenta de forma mais detalhada o funcionamento de expressões regulares. A lição possui versões em inglês (original) e francês.

>"In this lesson, we will use advanced find-and-replace capabilities in a word processing application in order to make use of structure in a brief historical document that is essentially a table in the form of prose."

#### Uso da lição dentro do Hemdig framework

- Explicações mais detalhadas sobre o funcionamento de expressões regulares.
  
### [OCR and Machine Translation](https://programminghistorian.org/en/lessons/OCR-and-Machine-Translation), Andrew Akhlaghi.

Essa lição foi escrita originalmente em inglês e atualemnte possui um processo de revisão em andamento, que pode ser [acessado aqui](https://github.com/programminghistorian/ph-submissions/issues/371).

>"Esta lição ensinará a converter imagens de textos em ficheiros textuais, bem como a traduzir estes ficheiros. A lição também ensinará a organizar e editar imagens para tornar mais fácil e precisa a conversão e tradução de pastas inteiras de ficheiros textuais. A lição conclui com uma discussão sobre as deficiências da tradução automática e como superá-las."

#### Uso da lição dentro do Hemdig framework

A lição apresenta como:

- Tratar imagens com ImageMagick
- Converter PDFs em formato de imagem TIFF. 
- Traduzir textos com o [Translate Shell](https://www.soimort.org/translate-shell/#translate-shell).

### [OCR with Google Vision API and Tesseract](https://programminghistorian.org/en/lessons/ocr-with-google-vision-and-tesseract), Isabelle Gribomont.

Essa lição também conta com um processo de tradução em andamento, que pode ser [acessado aqui](https://github.com/programminghistorian/ph-submissions/issues/575), e sua versão original foi escrita em inglês.

>O Google Vision e o Tesseract são ambas populares e poderosas ferramentas de OCR, mas cada uma tem as suas limitações. Nesta lição, será explicado como combinar os dois para aproveitar ao máximo os seus pontos fortes individuais e obter resultados de OCR ainda mais precisos.

#### Uso da lição dentro do Hemdig framework

A lição apresenta:

- Uma comparação de vantagens desvantagens entre o Google Vision e o Tesseract.
- como usar o Google Vision e o Tesseract em conjunto para obter melhores resultados de OCR.