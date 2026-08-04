---
name: base-penal-eleitoral
description: "Mapa do penal-eleitoral: CE arts. 289-354-A (tipos), 355-364 (rito), competencia (arts. 22/29/35), acao publica (355), papel do MP Eleitoral. Dual: orienta defesa do acusado e pecas de comunicacao/assistente quando cabivel. BLOQUEIA prescricacao inventada (GAP). Use quando disserem crime eleitoral, competencia penal, rito 355, denuncia em 10 dias, MP Eleitoral, mapa de tipos, prescricao eleitoral, base penal."
---

# BASE-PENAL-ELEITORAL

> Camada C7. Fundacao penal. **Nao** redige a peca final sozinha: entrega mapa, rito e limites para as skills de tipo e para `defesa-penal-eleitoral`.

## Anexos obrigatorios (context/)
- `context/codigo-eleitoral-crimes-e-processo.md` - crimes 289-354-A; processo 355-364; competencia; GAP de prescricacao - **grep + faixa**.
- `context/metodologia-eleitoral.md` - dual; 299 != 41-A; boca de urna = Lei 9.504 art. 39 par.5 (nao CE 39/337).
- `context/lei-9504-destaques.md` - art. 39 par.5 e art. 41-A (contraste civel-sancionatorio).
- `context/contas-e-fefc-2026.md` - ponte **Res. 23.607/2019 art. 82 (c/ 23.752/2026)** -> 354-A.

## Objetivo
Devolver: (1) se o fato e **crime eleitoral** do CE ou ilicito da Lei 9.504; (2) competencia; (3) marcos do rito 355-364; (4) o que **nao** se afirma (prescricao, cedula x urna).

## Lado
- **responde:** acusado - defesa, prazos do rito penal-eleitoral (**10 dias** tipicos != 3 dias do contencioso civel).
- **move:** comunicacao de crime (cidadao art. 356); assistente/querela **somente** se o regime do caso e o CPP subsidiario (art. 364) autorizar no ponto - **nao** inventar legitimidade do advogado do candidato como se fosse MP.
- Plugin **nao** redige peca do MP como "cliente"; MP e polo real (arts. 24/27/355).

## Mapa de tipos (CE) - selecao operacional
| Bloco | Arts. | Notas do corpus |
|---|---|---|
| Alistamento / titulo | 289-295 | 294 **revogado** (Lei 8.868/1994) |
| Sufragio / coacao | 296-304 | 299 = corrupcao eleitoral * |
| Mesa / cedula / voto | 307-318 | aplicabilidade a urna eletronica = **GAP** sem julgado |
| Partidos (fichas) | 319-321 | |
| Propaganda penal | 322-336 | 322/329/333 **revogados** onde marcado; 323 (fatos inveridicos + video, Lei 14.192); 324-326; 326-A; 326-B |
| Falsidades | 348-354 | publico/particular/ideologica/uso |
| Apropriacao de campanha | **354-A** | Lei 13.488/2017; ponte contas **Res. 23.607/2019 art. 82 (c/ 23.752/2026)** |

**Fora do CE mas crime eleitoral de campanha:**
- **Boca de urna / dia da eleicao:** **Lei 9.504 art. 39 par.5** (detencao 6m-1a ou PSC + multa) - **nao** CE art. 39 nem 337.
- **41-A Lei 9.504:** captacao ilicita - **ilicito eleitoral** (multa + cassacao registro/diploma), **nao** e o tipo penal 299.

## Competencia (CE)
- **Juiz eleitoral (zona)** - art. 35, II: crimes eleitorais e comuns conexos, ressalvada origem do TRE/TSE.
- **TRE** - art. 29, I, d: crimes de **juizes eleitorais**.
- **TSE** - art. 22, I, d: crimes de juizes do TSE e dos TREs.
- **MP:** PGE (art. 24) no TSE; PRE (art. 27) no TRE; acao **publica** (art. 355).

