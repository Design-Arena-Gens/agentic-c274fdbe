# Mercúrio Negro · Omniscient Market Architect Prompt

Aplicação Next.js que entrega o prompt **Mercúrio Negro**, projetado para transformar qualquer LLM em um Omniscient Market Architect (OMA) com cobertura total em finanças, macroeconomia e trading quantitativo.

## Stack
- Next.js 14 (App Router, prerenderização estática)
- React 18 + TypeScript
- CSS customizado com tema dark institucional

## Desenvolvimento
```bash
npm install
npm run dev
# http://localhost:3000
```

## Produção
```bash
npm run build
npm start  # porta 3000 por padrão
```

## Deploy
O projeto está publicado em produção via Vercel:

```
https://agentic-c274fdbe.vercel.app
```

## Estrutura
```
app/
 ├─ layout.tsx      # Metadata global e shell HTML
 ├─ page.tsx        # Página única com o prompt completo
 └─ globals.css     # Estilos globais e tema
public/             # Espaço para assets estáticos
```

## Manutenção
- `npm run lint` garante padrão de código Next/React.
- Dependências principais: `next@14.2.3`, `react@18.2.0`, `typescript@5.4.5`.
- Avaliar atualização do Next.js para uma versão com patch de segurança quando possível (ver alertas do CLI).
