---
name: recurso-ao-tre
description: "Recurso da decisao do juiz eleitoral (ou junta) ao TRE - dual recorrente x recorrido. Prazos 3 dias no rito de registro (LC 64 art. 8o) e residual CE art. 258; contrarrazoes 3 dias (art. 8o, par. 1o). Classifica o dies a quo (publicacao / mural eletronico Res. 23.609+23.754), efeito (CE 257 caput e par. 2o) e capitulos. Use ao dizer recorro ao TRE, ajuizo recurso contra a sentenca do juiz eleitoral, contrarrazoes no TRE, perdi o registro e quero recorrer, resourcei o AIJE em primeiro grau."
---

# RECURSO-AO-TRE

> Camada C8. **Standalone.** Dual **recorrente (move o recurso)** x **recorrido (contrarrazoes)**. Recebe de AIRC/AIJE/rep./RCED de 1o grau; entrega para `respe-ao-tse` / `ro-re-ao-stf` / `embargos-declaracao-eleitoral`.

## Anexos obrigatorios (context/)
- `context/contencioso-eleitoral-vias.md` - **par. 1.5** (rito LC 64 arts. 3-15, recurso 3 dias) · **par. 10** (regime recursal CE 257-265) - **grep + ler faixa**.
- `context/codigo-eleitoral-crimes-e-processo.md` - CE **257, 258, 259, 265** - **grep + ler faixa**.
- `context/lc-64-ficha-limpa.md` - rito de registro / prazos peremptorios art. 16.
- `context/metodologia-eleitoral.md` - dual · travas · dies a quo.
- `context/calendario-eleitoral-2026.md` - Res. **23.760** (marcos).

## Objetivo
Subir ao TRE com **via certa**, **tempestividade com dies a quo** e **capitulos delimitados**. Peca fecha por `suprema-corte-eleitoral` + `validador-eleitoral`.

## 1. Classifique a origem (antes de redigir)
| Origem | Prazo recursal no corpus | Dies a quo |
|---|---|---|
| AIRC / registro (municipal) | **3 dias** (LC 64 art. 8o) | publicacao da sentenca; contrarrazoes 3 dias art. 8o par. 1o |
| Residual (lei sem prazo especial) | **3 dias** (CE art. 258) | publicacao do ato/resolucao/despacho |
| Lei 9.504 art. 96 / art. 58 | **24 horas** (nao e 3 dias) | publicacao em cartorio/sessao - ver `calendario-e-prazos-eleitorais` |
| 41-A / 30-A / 73 par. 13 | **3 dias** da publicacao no DO | DO do julgamento |

> ⛔ **Nao** usar o residual de 3 dias onde a Lei 9.504 fixa **24h**. Errar o prazo = recurso morto (CE art. 259 - prazos preclusivos).

## 2. Efeito (CE 257) - nao inventar suspensao
- **Regra (art. 257 caput):** recursos eleitorais **nao** tem efeito suspensivo.
- **Excecao (art. 257 par. 2o):** recurso **ordinario** contra decisao de juiz ou TRE que resulte em **cassacao de registro, afastamento do titular ou perda de mandato** - recebido **com** efeito suspensivo.
- Preferencia de julgamento: art. 257 par. 3o (ressalva HC e MS).

⛔ **Proibido** escrever "recurso eleitoral nunca suspende" **e** "sempre suspende". Cite o caput **e** a excecao quando a hipotese for de cassacao/perda.

## 3. Dual - dois blocos (nao espelho)

### A) RECORRENTE (move o recurso)
1. **Tempestividade** com dispositivo + dies a quo + se continuo (LC 64 art. 16 apos 15/08).
2. **Admissibilidade no TRE:** CE art. 265 (cabe recurso ao TRE).
3. **Capítulos recorridos** nomeados (registro indeferido · cassação · multa · 8 anos · sucumbência). Delimite o objeto do recurso; CE art. 259 fixa prazos **preclusivos** — o corpus **não** ancora a fórmula “capítulo não recorrido preclui”; não inventar efeito além do prazo.
4. **Merito:** reabrir fato/prova ja suscitados; se for AIRC, lembrar crime de impugnacao temeraria (LC 64 art. 25) se o lado oposto tiver movido de ma-fe - so se houver base.
5. **Pedido:** reforma / anulacao parcial / efeito (se cabivel 257 par. 2o).

### B) RECORRIDO (contrarrazoes)
1. **Intempestividade** primeiro (prazo peremptorio).
2. **Tempestividade/preclusão de prazo** (CE art. 259) e eventual **objeto não recorrível** se o recurso extrapolar o que foi decidido — sem afirmar, sem âncora, que “capítulo não recorrido preclui”.
3. **Manutencao** da sentenca: onus do impugnante/representante no 1o grau (AIJE/AIME: onus de provar o abuso e de **quem move** - tese de defesa de 1a linha; ver `metodologia-eleitoral.md` par. 3).
4. **Nao inventar** legitimidade nem sancao que a via nao comina (AIME no CF par. 10 **nao** comina 8 anos no texto - `quadro-consequencias-por-via`).

## 4. Intimacao no registro (ciclo 2026)
Res. 23.609 art. 38 (redacao Res. **23.754/2026**): de **20/07 a 19/12** do ano eleitoral, intimacoes de registro a partidos/federacoes/coligacoes/candidatos pelo **mural eletronico**; termo inicial na data da publicacao (`contencioso` par. 10.7). **Cite base + alteracao 2026** (trava b).

## Metodologia
1. Lado: recorrente | recorrido | ambos (parecer).
2. Via de origem e **prazo especial** da tabela.
3. Dies a quo + contagem continua se apos 15/08 (LC 64 art. 16 + calendario).
4. Efeito 257 caput / par. 2o.
5. Redigir razoes **ou** contrarrazoes (dual).
6. Fechar: `suprema-corte-eleitoral` + `validador-eleitoral`.

## Regras de ouro
- ⛔ CE art. 105 **revogado** - se precisar do "5 de marco", e **Lei 9.504/1997 art. 105** (nomear a lei na linha).
- ⛔ Prazo perdido **nao volta**.
- ⛔ Nao confundir recurso ao TRE com REspe/RO ao TSE (`respe-ao-tse` / `ro-re-ao-stf`).
- Toda citacao com ancora em `context/`; o que o anexo nao tem = GAP.

## Entrega obrigatoria
(a) classificacao origem + prazo + dies a quo; (b) efeito 257; (c) bloco **recorrente** e/ou **recorrido**; (d) capitulos; (e) ressalvas 🟡/GAP. Validado por `suprema-corte-eleitoral` + `validador-eleitoral`.

## Guard
Zero prazo sem dispositivo. Zero "sempre/nunca suspende". Zero CE art. 105 vivo. Fecha por R1-R4 + validador.
