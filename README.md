# Meu Negócio Financeiro — versão 3

PWA financeiro com autenticação Supabase, recuperação de senha no próprio aplicativo e sincronização opcional via `public.app_data`.

## Publicação
Substitua os arquivos da raiz do repositório GitHub Pages pelos arquivos deste pacote.

## Supabase
Configure Site URL e Redirect URL para:
`https://jrserginho.github.io/meu-negocio-financeiro/`

A tabela `public.app_data` deve existir com RLS e políticas de acesso para o próprio usuário autenticado. Use apenas a Publishable Key no navegador. Nunca publique a Secret Key ou service_role.

A recuperação de senha usa `resetPasswordForEmail` e processa o evento `PASSWORD_RECOVERY` para permitir `updateUser({ password })`.


## Tipografia
A interface usa Inter (Google Fonts), com fontes de sistema como fallback quando offline.
