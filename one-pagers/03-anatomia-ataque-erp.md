# 03 — "Anatomia de um ataque a um ERP na nuvem — ao vivo, do phishing ao game over"

> Um ataque real encenado passo a passo contra um SaaS multi-tenant — e a defesa montada na frente da plateia com threat modeling. Evolução da "Visão Técnica de um Ataque" de 2025.

| | |
|---|---|
| **Palco recomendado** | Auditório presencial (excelente para plateia mista) |
| **Duração** | 45–60 min |
| **Formato** | Teatro técnico (ataque encenado) + threat modeling ao vivo |
| **Nível** | Acessível a técnico (narrativa conduz todos) |

## Gancho (por que agora)

Evolui a sua consagrada *"Visão Técnica de um Ataque Cibernético"* (Universo TOTVS 2025) para o mundo que a TOTVS constrói: **ERP/SaaS multi-tenant na nuvem**. Em 2026, o atacante não invade "um servidor" — ele passeia por identidades, APIs, filas e isolamento de tenant. Testes controlados mostram agentes atacantes percorrendo sistemas corporativos **em menos de 2 horas**. Ver isso encenado, do phishing ao `game over`, é o que fixa a mensagem numa plateia de 200 pessoas.

## Promessa ao público

1. Ver, de forma concreta, como um ataque moderno a SaaS realmente se desenrola.
2. Entender onde cada decisão de arquitetura teria quebrado a cadeia.
3. Aprender a conduzir uma sessão de **threat modeling (STRIDE)** numa feature real.

## Agenda (55 min)

| Bloco | Tempo | Conteúdo |
|------:|------:|----------|
| 0 | 04 min | Abertura: o e-mail inocente das 9h07 |
| 1 | **18 min** | **Ataque ao vivo:** phishing → credencial → API → escalonamento → bypass de isolamento de tenant → exfiltração |
| 2 | 06 min | Debrief: a kill chain remontada, onde estavam os pontos de quebra |
| 3 | **14 min** | **Threat modeling STRIDE** da mesma feature, montando a defesa com a plateia |
| 4 | 06 min | Arquitetura de referência: como um ERP SaaS bem desenhado teria resistido |
| 5 | 03 min | O twist de 2026: e se o atacante (ou o defensor) fosse uma IA? |
| 6 | 04 min | Fechamento + Q&A |

## Parte prática (o diferencial)

Um **ataque encenado passo a passo** contra um ERP SaaS multi-tenant fictício (do phishing ao bypass de *tenant isolation*), seguido de um exercício de **threat modeling STRIDE** conduzido ao vivo — a defesa é desenhada na frente da plateia, transformando espectadores em participantes.

## Reaproveitamento do portfólio

- `aula-totvs-arquitetura-seguranca` — **já tem** o case "ERP SaaS multi-tenant", o processo STRIDE e a arquitetura de referência completa (roteiro pronto)
- *Visão Técnica de um Ataque — Universo TOTVS* (deck 2025, base narrativa)
- `ATAQUE-APACHE-SHUTDOWN` — encenação técnica de ataque real
- *Anatomia de um Ataque Cibernético — FATECNOLOGIA 2025* (deck)

## Materiais de palco

- Slides + diagrama da kill chain + arquitetura de referência (SVGs canônicos)
- Roteiro de palco (hook, falas-âncora, clímax no bypass de tenant) — reaproveitar `GUIA-DE-CONDUCAO.md`
- Ambiente/asciinema do ataque + gravação de backup
