# LawHub

Textos jurídicos, legislação, pesquisas e traduções.

## Por que o LaTeX?

1. LaTeX cobra tempo de aprendizado antes de entregar produtividade.
A vantagem aparece depois: textos longos e complexos tornam-se mais fáceis de manter, revisar e padronizar do que em editores visuais.

2. Por ser baseado em texto puro, permite controle de versões eficiente e comparação clara entre alterações.
Em formatos binários (ODT ou DOCX), a comparação é possível, mas trabalhosa e pouco clara.

3. Outras alternativas existem, mas com limitações:

    1. TXT é simples demais.

    2. Markdown (MD) é fácil e amplamente difundido, mas não atende às necessidades de textos jurídicos estruturados.

    3. AsciiDoc e reST são adequados à documentação técnica, mas o LaTeX continua sendo uma ferramenta profissional consolidada de editoração.

    4. Wikis permitem colaboração e histórico de versões, mas exigem formatos externos para edição e distribuição, o que duplica o trabalho.

4. Documentos em LaTeX podem ser convertidos facilmente para outros formatos usando o pandoc.

5. LaTeX é padrão no meio acadêmico e técnico. O esforço inicial é compensado pela durabilidade, consistência e portabilidade dos textos.

## Cursos online gratuitos

YouTube. Professor Aquino - Matemática.
[Introdução ao LaTeX (Curso Completo)](https://www.youtube.com/playlist?list=PLa_2246N48_p9ndUHlO255uvKtSR8mshE).

## Programas de edição para Linux

- Texmaker
- TeXstudio (fork do Texmaker)
- Gummi

## Converter LaTeX para outros formatos

Instale o pandoc:

```console
sudo apt install pandoc
```

Sintaxe básica de conversão:

```console
pandoc <arquivo_origem> -o <arquivo_destino>
```

Exemplos:

```console
pandoc UCC.tex -o UCC.odt
pandoc UCC.tex -o UCC.docx
pandoc UCC.tex -o UCC.epub
```

Outros formatos e exemplos:
https://pandoc.org/demos.html

## Fontes

CASTRO, Marcílio Moreira de.
Dicionário de Direito, Economia e Contabilidade.
Português–inglês / inglês–português. 4. ed. Rio de Janeiro: Forense, 2013.
[[download](https://www.dropbox.com/s/g8h20zuppojlz0b/CASTRO%2C%20Marc%C3%ADlio%20Moreira%20de%20-%20Dicion%C3%A1rio%20de%20Direito%2C%20Economia%20e%20Contabilidade.pdf?dl=0)]

Legal Information Institute (LII), Cornell Law School.
[Uniform Commercial Code](https://www.law.cornell.edu/ucc).

Legal Information Institute (LII), Cornell Law School.
[United States Code](https://www.law.cornell.edu/uscode/text).

Office of the Law Revision Counsel, U.S. House of Representatives.
[United States Code](https://uscode.house.gov).
