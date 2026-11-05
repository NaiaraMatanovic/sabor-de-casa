---
schema_version: "3.0"
tipo: n2
projeto: adrop
ciclo: c06
conhecimento: deploy-github-pages
qual: n2-1
nivel: fixacao
---

# n2-1 — fixação

## Cenário

O site de receitas "Sabor de Casa" (a página do bolo de cenoura que você estilizou no Treino 3 do c03) vai para o ar. A dona quer mandar o link para as amigas.

O site nunca foi publicado e tem problemas que no computador passam despercebidos. Eles só aparecem quando alguém abre o link público e começa a clicar.

## Arquivos

Copie para uma pasta nova, `estudos/treino-git/sabor-de-casa`, mantendo as pastas:

- `bolo-de-cenoura.html`
- `css/receitas.css`
- `fotos/bolo-de-cenoura.jpg`
- `fotos/ponto-da-cobertura.jpg`

Todos estão em `aluno/3 - Estudo/adrop/Versão 1/2 - Ciclos/Ciclo 03 - css-box-model/Treinos/Treino 3 - transferência/`.

Não precisa criar nem procurar imagem nenhuma.

## O que fazer

1. Leve a pasta para um repositório público novo no GitHub, chamado `sabor-de-casa`.
2. Publique o repositório no GitHub Pages.
3. Abra o link público e faça o caminho de uma visitante: abra o endereço do site, depois clique em cada link de cada página.
4. Investigue cada problema que aparecer, no link público e pelo F12.
5. Corrija no computador e leve as correções ao site, até o "Como saber que funcionou" passar inteiro.

Para os links de receitas que não existem, a decisão de como resolver é sua. O que importa é que nenhum link do site leve a uma página de erro.

## Como saber que funcionou

- Abrir `https://naiaramatanovic.github.io/sabor-de-casa/` (sem nome de arquivo no fim) mostra uma página do site, com estilo.
- A página do bolo de cenoura abre com estilo e com as duas fotos.
- Clicar em qualquer link de qualquer página do site abre uma página do site, nunca o 404 do GitHub.
- Na aba Rede, com `Ctrl + F5`, nenhuma página do site tem arquivo com 404 (o `favicon.ico` pode ter).
- O link abre e funciona no celular.
- O `git status` mostra a árvore limpa e em dia com o GitHub.

## Entrega

Crie nesta pasta um arquivo `Registro.md` com o link público do site.

Quando terminar, avise no chat. O Mentor lê os arquivos desta pasta e a pasta `estudos/treino-git/sabor-de-casa`.
