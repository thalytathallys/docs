# Divulga Shopee API - Documentacao

Documentacao da API usando [Mintlify](https://mintlify.com).

## Setup

### 1. Instalar Mintlify CLI

```bash
npm i -g mintlify
```

### 2. Executar localmente

```bash
cd api-docs
mintlify dev
```

A documentacao estara disponivel em `http://localhost:3000`.

## Estrutura

```
api-docs/
├── docs.json              # Configuracao do Mintlify
├── openapi.json           # Especificacao OpenAPI
├── index.mdx              # Pagina inicial
├── quickstart.mdx         # Guia de inicio rapido
├── authentication.mdx     # Autenticacao
├── concepts/              # Conceitos e guias
│   ├── divulgacoes.mdx
│   ├── templates.mdx
│   ├── grupos.mdx
│   └── automacao.mdx
└── api-reference/         # Referencia da API
    ├── shopee/
    ├── whatsapp/
    ├── divulgacoes/
    ├── agendamentos/
    ├── templates/
    ├── templates-visual/
    ├── favoritos/
    ├── colecoes/
    ├── automacao/
    ├── dashboard/
    ├── ai/
    ├── credenciais/
    └── envios/
```

## Deploy

### Mintlify Cloud

1. Crie uma conta em [mintlify.com](https://mintlify.com)
2. Conecte seu repositorio GitHub
3. Configure o diretorio como `api-docs`

### Self-hosted

```bash
mintlify build
# Os arquivos estaticos estarao em .mintlify/
```

## Customizacao

Edite `docs.json` para:

- Alterar cores e tema
- Adicionar logo
- Configurar navegacao
- Adicionar integracoes (Analytics, etc.)

## Recursos

- [Documentacao Mintlify](https://mintlify.com/docs)
- [Componentes MDX](https://mintlify.com/docs/content/components)
- [Especificacao OpenAPI](https://mintlify.com/docs/api-playground/openapi)
