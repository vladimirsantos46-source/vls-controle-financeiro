# VLS — Controle Financeiro

Aplicação privada de controle financeiro pessoal, com interface responsiva e autenticação pelo Supabase.

## Tecnologias
- HTML, CSS e JavaScript
- Supabase Auth
- Supabase Postgres com Row Level Security (RLS)

## Segurança
- Este repositório contém apenas código-fonte.
- Não adicionar planilhas financeiras, extratos, senhas, tokens ou chaves secretas.
- A chave publishable do Supabase pode ser usada no cliente; nunca incluir a chave `service_role`.
- Os registros financeiros devem permanecer protegidos por políticas RLS vinculadas a `auth.uid()`.

## Estrutura inicial
- `index.html`: aplicação web inicial.
- `.gitignore`: arquivos locais e segredos excluídos do Git.

## Execução
Abra `index.html` em um servidor estático local ou publique o repositório privado em um serviço de hospedagem compatível. A publicação ainda não está configurada.
