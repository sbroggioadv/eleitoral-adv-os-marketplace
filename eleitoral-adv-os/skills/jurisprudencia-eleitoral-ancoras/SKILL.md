---
name: jurisprudencia-eleitoral-ancoras
description: "Jurisprudencia eleitoral ✅-only do corpus - Sumulas TSE 19/47/70, SV 18, sinteses STF Ficha Limpa com ressalva (Tema 387/860, ADC 29/30). Zero ementa de memoria; Sumula STF 728 = GAP. Use ao dizer sumula eleitoral, TSE 19, sumula 70, SV 18, Tema 860, precedente ficha limpa, jurisprudencia para a peca."
---

# JURISPRUDENCIA-ELEITORAL-ANCORAS

> Transversal. Precedente **real e citavel** no corpus - ou **GAP**. Trabalha colada ao `validador-eleitoral` e ao guard anti-alucinacao.

## Anexos obrigatorios (context/)
- `context/lc-64-ficha-limpa.md` - **par. 6** (Sumulas TSE 19/47/70 · SV 18 · STF sintese).
- `context/contencioso-eleitoral-vias.md` - GAP Sum. STF 728 · armadilhas.
- `context/cf-14-elegibilidade.md` - superveniencia · SV 18.
- `context/metodologia-eleitoral.md` - selos ✅/🟡/🔴.

## Objetivo
Devolver ancora **✅ do corpus** (ou 🟡 com ressalva) com teor e link no anexo. **Nunca** inventar acordao/sumula/tema.

## Ancoras ✅ (podem ir a peca - teor no anexo)
| Ancora | Teor util (resumo do corpus) | Uso |
|---|---|---|
| **Sum. TSE 19** | Inelegibilidade por abuso (art. 22 XIV): inicio no **dia da eleicao** do abuso; fim no dia de igual numero no **oitavo ano** seguinte | Contagem 8 anos AIJE/abuso |
| **Sum. TSE 47** | Inelegibilidade superveniente no **RCED** (CE 262): constitucional ou infraconstitucional **pos-registro**, ate a **data do pleito** | RCED - nao alargar sem base |
| **Sum. TSE 70** | Fim do prazo de inelegibilidade **antes do dia da eleicao** afasta inelegibilidade (verbete ainda cita art. 11 par. 10 Lei 9.504) | Superveniencia favoravel |
| **SV 18 STF** | Dissolucao da sociedade/vinculo conjugal **no curso do mandato** **nao afasta** inelegibilidade do CF art. 14 par. 7o | Parentesco / "divorcio limpa" = mito |

### Tensao obrigatoria na Sum. 70 (nao escolher lado)
- Art. 11 par. 10 Lei 9.504 = **REVOGADO** pela LC 219/2025.
- Texto vivo: **LC 64 art. 26-D** (alteracoes que afastem inelegibilidade **ate a diplomacao** - horizonte **mais amplo** que o verbete "antes do dia da eleicao").
- Ac.-TSE 29/5/2025 (AgR-REspEl 060022402) na pagina da sumula: marco do **1o turno** (extrato).
- 🔴 **GAP:** nao ha no corpus acordao pos-LC 219 reescrevendo a Sum. 70. **Declarar tensao** texto legal x verbete x julgado; nao afirmar que a sumula "morreu" nem que o 26-D e letra morta.

## 🟡 Sintese STF Ficha Limpa (noticia oficial lida - inteiro teor **nao** lido)
| Caso | O que a noticia registra | Selo |
|---|---|---|
| **RE 633703 Tema 387** | Ficha Limpa **nao** se aplicou as eleicoes **2010** (anterioridade CF 16) | 🟡 |
| **ADC 29/30 + ADI 4578** | Constitucionalidade; aplicacao a partir 2012; inelegibilidade **nao e pena criminal** | 🟡 |
| **RE 929670 / Tema 860** | Valida aplicacao do prazo de **8 anos** a condenados por abuso **antes** da LC 135 | 🟡 |
| **ADI 7881** | Impugna LC 219/2025 (contagem de prazos) | 🔴 **sub judice** (04/08/2026) |

**Regra 🟡:** pode **mencionar** a tese com ressalva "sintese oficial; inteiro teor nao lido no corpus". **Nao** aspas como se fosse ementa integral. Preferir reabrir PDF oficial antes de peca de alto risco.

## 🔴 Nunca citar sem reabrir fonte
- **Sumula STF 728** (prazo RE eleitoral) - HTTP 403 na captura; **GAP declarado** em `contencioso` e `codigo-eleitoral`.
- Acordaos TSE so em ementa de "Temas Selecionados" sem PDF - 🟡/nao baixar = nao pin aspas.
- Qualquer sumula TSE **nao aberta** no corpus (ex.: 1, 45 - so indexadas) - **nao inventar teor**.

## Metodologia
1. **Corpus primeiro:** grep em `lc-64-ficha-limpa.md` / `contencioso`.
2. ✅ → citar com teor do anexo + URL se houver.
3. 🟡 → ressalva + opcional WebFetch em fonte oficial (stf.jus.br / tse.jus.br).
4. 🔴/GAP → **nao citar**; listar como nao localizado.
5. Validar: `validador-eleitoral`.

## Entrega obrigatoria
Tabela: orgao/numero · tese 1-2 linhas · selo · link/anexo · pertinencia. Bloco de citacao **so** para ✅ (ou 🟡 com ressalva explicita).

## Guard
Zero ementa de memoria. Zero Sum. 728. Zero "a Sum. 70 morreu". Integra `validador-eleitoral` + `suprema-corte-eleitoral` (R3).
