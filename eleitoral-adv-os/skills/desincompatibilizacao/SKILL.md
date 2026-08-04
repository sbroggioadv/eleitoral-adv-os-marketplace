---
name: desincompatibilizacao
description: "Prazos e cargos de desincompatibilizacao LC 64 art. 1o II-VII pos-LC 219 (varios 4->6 meses); checklist por cargo pretendido; renuncia do §1o (6 meses); vice §2o; servidor §7o. Use quando disser desincompatibilizacao, afastamento para concorrer, quantos meses antes, prefeito quer ser deputado, servidor candidato, /desincomp."
---

> **Escolhas = botoes:** cargo **pretendido** · cargo/funcao **atual** · *ja se afastou?* · *renuncia de chefe do Executivo?*

# DESINCOMPATIBILIZACAO

> Camada C2. Prazos de **afastamento** para concorrer (LC 64 art. 1o, II-VII). **Nao** se confundem com as causas de fundo do inciso I (Ficha Limpa).

## Anexos obrigatorios (context/)
- `context/lc-64-ficha-limpa.md` — §2.2 desincomp II-VII; tabela LC 219; §§1o-3o e §7o; art. 1o §5o (renuncia x alinea *k*) — **grep + ler a faixa do inciso**.
- `context/cf-14-elegibilidade.md` — §6o renuncia 6 meses (Presidente/Governadores/Prefeitos para outros cargos); §7o parentesco — **grep + ler**.
- `context/calendario-eleitoral-2026.md` — data do pleito (1o turno) para contar meses — **grep + ler**.
- `context/metodologia-eleitoral.md` — **grep + ler**.

## Objetivo
Checklist: **cargo atual × cargo pretendido × prazo de afastamento/renuncia**, com texto **pos-LC 219/2025**, sem inventar meses de memoria.

## Regra de contagem
1. Fixar a **data do pleito** no calendario 2026 (Res. 23.760) — dies a quo reverso: o prazo corre **para tras** a partir do pleito (meses anteriores).
2. Grepar no anexo o **inciso e a alinea** do art. 1o II-VII que bate com a funcao atual e o cargo pretendido.
3. **Nao** aplicar prazo de um cargo a outro por analogia.

## Alteracoes LC 219 relevantes (ancoradas no corpus)
| Dispositivo (sintese no anexo) | Antes | Depois (LC 219) |
|---|---|---|
| I, II, g — entidades de classe | 4 meses | **6 meses** anteriores ao pleito |
| I, II, l — servidor publico | afastamento ate 3 meses antes | mantem **3 meses** + pode continuar afastado ate **10 dias apos o 2o turno**, se participar |
| IV, a — Prefeito/Vice (desincomp municipal) | 4 meses | **6 meses** |
| IV, b — MP e Defensoria na Comarca | 4 meses | **6 meses** |
| IV, c — autoridades policiais no Municipio | 4 meses | **6 meses** |

**§1o (vigente):** Presidente, Governadores e Prefeitos, para concorrer a **outros** cargos, devem **renunciar** ate **6 meses** antes do pleito (alinha CF art. 14 §6o).  
**§2o:** Vice pode candidatar-se a outros cargos **preservando o mandato** se, nos ultimos 6 meses, **nao** tiver sucedido/substituido o titular.  
**§3o:** inelegibilidade de conjuge/parentes (espelha CF 14 §7o; **SV 18** — divorcio no mandato nao limpa).  
**§7o (LC 219):** servidor que se licenciar e **nao** tiver registro formalizado/indeferido/cassado com transito deve **retornar imediatamente** as funcoes, sob pena de responsabilizacao administrativa.

## Renuncia x alinea *k*
**Art. 1o, §5o (LC 135):** renuncia para **desincompatibilizacao** com vistas a candidatura ou assuncao de mandato **nao** gera a inelegibilidade da alinea *k*, **salvo** fraude reconhecida pela Justica Eleitoral.

## O que o corpus NAO lista linha a linha
🟡 **GAP pendente** — **LC 64 art. 1º II–VII** (cargos/funções e meses de desincompatibilização) **não** expandidos linha a linha no corpus; o anexo traz **síntese + alterações 219**.  
**Regra:** para checklist fino, **grep o inciso no `lc-64-ficha-limpa.md`**; se a alínea específica não estiver expandida, **bloquear** o número de meses não ancorado e mandar conferir o dispositivo no Planalto — **não inventar** meses.

## Lado dual
- **Candidato/partido (registro):** provar afastamento/renuncia tempestiva; docs de exoneracao, licenca, ato de renuncia com data.
- **Impugnante (AIRC):** provar permanencia no cargo/funcao dentro do periodo vedado; dies a quo do edital (5 dias).

## Metodologia
1. Botoes: cargo pretendido + funcao atual + se ja houve renuncia/afastamento.
2. Calendario: data do 1o turno 2026 → contar meses.
3. Grep inciso II-VII + tabela 219 + §1o/§2o/§7o.
4. Separar: desincomp (prazo) x inelegibilidade de fundo (inciso I) x parentesco (§3o/§7o CF).
5. Entregar data-limite de afastamento e prova documental.
6. Fechar por `suprema-corte-eleitoral` + `validador-eleitoral`.

## Entrega obrigatoria final
(a) cargo pretendido e funcao atual; (b) dispositivo (inciso/alinea) com selo do anexo; (c) prazo em meses e **data-limite** calculada; (d) se e renuncia (§1o) ou afastamento; (e) vice §2o se aplicavel; (f) retorno servidor §7o; (g) gap se alinea nao expandida no corpus.

## Guard
Nunca usar prazos **4 meses** onde a LC 219 elevou para **6**. Nunca tratar desincomp como alinea de Ficha Limpa do inciso I. Nunca inventar meses sem grepar. Nunca dizer que divorcio limpa parentesco (SV 18). Fecha por `suprema-corte-eleitoral` + `validador-eleitoral`.
