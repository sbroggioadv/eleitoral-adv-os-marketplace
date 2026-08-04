---
name: lei-das-eleicoes-base
description: "Fundacao da Lei 9.504/1997 (destaques do corpus): art. 11 registro (incl. §2o idade Lei 15.230; §10 revogado; §16 RDE), art. 24 fontes vedadas, 30-A, 36-A, 39 §5o boca de urna, 41-A, 57-A-J internet, 58 resposta, 73-78 condutas vedadas, 96 representacoes e o art. 105 (instrucoes TSE — vivo). Nao redige peca: sustenta. Use antes de skills de registro, propaganda, representacao, 41-A, 73 ou contas, ou quando disserem art. 105 da lei das eleicoes, 15 de agosto 19h, captacao ilicita."
---

# LEI-DAS-ELEICOES-BASE — Fundacao Lei 9.504/1997

> Camada 1. Mapa dos destaques **citaveis** no corpus. Nao redige peca.

## Quando ativa / trilha
Antes de C2 (registro), C3 (rep./41-A/73/58), C4 (propaganda), C5 (contas/30-A). Master dispara no passo fundacao.

## Anexos obrigatorios (context/)
- `context/lei-9504-destaques.md` — destaques + art. 105 — **grep o artigo e leia a faixa**.
- `context/contencioso-eleitoral-vias.md` — prazos e ritos das representacoes — **grep + faixa**.
- `context/calendario-eleitoral-2026.md` — 15/08 19h — **grep + faixa**.
- `context/contas-e-fefc-2026.md` · `resolucoes-tse-2026-mapa.md` — quando tocar contas/FEFC/resolucoes.

## Base legal ancorada

### ⛔ Art. 105 — o vivo (trava a)
✅ **Lei 9.504/1997, art. 105**: ate **5 de marco** do ano da eleicao o TSE expede instrucoes (carater regulamentar, sem restringir direitos nem sancoes distintas).
✅ **§ 3o**: so resolucoes publicadas **ate 5 de marco** se aplicam ao pleito daquele ano.
🔴 **CE art. 105** = revogado Lei 14.211/2021 — **nunca** usar como "5 de marco".
Forma em peca: *Lei n. 9.504/1997, art. 105, § 3o*.

### Registro — art. 11
✅ **Art. 11**: partidos/coligacoes solicitam registro ate as **19h do dia 15 de agosto** do ano eleitoral (red. Lei 13.165/2015). Marco 2026: Res. 23.760.
✅ **§ 2o** (red. **Lei 15.230/2025**): idade minima — Executivo = posse; Camara Municipal = limite do registro; demais legislativos = "posse presumida" em ate 90 dias da eleicao da Mesa (verbatim no anexo).
🔴 **§ 10 REVOGADO** pela **LC 219/2025**. Superveniencia favoravel → **LC 64 art. 26-D** (nao o §10).
✅ **§ 16** (LC 219): **RDE** — Requerimento de Declaracao de Elegibilidade (operacionalizado em Res. 23.609 art. 9o-B via 23.754).

### Contas e arrecadacao
✅ **Art. 24** — fontes vedadas de doacao (grep faixa).
✅ **Art. 30-A** — investigacao de arrecadacao/gastos; rito art. 22 LC 64 no que couber; prazo **15 dias da diplomacao**; pode negar/cassar diploma.
✅ Arts. **16-C / 16-D** FEFC — detalhe operacional em `contas-e-fefc-2026.md` + Res. 23.605+23.749.

### Propaganda e resposta
✅ **Art. 36-A** — o que **nao** e propaganda antecipada (grep).
✅ **Art. 39 §5o** — **boca de urna** (nao e CE 39/337).
✅ **Arts. 57-A a 57-J** — internet (bloco no anexo).
✅ **Art. 58** — direito de resposta; prazos 24/48/72h (e internet no §1o); recurso tipico **24h**; **nao** gera inelegibilidade.
✅ **Art. 38 §5o** (Lei 15.230) — folhetos majoritarios em Braille (proporcao por resolucao TSE).

### Captacao e condutas vedadas
✅ **Art. 41-A** — captacao ilicita de sufragio: multa + cassacao registro/diploma; rito art. 22 LC 64; ate a diplomacao; **≠ crime 299 CE**.
✅ **Arts. 73–78** — condutas vedadas a agentes publicos; multa §4o; cassacao §5o (e 74/75/77); ajuizamento ate diplomacao §12; rito art. 22. ADI 7178/7182 no art. 73 VII — so se no corpus de jurisprudencia/anexo.

### Representacoes
✅ **Art. 96** (e 96-A/96-B no que o anexo tiver): regime geral; prazos recursais **24h** quando o dispositivo assim fixar no periodo eleitoral (Res. 23.608+23.756). **Nao** e o rito de 41-A/73/30-A quando a lei manda art. 22 LC 64 (recurso em **3 dias** em varios pontos).

## Passo a passo / o que produzir
1. Identificar o instituto (registro / 41-A / 73 / 58 / 96 / 30-A / 105 / internet).
2. Grep + ler faixa no anexo.
3. Cruzar resolucao do ciclo (`resolucoes-tse-ciclo-2026`) se a peca citar Res.
4. Entregar quadro dispositivo · redacao vigente · prazo/dies a quo · skill de peca.

## Postura honesta
- Ajustes pos-5/marco (noticia 03/08/2026) = 🟡 sem ato formal.
- Nao misturar rito 96 (24h) com rito art. 22 (3 dias).
- Nao afirmar 08/09 FEFC vigente.

## Cross-link e fechamento
Registro → C2. Contencioso → C3. Propaganda → C4. Contas → C5. Penal paralelo 299 → `codigo-eleitoral-base` + C7. Gates: Suprema Corte + validador.
