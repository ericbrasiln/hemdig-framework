# Como utilizar os recursos desse livro

Esse livro foi construído com o *Jupyter Book*, um projeto de código aberto que possibilita a elaboração e publicação de livros e documento "a partir de material computacional"[^1]. Com ele é possível combinar a escrita, através da sintaxe Markdown, com a execução de blocos de código e a exibição dos seus resultados. Isso é possível pois ele é capaz de renderizar arquivos `.ipynb`, ou seja, *jupyter notebooks*, que são amplamente usados para análise de dados, visualização e ensino.

Além disso, o *Jupyter Book* nos oferece uma série de recursos úteis após sua publicação online: além da visualização de texto, imagens e da execução de código e a apresentação de seus resultados, é possível realizar o download de cada página em diferentes formatos (.pdf, .md, .ipybn) e executar os *notebooks* através de plataformas em nuvem como Binder, Google Colab, Microsoft Azuere.

Também permite uma ampla configuração de seu layout e a inclusão de notas, referências cruzadas, bibliografias e índices,  e conexão com serviços externos como o Github.

Para mais informações sobre Jupyter Books ver {cite:ts}`walsh_melaniewalshintro-cultural-analytics_2021` e sobre jupyter notebooks, ver {cite:ts}`dombrowski_introducao_2019`.

[^1]: Executable Books Community. “Jupyter Book”. Zenodo, February 12, 2020. https://doi.org/10.5281/zenodo.4539666.

```{admonition} Nota
:class: note
Para melhor aproveitamento de todos os recursos, recomendo que você acesse esse livro em um computador e utilize o tema claro.
```

## Opções 

No menu superior direito, algumas opções estão disponíveis, dependendo di tipo de cada página.

```{figure} ./../assets/images/rocket.png
:height: 50px
:name: rocket
:align: center

Sempre que o ícone do foguete aparecer no alto da página, é possível executar os códigos presentes no notebook em serviços de nuvem. Aqui configuramos para que o Binder e o Google Colab apareçam como opções.
```

```{figure} ./../assets/images/octocat.png
:height: 50px
:name: octocat
:align: center

O ícone do octocat, símbolo do Github, permite que você acesse o repositório do livro no Github, e também possa abrir *issues* diretamente na página em que você está.
```

```{figure} ./../assets/images/download.png
:height: 50px
:name: download
:align: center

Esse ícone permite visualizar as opções de download para a página em que você está. 
```

```{figure} ./../assets/images/fscreen.png
:height: 50px
:name: fscreen
:align: center

Esse ícone permite que você coloque a página no modo *full screen*.
```

```{figure} ./../assets/images/sun.png
:height: 50px
:name: sun
:align: center

Ícones para seleção de tema claro ou escuro.
```

```{figure} ./../assets/images/search.png
:height: 50px
:name: search
:align: center

Ícone para pesquisa no livro.
```

```{figure} ./../assets/images/list.png
:height: 50px
:name: list
:align: center

Mostra barra com tópicos da página
```

---

## Referências

```{bibliography}
:filter: docname in docnames
:style: alpha
```