---
name: triagem-eleitoral
description: "Classifica a demanda eleitoral e roteia para as skills certas. Pergunta CRITICA 1: voce move ou responde? Depois fixa fase do ciclo, via candidata (AIRC/AIJE/AIME/rep./RCED/contas/penal/recurso), cargo/circunscricao, documentos minimos e prazo em curso com dies a quo. Use quando o operador descrever situacao eleitoral sem caminho, ou disser triagem, qual o caminho, que peca eu uso, por onde comeco, recebi citacao, quero impugnar, /triagem-eleitoral."
---

> **Escolhas = botoes:** lista fechada (lado, fase, via, cargo, sim/nao) → **AskUserQuestion** (max. 4; se mais, divida).

# TRIAGEM-ELEITORAL

> Camada 0. Porta de classificacao, chamada pelo `eleitoral-master` no inicio de todo caso. Define **lado primeiro**, depois fase, via e prazo.

## Anexos obrigatorios (context/)
- `context/metodologia-eleitoral.md` — dual e protocolo — **grep + faixa**.
- `context/contencioso-eleitoral-vias.md` — mapa via x prazo x consequencia §0 — **grep + faixa**.
- `context/calendario-eleitoral-2026.md` — marcos Res. 23.760 — **grep + faixa**.
- `context/cf-14-elegibilidade.md` — condicao x inelegibilidade — **grep + faixa**.

## Objetivo
Em poucas perguntas devolver: **lado + fase + via + skill(s) alvo + prazo em curso (dies a quo)**, e handoff ao master.

## Quando ativar
Caso novo, "por onde comeco", "que peca", "vale entrar", ou master abre demanda sem classificacao.

## Pergunta 1 (CRITICA) — LADO
**Voce move (impugna/ajuiza/acusa) ou responde (contesta/defende)?**
- **Move** → trilha de ataque; checar legitimidade na skill da via (ex. LC 64 art. 3o na AIRC).
- **Responde** → trilha de defesa; em AIJE/AIME carregar **onus de quem move** como tese de 1a linha.
- **Ambos / parecer** → `parecer-eleitoral` + quadro de riscos dos dois polos.
- **Ambiguo** → botoes: Impugna · Defende · Parecer (ambos).

> Errar o lado destroi a peca: pedido de 8 anos na AIME pelo polo errado, ou defesa que "espelha" onus que nao tem.

## Pergunta 2 — FASE do ciclo
Botoes: Pre-registro · Registro (ate 15/08 19h em 2026) · Campanha · Pos-1o turno · Pos-2o turno · Pos-diplomacao.
Marcos ancora: `calendario-eleitoral-2026.md` (Res. 23.760) — registro **15/08 19h**; 1o turno **04/10**; 2o **25/10**.

## Pergunta 3 — VIA candidata (roteamento)
| Sinal do operador | Via | Skills alvo (lado) |
|---|---|---|
| Impugnar registro / inelegibilidade no registro | **AIRC** | `airc-impugnacao-de-registro` (move) · `defesa-em-inelegibilidade` (responde) · `condicoes-de-elegibilidade` |
| Abuso de poder / AIJE / 8 anos | **AIJE** | `aije-abuso-de-poder` (**ambos**; onus = move) |
| Mandato pos-diplomacao / 15 dias | **AIME** | `aime-impugnacao-de-mandato` (**ambos**; onus = move; sem 8 anos no CF §10) |
| Compra de voto / 41-A | **41-A** | `captacao-ilicita-41a` |
| Agente publico / conduta vedada | **73-78** | `condutas-vedadas-73-78` |
| Propaganda / resposta | **96 / 58** | `representacoes-lei-9504` · `direito-de-resposta-58` · C4 propaganda |
| Contas / gasto ilicito / 30-A | **contas / 30-A** | `contas-de-campanha` · `defesa-contas-desaprovadas` · `fefc-e-fundo-partidario` |
| Diploma ja expedido / RCED | **RCED** | `rced-contra-diploma` |
| Crime 299 / boca de urna / falsidade | **penal** | C7 (`corrupcao-eleitoral-299` · `boca-de-urna-e-propaganda-penal` · `defesa-penal-eleitoral`) |
| Recorrer / contrarrazoes | **recurso** | C8 conforme instancia |
| Partido / filiacao / fundo | **partidario** | C6 |
| Cruzamento multi-frente | **P4** | `protocolo-p4-eleitoral` |

## Pergunta 4 — Cargo e circunscricao
Presidente · Gov/Sen/Dep · Pref/Vereador. Define competencia (AIRC: LC 64 art. 2o p.u. — TSE/TRE/juiz).

## Pergunta 5 — Documentos minimos (nao inventar)
Lista o que falta: edital de registro · RRC/DRAP · autos · diploma · prestacao de contas · prova documental do abuso · certidoes. Campo vazio = **"a confirmar"**.

## Gestao obrigatoria
- Condicao x inelegibilidade: se a duvida e "pode registrar?", abrir `condicoes-de-elegibilidade` + `ficha-limpa-e-inelegibilidades` **antes** da peca.
- Prazo: sempre apontar `calendario-e-prazos-eleitorais` e dies a quo da via na tabela de `contencioso-eleitoral-vias.md`.
- Fundacao C1 sob demanda via master.

## Entrega obrigatoria final
3 a 5 linhas: **lado · fase · via · skill(s) · prazo (dispositivo + dies a quo) · docs faltantes** + handoff ao `eleitoral-master`.

## Guard
Nao redigir peca aqui — so classificar. Nao unificar AIRC/AIJE/AIME. Nao preencher GAP (prazo final AIJE generica; rito AIME) por analogia silenciosa — declarar. FEFC: nao cravar 08/09.
