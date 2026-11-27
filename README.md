# Monitoramento PAP

Minissistema em desenvolvimento para apoiar o controle e o acompanhamento dos PAPs da SAF pelas equipes de monitoramento.

## Tecnologias

- HTML5, CSS3 e JavaScript puro com módulos ES.
- Bootstrap via CDN, quando necessário.
- Supabase, previsto para banco de dados e autenticação.
- GitHub para versionamento.
- GitHub Pages como hospedagem temporária planejada.

## Estrutura de diretórios

```text
monitoramento-pap/
├── index.html
├── README.md
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── config.js
│   │   ├── supabase.js
│   │   ├── app.js
│   │   └── modules/
│   │       └── README.md
│   └── img/
│       └── README.md
└── database/
    ├── schema.sql
    └── policies.sql
```

## Principais arquivos e responsabilidades

- `index.html`: documento HTML principal e carregamento dos recursos da aplicação.
- `assets/css/style.css`: estilos da aplicação.
- `assets/js/config.js`: espaço reservado para configurações públicas.
- `assets/js/supabase.js`: ponto reservado para a futura inicialização do cliente Supabase.
- `assets/js/app.js`: ponto de entrada do JavaScript.
- `assets/js/modules/`: diretório reservado para módulos JavaScript.
- `assets/img/`: diretório reservado para imagens e recursos visuais.
- `database/schema.sql`: reservado à futura definição da estrutura do banco de dados.
- `database/policies.sql`: reservado às futuras políticas de segurança e acesso (RLS).

## Situação atual

O repositório contém somente a estrutura inicial e arquivos-base. As telas, regras de negócio e funcionalidades ainda não foram implementadas.

A integração com o Supabase ainda não foi configurada. O GitHub Pages também ainda não foi configurado.

Nenhuma tabela ou política de banco de dados foi definida nesta etapa.

## Segurança

Não inserir credenciais administrativas nem a chave `service_role` no frontend. Quando a integração for autorizada e implementada, utilizar somente a chave pública apropriada e políticas RLS compatíveis com as regras de acesso aprovadas.
