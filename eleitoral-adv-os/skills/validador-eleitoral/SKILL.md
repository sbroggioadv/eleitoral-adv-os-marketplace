---
name: validador-eleitoral
description: "Gate de verificacao do plugin eleitoral: cruza CADA dispositivo, sumula, resolucao, prazo e consequencia do rascunho com os anexos context/ ANTES de selar. Hospeda a tabela de correcoes travadas (CE 105, base+2026, FEFC 30/08, 299x41-A, desaprovacao x cassacao, AIME sem 8 anos no CF, art. 11 §10 morto, etc.), a lista 🟡/GAP e o gate de calendario 2026. Use antes de selar qualquer peca ou parecer, ou quando disserem confere as citacoes, esse artigo esta certo, pode protocolar."
---

# VALIDADOR-ELEITORAL — Gate de verificacao (cruza com context/)

> Camada 1 (QA de fundacao). Ultima linha antes de selar, junto com a Suprema Corte. Nao redige: audita citacao a citacao. O `anti-alucinacao-eleitoral` atua na **geracao**; **aqui** a conferencia e o veredito por item.

## Anexos obrigatorios (context/)
- Todos os 10 anexos em `context/` sob demanda — **grep o artigo e leia a faixa**.
- Checklist fixo: `metodologia-eleitoral.md` · `resolucoes-tse-2026-mapa.md` · `contencioso-eleitoral-vias.md` · `calendario-eleitoral-2026.md` · `lc-64-ficha-limpa.md` · `lei-9504-destaques.md` · `codigo-eleitoral-crimes-e-processo.md` · `contas-e-fefc-2026.md` · `cf-14-elegibilidade.md` · `lei-9096-partidos.md`.

## Objetivo e quando ativar
Para cada afirmacao juridica: **CONFIRMADO** · **CORRIGIR → [substituto]** · **CHECAR AO VIVO** (🟡/GAP). Roda antes de selar; alimenta R2/R3 da Suprema Corte.

## Tabela de correcoes travadas

| Nunca escreva | Escreva / faca |
|---|---|
| 1. "CE art. 105" / "Codigo Eleitoral art. 105" como 5 de marco | **Lei 9.504/1997, art. 105 e §3o**; CE 105 = **revogado** Lei 14.211/2021 |
| 2. "Res. 23.609/2019" (ou 23.610/23.607/23.608/23.600/23.605) **pura** como texto 2026 | **Base + alteracao 2026** (ex. 23.609/2019 + 23.754/2026) |
| 3. Calendario 2022/2024 para o pleito 2026 | **Somente Res. 23.760/2026** |
| 4. FEFC cotas ate **08/09** como vigente | **30/08 ✅** (23.752 + 23.760); 08/09 = noticia 03/08 🟡 sem ato formal |
| 5. Art. 11 §10 Lei 9.504 como vivo | **Revogado** LC 219/2025 → **LC 64 art. 26-D**. ⚠️ **PENDENTE** — **LC 64 art. 26-D** × **Súmula-TSE 70** (súmula ainda cita §10 revogado) |
| 6. "299 CE = 41-A" / sinonimos | 299 = crime (reclusao); 41-A = captacao (multa+cassacao) |
| 7. Boca de urna como CE art. 39 / 337 | **Lei 9.504 art. 39, §5o** |
| 8. Desaprovação de contas = cassação de diploma / perda automática de quitação | Desaprovação ≠ cassação; quitação **Res. 23.607/2019 com alterações da 23.752/2026, art. 80** = **não prestação**; cassação por gasto → via **30-A** ou abuso |
| 9. AIME com **8 anos** so no CF art. 14 §10 | CF §10 **nao** comina 8 anos; 8 anos tipicos da **AIJE** art. 22, XIV |
| 10. Art. 22, XV LC 64 vivo / "AIJE so 3 anos" | **XV revogado** (LC 135); XIV = 8 anos + cassacao |
| 11. RCED generico por abuso (texto antigo) | So hipoteses **CE art. 262** vigente (Lei 12.891+) |
| 12. Condicao de elegibilidade = inelegibilidade | CF 14 §3o ≠ LC 64 art. 1o |
| 13. Prazo sem dies a quo / 24h trocado por 3d residual | Dispositivo + dies a quo + natureza + duracao |
| 14. Sumula STF 728 sem reabrir fonte | **GAP** na captura (HTTP 403) — CHECAR AO VIVO ou remover |
| 15. Prazo final AIJE abuso "puro" inventado | **GAP** no art. 22 — declarar |
| 16. Rito/legitimados AIME "pela CF" | CF so §§10-11 — rito = **GAP**/🟡 |
| 17. Alinea **d** com redacao "nova" da LC 219 | Tentativa **VETADA** — permanece LC 135 |

## 🟡 / GAP — nunca afirmar seco
- Ato formal FEFC 08/09 (03/08/2026).
- Prazo final AIJE generica art. 22.
- Rito e legitimados AIME fora da CF.
- Sumula STF 728 (texto oficial nao lido).
- Portaria 449/2026 numeros se 🟡 no corpus.
- Res. 23.604 contas anuais se inteiro teor parcial.
- Prescricao penal-eleitoral (sem tabela nos arts. 289–364 abertos).
- Jurisprudencia monocratica ou ementa sem ✅ no corpus.

**Regua do 🟡:** afirma o provado → marca o que falta → diz o que conferir → roteia. Nunca vira fato categorico.

## Gate de calendario 2026 (bloqueante se a peca depender)
1. Registro: **15/08 19h** (23.760 + art. 11 Lei 9.504).
2. FEFC cotas: **30/08** ate ato formal em contrario lido no DJE.
3. Turnos: **04/10** e **25/10** (23.760).
4. Parcial contas: movimento ate 08/09; envio ate 13/09 (23.760).
5. Se a noticia de 03/08/2026 mudou o ponto da peca: **CHECAR AO VIVO** o numero da resolucao/portaria antes de selar.

## Metodologia
1. Extrair **toda** citacao do rascunho (artigo, sumula, res., prazo, consequencia).
2. Grep no anexo; ler faixa; comparar numero, redacao e vigencia.
3. Rodar a tabela de correcoes + lista 🟡/GAP + calendario.
4. Dual: se AIJE/AIME, a peca de **responde** ataca o onus de quem move? Se **move**, ha legitimidade e pedido compativel com a via?
5. Consequencia pedida bate com a via (tabela-mestra vias §0)?
6. Veredito por item + global. Um CORRIGIR ou CHECAR pendente → **nao selar**.

## Entrega obrigatoria final
Tabela: citacao · anexo/faixa · veredito (CONFIRMADO / CORRIGIR / CHECAR AO VIVO) · nota. Global **PODE SELAR** so com tudo confirmado; senao, devolve a skill de origem.

## Guard
Nenhuma peca eleitoral sela com item nao confirmado. Fonte no `context/` vence memoria. As 14 verdades e as 3 travas vivem no `anti-alucinacao-eleitoral` — rascunho que as contraria volta para la. Suprema Corte (R1-R4) roda em paralelo no fecho.
