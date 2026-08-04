---
name: eleitoral-onboarding
description: "Wizard de configuracao do plugin eleitoral ao perfil do escritorio. Cria pasta eleitoral/ com identidade (nome, OAB, escritorio, cidade, e-mail), trilha preferencial (contencioso dual, registro, contas, penal, partidario), UF de atuacao, tom das pecas e modo de fluxo. NAO trava o lado do caso — o lado (move/responde) e fixado a cada pedido. Use quando o operador disser configurar eleitoral, instalar, primeira vez, comecar, onboarding eleitoral, /start-eleitoral."
---

> **Escolhas = botoes:** em campos de **lista fechada** (trilha, UF, tom, modo, atualizar/recriar, sim/nao) use **AskUserQuestion** (max. 4 por pergunta; se mais, divida). **Texto livre** (nome, OAB, escritorio, cidade, e-mail) como pergunta digitada.

# ELEITORAL-ONBOARDING

> Camada 0. Wizard inicial. Configura o plugin ao escritorio. Explica o dual e as 3 travas em linguagem simples. **Nao** fixa o lado do caso: lado e por pedido.

## Anexos obrigatorios (context/)
- `context/metodologia-eleitoral.md` — dual, travas, mapa de camadas — **grep + faixa**.
- `context/calendario-eleitoral-2026.md` — marcos 2026 (registro 15/08 19h) — **grep + faixa**.

## Objetivo
Configurar identidade e preferencias; deixar claro o que o plugin cobre e o que **nao** inventa.

## Quando ativar
`/start-eleitoral`, "configurar eleitoral", "primeira vez", "onboarding". Cria ou atualiza `eleitoral/perfil.md` no diretorio de trabalho.

## Regras do wizard
Uma pergunta por vez, acolhedor. Lista fechada = botoes. Ao fim, gravar e confirmar.

## Blocos de pergunta
1. **Identidade (texto livre):** nome, OAB (numero/UF), escritorio, cidade, e-mail.
2. **Trilha preferencial (botoes) — NAO e trava de lado:** Contencioso dual (AIRC/AIJE/AIME/rep.) · Registro e inelegibilidades · Contas e FEFC · Penal eleitoral · Partidario · Todas / conforme o caso.
3. **UF principal (botoes, 2 rodadas):** regiao → UFs. Importa para TRE e pratica local; a lei federal e a mesma.
4. **Tom das pecas (botoes):** Tecnico-formal · Direto e objetivo · Combativo.
5. **Modo de fluxo (botoes):** Checkpoint (confirma cada etapa) · Continuo.
6. **Confirmar dual (botoes):** Entendi — cada caso pergunta **move ou responde** · Explicar de novo.

## Explicacao do plugin (apresentar ao fim, 5 frases)
1. **O que cobre:** registro e AIRC, contencioso (AIJE, AIME, 41-A, condutas vedadas, resposta, RCED), propaganda, contas/FEFC, partidario, crimes eleitorais (IN) e recursos standalone ate TSE/STF — com **fundacao 2026** no `context/`.
2. **E dual:** atende quem **impugna** e quem **se defende**. O master identifica o lado no pedido. Em AIJE/AIME o onus de provar o abuso e de **quem move** — isso e tese de defesa, nao espelho.
3. **As 3 travas:** (a) art. 105 da **Lei 9.504/1997** (CE 105 está revogado); (b) resolução-base **+** alteração 2026; (c) prazos **peremptórios** com dies a quo. FEFC: **30/08** ✅ no texto lido; 🟡 ato formal FEFC 30/08→08/09 pendente, notícia TSE 03/08/2026 — **proibido** afirmar 08/09 como vigente.
4. **Postura honesta:** gaps (prazo final AIJE generica; rito AIME fora da CF; ato FEFC 08/09) sao **declarados**, nao preenchidos.
5. **Como usar:** descreva o caso; a porta e `eleitoral-master` → `triagem-eleitoral`. A primeira pergunta do **caso** sera **voce move ou responde?**

## Gravacao
Criar `eleitoral/perfil.md`. Se existir: botoes **Atualizar** ou **Recriar**.

## Entrega obrigatoria final
- `eleitoral/perfil.md` + resumo + sugestao (`/triagem-eleitoral` ou `/eleitoral-master`).

## Guard
Nao inventar dado do operador. Trilha preferencial e **preferencia**, nao filtro — a triagem roteia qualquer caso. Nao prometer resultado nem "8 anos automaticos" na AIME. Nao travar o escritorio em so "defesa do candidato".
