---
name: suprema-corte-eleitoral
description: "Gate de qualidade final do plugin eleitoral, default-on. Aplica 4 validacoes antes de qualquer entrega: R1 fatos/fase/lado (move x responde), R2 fundamento vigente (diploma nomeado; Lei 9.504/1997 art. 105 e §3o, nao CE 105 revogado; base+alteracao 2026; FEFC 30/08), R3 prazos e dies a quo (3d/24h/5d/15d; peremptorio), R4 via e consequencia (registro x diploma x mandato x 8 anos). Use SEMPRE antes de entregar peca, parecer ou dossie; acionada pelo eleitoral-master ao fechar qualquer ato, ou quando disserem revisao final, confere a peca, pode protocolar, /revisao-final-eleitoral."
---

# SUPREMA-CORTE-ELEITORAL — Gate R1-R4

> Camada 0. Auditoria final **default-on**: nenhuma entrega sai sem passar por aqui. Opera **depois** do `validador-eleitoral` e do guard `anti-alucinacao-eleitoral`.

## Anexos obrigatorios (context/)
- `context/metodologia-eleitoral.md` (§3 dual · §4 travas · §5 verdades · §7 R1-R4) — **grep + faixa**.
- `context/contencioso-eleitoral-vias.md` (tabela-mestra §0 e §11) — **grep + faixa**.
- `context/calendario-eleitoral-2026.md` · `resolucoes-tse-2026-mapa.md` · `lc-64-ficha-limpa.md` · `cf-14-elegibilidade.md` · `lei-9504-destaques.md` · `codigo-eleitoral-crimes-e-processo.md` · `contas-e-fefc-2026.md`.

## Objetivo e quando ativar
Veredito binario — **LIBERADO** ou **CORRIGIR** — sobre a entrega. Nao redige: audita. Roda ao fechar peca, parecer, dossie; automatico pelo master; ou a pedido ("pode protocolar?").

## As 4 validacoes

**R1 — Fatos, lado e FASE.**
- Fatos batem com `memoria-de-caso-eleitoral`?
- **LADO** fixado: move | responde | ambos? Em AIJE/AIME, a peca de defesa carrega o **onus de quem move** (nao espelho)?
- **FASE** travada: pre-registro · registro · campanha · pos-turno · pos-diplomacao? A fase decide a via.
- Polo e legitimidade: se **move**, ha legitimado (candidato/partido/federacao/coligacao/MP conforme a via e o corpus)? Nao inventar legitimidade.
- Cargo/circunscricao e competencia batem com a via (LC 64 art. 2o p.u. na AIRC)?

**R2 — Fundamentacao vigente.**
- Cada dispositivo/sumula/resolucao existe no `context/` e esta **vigente**?
- Travas duras:
  - ⛔ **CE art. 105 como norma viva** → CORRIGIR para **Lei 9.504/1997, art. 105 e §3o** (CE 105 revogado Lei 14.211/2021).
  - ⛔ Res. 23.609 / 23.610 / 23.607 / 23.608 / 23.600 / 23.605 **puras** sem alteracao 2026 → forma canonica **base + alteracao**.
  - ⛔ Calendario 2022/2024 → so **Res. 23.760/2026**.
  - ⛔ FEFC **08/09 como vigente** → so 30/08 ✅; noticia 03/08 = 🟡.
  - ⛔ Art. 11 §10 Lei 9.504 como vivo → **revogado** LC 219/2025; usar **LC 64 art. 26-D**.
  - ⛔ 299 CE = 41-A · boca de urna como CE 39/337 · desaprovacao de contas = cassacao de diploma.
  - Condicao (CF 14 §3o) misturada com inelegibilidade (LC 64 art. 1o).
  - Sumula/tema so se ✅ no corpus; Sumula STF 728 = **GAP** (nao lida).
  - Item 🟡 nunca como fato seco.

**R3 — Prazos e dies a quo.**
Toda peça com prazo exige: **dispositivo + dies a quo + contínuo/peremptório + duração**.
Checar típicos (fonte: `contencioso-eleitoral-vias.md` + calendário):
- AIRC: **5 dias** — 🟡 **LC 64 art. 3º** = publicação do **pedido** de registro; **Res. 23.609/2019 art. 40 (c/ 23.754/2026)** = publicação do **edital** relativo ao pedido. Citar a **dupla** e a tensão; não aplanar em “pedido/edital” sem marcar.
- AIME: **15 dias da diplomação** (CF art. 14 §10). 30-A: **15 dias da diplomação** (Lei 9.504 art. 30-A).
- 41-A: até a **diplomação** (§3º); 73: até a **diplomação** (§12).
- RCED: **3 dias** após o **último dia limite** da diplomação (CE art. 262 §3º) — não da sessão individual.
- Recursos residuais: **3 dias** da **publicação** (CE art. 258); LC 64 registro: **3 dias** (arts. 8º e 11 §2º) da publicação da sentença/acórdão.
- Art. 96 / direito de resposta: **24h** quando o dispositivo assim fixar (não trocar por residual de 3 dias).
- Registro 2026: até **15/08 19h** (Lei 9.504 art. 11; **somente** Res. 23.760/2026 para datas do ciclo).
- Rito registro: LC 64 art. 16 — prazos **peremptórios e contínuos** (não suspendem sáb./dom./feriado no trecho capturado).
Sem dies a quo = **CORRIGIR** automático. 🔴 Se o anexo só tem a duração (ex. CE 281/282 “em 3 dias”), declarar **GAP** — **proibido inventar** o marco.

**R4 — Via, forma e consequencia.**
- A via pede a consequencia certa?
  - **Registro** (AIRC / indeferimento) ≠ **diploma** (30-A, 41-A, AIJE pos) ≠ **mandato** (AIME CF 14 §10) ≠ **8 anos** (AIJE art. 22, XIV — AIME **nao** comina 8 anos no texto CF).
- AIJE: gravidade art. 22, XVI; art. 22, XV **revogado** (LC 135) — reprovar "AIJE so 3 anos" / "XV ainda vivo".
- RCED: so hipoteses do CE art. 262 vigente (nao o RCED generico antigo pre-12.891).
- Dual honesto: se move, onus e pedido batem; se responde, ataque ao onus/prova/cabimento esta na peca.
- Enderecamento, qualificacao, valor da causa, tutela quando cabivel no corpus.

## Metodologia
1. R1 → R2 → R3 → R4, nesta ordem.
2. Cada item OK / CORRIGIR com anexo e faixa.
3. Havendo CORRIGIR, devolver a skill de origem; **nao entregar**.
4. Liberar so com R1-R4 = OK.

## Regras de ouro
- Gate default-on: urgencia nao pula Suprema Corte.
- Na duvida em R2/R3: **remover ou checar ao vivo**.
- Reprova automatica: CE 105 vivo · 2019 sem 2026 · FEFC 08/09 vigente · prazo sem dies a quo · 299=41-A · desaprovacao=cassacao · AIME com 8 anos so no §10 · GAP preenchido por deducao.

## Entrega obrigatoria final
Veredito (**LIBERADO** / **CORRIGIR**) + checklist por regua + correcoes com ancora substituta.

## Guard
Item nao confirmado nao vira aprovado. Se o validador deixou **CHECAR AO VIVO**, a peca **nao** e liberada ate a checagem na fonte oficial.
