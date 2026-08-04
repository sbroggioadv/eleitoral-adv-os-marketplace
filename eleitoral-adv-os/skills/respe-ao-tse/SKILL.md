---
name: respe-ao-tse
description: "Recurso Especial eleitoral (REspe) ao TSE - CE art. 276, I (violacao de lei ou divergencia entre tribunais eleitorais). Dual recorrente x recorrido. Prazo 3 dias (CE 276 par. 1o). Nao confundir com RO (276 II) nem com RE ao STF. Use ao dizer REspe, recurso especial ao TSE, o TRE violou a lei, divergencia entre TREs, contrarrazoes no especial eleitoral, denegaram o especial."
---

# RESPE-AO-TSE

> Camada C8. **Standalone.** Dual **recorrente** x **recorrido**. Nao e RO (`ro-re-ao-stf`). Nao e agravo de admissibilidade (`agravos-e-admissibilidade`).

## Anexos obrigatorios (context/)
- `context/contencioso-eleitoral-vias.md` - **par. 10.3** (CE 276 I e par. 1o; 279) - **grep + ler faixa**.
- `context/codigo-eleitoral-crimes-e-processo.md` - CE **276, 279** - **grep + ler faixa**.
- `context/metodologia-eleitoral.md` - dual · ED (CE 275) para forçar ponto de direito.
- `context/lc-64-ficha-limpa.md` - quando a materia for inelegibilidade / AIRC art. 11 par. 2o (3 dias ao TSE apos acordao TRE no rito de registro).

## Objetivo
Passar da **admissibilidade** do REspe com hipotese correta (276 I *a* ou *b*) e prazo vivo. Peca fecha por `suprema-corte-eleitoral` + `validador-eleitoral`.

## 1. Cabimento - CE art. 276, I (somente)
Decisoes dos TREs sao **terminativas**, **salvo**:

| Inciso | Hipotese | O que provar na peca |
|---|---|---|
| **I, a** | Contra **expressa disposicao de lei** | Dispositivo violado **nomeado** (lei + artigo na mesma linha) + trecho do acordao que o contraria |
| **I, b** | **Divergência** de interpretação entre tribunais eleitorais | Acórdão paradigma + trecho que demonstra a divergência (CE art. 276, I, b) — o corpus **não** fixa “confrontação analítica” como rótulo; não inventar requisito formal além do inciso |

### ⛔ Nao e REspe
- **RO** - CE art. 276, II (*a* diploma federal/estadual; *b* denegacao HC/MS) → `ro-re-ao-stf`.
- **RE ao STF** - regime constitucional; **Sumula STF 728 = GAP** no corpus (HTTP 403) - **nao** citar sem reabrir fonte (`contencioso` par. 10.4).
- Mérito puro de fato **sem** violação de lei / divergência — o REspe **não** reabre prova só por insatisfação com o acórdão (CE art. 276, I exige *a* ou *b*).

## 2. Prazo e dies a quo
- **3 dias** (CE art. 276, par. 1o).
- Dies a quo nos casos I *a*/*b*: **publicacao da decisao**.
- Registro (AIRC): recurso ao TSE em **3 dias** da leitura/publicacao do acordao (LC 64 art. 11, par. 2o) - cruzar com a hipotese de cabimento.

ED (CE art. 275) **interrompem** o prazo para outros recursos (§5º) — usar `embargos-declaracao-eleitoral` para forçar o TRE a enfrentar o ponto de direito **antes** do REspe quando o acórdão omitiu. O corpus **não** ancora o rótulo “prequestionamento”; se a peça o invocar, **CHECAR AO VIVO** a fonte oficial.

## 3. Dual - dois blocos

### A) RECORRENTE (REspe)
1. **Tempestividade** (3 dias + dies a quo + interrupcao por ED se houver).
2. **Enquadramento** I *a* e/ou I *b* no primeiro paragrafo.
3. **Ponto de direito no acórdão:** o TRE deve ter enfrentado o dispositivo (ou ED CE 275 deve ter forçado). A **admissibilidade** do REspe tem requisitos próprios — **GAP** no corpus quanto a formulação de “não conhecimento”; **conferir a faixa** (CE art. 276 / `contencioso-eleitoral-vias` par. 10.3) **antes de citar** qualquer barreira de admissibilidade. **Não** selar “prequestionamento” sem âncora no corpus.
4. **Razão:** violação (I, a) ou divergência com paradigma (I, b); pedido de conhecimento e provimento.
5. Se denegado na origem → `agravos-e-admissibilidade` (CE art. 279, 3 dias).

### B) RECORRIDO (contrarrazoes / impugnacao ao especial)
1. **Intempestividade**.
2. **Não cabimento:** atacar o enquadramento em CE art. 276, I *a*/*b* (a via exige violação de lei ou divergência entre tribunais eleitorais). A admissibilidade do REspe tem requisitos próprios — **GAP** no corpus quanto a rol taxativo de hipóteses de não conhecimento; **não inventar** lista de não-cabimento; **conferir a faixa** antes de citar.
3. **Merito residual** so se o especial for conhecido: manter o acordao; reforcar onus de quem moveu a acao de origem (AIJE/AIME: onus do autor).
4. **Nao achar** sancao: o REspe nao cria 8 anos se a via de origem nao cominou.

## 4. Efeito
Regra geral: CE art. 257 caput (**sem** suspensivo). A excecao do par. 2o fala em recurso **ordinario** em hipotese de cassacao/afastamento/perda - **nao** reescrever o REspe como se fosse RO. Se a peca misturar vias, classifique e separe.

## Metodologia
1. Lado: recorrente | recorrido.
2. Provar 276 I *a*/*b* (ou declarar nao cabe e apontar RO/outro).
3. Prazo 3 dias + ED (CE 275) se o TRE omitiu o ponto de direito.
4. Redigir razoes **ou** contrarrazoes.
5. Fechar: `suprema-corte-eleitoral` + `validador-eleitoral`.

## Regras de ouro
- ⛔ **Nao confundir REspe com RO.**
- ⛔ **Nao citar Sumula STF 728** sem reabrir stf.jus.br (GAP corpus).
- ⛔ Nenhuma citacao sem ancora em `context/`.
- ⛔ Nomear diploma + artigo na mesma linha (homonimos / revogados).

## Entrega obrigatoria
(a) hipótese 276 I *a*/*b* ou recusa fundamentada; (b) tempestividade; (c) dual recorrente/recorrido; (d) ponto de direito enfrentado no TRE (ou ED); (e) GAP/🟡. Validado por `suprema-corte-eleitoral` + `validador-eleitoral`.

## Guard
Zero REspe "de fato". Zero RO rotulado de especial. Zero Sum. 728 inventada. Fecha por R1-R4 + validador.
