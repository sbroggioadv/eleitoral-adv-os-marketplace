---
name: rrc-drap-dce-registro
description: "Monta e audita o pedido de registro (DRAP/RRC/DCE), RDE (Lei 9.504 art. 11 §16), idade minima (art. 11 §2o Lei 15.230) e o prazo peremptorio 15/08 19h. Cite sempre Res. 23.609/2019 + 23.754/2026. Use quando o operador disser registro de candidatura, DRAP, RRC, DCE, RDE, CANDex, pedido de registro, 15 de agosto, idade minima, quero registrar o candidato, /rrc."
---

> **Escolhas = botoes:** lista fechada (lado, cargo, fase) via **AskUserQuestion** (max. 4).

# RRC-DRAP-DCE-REGISTRO

> Camada C2. Operacao do **pedido de registro** e auditoria de documentos. Nao redige AIRC (ver `airc-impugnacao-de-registro`).

## Anexos obrigatorios (context/)
- `context/lei-9504-destaques.md` — art. 11 (caput, §§1o-2o, §4o, §16 RDE); **§10 REVOGADO** pela LC 219/2025 — **grep + ler a faixa**.
- `context/resolucoes-tse-2026-mapa.md` — trava base+alteracao; CANDex art. 8o-A; prazo art. 19 §2o; RDE art. 9o-B (redacao 23.754) — **grep + ler**.
- `context/calendario-eleitoral-2026.md` — marco 15/08 19h (Res. 23.760) — **grep + ler**.
- `context/lc-64-ficha-limpa.md` — art. 26-D (afericao no registro + superveniente favoravel ate diplomacao); art. 16 prazos — **grep + ler**.
- `context/cf-14-elegibilidade.md` — CF art. 14 §3o condicoes — **grep + ler**.
- `context/metodologia-eleitoral.md` — dual + travas — **grep + ler**.

## Objetivo
Entregar checklist de **registro vivo** (docs, idade, filiacao, quitacao, RDE opcional) com **dies a quo** e sem citar norma morta.

## Lado (sempre primeiro)
- **partido/federacao/coligacao** (apresenta DRAP/RRC) x **candidato** (autoriza; §4o se o partido nao requerer).
- Botoes: *montando pedido* · *auditando pedido ja protocolado* · *RDE pre-registro*.

## Marco de prazo (trava c)
1. **Lei 9.504/1997, art. 11, caput** (redacao Lei 13.165/2015): registro ate as **19h do dia 15 de agosto** do ano da eleicao.
2. **Res.-TSE 23.609/2019, art. 19, §2o** (redacao **23.754/2026**): DRAP e RRC por internet ate **19h de 15 de agosto**, com recibo do horario.
3. **Res. 23.760/2026** no calendario: mesmo marco — so cite **23.760** para datas do ciclo.
4. **Dies a quo de contagem de prazos do rito de registro:** apos o fim do prazo de registro, LC 64 **art. 16** — prazos **peremptorios e continuos**; **nao** suspendem sabado/domingo/feriado.
5. **RDE (art. 11 §16 Lei 9.504 + Res. 23.609/2019 art. 9º-B, redação 23.754/2026):** pré-candidato ou partido com dúvida razoável sobre capacidade eleitoral passiva; impugnação em **5 (cinco) dias** por partido/federação com órgão na circunscrição. 🔴 O *dies a quo* dos 5 dias **não está** na faixa capturada do art. 9º-B — confira o texto integral da resolução compilada antes de protocolar. **§11 da resolução:** sem registro até 15/08, RDE **extinto sem resolução de mérito** (CPC 485 IV) — ressalva art. 29 *caput* (conferir no anexo).

## Idade minima (nao usar regra antiga)
**Lei 9.504 art. 11, §2o (Lei 15.230/2025)** — tres marcos:
- **I** data da **posse** — cargos do **Executivo**;
- **II** data-limite do **pedido de registro** — **Camaras Municipais** (vereador);
- **III** **posse presumida** (ate 90 dias da eleicao da Mesa) — demais Casas Legislativas.
Idades em **CF art. 14, §3o, VI** (`cf-14-elegibilidade.md`). Nunca devolver so "data da posse" para todos os cargos.

## Documentos do pedido (art. 11 §1o — checklist, nao inventar)
Ata da convencao (art. 8o) · autorizacao escrita · prova de filiacao · declaracao de bens · titulo/certidao de eleitor na circumscricao · quitacao eleitoral · certidoes criminais (JE/Federal/Estadual) · fotografia · propostas (Prefeito/Governador/Presidente — inciso IX).
**CANDex obrigatorio** (Res. 23.609 art. 8o-A via 23.754): ata, lista e pedido via internet nos sitios dos tribunais.
§3º: juiz pode abrir prazo de **72 horas** para diligências (Lei 9.504 art. 11 §3º) — contagem a partir da **abertura** do prazo pelo juiz; se a contagem fina (ciência × despacho) importar, confira o compilado. §4º: se partido não requerer, candidato pode em até **48h** após publicação da lista (redação no anexo).

## Afericao no registro (2026)
- **Vivo:** LC 64 **art. 26-D** — condicoes e causas aferidas na formalizacao do registro; superveniente que **afaste/extinga** inelegibilidade ate a **diplomacao**.
- **Morto:** Lei 9.504 art. 11 **§10** — **revogado** pela LC 219/2025 art. 4o. **Proibido** citar como vigente.
- ⚠️ **PENDENTE** — **LC 64 art. 26-D** × **Súmula-TSE 70**: a súmula ainda cita o §10 revogado e marco “antes do dia da eleição” — **declarar a tensão**, não apagar a súmula nem fingir que o §10 vive (`lc-64-ficha-limpa.md`).

## Metodologia
1. Fixar **cargo + circumscricao + polo** (partido x candidato).
2. Conferir **calendario 23.760** e se o protocolo ainda cabe ate 15/08 19h.
3. Grep art. 11 + Res. 23.609+23.754 no context; montar checklist de docs.
4. Idade: aplicar inciso I/II/III do §2o conforme o cargo.
5. Se dúvida de elegibilidade: oferecer **RDE** com impugnação em 5 dias (**GAP** de *dies a quo* até conferir o texto) e risco de extinção sem registro.
6. Cruzar condicoes (`condicoes-de-elegibilidade`) e desincomp (`desincompatibilizacao`) e Ficha Limpa (`ficha-limpa-e-inelegibilidades` / `defesa-em-inelegibilidade`).
7. Fechar por `suprema-corte-eleitoral` + `validador-eleitoral`.

## Entrega obrigatoria final
(a) polo e cargo; (b) **dies a quo** e se o 15/08 19h ainda esta vivo; (c) checklist de docs art. 11 §1o com faltas; (d) idade com inciso do §2o; (e) RDE sim/nao e risco de extincao; (f) gaps (doc ausente no corpus = nao afirmar); (g) handoff AIRC se ja houver edital/impugnacao.

## Guard
Nunca citar **CE art. 105** como norma viva do "5 de marco" — e **Lei 9.504 art. 105**. Nunca citar **art. 11 §10** como vigente. Nunca citar Res. **23.609 pura** sem **23.754/2026**. Nunca inventar prazo de substituicao aqui (ver `substituicao-de-candidato`). Nunca misturar **condicao** (CF 14 §3o) com **inelegibilidade** (LC 64 art. 1o). Fecha por `suprema-corte-eleitoral` + `validador-eleitoral`.
