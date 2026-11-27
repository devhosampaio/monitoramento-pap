# Monitoramento PAP

Minissistema para apoiar o controle e o monitoramento dos PAPs da SAF.

## Stack

- HTML, CSS e JavaScript puros (módulos ES).
- Bootstrap via CDN, quando necessário.
- Supabase para banco de dados e autenticação.
- GitHub para versionamento.
- GitHub Pages para hospedagem.

## Estrutura

- `index.html`: documento principal da aplicação.
- `assets/css/style.css`: estilos personalizados.
- `assets/js/config.js`: configurações públicas do projeto.
- `assets/js/supabase.js`: ponto de integração com o Supabase.
- `assets/js/app.js`: ponto de entrada da aplicação.
- `assets/js/modules/`: espaço para módulos independentes.
- `assets/img/`: recursos de imagem.
- `database/schema.sql`: reservado à futura modelagem do banco.
- `database/policies.sql`: reservado às futuras políticas de segurança.

## Estado atual

Esta é apenas a estrutura inicial. Telas, funcionalidades, configuração do Supabase, modelagem do banco, políticas de acesso e publicação ainda não foram implementadas.

## Segurança

Nunca inclua credenciais administrativas ou a chave `service_role` no código do frontend. Quando o Supabase for configurado, utilize apenas a chave pública apropriada e políticas RLS definidas para as regras de negócio.
