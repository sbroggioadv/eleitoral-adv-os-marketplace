---
name: airc-impugnacao-de-registro
description: "AIRC dual: impugna ou defende o registro. Cabimento, legitimidade (candidato/partido/federacao/coligacao/MP), prazo 5 dias (pedido LC 64 x edital Res. 23.609/2019 + 23.754/2026), rito arts. 3-15 LC 64, noticia de inelegibilidade (nao substitui AIRC). Use quando disser AIRC, impugnar registro, edital de registro, noticia de inelegibilidade, contestacao de registro, /airc."
---

> **Escolhas = botoes:** *move (impugna)* · *responde (candidato)* · *parecer ambos*.

# AIRC-IMPUGNACAO-DE-REGISTRO

> Camada C2. **Dual.** Impugnacao ao registro de candidatura (AIRC). Consequencia: indeferimento/cancelamento de **registro**; se diploma ja expedido, nulidade pelo art. 15 LC 64 — **nao** e AIJE nem AIME.

## Anexos obrigatorios (context/)
- `context/contencioso-eleitoral-vias.md` — §1 AIRC (legitimidade, prazo, rito, noticia art. 44) — **grep + ler**.
- `context/lc-64-ficha-limpa.md` — arts. 2-6, 15, 16, 25; art. 1o causas — **grep + ler**.
- `context/resolucoes-tse-2026-mapa.md` + faixas de Res. 23.609 **+ 23.754/2026** no contencioso — arts. 38, 40, 44 — **grep + ler**.
- `context/lei-9504-destaques.md` — art. 11 prazo registro — **grep + ler**.
- `context/cf-14-elegibilidade.md` — condicao x inelegibilidade — **grep + ler**.
- `context/metodologia-eleitoral.md` — dual — **grep + ler**.

## Objetivo
Peca de **ataque** ou **defesa** no registro, com dies a quo, legitimidade e causa juridica correta (condicao **ou** inelegibilidade — nunca misturar).

## Assimetria (dizer, nao achar)
- **Move** carrega o onus de **fundar** a impugacao (LC 64 art. 3o: peticao fundamentada; §3o: meios de prova e ate 6 testemunhas).
- **Responde** ataca legitimidade, tempestividade, tipicidade da causa, prova e superveniencia favoravel (art. 26-D).
- Noticia de inelegibilidade (cidadao) **nao** e AIRC e **nao** confere ao noticiante o polo pleno da impugacao.

## MOVE — impugnar o registro
1. **Legitimidade (LC 64 art. 3o caput + Res. 23.609/2019 art. 40, c/ 23.754/2026):** qualquer **candidato**, **partido**, **federacao**, **coligacao** ou **MP**, em peticao fundamentada. Impugacao de partido/candidato **nao impede** MP no mesmo sentido (art. 3o §1o).
2. **Impedimento do membro do MP:** LC 64 art. 3o §2o fala **4 anos** de atividade politico-partidaria; Res. 23.609/2019 art. 40 §3o (c/ 23.754/2026) adota **2 anos** c/c LC 75/1993 art. 80 — ⚠️ **PENDENTE** — **tensao textual** LC 64 art. 3 §2 × Res. 23.609 art. 40 §3: citar ambos; nao esconder nem "escolher" o prazo.
3. **Prazo 5 dias — dies a quo (dupla citacao obrigatoria):**
   - LC 64 art. 3o: 5 dias da **publicacao do pedido de registro**;
   - Res. 23.609/2019 art. 40 (c/ 23.754/2026): 5 dias da **publicacao do edital relativo ao pedido**.
   Na pratica o edital operacionaliza o marco. Prazos **peremptorios e continuos** (LC 64 art. 16).
