# Meu Negócio Financeiro

PWA de gestão financeira para pequenos negócios. A versão 2 adiciona autenticação Supabase e sincronização opcional usando a tabela `public.app_data`.

## Publicação
Envie todos os arquivos para a raiz do repositório GitHub Pages.

## Supabase
A tabela `public.app_data` deve existir com RLS ativado e políticas para usuários autenticados. Use apenas a Publishable Key no navegador; nunca publique a Secret Key/service_role.
