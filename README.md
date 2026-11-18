# Locagora Smart – Painel de Operações

Painel único, em tela cheia, com todos os módulos: Agenda de Leads, LOC PÁTIO, LOC MECÂNICA, LOC CS, LOC GESTÃO, LOC COMERCIAL, LOC SAC, LOC SUPORTE e LOJA LOCAGORA.

É um site estático (um único `index.html`), sem build e sem dependências.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `locagora-painel`). Se for guardar dados reais da operação, deixe **privado**.
2. Envie `index.html` e este `README.md` para a branch `main`.
3. No repositório: **Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save**.
4. Em alguns minutos o painel abre em `https://SEU-USUARIO.github.io/locagora-painel/`.

> Páginas do GitHub Pages em repositório privado exigem plano pago. Como os dados ficam no navegador de cada usuário, o repositório contém só o código, nunca os registros.

## Onde ficam os dados

Hoje, no navegador (localStorage) de quem usa. Use **⬇ Backup** para exportar tudo em JSON e **⬆ Restaurar** para levar a outro computador. Cada tabela também exporta CSV.

Para vários atendentes compartilharem os mesmos dados, o próximo passo é ligar o painel ao banco (Supabase/Render).
