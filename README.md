# Custo Certo 2.0

Base profissional do Custo Certo, construída com Next.js, TypeScript e estrutura preparada para Supabase e Vercel.

## O que já funciona

- Dashboard responsivo
- Catálogo de produtos
- Busca
- Favoritos
- Comparação de TVs
- Orçamento
- Alertas
- Gráfico de histórico
- Cadastro local de produtos
- Índice Custo Certo
- Layout adaptado para celular
- Esquema inicial do Supabase
- Verificação automática no GitHub Actions

> Os preços atuais são dados demonstrativos. A integração real com lojas será feita na próxima etapa usando APIs e meios permitidos.

## Como usar no computador

Instale o Node.js 22 ou superior.

```bash
npm install
npm run dev
```

Abra:

```text
http://localhost:3000
```

## Publicar na Vercel

1. Envie todos os arquivos para o repositório `custo-certo`.
2. Entre na Vercel.
3. Clique em **Add New > Project**.
4. Importe o repositório do GitHub.
5. A Vercel reconhecerá o Next.js automaticamente.
6. Clique em **Deploy**.

## Configurar Supabase posteriormente

1. Crie um projeto no Supabase.
2. Execute `supabase/schema.sql` no SQL Editor.
3. Copie `.env.example` para `.env.local`.
4. Preencha as chaves do projeto.

## Importante ao substituir o site antigo

Apague os arquivos antigos da raiz antes de enviar esta versão, especialmente:

- `index.html`
- `styles.css`
- `app.js`

Depois envie o conteúdo deste ZIP diretamente para a raiz do repositório.
