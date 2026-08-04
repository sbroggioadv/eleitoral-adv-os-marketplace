---
name: calendario-e-prazos-eleitorais
description: "Trava de calendario e prazos eleitorais 2026 - Res. 23.760 + tabela por via com dies a quo (5d AIRC, 15d AIME/30-A, ate diplomacao 41-A/73, 3d RCED/recursos, 24h art. 96/58). FEFC 30/08 ok, 08/09 so noticia amarela. Use ao dizer qual o prazo, calendario 2026, ate quando posso ajuizar, dies a quo, perdi o prazo, FEFC, registro 15/08."
---

# CALENDARIO-E-PRAZOS-ELEITORAIS

> Transversal. **Trava (c)** do dominio. Nao redige peca - **ancora o relogio** de todas as skills. Dual: quem move **e** quem responde precisam do mesmo dies a quo.

## Anexos obrigatorios (context/)
- `context/calendario-eleitoral-2026.md` - Res. **23.760/2026** (somente - nao reutilizar 2022/2024).
- `context/contencioso-eleitoral-vias.md` - **par. 0, 10.6, 11** (prazos por via).
- `context/resolucoes-tse-2026-mapa.md` - base + alteracao 2026 · FEFC.
- `context/metodologia-eleitoral.md` - travas a/b/c · prazo peremptorio.
- `context/lc-64-ficha-limpa.md` - art. 16 (prazos peremptorios e continuos).

## Objetivo
Devolver **marco + dispositivo + dies a quo + se continuo/peremptorio**. Sem dies a quo = nao sela.

## 1. Marcos 2026 citaveis (Res. 23.760)
| Marco | Data | Selo |
|---|---|---|
| Data-limite instrucoes TSE | **5 de marco** - **Lei 9.504/1997 art. 105** (nao CE 105) | ✅ |
| Registro candidatura (DRAP/RRC) | **15/08/2026 ate 19h** | ✅ |
| Contagem prazos continuos (eleicoes) | a partir de **15/08** (LC 64 art. 16) | ✅ |
| FEFC / FP minimos mulheres-negras-indigenas (calendario) | **30/08/2026** | ✅ |
| Prestacao parcial contas (movimento ate 08/09; envio ate) | **ate 13/09/2026** | ✅ |
| 1o turno | **04/10/2026** | ✅ |
| 2o turno | **25/10/2026** | ✅ |

## 2. ⛔ TRAVA FEFC 30/08 ✅ vs 08/09 🟡
- Corpus: Res. 23.607/2019 art. 17 par. 9o (redacao 23.752/2026) + calendario 23.760 = **30 de agosto** ✅.
- Noticia TSE **03/08/2026** sobre mudanca para **08/09** = 🟡; **ato formal nao localizado**.
- 🔴 **PROIBIDO** afirmar 08/09 como vigente em peca. Se mencionar a noticia: selo 🟡 + ressalva de ato formal pendente.

## 3. Tabela de prazos por via (ajuizamento + recurso)
| Via | Prazo de ajuizamento / marco | Dies a quo | Recurso tipico |
|---|---|---|---|
| **AIRC** | **5 dias** | publicacao do **pedido** (LC 64 art. 3o) / **edital** (Res. **23.609/2019** art. 40 **+ 23.754/2026**) - tensao 🟡: citar ambos | **3 dias** (LC 64 art. 8o) |
| **AIJE** art. 22 | 🔴 **prazo final generico GAP** no art. 22 | nao inventar; 30-A/41-A/73 tem prazo proprio | rito art. 22; recurso conforme a lei da via |
| **AIME** | **15 dias** | **diplomacao** (CF 14 par. 10) | rito legal 🟡 GAP |
| **30-A** | **15 dias** | diplomacao | **3 dias** DO (Lei 9.504) |
| **41-A** | ate a **diplomacao** (par. 3o) | marco final = diplomacao | **3 dias** DO |
| **73** condutas | ate diplomacao (par. 12) | idem | **3 dias** DO (par. 13) |
| **Dir. resposta 58 — pedido** | **24h** HG / **48h** programacao radio-TV / **72h** imprensa / internet (a qualquer tempo se ainda divulgado ou **72h** apos retirada) | **veiculacao** / retirada (art. 58 §1o) | — |
| **Dir. resposta 58 — defesa** | **24h** | intimacao / ciencia do pedido (§2o) | — |
| **Dir. resposta 58 — decisao** | ate **72h** | do **pedido** (§2o) | — |
| **Dir. resposta 58 — recurso** | **24h** | **publicacao** em cartorio/sessao (§5o); contrarrazoes em igual prazo | **24h** no grau recursal (§6o) |
| **Rep. 96 — recurso** | 🟡 caput sem prazo geral de ajuizamento | "salvo disposicoes especificas" | **24h** (recurso tipico) |
| **RCED** | **3 dias** apos **ultimo dia limite** da diplomacao | CE 262 par. 3o; suspensao 20/12-20/01 | regime CE |
| **Recursos residuais CE** | **3 dias** | publicacao (CE 258) | - |
| **REspe / RO** | **3 dias** | 276 par. 1o (publicacao ou sessao diplomacao) | - |
| **ED** | **3 dias** | publicacao; **interrompem** outros prazos (275 par. 5o) | - |

## 4. Regras de contagem (nao negociar)
1. Prazo eleitoral e **peremptorio**. Perdido = morto (CE 259 preclusivo).
2. Apos **15/08**, LC 64 art. 16: prazos do art. 3o e seguintes **peremptorios e continuos**; apos fim do prazo de registro **nao se suspendem** sabados/domingos/feriados.
3. **24h** (96/58) **nao** e "3 dias residual".
4. Toda peca: **dispositivo + dies a quo + continuo/peremptorio + numero (3d/24h/5d/15d)**.

## 5. Trava (a) e (b) no relogio
- **Art. 105:** vivo = **Lei 9.504/1997 art. 105**; CE art. 105 = **REVOGADO** (Lei 14.211/2021).
- Resolucoes: **base 2019 + alteracao 2026** (ex.: 23.609+23.754). Calendario = **so 23.760**.

## Metodologia
1. Identificar via e fase do ciclo.
2. Grep o prazo no `contencioso` / `calendario`.
3. Devolver tabela: marco · dies a quo · selo · risco de perda.
4. Se GAP (AIJE final; rito AIME; FEFC 08/09): **declarar**, nao preencher.

## Entrega obrigatoria
Tabela do caso com (a) via; (b) prazo; (c) dies a quo; (d) se continuo; (e) FEFC/registro se relevante; (f) GAPS. Nao redige peca.

## Guard
Zero 08/09 FEFC vigente. Zero CE art. 105 vivo. Zero prazo sem dies a quo. Integra `validador-eleitoral`.