4. **Objeto:** falta de **condicao** (CF 14 §3o) **ou** incidencia de **inelegibilidade** (CF 14 §§4o-9o / LC 64 art. 1o). Separar no preambulo.
5. **Rito (LC 64):** impugacao 5d (art. 3o) · contestacao **7 dias** apos notificacao (art. 4o) · inquiricao 4 dias / diligencias 5d (art. 5o) · alegacoes 5 dias comuns (art. 6o) · recurso art. 8o em **3 dias** (ver C8).
6. **Prova:** especificar meios desde logo; max. 6 testemunhas (art. 3o §3o).
7. **Crime de impugacao temeraria** — LC 64 art. 25: avisar o cliente do risco se ma-fe/temeridade.
8. **Efeitos (art. 15 LC 64, redacao LC 135):** decisao colegiada ou transito que declare inelegibilidade → nega/cancela registro ou **anula diploma** se ja expedido; comunicacao imediata MPE/orgao.

## RESPONDE — defesa do candidato
1. **Tempestividade:** dies a quo do edital/pedido; se fora, preliminar de intempestividade (peremptorio).
2. **Ilegitimidade ativa** e impedimento do membro do MP (tabela 4a x 2a; ⚠️ PENDENTE tensao textual acima).
3. **Confusao condicao x inelegibilidade** — atacar se a inicial misturou.
4. **Merito da alinea / condicao** — grepar a alinea no `lc-64-ficha-limpa.md` com **marcos LC 219/2025**; nao usar texto 2010 de memoria.
5. **Superveniencia favoravel:** art. **26-D** LC 64 (ate diplomacao) + ⚠️ **PENDENTE** — **tensao Sum. 70 × LC 64 art. 26-D**: declarar, nao "escolher lado".
6. **Cautelar 26-C** se couber (alines d,e,h,j,l,n): pedido **na interposicao** do recurso, sob pena de preclusao — detalhe em `defesa-em-inelegibilidade`.
7. Contestacao em **7 dias** (art. 4o) com docs e rol de testemunhas.

## Noticia de inelegibilidade (nao e AIRC)
**Res. 23.609/2019 art. 44 (c/ 23.754/2026):** qualquer cidadao no gozo dos direitos politicos, em **5 dias** do edital, da **noticia**; MP comunicado; **nao substitui** impugacao com legitimidade plena. Se o operador for so cidadao: explicar o teto da via.

## Consequencia (anti-troca de sancoes)
| Via | O que a AIRC entrega |
|---|---|
| AIRC | indeferimento/cancelamento de **registro**; nulidade de diploma se art. 15 |
| AIJE art. 22 XIV | cassacao registro/diploma + **8 anos** |
| AIME CF 14 §10 | impugacao de **mandato** (sem 8 anos no texto CF) |

## Metodologia
1. Lado (botoes) · cargo · data do edital/pedido · causa (condicao x inelegibilidade).
2. Grep legitimidade + prazo + rito no contencioso.
3. Montar **bloco MOVE** ou **RESPONDE** (ou ambos em parecer).
4. Cruzar `condicoes-de-elegibilidade` / `ficha-limpa-e-inelegibilidades` / `defesa-em-inelegibilidade`.
5. Fechar por `suprema-corte-eleitoral` + `validador-eleitoral`.

## Entrega obrigatoria final
(a) lado; (b) legitimidade; (c) **dies a quo** 5 dias (pedido+edital); (d) causa separada (condicao x inelegibilidade); (e) rito e prazo de contestacao/recurso; (f) tese do polo ativo e do passivo; (g) risco art. 25 se move; (h) o que a AIRC **nao** comina (8 anos por si so).

## Guard
Nunca tratar noticia de inelegibilidade como AIRC. Nunca contar 5 dias em dias uteis apos o fim do prazo de registro (art. 16). Nunca citar 23.609 sem **23.754/2026**. Nunca prometer 8 anos so com AIRC. Nunca usar art. 11 §10 Lei 9.504 como vigente. Fecha por `suprema-corte-eleitoral` + `validador-eleitoral`.
