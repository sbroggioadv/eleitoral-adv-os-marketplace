---
name: memoria-de-caso-eleitoral
description: "Mantem o estado append-only de um caso eleitoral — polo e lado (move/responde), cargo, circunscricao, fase do ciclo, via, n. de autos, datas (registro, edital, diplomacao), prazos correndo com dies a quo, provas, selos ✅/🟡 e proximo passo. Use quando o operador retomar um caso, perguntar onde paramos, status, cronologia ou prazos, ou quando o eleitoral-master carregar e atualizar o estado. Tambem ao iniciar caso novo."
---

# MEMORIA-DE-CASO-ELEITORAL

> Camada 0. Registro **append-only** do caso. O `eleitoral-master` le no inicio e atualiza no fim de cada ato. Estado e fato, nao opiniao.

## Anexos obrigatorios (context/)
- `context/metodologia-eleitoral.md` — fluxo e o que cada etapa exige de estado — **grep + faixa**.
- `context/calendario-eleitoral-2026.md` · `contencioso-eleitoral-vias.md` — marcos e dies a quo — **grep + faixa**.
- Prazos de registro: LC 64 art. 16 em `lc-64-ficha-limpa.md` / vias — **grep + faixa**.

## Objetivo
Nunca perder o fio: quem move/responde, qual a via, quais datas criticas e **qual o proximo prazo fatal**.

## Quando ativar
Retomar caso, "onde paramos", "status", "prazos"; master carrega/atualiza; caso novo.

## Onde grava
`eleitoral/casos/<slug-do-caso>.md` no diretorio de trabalho. **Append-only:** cada ato = nova linha no historico; nunca apagar o anterior.

## Estrutura do arquivo de caso
```markdown
# Caso: <titulo>
## Polo e lado
- Cliente: <nome/partido/federacao> | lado: <move / responde / ambos-parecer>
- Contraparte: <...> | qualificacao: <candidato / partido / MP / coligacao>
- Legitimidade para a via: <ok / a confirmar / nao legitimado> | base: <ex. LC 64 art. 3o>
## Cargo e circunscricao
- Cargo: <Pres / Gov / Sen / Dep / Pref / Ver> | UF/municipio: <...>
- Competencia (via): <JE / TRE / TSE> | base: <...>
## Fase e via
- Fase: <pre-registro / registro / campanha / pos-turno / pos-diplomacao>
- Via principal: <AIRC / AIJE / AIME / 30-A / 41-A / 73 / 96 / 58 / RCED / contas / penal / recurso>
- Vias paralelas (P4): <lista>
## Datas-marco
- Pedido de registro / edital: <data> | limite registro 2026: 15/08 19h (Res. 23.760)
- Convencao / campanha: <...>
- 1o turno / 2o turno: <04/10 / 25/10 se 2026>
- Diplomacao (ultimo dia limite): <data>
## Processos
- <n. autos> | <classe> | <orgao> | <polo> | <fase> | <ultima mov.>
## Provas e documentos
- <doc> | status: <lido / faltante / a confirmar> | selo: <✅/🟡>
## Prazos (fatais primeiro)
- <data fatal> | <ato> | <dispositivo> | dies a quo: <marco> | <continuo/peremptorio> | <3d/5d/15d/24h>
## Onus e assimetria
- Via com onus assimetrico? <AIJE/AIME sim / nao> | quem prova o abuso: <quem move>
## Historico (append-only)
- <data> | <ato> | <skill> | <resultado>
## Proximo passo
- <acao> ate <data> | dies a quo: <...>
```

## Metodologia
1. Ao abrir: preencher polo/lado, cargo, fase, via, datas e prazos conhecidos. Sem dado = **"a confirmar"** — nunca estimar.
2. A cada ato: acrescentar linha no historico; atualizar Prazos e Proximo passo.
3. Nunca sobrescrever historico.
4. Devolver ao master resumo de 3 a 5 linhas + proximo prazo fatal.

## Regras de ouro
- **Quatro campos que decidem o caso:** lado (move/responde), fase, **dies a quo** do prazo fatal, e se a via e AIJE/AIME (onus de quem move).
- Datas e numeros **exatos da fonte** (edital, autos, diploma, prestacao de contas).
- FEFC / contas: marcar 30/08 ✅ vs noticia 08/09 🟡 se o caso tocar cotas.
- Registro 2026: **15/08 19h** e peremptorio — registrar se o pedido foi a tempo.

## Entrega obrigatoria final
Arquivo criado/atualizado + resumo (lado, via, proximo prazo fatal, docs faltantes).

## Guard
Nao inventar n. de processo, data de edital ou diplomacao. Sem marco inicial documentado, o prazo fica "a confirmar" e a peca nao sela (trava c).
