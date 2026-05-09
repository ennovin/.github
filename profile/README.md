# Ennovin

Recomendacao gastronomica conversacional — comecando por vinhos.

Plataforma B2B2C que entrega um sommelier virtual via WhatsApp para adegas, restaurantes e wine shops brasileiros. O cliente final escaneia um QR code, conversa naturalmente, e recebe recomendacoes personalizadas da carta do estabelecimento. O gestor recebe leads qualificados, dimensoes coletadas (gosto, contexto, ocasiao, emocao) e — quando habilita — link de checkout direto na conversa.

## Princípios

- **Privacidade do cliente acima de conveniencia** — LGPD-first, telefone pseudonimizado via HMAC, retencao minimizada, consentimento explicito.
- **Curadoria humana acima de automacao cega** — IA recomenda apenas itens da carta do gestor; sommelier humano permanece referencia.
- **Conversa natural acima de formularios** — WhatsApp-native, sem app, sem login para o cliente final.
- **Recomendacao explicavel acima de caixa-preta** — toda recomendacao tem um "porque" rastreavel; prompts e chains versionados.
- **Facilitador de transacao, nunca merchant of record** — quando ha checkout, o link e emitido pelo PSP do gestor; plataforma nunca toca dinheiro.

## Stack

Python (FastAPI + LangGraph) · Next.js · Postgres · Redis · DOKS · Helm · Terraform · OpenAI · Twilio · Stripe Connect Standard.

## Localizacao

Brasil. Pricing em BRL. Painel admin em PT-BR.
