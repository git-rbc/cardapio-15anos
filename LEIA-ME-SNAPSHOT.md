# Snapshot do que estava em cardapio-15anos.vercel.app

Capturado em 2026-08-28 direto do ar, porque esse site **não saía de repositório
nenhum**: foi publicado por linha de comando a partir de uma pasta, na Vercel
pessoal `vinicius-projectsfdj`, e o conteúdo existia só lá.

Não é a `main`. É um retrato, para o material parar de depender da máquina de
alguém e para dar para comparar com o que está versionado.

## Como difere da `main`

A `main` usa a convenção de 15 anos: `gastronomia.html` é o hub e `index.html`
é o buffet. Este snapshot usa a convenção do casamento: `index.html` é o hub e
`buffet.html` é o buffet.

Só existem aqui (não estão na `main`):
- `buffet.html`
- `doces.html`
- `drinks-sem-alcool.html`

O `gastronomia.html` existe nos dois, mas aqui ele é só um **redirect de 496
bytes** para a raiz: nesta versão o hub virou a inicial. Na `main` ele ainda é
o hub de verdade.

Falta um arquivo: `fotos/doces-card.webp` deu 404 no próprio site de origem, ou
seja, já estava quebrado em produção.
