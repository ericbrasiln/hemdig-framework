# OCR-D: apresentação

O OCR-D é um projeto financiado pelo DFG (*Deutsche Forschungsgemeinschaft*) que visa criar um framework para o processamento de documentos digitais desenvolvido para lidar com o _Union Catalogue of Books_ dos séculos XVI ao XVIII. Iniciado em 2014, o projeto OCR-d tem como principal objetivo:

>the conceptual and technical preparation of the full text transformation of the VD. The task of automatic full-text recognition is broken down into its individual process steps, which can be retraced in the open source OCR-D software. This allows to create optimal workflows for the old prints to be processed and thus to generate scientifically usable full texts. (“The OCR-D project - OCR-D”. s.d. Acedido a 2 de agosto de 2023. https://ocr-d.de/en/about.html.)

Seu framework reúne uma série de ferramentas que contemplam todas as etapas de processamento necessárias para a conversão de imagens de documentos em texto. O infográfico abaixo apresenta as etapas de processamento do OCR-D:

![OCR-D Workflow](https://ocr-d.de/assets/Funktionsmodell.svg)

Buscando aplicar esse framework para jornais digitalizados em português, testamos uma série de ferramentas do OCR-D. Como jornais históricos apresentam uma série de desafios para seu tratamento digital e conversão para texto -- como a qualidade da digitalização, a presença de muitos ruídos, manchas, rasgos, layouts complexos em múltiplas colunas e variações de fontes entre outros tantos[^1] --, mesmo o OCR-D não é capaz de lidar de forma satisfatória com essas questões sem que haja um treinamento específico do modelo para um determinado conjunto de dados.

Sendo assim, buscamos aqui apresentar um exemplo de workflow sendo aplicado em dois conjuntos distintos de imagens de jornais digitalizados. O primeiro teste será realizado com duas páginas, de qualidades distintas, do jornal _O Paiz_ do Rio de Janeiro. O segundo teste será realizado com doze edições do jornal *Boletim de Eugenia* do Rio de Janeiro, totalizando 48 imagens de páginas digitalizadas.

[^1]: Jarlbrink, Johan, e Pelle Snickars. “Cultural Heritage as Digital Noise: Nineteenth Century Newspapers in the Digital Archive”. Journal of Documentation 73, nº 6 (12 de outubro de 2017): 1228–43. https://doi.org/10.1108/JD-09-2016-0106. Ehrmann, Maud, Estelle Bunout, e Marten Düring. “Historical Newspaper User Interfaces: A Review”. Em Libraries: Dialogue for Change. Athens, Greece, 2017. http://library.ifla.org/id/eprint/2578/. Liebl, B., e M. Burghardt. “From Historical Newspapers to Machine-Readable Data: The Origami OCR Pipeline”. Em CEUR Workshop Proc., organizado por Karsdorp F., McGillivray B., Nerghes A., e Wevers M., 2723:351–73. Amsterdam: CEUR-WS, 2020. http://ceur-ws.org/Vol-2723/long20.pdf.

Primeiro, veremos como instalar o OCR-D, como criar um ambiente virtual e um workspace. Em seguida, veremos como aplicar um workflow para as duas páginas do jornal _O Paiz_. Por fim, veremos como aplicar um workflow para as doze edições do jornal *Boletim de Eugenia*.

https://github.com/OCR-D

Explicar que ele já inclui Calamari, Tesseract e Ocropus