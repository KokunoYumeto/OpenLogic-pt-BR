# The Open Logic Text — edição em português brasileiro

Edição independente e completa em português brasileiro (`pt-BR`) do material
do [Open Logic Project](https://openlogicproject.org/). Ela não é uma
publicação oficial do projeto e não implica endosso dos autores ou mantenedores
do original.

## Ler, baixar e citar

- [Leitor completo em PDF](https://github.com/KokunoYumeto/OpenLogic-pt-BR/releases/download/v2026-08-17-r1/00_OLP_pt-BR_CURRENT_LINKED_READER.pdf)
- [Versão imutável: doi:10.5281/zenodo.21973105](https://doi.org/10.5281/zenodo.21973105)
- [Linhagem permanente: doi:10.5281/zenodo.21973104](https://doi.org/10.5281/zenodo.21973104)
- [Artefatos da versão 2026-08-17-r1](https://github.com/KokunoYumeto/OpenLogic-pt-BR/releases/tag/v2026-08-17-r1)

## Estado desta edição

- Os 722 arquivos da lista congelada estão traduzidos em pt-BR: 606 unidades
  de leitura, 101 controladores de capítulo/parte, 13 fragmentos auxiliares,
  uma raiz de conteúdo e um arquivo de front matter.
- O leitor completo compila em 1.053 páginas. A compilação final não contém
  referências ou citações indefinidas.
- Comandos e ambientes TeX, imports, rótulos, referências, identificadores e a
  matemática não textual foram comparados com a fonte congelada por arquivo.
- `translation_progress.tsv` registra os 722 caminhos, métodos, hashes e
  resultados de paridade.
- Não se alega revisão humana nativa, validação comunitária ou equivalência
  normativa com português europeu ou variedades dos países africanos de
  língua portuguesa.

## Fonte e referência portuguesa

A autoridade é `OpenLogicProject/OpenLogic`, commit
`9620cc73f9c8e0ad003c514a5d3748f29611c4c0`, árvore
`f67757bb9305b173634082ab4cefd5601a707a34`, sob CC BY 4.0. O universo de
tradução é a lista de 722 caminhos de `control/CLOSURE_0722.csv`.

A publicação `OpenLogicProject/OpenLogic-pt` foi usada como referência quando
estruturalmente compatível, fixada no commit
`51c227190f56bae45d19a85747fc031de430bd3c`, árvore
`5083d9763a3b6de3718e8400950f43e1eb4bd955`. Ela contém 684 dos 722 caminhos;
nenhum texto foi aceito apenas por igualdade de nome ou caminho.

## Compilar

Com uma instalação TeX Live ou MiKTeX completa:

```text
latexmk -pdf -interaction=nonstopmode -halt-on-error open-logic-complete.tex
```

O controlador usa `brazilian` no `babel`, `open-logic-locale.sty` para o
frontispício e as legendas, e `open-logic-ptBR-config.sty` para os tokens
textuais `!!{…}`.

## Artefatos e licença

A versão publicada contém o leitor PDF, fontes editáveis, evidência e
proveniência, e um manifesto SHA-256. O trabalho original é de
[The Open Logic Project](https://openlogicproject.org/people/) e é distribuído
sob a [Creative Commons Atribuição 4.0 Internacional](https://creativecommons.org/licenses/by/4.0/).
As alterações desta edição são uma tradução/adaptação independente sob a mesma
licença. Consulte `LICENSE.md`, `TRANSLATION_NOTES.md`, `CITATION.cff` e
`.zenodo.json`.
