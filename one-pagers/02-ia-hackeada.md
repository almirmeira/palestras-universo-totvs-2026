# 02 — "A IA que você contratou também pode ser hackeada"

> Prompt injection, memória envenenada e agentes sequestrados — a nova superfície de ataque que já afeta 1 em cada 3 agentes. Demo do ataque + checklist de defesa para levar.

| | |
|---|---|
| **Palco recomendado** | Auditório presencial (o tema mais "quente" de 2026) |
| **Duração** | 45–60 min |
| **Formato** | Palestra + demo de ataque encenado |
| **Nível** | Intermediário |

## Gancho (por que agora)

Este é *o* desafio definidor de 2026. Quando você embarca um agente de IA no seu ERP/SaaS, você cria uma **nova superfície de ataque** que os controles clássicos não cobrem:

- **Prompt injection** já afeta mais de **1/3** dos agentes em produção.
- Ataques **multi-turno** atingiram **92% de sucesso** em testes com 8 modelos.
- **Memory poisoning:** o adversário implanta informação falsa na memória de longo prazo — e, diferente do prompt injection, ela **persiste entre sessões**.
- **MCP / supply chain:** tool poisoning, RCE e acesso super-privilegiado no ecossistema de ferramentas.

É diretamente relevante para quem está colocando IA dentro de produtos — como a TOTVS.

## Promessa ao público

1. Enxergar a IA agêntica como ativo a ser protegido, não só usado.
2. Reconhecer os 5 vetores centrais (injection, tool misuse, memory poisoning, privilege escalation, supply chain/MCP).
3. Sair com um **checklist de hardening de agentes** aplicável na segunda-feira.

## Agenda (55 min)

| Bloco | Tempo | Conteúdo |
|------:|------:|----------|
| 0 | 04 min | Abertura: "você confiaria uma chave do cofre a um estagiário que acredita em tudo?" |
| 1 | 08 min | A nova superfície de ataque — mapa dos 5 vetores de 2026 |
| 2 | **14 min** | **Demo:** prompt injection + tool misuse contra um agente ligado a um ERP fictício |
| 3 | 08 min | Memory poisoning e ataques multi-turno — por que persistem |
| 4 | 08 min | MCP e supply chain de ferramentas — o elo esquecido |
| 5 | 09 min | **Checklist de hardening** (OWASP para LLM/agentes, Zero Trust para IA) |
| 6 | 04 min | Fechamento + Q&A |

## Parte prática (o diferencial)

**Demo encenada** de um *prompt injection* seguido de *tool misuse*: um agente conectado a um ERP fictício é induzido a executar uma ação indevida (ex.: exfiltrar dados de outro tenant). Em seguida, aplica-se o hardening ao vivo e repete-se o ataque — que falha. A plateia recebe o **checklist** correspondente.

## Reaproveitamento do portfólio

- `Cryp2pentest` — PTaaS governado por IA, base de técnicas ofensivas
- `flashcards-vibe-hacking` — vetores de ataque a assistentes de IA
- Acervo **EASM** (`PALESTRA - EASM`, `CyCognito-EASM-Training`) — superfície de exposição
- `grc-ia-multicloud` — governança e controles de IA

## Materiais de palco

- Slides + SVGs do mapa de vetores
- Ambiente de demo do agente vulnerável + gravação de backup
- Checklist de hardening (1 página, PDF) com QR para download
