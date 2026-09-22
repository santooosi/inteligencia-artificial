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

Por padrão, o template utiliza o estilo bibliográfico em português:

```latex
\bibliographystyle{apalike-pt}
```

Caso seja necessário usar o estilo em inglês, basta alterar para:

```latex
\bibliographystyle{apalike}
```

Essa configuração fica na definição do comando `\referencepage`, no arquivo `eic-bcc-tcc.cls`.