## Rito 355-364 - marcos (duracoes no corpus; *dies a quo* com GAP onde nao capturado)
| Art. | Marco | Prazo / efeito | Dies a quo |
|---|---|---|---|
| 355 | Acao publica | infracoes do CE | — |
| 356 | Comunicacao | qualquer cidadao ao juiz da zona; verbal -> termo -> MP | — |
| 357 | Denuncia do MP | **10 dias**; arquivamento com controle do PRE; eleitor pode provocar se juiz nao age de oficio em 10 dias | 🔴 **GAP** — corpus so resume "em 10 dias"; confira CE integral (marco do recebimento da comunicacao/autos) antes de selar |
| 358 | Rejeicao da denuncia | fato nao e crime; **punibilidade extinta por prescricacao ou outra causa**; ilegitimidade/falta de condicao | — |
| 359 | Recebida a denuncia | depoimento pessoal; citacao; notificacao do MP; reu/defensor: **10 dias** alegacoes escritas + rol de testemunhas | Do **recebimento da denuncia / citacao** (texto art. 359) — ainda assim, se a contagem operacional nao estiver nos autos, confira CE integral |
| 360 | Alegacoes finais | **5 dias** acusacao e defesa | 🔴 **GAP** — duracao no corpus; *dies* do despacho/intimacao **nao capturado** — confira CE integral |
| 361 | Sentenca | **10 dias** apos conclusos | Apos **conclusos** (texto) |
| 362 | Recurso condenacao/absolvicao | ao TRE em **10 dias** | 🔴 **GAP** — duracao no corpus; *dies* (publicacao/ciencia) **nao capturado** — confira CE integral |
| 363 | Execucao no TRE | baixa; vista ao MP | — |
| 364 | CPP | lei **subsidiaria/supletiva** no processo, julgamento, recursos e execucao dos crimes eleitorais e conexos | — |

**Armadilha de prazo:** o contencioso civel-eleitoral recursal costuma ser **3 dias**; o penal-eleitoral do CE acima e **10/5/10**. Nunca importar o 3 dias para a defesa criminal sem dispositivo.

## [STOP] PRESCRICAO = GAP DECLARADO (G8)
- Unica mencao lida: art. 358, II (rejeicao se punibilidade ja extinta "pela prescricacao ou outra causa").
- **Nao ha** tabela de prazos prescricionais nos arts. 289-364 abertos.
- Art. 364 manda CPP no **processo** - **nao** declara, no trecho lido, incidencia do CP art. 109 sobre prazos.
- **RECUSADO:** analogia automatica ao CP / "costume forense".
- Em peca: **bloquear** afirmacao de prazo prescricional; exigir fonte primaria (TSE/STF inteiro teor) ou decisao de produto com selo [Y].

## Outros GAPs que a base carrega
- Tipos de **cedula de papel** vs urna eletronica (G9).
- Sumula/tema penal nao aberto no corpus - nao inventar.

## Dual (protocolo de uso)
1. Classificar o fato no mapa (CE x 9.504 39 par.5 x 41-A civel).
2. Fixar competencia e se ha conexao com crime comum (art. 35 II / 364).
3. Se **responde:** ir a `defesa-penal-eleitoral` + skill do tipo (299 / boca / falsidades).
4. Se **move** (vitima/candidato): comunicacao 356 + diligencias; **nao** prometer que o advogado substitui o MP na acao publica.
5. Cruzar multi-via via `protocolo-p4-eleitoral` (mesmo fato: 299 + 41-A + AIJE + contas) **sem** fundir sancoes.

## Entrega obrigatoria final
Mapa do fato -> tipo(s) -> competencia -> fase do rito -> prazos com dies a quo -> gaps (prescricao/cedula) -> skill de destino. Fecha por `validador-eleitoral` + `suprema-corte-eleitoral` (R2 diploma nomeado; R3 prazo).

## Guard
- Boca de urna != CE 39/337.
- 299 != 41-A.
- Sem prazo de prescricacao inventado.
- CE art. 105 **revogado** (Lei 14.211/2021) - irrelevante ao penal; se citar "5 de marco", e **Lei 9.504 art. 105**.
- Cross-link: `corrupcao-eleitoral-299` - `boca-de-urna-e-propaganda-penal` - `falsidades-e-apropriacao-campanha` - `defesa-penal-eleitoral` - `codigo-eleitoral-base`.
