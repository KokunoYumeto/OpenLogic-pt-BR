# The Open Logic Text — edição em português brasileiro

> Esta edição consta do [catálogo central de traduções do Open Logic](https://github.com/KokunoYumeto/OpenLogic-translations); o catálogo distingue a cobertura das fontes traduzidas da cobertura do leitor independente.

Edição independente e completa em português brasileiro (`pt-BR`) de
*The Open Logic Text*, do [Open Logic Project](https://openlogicproject.org/).
O livro apresenta lógica formal e metalógica em um percurso amplo: lógica
proposicional e de primeira ordem, teoria de modelos, computabilidade,
incompletude, lógica modal, teoria dos conjuntos e teoria da prova.

## Ler, baixar e citar

- [Leitor completo em PDF](https://github.com/KokunoYumeto/OpenLogic-pt-BR/releases/download/v2026-08-20-r5/00_OLP_pt-BR_CURRENT_LINKED_READER.pdf)
- [Versão imutável: doi:10.5281/zenodo.22036013](https://doi.org/10.5281/zenodo.22036013)
- [Linhagem permanente: doi:10.5281/zenodo.21973104](https://doi.org/10.5281/zenodo.21973104)
- [Fontes e evidência da versão 2026-08-20-r5](https://github.com/KokunoYumeto/OpenLogic-pt-BR/releases/tag/v2026-08-20-r5)

## Esta edição

- O corpus congelado tem 722 arquivos traduzidos: 606 unidades de leitura,
  101 controladores de capítulo ou parte, 13 fragmentos auxiliares, uma raiz
  de conteúdo e um arquivo de abertura.
- O leitor completo tem 1.029 páginas em formato Letter, com sumário,
  bibliografia e links internos.
- Comandos e ambientes TeX, imports, rótulos, referências, identificadores e
  a estrutura matemática foram comparados com a fonte congelada por arquivo.
- `translation_progress.tsv` registra os 722 caminhos, estados, hashes e
  resultados de paridade.

## Fonte e atribuição

A autoridade textual é `OpenLogicProject/OpenLogic`, commit
`9620cc73f9c8e0ad003c514a5d3748f29611c4c0`, árvore
`f67757bb9305b173634082ab4cefd5601a707a34`, sob CC BY 4.0. A edição
portuguesa existente em `OpenLogicProject/OpenLogic-pt`, commit
`51c227190f56bae45d19a85747fc031de430bd3c`, foi usada como referência
quando estruturalmente compatível. Esta publicação é uma adaptação
independente e não implica endosso dos autores ou mantenedores do original.

## Compilar

Com uma instalação completa de TeX Live ou MiKTeX:

```text
latexmk -pdf -interaction=nonstopmode -halt-on-error open-logic-complete.tex
```

O controlador usa `brazilian` no `babel`, Palatino/Helvetica/Courier e a
infraestrutura completa do Open Logic Project.

## Arquivos publicados

A versão inclui o leitor PDF, as fontes TeX editáveis, a evidência de
proveniência e um manifesto SHA-256. Consulte `LICENSE.md`,
`TRANSLATION_NOTES.md`, `CITATION.cff` e `.zenodo.json`.
