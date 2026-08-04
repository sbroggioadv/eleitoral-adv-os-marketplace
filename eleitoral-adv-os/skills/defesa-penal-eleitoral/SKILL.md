---
name: defesa-penal-eleitoral
description: "Defesa (e move residual) no rito penal-eleitoral CE arts. 355-364: comunicacao, denuncia em 10 dias, rejeicao 358, alegacoes escritas 10 dias, finais 5 dias, sentenca 10 dias, recurso ao TRE 10 dias, CPP subsidiario (364). Dual foco responde; prazos != 3 dias civeis. Bloqueia prescricacao inventada. Use quando disserem defesa criminal eleitoral, contestar denuncia, prazo de 10 dias, recurso penal TRE, art. 359, fui citado em crime eleitoral."
---

# DEFESA-PENAL-ELEITORAL

> Camada C7. Rito e peca de **defesa** (foco) e de **ataque residual** (comunicacao/assistente quando o corpus permite). Os tipos vivem nas skills irmas.

## Anexos obrigatorios (context/)
- `context/codigo-eleitoral-crimes-e-processo.md` - arts. 355-364; competencia; GAP prescricacao par.2.4.
- `context/metodologia-eleitoral.md` - dual; prazos peremptorios; 299!=41-A.
- Skills de tipo: `corrupcao-eleitoral-299` - `boca-de-urna-e-propaganda-penal` - `falsidades-e-apropriacao-campanha` - `base-penal-eleitoral`.

## Objetivo
Controlar **fase, prazo com dies a quo e tese processuais** do penal-eleitoral, sem importar o relogio de 3 dias do contencioso civel.

## Lado
| Lado | Atuacao nesta skill |
|---|---|
| **responde** (default) | defesa do acusado: rejeicao, alegacoes, instrucao, finais, recurso |
| **move** | comunicacao art. 356; provocacao se inercia (357); assistente **so** se cabivel via CPP art. 364 - sem usurpar o MP |
| **ambos** | parecer de risco e multi-via (P4) |

Ambiguo -> botoes: *defesa criminal* - *comunicar fato ao juizo/MP* - *parecer multi-via* - *so civel (41-A/propaganda)*.

## Linha do tempo do rito (CE) — durações no corpus; dies a quo com GAP
1. **Notícia** (356): cidadão comunica ao juiz da zona; se verbal, reduz a termo e remete ao MP.
2. **Denúncia** (357): MP oferece em **10 dias**. 🔴 O *dies a quo* **não está** na faixa capturada (só a duração) — confira o CE integral e o termo nos autos; **proibido** inventar "recebimento/remessa/prática do juízo".
3. **Controle de arquivamento** (357): PRE; eleitor pode representar se juiz não age de ofício em **10 dias** (mesmo GAP de marco se a peça precisar selar).
4. **Rejeição** (358): (I) fato não é crime; (II) punibilidade extinta por **prescrição** ou outra causa; (III) ilegitimidade/falta de condição.
5. **Recebimento** (359): juiz designa depoimento pessoal; cita réu; notifica MP.
6. **Alegações escritas + rol** (359 p.u.): réu ou defensor em **10 dias**. 🔴 *Dies a quo* **não nominado** na faixa capturada — fechar só com o CE integral ou o marco dos autos; **não** imputar "citação/juntada" sem fonte.
7. **Alegações finais** (360): **5 dias** para acusação e defesa. 🔴 *Dies a quo* **não está** na faixa — conferir CE integral / autos.
8. **Sentença** (361): **10 dias** após conclusos (marco de conclusos no texto).
9. **Recurso** de condenação/absolvição (362): ao **TRE** em **10 dias**. 🔴 *Dies a quo* **não está** na faixa capturada — conferir CE integral / publicação nos autos.
10. **Execução** no TRE (363); **CPP** subsidiário (364) para processo, julgamento, recursos e execução.

### Tabela anti-confusao de prazos
| Ambiente | Prazo tipico no corpus | Nao misturar com |
|---|---|---|
| Penal-eleitoral (355-364) | **10 / 5 / 10** dias | |
| Recursos civeis-eleitorais / LC 64 residual | muitas vias em **3 dias** | defesa criminal |
| Representacoes art. 96 / resposta art. 58 | **24h** | penal |
| 41-A recurso | **3 dias** do DO | art. 362 CE |

## Dual - conteudo da peca

### RESPONDE (defesa)
**Processual (primeira linha):**
1. Incompetencia (art. 35 II / 29 / 22) se o foro e de tribunal.
2. Rejeicao 358 I - atipicidade (remeter a skill do tipo).
3. Rejeicao 358 II - **so** se prescricacao/outra causa de extincao estiver **provada** em fonte primaria; senao **GAP**, nao inventar prazo.
4. Rejeicao 358 III - ilegitimidade/falta de condicao da acao.
5. Nulidades de citacao/intimacao; cerceamento; prova ilicita (via CPP 364 - citar dispositivo do CPP **so** apos abrir a fonte; se nao abriu, declarar).
6. Absolucao: insuficiencia de prova; duvida; desclassificacao para tipo diverso **com** diploma.

**Merito por familia de tipo:**
- 299 -> `corrupcao-eleitoral-299` (e contraste 41-A).
- Boca/propaganda -> `boca-de-urna-e-propaganda-penal`.
- 348-354-A -> `falsidades-e-apropriacao-campanha`.

**Onus:** na acao publica, a acusacao prova o fato tipico. Defesa **nao** e espelho do ataque: prioriza falhas de prova, tipicidade e rito.

### MOVE (residual)
1. Comunicacao fundamentada (356) com documentos.
2. Acompanhar prazo de 10 dias do MP (357); provocar se inercia do juiz.
3. Assistente: somente se o regime subsidiario do CPP no caso concreto autorizar - **confirmar na fonte**; plugin nao inventa legitimidade.
4. Estrategia multi-via: abrir 41-A / representacao / AIJE **em autos proprios** com onus e sancao corretos (P4).

## O que esta skill RECUSA
1. Afirmar prazo prescricional por analogia ao CP (G8).
2. Aplicar prazo de **3 dias** do contencioso civel a alegacoes/recurso criminal do CE.
3. Redigir denuncia em nome do MP como se cliente.
4. Fundir cassacao de diploma (41-A/30-A/AIJE) com pena criminal no mesmo pedido sem vias separadas.

## Entrega obrigatoria final
(1) lado; (2) fase do rito 355-364; (3) **proximo prazo** com dispositivo + dies a quo nos autos; (4) teses processuais e de merito (skill de tipo); (5) multi-via se houver; (6) gaps. Fecha por `suprema-corte-eleitoral` (R3 prazos) + `validador-eleitoral`.

## Guard
- 10 dias penais != 3 dias civeis.
- Sem prescricacao inventada.
- Sem CE art. 105 vivo.
- Cross-link: `base-penal-eleitoral` - skills de tipo C7 - `protocolo-p4-eleitoral` - `recurso-ao-tre` (recurso criminal tem base no 362; nao substituir pelo REspe civel sem cabimento).
