# Notas de tradução — português brasileiro

## Escopo concluído

Esta edição traduz os 722 arquivos da lista congelada: 606 unidades de
leitura, 81 controladores de capítulo, 20 controladores de parte, 13 fragmentos
auxiliares, uma raiz de conteúdo e um front matter. O estado, os hashes e o
método de cada arquivo estão em `translation_progress.tsv`.

A base foi `OpenLogicProject/OpenLogic` no commit
`9620cc73f9c8e0ad003c514a5d3748f29611c4c0`, árvore
`f67757bb9305b173634082ab4cefd5601a707a34`. A lista de 722 arquivos tem
SHA-256 `4F0DFAA58C38B54C00180DE30AE09507D0DF9FBEA1E0ED6729DB7E2FA77AAC2F`.

## Referência portuguesa e tradução direta

A referência pública `OpenLogicProject/OpenLogic-pt` foi fixada no commit
`51c227190f56bae45d19a85747fc031de430bd3c`, árvore
`5083d9763a3b6de3718e8400950f43e1eb4bd955`. O ZIP preservado tem SHA-256
`AC7C34787F63D1F37C14EA451A048F0BFE80A17D240F9702B64A017076DC6248`.
Dos 722 caminhos, 684 existem nessa árvore e 38 não existem.

A referência foi aproveitada apenas quando seu conteúdo pôde ser adaptado sem
romper a autoridade inglesa. Arquivos ainda ingleses, parcialmente traduzidos,
com matemática divergente ou com comandos incompatíveis foram traduzidos ou
reparados diretamente. Por isso, o progresso distingue portas estruturais,
traduções diretas e traduções assistidas pela referência.

## Regras de preservação

Cada arquivo foi confrontado com a fonte congelada para preservar:

1. nomes e ordem de comandos TeX;
2. ambientes e ordem de abertura e fechamento;
3. imports, rótulos, referências, citações, identificadores, caminhos e URLs;
4. matemática não textual, permitindo tradução somente em corpos textuais
   explícitos como `\text{…}`, `\textrm{…}`, `\textnormal{…}` e `\mbox{…}`;
5. exemplos, exercícios, front matter, navegação, licença e atribuição.

Anomalias da fonte foram preservadas quando corrigi-las mudaria silenciosamente
a autoridade. Sete correções de alta confiança encontradas durante a tradução
foram relatadas separadamente ao projeto original em
<https://github.com/OpenLogicProject/OpenLogic/issues/435>.

## Registro brasileiro

Escolhas correntes incluem `arquivo`, `seção`, `fato`, `você` e `conjunto
potência`. Alternativas materialmente úteis incluem `ficheiro`, `secção`,
`facto`, construções sem `você` e `conjunto das partes`. A edição é rotulada
honestamente como português brasileiro; não representa uma norma portuguesa,
africana ou pan-lusófona.

## Compilação e limites

O controlador completo usa `brazilian` no `babel` e compila em 1.052 páginas.
A compilação final não contém referências nem citações indefinidas. Permanecem
dois avisos de rótulo duplicado herdados da fonte:
`sfr:siz:red:prob:nat-nat` e `sfr:siz:red:prob:nat-nat@cref`.

A cobertura 722/722, a paridade mecânica, a compilação e a inspeção visual não
equivalem a revisão humana nativa, validação didática ou aceitação comunitária.
Essas condições não são alegadas nem impostas como barreira de publicação.
