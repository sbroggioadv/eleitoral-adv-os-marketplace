---
name: resolucoes-tse-ciclo-2026
description: "Mapa base→alteracao 2026 das resolucoes TSE (registro 23.609+23.754, propaganda 23.610+23.755, contas 23.607+23.752, FEFC 23.605+23.749, pesquisas 23.600+23.747, representacoes 23.608+23.756, ilicitos 23.735+23.757, calendario 23.760). Forma de citacao canonica e trava Lei 9.504/1997 art. 105 e §3o (CE 105 revogado). Use antes de citar qualquer resolucao do ciclo, ou quando disserem resolucao de registro, 23.609, calendario 2026, FEFC, prestacao de contas TSE."
---

# RESOLUCOES-TSE-CICLO-2026 — Mapa base + alteracao

> Camada 1. O TSE **nao reedita do zero**: mantem bases e **altera** em 2026. Esta skill fixa a **forma de citacao** e o mapa minimo.

## Quando ativa / trilha
Sempre que a peca citar Res.-TSE de registro, propaganda, contas, FEFC, pesquisas, representacoes, ilicitos ou calendario. Master no passo fundacao; validador e Suprema Corte cobram o mesmo mapa.

## Anexos obrigatorios (context/)
- `context/resolucoes-tse-2026-mapa.md` — tabela-mestra §2.1 + trechos — **grep + faixa**.
- `context/calendario-eleitoral-2026.md` — so 23.760 — **grep + faixa**.
- `context/contas-e-fefc-2026.md` — 23.752 / 23.749 / FEFC — **grep + faixa**.
- `context/metodologia-eleitoral.md` trava (b)(c) — **grep + faixa**.

## Trava (a) no preambulo das resolucoes
Fundamento de instrucoes = **Lei 9.504/1997, art. 105** (preambulos 2026 citam esse artigo). CE art. 105 esta **revogado**.

## Tabela-mestra (forma canonica)

| Tema | Base | Alteracao 2026 | Citar como |
|---|---|---|---|
| Calendario | — | **23.760/2026** | **somente** 23.760/2026 |
| Registro | 23.609/2019 | **23.754/2026** | 23.609/2019 + 23.754/2026 |
| Propaganda / internet / IA | 23.610/2019 (+ 23.732/2024) | **23.755/2026** | 23.610 + 23.732 + 23.755 |
| Contas de campanha | 23.607/2019 | **23.752/2026** | 23.607/2019 + 23.752/2026 |
| FEFC | 23.605/2019 | **23.749/2026** | 23.605/2019 + 23.749/2026 |
| Pesquisas | 23.600/2019 | **23.747/2026** | 23.600/2019 + 23.747/2026 |
| Representacoes / resposta | 23.608/2019 | **23.756/2026** | 23.608/2019 + 23.756/2026 |
| Ilicitos | 23.735/2024 | **23.757/2026** | 23.735/2024 + 23.757/2026 |

**Exemplo de peca:** *Resolucao-TSE n. 23.609/2019, com as alteracoes da Resolucao-TSE n. 23.754/2026*.

⛔ **Proibido:** "conforme a Res. 23.609/2019" como se bastasse para o pleito 2026.

## Marcos e trechos operacionais (so apos grep)

### Calendario — 23.760
- Registro candidatura: ate **15/08/2026, 19h**.
- Data-limite instruções (**Lei 9.504/1997, art. 105 e §3º**): **5 de março** (CE art. 105 = **revogado** Lei 14.211/2021).
- 1o turno **04/10**; 2o **25/10** (marcos na tabela do anexo).
- FEFC cotas no calendario: **30/08/2026** ✅.
- Parcial de contas: movimento ate **08/09**; envio ate **13/09**.

### Registro — 23.754 sobre 23.609
- **RDE** art. 9o-B (LC 219/2025).
- **Art. 52** (red. 23.754): afericao elegibilidade/inelegibilidade = **LC 64 art. 26-D**.
- Idade: art. 9o §2o com **Lei 15.230/2025**.
- Impugnacao: arts. 40/44 (5 dias do edital; noticia de inelegibilidade) — grepar vias + mapa.
- Mural de intimacoes: periodo atualizado na 23.754 (20/07 a 19/12 no corpus de vias).

### Contas / FEFC — 23.752 e 23.749
- Cotas FEFC mulheres/negros/indigenas: art. 17 §§ (red. 23.752) — **30 de agosto** no texto lido.
- 🟡 Noticia 03/08/2026 (mudanca para 08/09 + transferencias 2o turno): **ato formal nao localizado** — peca usa 30/08 ✅; noticia so com selo 🟡.
- FEFC exclusivo nas campanhas das cotas (art. 6o §7o red. 23.749) — grepar.
- Desfechos contas (aprovacao/ressalvas/desaprovacao/nao prestacao): `contas-e-fefc-2026.md`; art. 80 quitacao = **nao prestacao**.

### Representacoes — 23.756
- Representacoes especiais (30-A, 41-A, 73 etc.) e rito art. 22 LC 64: grepar arts. 44/7o no mapa.
- Prazos art. 96 / resposta: continuos e peremptorios no periodo (texto art. 7o no mapa).

## Passo a passo / o que produzir
1. Tema da citacao → linha da tabela-mestra.
2. Grep o artigo na resolucao-alteradora / base no anexo.
3. Entregar forma canonica + faixa + selo ✅/🟡.
4. Se a noticia de ago/2026 afetar o ponto: **nao** cravar; marcar 🟡.

## Postura honesta / GAPS
- Texto consolidado HTML "tudo embutido" nao varrido artigo a artigo — preferir alteradora 2026 lida ✅.
- Numero do calendario 2022/2024 "substituido" pela 23.760: **GAP** de mapeamento 1:1 — citar so 23.760.
- Portaria 449/2026 (limites gastos): 🟡 valores se inteiro teor parcial no corpus.

## Cross-link e fechamento
Registro → C2. Propaganda → C4. Contas/FEFC → C5. Representacoes → C3. Calendario transversal → `calendario-e-prazos-eleitorais`. Gates obrigatorios.
