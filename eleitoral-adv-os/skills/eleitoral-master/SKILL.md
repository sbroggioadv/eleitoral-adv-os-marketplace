---
name: eleitoral-master
description: "Orquestrador do plugin eleitoral-adv-os e porta unica do contencioso eleitoral dual (move x responde). Identifica o LADO no proprio pedido, fixa fase do ciclo, via (AIRC/AIJE/AIME/rep./RCED/contas/penal/recurso/partidario) e prazo com dies a quo, dirime as skills e fecha toda peca por suprema-corte-eleitoral (R1-R4) + validador-eleitoral. Use quando o operador descrever tarefa eleitoral sem skill especifica, ou disser eleitoral-master, registro, AIRC, AIJE, AIME, 41-A, conduta vedada, contas, FEFC, crime 299, recurso TRE/TSE, /eleitoral-master."
---

# ELEITORAL-MASTER — Orquestrador (porta unica dual)

> Camada 0. Porta unica. A primeira pergunta do caso **nao** e "qual acao?" — e **"voce move ou responde?"**. O plugin e dual (decisao Doc 04/08/2026): contencioso pelos dois lados, com onus assimetrico declarado.

## Anexos obrigatorios (context/)
- `context/metodologia-eleitoral.md` — dual, 3 travas, 14 verdades, R1-R4 — **ler primeiro**.
- `context/contencioso-eleitoral-vias.md` — tabela-mestra via x prazo x consequencia — **grep + faixa**.
- `context/calendario-eleitoral-2026.md` — Res. 23.760 marcos (registro 15/08 19h) — **grep + faixa**.
- Demais sob demanda: `cf-14-elegibilidade.md` · `lc-64-ficha-limpa.md` · `lei-9504-destaques.md` · `codigo-eleitoral-crimes-e-processo.md` · `resolucoes-tse-2026-mapa.md` · `contas-e-fefc-2026.md` · `lei-9096-partidos.md`.

## Objetivo
Conduzir a demanda eleitoral: **lado → fase → via → prazo → skill side-aware → gate**, sem inventar legitimidade, prazo ou consequencia.

## Quando ativar
Operador descreve o caso sem skill, pede "conduz", "qual o caminho", "monta a peca". Primeira vez no plugin → `eleitoral-onboarding` **antes** de qualquer trilha.

## Protocolo de lado (gate 1 — inegociavel)
1. **LADO:** move | responde | ambos (parecer) | ambiguo → botoes (AskUserQuestion: Impugna · Defende · Ambos/parecer).
2. **FASE:** pre-registro · registro · campanha · pos-1o/2o turno · pos-diplomacao.
3. **VIA:** AIRC | AIJE | AIME | 30-A | 41-A | 73-78 | rep. 96 | resposta 58 | RCED | contas | penal | recurso | partidario.
4. **PRAZO:** dispositivo + **dies a quo** + continuo/peremptorio (trava c; LC 64 art. 16 no rito de registro).
5. Skill side-aware + `anti-alucinacao-eleitoral`.
6. `suprema-corte-eleitoral` R1-R4 + `validador-eleitoral`.

**Dual NAO significa:** simetria de sancoes; redigir peca do MP como "cliente"; inventar legitimidade (LC 64 art. 3o — move so para legitimados).

### Assimetria canonica (AIJE / AIME) — texto fixo em toda peca C3
> Em AIJE e AIME, o **onus de provar o abuso** (e demais fatos constitutivos do pedido) e de **quem move**. Isso e **tese de defesa** de primeira linha (falta de prova / indicios insuficientes / ausencia de gravidade no art. 22, XVI). Os lados **nao** sao espelhos de sancao nem de onus.

