# Formulário de Inscrição

Página de formulário para captura de leads com envio via webhook.

## Deploy

Este projeto está configurado para deploy automático no **Vercel**.

### Como fazer o deploy

1. Instale a Vercel CLI: \
pm i -g vercel\
2. Rode \ercel\ na pasta do projeto e siga as instruções
3. Ou conecte o repositório diretamente pelo dashboard do Vercel: https://vercel.com/new

## Campos do formulário

- Nome Completo
- Email
- Telefone
- Idade
- Ocupação Atual
- Segmento de Mercado

## Webhook

Os dados são enviados via \POST\ em JSON para o endpoint configurado.

