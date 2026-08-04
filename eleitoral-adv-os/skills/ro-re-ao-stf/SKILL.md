---
name: ro-re-ao-stf
description: "Recurso Ordinario eleitoral (CE 276 II ao TSE; CE 281 ao STF) e a porta do RE eleitoral com GAP da Sumula STF 728. Dual recorrente x recorrido. Hipoteses fechadas: diploma federal/estadual, denegacao HC/MS, invalidade de lei/ato vs CF. Use ao dizer RO eleitoral, recurso ordinario diploma, RO ao STF, HC denegado no TSE, RE eleitoral, Sumula 728."
---

# RO-RE-AO-STF

> Camada C8. **Standalone.** Cobre **RO ao TSE** (CE 276 II), **RO ao STF** (CE 281) e o **aviso de GAP** do RE. Dual **recorrente** x **recorrido**.

## Anexos obrigatorios (context/)
- `context/contencioso-eleitoral-vias.md` - **par. 10.3-10.4** (276 II, 281, 282; GAP Sum. 728) - **grep + ler faixa**.
- `context/codigo-eleitoral-crimes-e-processo.md` - CE **276 II, 281, 282** - **grep + ler faixa**.
- `context/metodologia-eleitoral.md` - dual · GAPS.
- `context/cf-14-elegibilidade.md` - quando a materia for elegibilidade / AIME (CF 14).

## Objetivo
Escolher a **hipotese correta de RO** (nao REspe) e **nao inventar** o RE via Sumula 728 sem fonte reaberta.

## 1. RO ao TSE - CE art. 276, II
| Alinea | Hipotese | Dies a quo (par. 1o) |
|---|---|---|
| **II, a** | Expedicao de diplomas nas eleicoes **federais e estaduais** | da **sessao da diplomacao** |
| **II, b** | Denegacao de **HC** ou **MS** | da **publicacao** da decisao |

Prazo: **3 dias** (CE 276 par. 1o).

> ⛔ **Nao** usar RO para "o TRE errou a lei" generico - isso e **REspe** (276 I) → `respe-ao-tse`.
> ⛔ RCED (CE 262) e via **propria** de ataque ao diploma com hipoteses limitadas - nao confundir com RO 276 II *a* (ver skills de RCED / contencioso).

## 2. RO ao STF - CE art. 281
Decisoes do TSE em regra **irrecorriveis**, **salvo**:
- as que declararem **invalidade de lei ou ato contrario a CF**;
- as **denegatorias de HC ou MS**.

Prazo: **3 dias** (CE art. 281). 🔴 O *dies a quo* **não está** na faixa capturada (só a duração) — confira o texto integral antes de protocolar.  
Denegado o RO: **agravo** em **3 dias** (CE art. 282) → `agravos-e-admissibilidade`. 🔴 Mesmo GAP de *dies a quo* no art. 282 — **proibido inventar** o marco.

## 3. RE eleitoral - 🔴 GAP Sumula STF 728
O corpus registra que buscas apontam Sumula STF 728 ("tres dias" para RE contra decisao do TSE), mas a pagina do STF retornou **HTTP 403** na captura - **texto oficial nao lido**.

**Regra inviolavel desta skill:**
- **Nao** afirmar Sumula 728 nem o prazo do RE **como se estivesse no corpus**.
- Se o caso exigir RE: declarar **GAP**, mandar **reabrir** stf.jus.br / fonte oficial, e so entao citar.
- Enquanto GAP: trabalhar com **RO 281** nas hipoteses legais e nao "inventar RE".

## 4. Efeito (CE 257)
- Caput: sem suspensivo (regra).
- Par. 2o: recurso **ordinario** contra decisao de juiz ou TRE que resulte em **cassacao de registro, afastamento do titular ou perda de mandato** → **com** efeito suspensivo.
- ⛔ Nao dizer "nunca suspende" nem "sempre suspende".

## 5. Dual - dois blocos

### A) RECORRENTE
1. Enquadrar **276 II *a*/ *b*** ou **281** no primeiro paragrafo.
2. Tempestividade (3 dias + *dies a quo* **só se ancorado**): no RO-TSE, CE 276 §1º dá sessão de diplomação (II *a*) ou publicação (II *b*); no RO-STF (281/282) o corpus **não** fixa o marco — **GAP**, conferir texto integral.
3. Fundamento constitucional/legal objetivo (invalidade vs CF; denegacao HC/MS; diploma nas hipoteses).
4. Pedido: conhecimento e provimento; se for o caso, efeito 257 par. 2o.
5. Se denegado: agravo 279/282.

### B) RECORRIDO
1. **Nao cabimento** (via errada: era REspe; diploma municipal fora de 276 II *a*; HC/MS nao denegado).
2. **Intempestividade** (dies a quo da sessao de diplomacao e armadilha classica).
3. Manutencao do acordao; onus e sancao da via de origem (nao inflar 8 anos se a via nao cominou - `quadro-consequencias-por-via`).
4. Em RE: se a parte contraria citar Sum. 728 sem fonte, **exigir** a fonte oficial (GAP simetrico).

## Metodologia
1. Lado: recorrente | recorrido.
2. RO-TSE vs RO-STF vs RE-GAP.
3. Dies a quo (sessao diplomacao / publicacao).
4. Dual razoes / contrarrazoes.
5. Fechar: `suprema-corte-eleitoral` + `validador-eleitoral`.

## Regras de ouro
- ⛔ RO != REspe.
- ⛔ Sumula 728 **sem reabrir fonte = proibido**.
- ⛔ CE art. 105 revogado; "5 de marco" = Lei 9.504/1997 art. 105.
- Citacao so com ancora em `context/`.

## Entrega obrigatoria
(a) via e hipotese (276 II / 281 / RE-GAP); (b) prazo + dies a quo; (c) dual; (d) efeito 257; (e) bloco GAP 728 se RE. Validado por `suprema-corte-eleitoral` + `validador-eleitoral`.

## Guard
Zero Sum. 728 "de memoria". Zero RO onde cabia especial. Fecha por R1-R4 + validador.
