---
name: quadro-consequencias-por-via
description: "Tabela acao x prazo x cassacao registro/diploma/mandato x multa x 8 anos - anti-troca de sancao no contencioso eleitoral. Dual: o que cada lado pode pedir e o que nao cabe. Use ao dizer o que eu ganho se ganhar a AIJE, AIME da 8 anos?, cassacao de diploma ou mandato, consequencia da via, troca de sancao."
---

# QUADRO-CONSEQUENCIAS-POR-VIA

> Transversal. **Anti-troca de sancao.** Consequencias **nao sao intercambiaveis** (`contencioso` par. 0). Dual: limita o **pedido** de quem move e a **defesa** de quem responde.

## Anexos obrigatorios (context/)
- `context/contencioso-eleitoral-vias.md` - **par. 0 e 11** (tabela-mestra).
- `context/codigo-eleitoral-crimes-e-processo.md` / contas - desfechos distintos.
- `context/metodologia-eleitoral.md` - verdade 4 · assimetria AIJE/AIME.
- `context/lc-64-ficha-limpa.md` - art. 22 XIV · alinea *j* · art. 15.

## Objetivo
Devolver, para a via do caso: **o que cai**, **o que nao cai**, **prazo**, **8 anos sim/nao**. Impede peca que pede "8 anos + perda de mandato + multa" na via errada.

## Tabela-mestra (corpus par. 11 - selos do anexo)
| Acao | Marco do prazo | Cassacao **registro** | Cassacao **diploma** | Perda **mandato** | Multa | Inelegib. **8 anos** |
|---|---|---|---|---|---|---|
| **AIRC** | 5d pedido/edital | Sim (indeferimento/cancelamento) | Nulidade se ja expedido (LC 64 art. 15) | Nao e objeto proprio | Nao no art. 15 | Se a causa for alinea LC 64 art. 1o |
| **AIJE** art. 22 | 🔴 prazo final generico **GAP** | Sim (XIV) | Sim (XIV) | Indireto se diploma cassado | Nao no XIV | **Sim** (XIV - 8 anos a partir da eleicao do abuso; Sum. TSE 19) |
| **AIME** | 15d diplomacao (CF 14 par. 10) | Nao e o nome da sancao CF | 🟡 via perda de mandato na pratica | **Sim** (objeto CF) | Nao no par. 10 | **Nao** no texto do par. 10 |
| **30-A** | 15d diplomacao | - | **Sim** (par. 2o) | - | - | Via art. 1o I *j* (gastos/doacao ilicitos) se condenacao |
| **41-A** | Ate diplomacao | **Sim** | **Sim** | - | **Sim** (1k-50k UFIR) | Via art. 1o I *j* (captacao ilicita) |
| **73** condutas | Ate diplomacao (par. 12) | **Sim** (par. 5o) | **Sim** (par. 5o) | - | **Sim** (par. 4o) | Via *j* se cassacao |
| **Dir. resposta 58** | 24/48/72h | Nao | Nao | Nao | Sim se descumprir (par. 8o) | Nao |
| **Rep. 96** | 🟡 sem prazo geral | Depende do dispositivo | Depende | Depende | Depende | Depende |
| **RCED** | 3d apos ultimo dia limite diplomacao | Nao e AIJE | Afasta diploma nas hipoteses do caput | Pode afetar exercicio (CE 216: exerce ate TSE decidir) | Nao | **Nao** comina 8 anos |
| **Contas (adm)** | calendarios Res. contas | Nao automatico | Nao automatico | Nao automatico | Regime proprio | Nao confudir com AIJE |
| **Crime 299 CE** | rito penal | Nao e a sancao do tipo | Nao e a sancao do tipo | Nao e a sancao do tipo | Dias-multa penais | Inelegib. pode vir de **condenacao** em alinea propria - nao misturar com 41-A |

## Dual - como usar o quadro

### Quem **move**
1. Escolher a via pelo **objeto util** (quer cassar registro na campanha? diploma? mandato pos-diplomacao? 8 anos?).
2. Pedir **so** o que a via comina. Pedir 8 anos em AIME **so com CF par. 10** = erro.
3. Se o mesmo fato caber em mais de uma via: `protocolo-p4-eleitoral` + prazos distintos.

### Quem **responde**
1. Argir **pedido juridicamente impossivel** / inadequacao da via.
2. Separar: mesmo que haja ilicito, a **sancao pedida** pode estar errada.
3. Em AIJE/AIME: onus da prova do abuso e de quem move - defesa de 1a linha.
4. RCED: limitar ao caput do CE 262 (nao AIJE disfarcada).

## Erros classicos (proibidos na peca)
1. "AIME cassou e gerou 8 anos" **so** com CF art. 14 par. 10.
2. "AIJE so multa" (XIV e cassacao + 8 anos).
3. "RCED e o recurso generico pos-diploma para abuso".
4. "Desaprovacao de contas = cassacao de diploma".
5. "299 e a mesma coisa que 41-A".
6. "Recurso eleitoral nunca/sempre suspende" (CE 257 caput + par. 2o).

## GAPS a declarar (nao preencher)
- Prazo final da **AIJE generica** de abuso (art. 22 silente).
- **Rito legal** da AIME (legitimados/prazos de defesa) ausente na CF.
- **Sum. STF 728** (RE) sem texto lido.
- 🟡 **PENDENTE** — FEFC **08/09** (noticia TSE 03/08/2026) **sem ato formal** localizado; vigente no corpus = **30/08 ✅** (Res. 23.607/2019 art. 17 §9º, red. 23.752/2026). **Proibido** afirmar 08/09 como vigente.

## Metodologia
1. Identificar via real do caso (nao a que o usuario "acha").
2. Devolver linha da tabela + dies a quo (`calendario-e-prazos-eleitorais`).
3. Dual: pedidos cabiveis x defesas de inadequacao.
4. Se multi-via: matriz P4.

## Entrega obrigatoria
(a) via; (b) o que a via **comina**; (c) o que **nao** comina; (d) prazo; (e) 8 anos sim/nao com base; (f) GAPS. Validar pedidos da peca contra esta tabela antes de `suprema-corte-eleitoral`.

## Guard
Zero troca de sancao. Zero 8 anos sem alinea/XIV. Integra `parecer-eleitoral` e skills de peca. Fecha com `validador-eleitoral` se a peca citar numero de multa/UFIR.
