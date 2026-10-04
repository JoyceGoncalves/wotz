# Wotz Shop — Estoque e Vendas

Aplicativo de gestão em HTML/CSS/JavaScript, pronto para publicação como site estático no Render.

## Arquivos

- `index.html`: aplicativo
- `assets/wotz-logo.png`: imagem da loja
- `render.yaml`: configuração opcional do Render Blueprint

## Publicar no Render

O repositório já inclui `render.yaml`. No Render, escolha **New → Blueprint**, conecte o repositório `JoyceGoncalves/wotz` e confirme a criação do serviço estático `wotz-shop`.

Também é possível criar um **Static Site** manualmente usando:

- Build command: `echo "No build step required"`
- Publish directory: `.`

## Primeiro acesso

- Usuário: `admin`
- Senha: `admin`

## Nota sobre os dados

Esta versão é um protótipo estático. Usuários, produtos, vendas e movimentações ficam no armazenamento local do navegador; não são sincronizados entre computadores e não há autenticação protegida por servidor. Não use dados reais da loja até conectar o aplicativo a um backend com banco de dados e autenticação.

