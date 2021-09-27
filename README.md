# LawHub
Textos jurídicos, legislação, pesquisas e traduções.

1. [Sobre o LaTeX](https://github.com/Nerun/lawhub#1-sobre-o-latex)

    1. [Cursos online gratuitos](https://github.com/Nerun/lawhub#11-cursos-online-gratuitos)

    2. [Programas de edição](https://github.com/Nerun/lawhub#12-programas-de-edi%C3%A7%C3%A3o)

    3. [Converter LaTeX para outros formatos](https://github.com/Nerun/lawhub#13-converter-latex-para-outros-formatos)

2. [Fontes](https://github.com/Nerun/lawhub#2-fontes)

3. [Links úteis](https://github.com/Nerun/lawhub#3-links-%C3%BAteis)

## 1 Sobre o LaTeX
Por que o LaTeX?

1. Ele é muito fácil de aprender.

2. Por ser em modo texto é fácil verificar as mudanças no GitHub, facilitando o trabalho de comparar as mudanças, já que em binário (ODT ou DOCX) seria impossível. Haveria outras opções, porém:

    1. o formato TXT é simples demais;

    2. o formato MARKDOWN (MD) é um pouco melhor e muito mais fácil de aprender que o LaTeX, porém o LaTeX produz resultados visuais melhores, mesmo quando convertido para outros formatos;

    3. haveria a possibilidade de criar uma Wiki usando o [mediawiki](https://www.mediawiki.org). As wikis permitem trabalho colaborativo, comparação de versões e links de download (externo). Porém, o formato não dá pra converter fácil. Cada artigo na wiki teria que ter um link para baixar o conteúdo em um formato amigável para edição. Dobraria o trabalho.

3. É fácil de converter para outros formatos (vide abaixo).

4. Ao se dedicar ao LaTeX você estará aprendendo uma linguagem importante no meio acadêmico.

### 1.1 Cursos online gratuitos
Rápido e fácil:

* YOUTUBE. Professor Aquino - Matemática. [Introdução ao LaTeX (Curso Completo)](https://www.youtube.com/playlist?list=PLa_2246N48_p9ndUHlO255uvKtSR8mshE).

### 1.2 Programas de edição
Texmaker (minha escolha):
```
sudo aptitude install texmaker
```
Gummi:
```
sudo aptitude install gummi
```

### 1.3 Converter LaTeX para outros formatos
Instale:
```
$ sudo aptitude install pandoc
```
Para converter use a fórmula:
```
$ pandoc <arquivo original> -o <arquivo destino>
```
Exemplos:

Converter para *LibreOffice* ODT:
```
$ pandoc UCC.tex -o UCC.odt
```
Converter para *MS Word* DOCX:
```
$ pandoc UCC.tex -o UCC.docx
```
Converter para EPUB:
```
$ pandoc UCC.tex -o UCC.epub
```

É possível converter também para HTML e outros formatos, [consulte essa referência fácil](https://pandoc.org/demos.html).

## 2 Fontes
* CASTRO, Marcílio Moreira de. [Dicionário de Direito, Economia e Contabilidade](https://www.dropbox.com/s/g8h20zuppojlz0b/CASTRO%2C%20Marc%C3%ADlio%20Moreira%20de%20-%20Dicion%C3%A1rio%20de%20Direito%2C%20Economia%20e%20Contabilidade.pdf?dl=0): português-inglês / inglês-português. 4. ed. Rio de Janeiro: Forense, 2013.
* LEGAL INFORMATION INSTITUTE (LII) of Cornell Law School. [Uniform Commercial Code](https://www.law.cornell.edu/ucc).

## 3 Links úteis
* DILLINGER. [Online Markdown Editor](https://dillinger.io) - ótimo site para testar seus markdowns
* GITHUB. [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) - códigos markdown
* MARKDOWN GUIDE. [Basic Syntax](https://www.markdownguide.org/basic-syntax) - excelente guia
