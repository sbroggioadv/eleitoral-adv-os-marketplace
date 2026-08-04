---
name: codigo-eleitoral-base
description: "Fundacao do Codigo Eleitoral (Lei 4.737/1965) vigente no corpus: processo e recursos (incl. 257-282, 262 RCED, 275 ED), crimes 289-354-A e rito penal 355-364; marca REVOGADOS (art. 105 CE, 329, 333 etc.) e atualizacoes (Lei 15.358/2026 em alistamento). Nao redige peca: sustenta quem redige. Use antes de skill penal, RCED ou recurso eleitoral, ou quando disserem o 105 do Codigo, RCED, embargos 275, crime 299, boca de urna no CE."
---

# CODIGO-ELEITORAL-BASE — Fundacao CE (Lei 4.737/1965)

> Camada 1. Entrega o mapa **vigente** do CE no corpus e **marca revogados**. Nao redige peca.

## Quando ativa / trilha
Antes ou junto de C7 (penal), C8 (recursos), `rced-contra-diploma`, e qualquer citacao ao CE. Disparada pelo master no passo fundacao.

**Vizinha:** `lei-das-eleicoes-base` (9.504) — o **105 vivo** esta la, nao aqui.

## Anexos obrigatorios (context/)
- `context/codigo-eleitoral-crimes-e-processo.md` — crimes + processo + recursos — **grep o artigo e leia a faixa**.
- `context/contencioso-eleitoral-vias.md` §9-10 — RCED e regime recursal — **grep + faixa**.
- `context/metodologia-eleitoral.md` trava (a) — homonimo 105 — **grep + faixa**.
- `context/lei-9504-destaques.md` — boca de urna 39 §5o (contraste) — **grep + faixa**.

## Base legal ancorada

### ⛔ Homonimo e revogados criticos
| Dispositivo | Status no corpus |
|---|---|
| **CE art. 105** | 🔴 **REVOGADO** pela Lei 14.211/2021 — **nao existe** como norma viva. Instrucoes TSE = **Lei 9.504/1997, art. 105**. |
| CE arts. 329, 333 | ✅ Revogados pela Lei 9.504/1997 |
| CE art. 294 | ✅ Revogado pela Lei 8.868/1994 |
| Texto antigo RCED (pre-12.891) | 🔴 Hipoteses amplas de abuso **substituidas** — so vale CE art. 262 vigente |

### Atualizacao 2026 (alistamento)
✅ **Lei 15.358/2026** altera CE art. 5o, IV e art. 71, VI (inalistaveis/cancelamento — pessoas recolhidas a estabelecimento prisional ainda sem condenacao definitiva). Grep no anexo de CE / destaques 9.504 mapa de alteracoes.

### Recursos e processo (faixas citaveis)
- ✅ **Art. 257 *caput***: recursos eleitorais **nao** tem efeito suspensivo.
- ✅ **Art. 257 §2o** (Lei 13.165/2015): **excecao** — RO contra decisao que resulte em cassacao de registro, afastamento do titular ou perda de mandato → efeito suspensivo. ⛔ Nao dizer "recurso eleitoral **nunca** suspende".
- ✅ **Art. 258**: prazo residual **3 dias** quando nao houver prazo especial. 🔴 Se a peca precisar do *dies a quo* fino (publicacao/ciencia), confira CE integral — o resumo do corpus so fixa a **duracao**.
- ✅ **Art. 262** (Lei 12.891/2013 + §§ Lei 13.877/2019): RCED **somente** inelegibilidade superveniente/constitucional e falta de condicao de elegibilidade; prazo **3 dias** apos **ultimo dia limite da diplomacao** (§3o) — *dies* no proprio §3o.
- ✅ **Art. 216**: diplomado exerce o mandato ate decisao final do TSE (efeito pratico do diploma).
- ✅ **Art. 275**: embargos de declaracao — **3 dias**; interrompem prazo; multa protelatorios (red. alinhada CPC). 🔴 *Dies* operacional (publicacao) — confira faixa integral se nao espelhada.
- ✅ **Art. 276**: RESPE (I) e RO (II); prazo **3 dias** (§1o) — *dies* no corpus: **publicacao** da decisao (I *a*/*b* e II *b*); **sessao da diplomacao** (II *a*). Nao confundir RESPE com RO.
- ✅ **Arts. 279 / 282**: agravos (admissibilidade) em **3 dias** — 🔴 *dies a quo* **nao** esta na faixa capturada (so "em 3 dias"); confira CE integral antes de protocolar.

### Crimes (mapa 289–354-A)
- ✅ **Art. 299** — corrupcao eleitoral (dar/oferecer/prometer/solicitar/receber; "ainda que nao aceita"); **≠ 41-A** da Lei 9.504.
- ✅ **Arts. 322–326-B** — propaganda (incl. **323 video/internet** Lei 14.192; 326-B genero no corpus); **329/333 revogados**. 🔴 **GAP** — jurisprudencia **art. 323 × deepfake/IA** **nao aberta** no corpus; **nao** selar tipicidade de IA/deepfake sem fonte primaria.
- ✅ **Arts. 348–354** falsidades; **354-A** apropriacao de recursos de campanha.
- ⛔ **Boca de urna** **nao** e "CE art. 39": e **Lei 9.504 art. 39, §5o** (`lei-9504-destaques.md` / crimes anexo §1.2).

### Rito penal (355–364)
- ✅ **Art. 355**: acao publica.
- Prazos tipicos do rito penal-eleitoral (incl. defesa em **10 dias** apos citacao no art. 359; denuncia **10 dias** no art. 357; finais **5 dias** no art. 360; recurso **10 dias** no art. 362) — **grep §2.3**; **≠** os 3 dias do contencioso civil-eleitoral. 🔴 Varios *dies a quo* (357/360/362) **nao** estao na faixa resumida — **GAP**: confira CE integral; **nao** selar contagem operacional por memoria.
- 🔴 **Prescricao:** **GAP** — nao ha tabela propria nos arts. 289–364 abertos; **nao inventar** prazo prescricional.

## Passo a passo / o que produzir
1. Classificar: recurso · RCED · crime · rito penal · (nunca "105 CE vivo").
2. Grep no anexo; ler faixa; marcar ✅/🟡/🔴.
3. Entregar quadro: dispositivo · status · faixa · ponte para skill de peca (C7/C8/RCED).

## Postura honesta
- Sumula STF 728 (prazo RE) = **GAP** na captura — nao citar sem reabrir stf.jus.br.
- Prescricao penal-eleitoral = **GAP**.
- Competencia e MP: grepar §2 do anexo CE; nao extrapolar.

## Cross-link e fechamento
Recursos → C8. Penal → C7. RCED → `rced-contra-diploma`. 41-A / boca de urna → `lei-das-eleicoes-base` + skills C3/C4/C7. Toda peca fecha por `suprema-corte-eleitoral` + `validador-eleitoral`.
