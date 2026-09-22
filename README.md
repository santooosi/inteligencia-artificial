# Classe EIC-BCC-TCC

Define um modelo LaTeX para TCCs do BCC Cefet/RJ. O projeto possui os seguintes arquivos:
- **figuras/figure.png**: Exemplo de figura a ser utilizada no texto;
- **ficha.pdf**: Exemplo de arquivo de ficha catalográfica contendo as informações necessárias sobre solicitação de ficha para a biblioteca;
- **eic-bcc-tcc.cls**: Classe para escrita do TCC em LaTeX;
- **apalike-pt.bst**: Estilo bibliográfico em português, usado por padrão no template;
- **apalike.bst**: Estilo bibliográfico em inglês, para uso alternativo quando necessário;
- **references.bib**: Exemplo de arquivo contendo as informações bibliográficas das referências;
- **main.tex**: Exemplo de uso da classe ```eic-bcc-tcc```.
- **Trabalho de Conclusao EIC BCC.pdf**: PDF gerado usando a classe ```eic-bcc-tcc``` contendo a explicação sobre os elementos de um TCC.

## Artigo sobre IA generativa no ensino superior

O artigo *Generative AI and Higher Education: Trends, Challenges, and Future Directions from a Systematic Literature Review*, de João Batista, Anabela Mesquita e Gonçalo Carnaz, publicado na revista *Information* em 2024, apresenta uma revisão sistemática da literatura sobre o uso de inteligência artificial generativa no ensino superior. Seguindo as diretrizes PRISMA, os autores analisaram publicações indexadas nas bases Scopus e Web of Science entre janeiro de 2023 e janeiro de 2024: de 102 artigos inicialmente identificados, 37 atenderam aos critérios de inclusão. Os estudos foram organizados em três temas principais: aplicações de tecnologias de IA generativa, aceitação e percepções dos diferentes envolvidos e situações específicas de uso. A revisão destaca possibilidades de aplicação da IA generativa no ensino e na aprendizagem, mas também discute desafios relacionados à avaliação, às estratégias institucionais, à integridade acadêmica e às questões éticas. O trabalho aponta ainda direções para pesquisas futuras, incluindo estratégias pedagógicas, políticas e ética, impactos nos processos de ensino e aprendizagem, percepções de estudantes e professores, avanços tecnológicos e preparação para o mercado de trabalho. (Batista, Mesquita e Carnaz, 2024, DOI: 10.3390/info15110676.)

Por padrão, o template utiliza o estilo bibliográfico em português:

```latex
\\bibliographystyle{apalike-pt}
```

Caso seja necessário usar o estilo em inglês, basta alterar para:

```latex
\\bibliographystyle{apalike}
```

Essa configuração fica na definição do comando `\\referencepage`, no arquivo `eic-bcc-tcc.cls`.