## Metodologia
1. Ler `metodologia-eleitoral.md`.
2. Classificar por `triagem-eleitoral` (lado + fase + via + docs minimos).
3. Carregar `memoria-de-caso-eleitoral`.
4. **Fundacao C1** quando a peca toca base normativa: `codigo-eleitoral-base` · `lei-das-eleicoes-base` · `lei-dos-partidos-base` · `ficha-limpa-e-inelegibilidades` · `resolucoes-tse-ciclo-2026`.
5. **Dirimir a trilha** (`metodologia-eleitoral.md` §6 — anexos e camadas):
   - **C2 registro:** `rrc-drap-dce-registro` · `airc-impugnacao-de-registro` · `defesa-em-inelegibilidade` · `condicoes-de-elegibilidade` · `desincompatibilizacao` · `substituicao-de-candidato`.
   - **C3 contencioso (todas dual):** `aije-abuso-de-poder` · `aime-impugnacao-de-mandato` · `representacoes-lei-9504` · `captacao-ilicita-41a` · `condutas-vedadas-73-78` · `direito-de-resposta-58` · `rced-contra-diploma`.
   - **C4 propaganda:** `propaganda-eleitoral-regras` · `propaganda-internet-e-ia` · `pesquisas-eleitorais`.
   - **C5 contas:** `contas-de-campanha` · `contas-partidarias-anuais` · `defesa-contas-desaprovadas` · `arrecadacao-gastos-fontes-vedadas` · `fefc-e-fundo-partidario`.
   - **C6 partidario:** `criacao-fusao-incorporacao-partido` · `filiacao-domicilio-e-janela` · `fidelidade-partidaria` · `fundo-partidario-regime`.
   - **C7 penal:** `base-penal-eleitoral` · `corrupcao-eleitoral-299` · `boca-de-urna-e-propaganda-penal` · `falsidades-e-apropriacao-campanha` · `defesa-penal-eleitoral`.
   - **C8 recursos:** `recurso-ao-tre` · `respe-ao-tse` · `ro-re-ao-stf` · `embargos-declaracao-eleitoral` · `agravos-e-admissibilidade`.
   - **T:** `calendario-e-prazos-eleitorais` · `parecer-eleitoral` · `protocolo-p4-eleitoral` · `estilo-eleitoral` · `jurisprudencia-eleitoral-ancoras` · `quadro-consequencias-por-via`.
6. Gate final: `suprema-corte-eleitoral` + `validador-eleitoral`; guard permanente `anti-alucinacao-eleitoral`.
7. Atualizar `memoria-de-caso-eleitoral`.

## Regras de ouro (nunca contrariar)
1. **art. 105 e HOMONIMO:** CE art. 105 = **REVOGADO** (Lei 14.211/2021). Vivo = **Lei 9.504/1997, art. 105 e §3o**. Nomear a lei na linha.
2. **Base 2019 + alteracao 2026** — nunca Res. 23.609/23.610/23.607/23.608 "pura" como texto final. Forma: `23.609/2019 + 23.754/2026` (e analogos). Calendario: **somente 23.760/2026**.
3. **FEFC:** 30/08 ✅ (23.752 + 23.760). Noticia 03/08/2026 sobre 08/09 = 🟡; **proibido** afirmar 08/09 vigente.
4. Consequencias **nao** intercambiaveis: cassacao de **registro** ≠ **diploma** ≠ impugnacao de **mandato** (AIME) ≠ inelegibilidade de **8 anos**.
5. **Condicao** (CF 14 §3o) ≠ **inelegibilidade** (CF 14 §§4o-9o + LC 64 art. 1o).
6. Art. 11 §10 Lei 9.504 **REVOGADO** (LC 219/2025) → superveniencia = **LC 64 art. 26-D**; tensao com Sumula-TSE 70 (declarar).
7. Crime **299 CE** ≠ captacao **41-A**; boca de urna = **Lei 9.504 art. 39 §5o**.
8. Desaprovacao de contas ≠ cassacao de diploma; quitacao impedida na **nao prestacao** (Res.-TSE 23.607/2019 + Res.-TSE 23.752/2026 art. 80).
9. Prazo eleitoral e **peremptorio**; muita via recursal em **3 dias**; rep. art. 96 / resposta em **24h**. Sem dies a quo = nao sela.
10. GAPs: prazo final AIJE generica art. 22; rito/legitimados AIME fora da CF; Sumula STF 728 (nao lida) — **declarar, nao inventar**.

## Entrega obrigatoria final
Artefato da skill acionada, validado, com memoria atualizada e proximo passo + prazo (dispositivo + dies a quo).

## Guard
Nenhuma peca sai sem lado fixado, via batendo com a **consequencia pedida**, e gates R1-R4 + validador. Na duvida de vigencia: bloquear e checar ao vivo.
