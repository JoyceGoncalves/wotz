# Wotz Shop — Estoque e Vendas

Aplicativo de gestão em HTML/CSS/JavaScript, pronto para publicação como site estático no Render.

## Arquivos

- `index.html`: aplicativo
- `assets/wotz-logo.jpg`: imagem da loja
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

## Compartilhar o catálogo

A sessão permanece ativa quando a página é atualizada e termina ao escolher **Sair**. Na aba **Catálogo**, escolha **Baixar catálogo para enviar**. O aplicativo gera um arquivo HTML independente, somente para visualização, com os produtos, preços, disponibilidade e fotos cadastradas no momento da exportação. Envie esse arquivo; quem receber pode abri-lo sem login. Ele é uma cópia e não atualiza automaticamente quando o estoque mudar.

## Cadastro de vários produtos

Na aba **Produtos**, escolha **Cadastro em lote** para preencher vários itens em linhas e salvar todos juntos, com código de barras, quantidade, custos, preço de venda e foto. Linhas vazias são ignoradas e códigos duplicados são avisados.