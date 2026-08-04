---
name: substituicao-de-candidato
description: "Substituicao no registro/campanha: o que o corpus ancora (registro 15/08 19h, RDE, Res. 23.609+23.754) e o que e GAP (prazos/hipoteses de substituicao da Lei 9.504 nao capturados verbatim no anexo). Nao inventar prazo. Use quando disser substituicao de candidato, candidatura vaga, trocar o nome na chapa, renuncia apos registro."
---

> **Escolhas = botoes:** *antes do pedido de registro* · *apos o registro* · *apos a eleicao* · *so duvida de elegibilidade (RDE)*.

# SUBSTITUICAO-DE-CANDIDATO

> Camada C2. **Honestidade de corpus primeiro.** O anexo de destaques da Lei 9.504 **não** captura o regime completo de substituição (tipicamente art. 13 e correlatos) em faixa verbatim. **Proibido inventar prazo ou hipótese.**

## Anexos obrigatorios (context/)
- `context/lei-9504-destaques.md` — art. 11 (registro, §4o candidato se partido nao requerer); RDE §16 — **grep + ler**. Confirmar se ha faixa de substituicao; se nao houver, **GAP**.
- `context/resolucoes-tse-2026-mapa.md` — Res. **23.609/2019 + 23.754/2026** (CANDex, DRAP/RRC, RDE art. 9o-B) — **grep "substitui"**; se so UFIR/IA, **nao** e regime de candidato.
- `context/calendario-eleitoral-2026.md` — 15/08 19h e demais marcos — **grep + ler**.
- `context/contencioso-eleitoral-vias.md` — efeitos de indeferimento/cancelamento de registro — **grep + ler**.
- `context/metodologia-eleitoral.md` — gaps — **grep + ler**.

## O que o corpus SUSTENTA (use livremente)
1. **Pedido de registro:** Lei 9.504 art. 11 caput + Res. 23.609 art. 19 §2o (23.754): DRAP/RRC ate **19h de 15 de agosto**.
2. **Se o partido nao requer:** art. 11 §4o — candidato pode requerer em ate **48h** apos publicacao da lista (redacao no anexo).
3. **RDE (art. 11 §16 + Res. 23.609/2019 art. 9º-B, redação 23.754/2026):** dúvida razoável de capacidade eleitoral passiva **antes**; impugnação em **5 dias** — 🔴 *dies a quo* **não capturado** na faixa do art. 9º-B; sem registro até 15/08 → RDE extinto sem mérito (§11 da resolução, ressalva art. 29).
4. **Indeferimento/cancelamento de registro:** efeitos LC 64 art. 15 e vias AIRC — ver `airc-impugnacao-de-registro`. Isso **abre** a discussao pratica de nova indicacao, mas **nao** substitui o dispositivo de substituicao.
5. **Forma de citacao de resolucao:** sempre **base 2019 + alteracao 2026** (trava b).

## GAP DECLARADO (obrigatorio na peca/parecer)
| Tema | Status no corpus |
|---|---|
| Hipóteses legais de substituição (falecimento, renúncia, indeferimento, etc.) | **Não** capturadas verbatim em `lei-9504-destaques.md` — **não confirmado** no corpus |
| Prazos em dias/horas para substituir apos cada hipotese | **GAP** — nao cravar |
| Quotas / sexo / raca na substituicao | **GAP** se nao grepar texto no anexo |
| Dispositivo Res. 23.609 sobre substituicao alem do registro/RDE | **Conferir** compilado; se ausente no mapa, nao afirmar |

**Comportamento obrigatorio:**  
1. Declarar o GAP.  
2. Mandar o operador **abrir no Planalto** o art. de substituicao da Lei 9.504 e a faixa correspondente da Res. 23.609 **compilada com 23.754/2026**.  
3. So apos o operador colar/confirmar o texto, redigir a peca com dies a quo.  
4. **Nunca** completar com "prazo padrao de X dias" de memoria de treino.

## Lado dual (quando o texto for confirmado fora do gap)
- **Partido/federacao/coligacao:** requer substituicao e novo RRC/documentos art. 11 §1o.
- **Impugnante/terceiro:** atacar intempestividade, ilegitimidade da hipotese, vicio de documentacao ou fraude de substituicao — **so** com base no dispositivo confirmado.

## Metodologia
1. Fase: pre-15/08 · pos-registro · pos-eleicao.
2. Grep anexos por "substitui" / art. 13 / candidato.
3. Se **nao** houver faixa: emitir **parecer de gap** + checklist do que ja se pode fazer (RDE, registro no prazo, AIRC defesa, art. 11 §4o).
4. Se houver faixa (atualizacao futura do context): citar diploma+artigo+dies a quo e so entao redigir.
5. Fechar por `suprema-corte-eleitoral` + `validador-eleitoral`.

## Entrega obrigatoria final
(a) fase do ciclo; (b) o que o corpus **autoriza** agora; (c) **GAP** nomeado; (d) perguntas ao operador (hipotese fatica + texto legal confirmado); (e) proibicao explicita de prazo inventado; (f) handoff `rrc-drap-dce-registro` / `airc` se couber.

## Guard
Nunca inventar prazo de substituicao. Nunca citar CE art. 105 como base de instrucoes. Nunca 23.609 sem 23.754. Nunca tratar RDE como substituicao de candidato. Parecer parcial com gap **vale**; silencio sobre o gap **nao**. Fecha por `suprema-corte-eleitoral` + `validador-eleitoral`.
