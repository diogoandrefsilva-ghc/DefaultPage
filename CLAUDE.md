# DefaultPage — guia para o assistente

Página simples (landing/default) servida no GitHub Pages.
**Sem build, sem npm.** Um único `index.html` (~231 linhas) com markup + CSS + JS inline.

## Regras
- É pequeno: lê o `index.html` todo só se precisares; caso contrário, vai direto ao troço relevante.
- Faz **edições cirúrgicas** (diffs pequenos). Não reescrevas o ficheiro inteiro sem necessidade.
- Se houver `onclick="…"` no HTML, as funções têm de continuar **globais**.

## Deploy
GitHub Pages a partir de `main`. Um push para `main` publica.
