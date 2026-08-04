---
name: estilo-eleitoral
description: "Voz e forma de peca eleitoral despersonalizada - peticao, contrarrazoes, razoes recursais, defesa criminal, defesa de contas. Checklist anti-desatualizacao (Lei 9.504/1997 art. 105, base+2026, FEFC 30/08, dual, dies a quo). Use internamente antes de entregar qualquer peca eleitoral, ou ao dizer tom da peca, como redigir, padrao de estilo."
---

# ESTILO-ELEITORAL

> Transversal. Camada de estilo - consultada **antes** de entregar a peca. Garante tom, enderecamento e terminologia **vigente 2026**. Despersonalizado (familia Adv-OS).

## Anexos obrigatorios (context/)
- `context/metodologia-eleitoral.md` - dual · 3 travas · R1-R4.
- `context/resolucoes-tse-2026-mapa.md` - base + alteracao 2026.
- `context/calendario-eleitoral-2026.md` - marcos.
- Skills: `calendario-e-prazos-eleitorais` · `validador-eleitoral` · `suprema-corte-eleitoral`.

## Checklist anti-desatualizacao (rodar em TODA peca)
1. **Art. 105:** so **Lei 9.504/1997 art. 105** (5 de marco). 🔴 Nunca CE art. 105 como vivo (revogado Lei 14.211/2021).
2. **Resolucoes:** base 2019/2021/2024 **+** alteracao 2026 na mesma citacao (ex.: Res. 23.609/2019 + 23.754/2026). Calendario = **so 23.760**.
3. **FEFC:** **30/08** ✅; **08/09** so como noticia 🟡 com ato formal pendente - nunca vigente.
4. **Dual:** a peca declara o **lado** (move/responde). Em AIJE/AIME, onus de provar abuso = quem move (tese de defesa se responde).
5. **Prazo:** dispositivo + **dies a quo** + se continuo/peremptorio. 24h != 3 dias.
6. **Consequencia:** registro != diploma != mandato != 8 anos - nao trocar (`quadro-consequencias-por-via`).
7. **299 != 41-A:** crime x captacao ilicita (sancoes distintas).
8. **Art. 11 par. 10 Lei 9.504:** **revogado** LC 219/2025; superveniencia favoravel = **LC 64 art. 26-D** (+ tensao Sum. TSE 70 - declarar, nao escolher lado).
9. **Citacoes:** so com ancora em `context/` ou fonte reaberta e validada. 🟡 nunca vira ✅.
10. **Sem promessa de resultado** (etica OAB). Sem PII de terceiros. Autoria generica do escritorio do **cliente** (plugin despersonalizado).

## Enderecamento
| Peca | Destinatario tipico |
|---|---|
| AIRC / AIJE / rep. 1o grau | Juiz Eleitoral da zona / Corregedoria conforme a via |
| Recurso ao TRE | Tribunal Regional Eleitoral |
| REspe / RO / agravo | TSE (ou STF no 281/282) |
| ED | orgao que proferiu a decisao |
| Defesa criminal eleitoral | Juizo criminal eleitoral (rito CE 355+) |
| Defesa de contas | instancia da prestacao (resolucao de contas consolidada) |

## Estrutura padrao por tipo
- **Peticao inicial / representacao:** enderecamento · legitimidade · fatos com datas · enquadramento (lei+artigo na linha) · provas · pedidos (sancao **da via**) · valor/preparo se couber.
- **Contestacao / defesa:** tempestividade · preliminares (ilegitimidade, inepcia, litispendencia) · onus · merito · pedidos.
- **Contrarrazoes / razoes recursais:** tempestividade · cabimento · capitulos · merito · efeito 257 se invocado.
- **ED:** vicios numerados · dispositivo+diploma · prequestionamento se for o caso.
- **Defesa criminal:** tipicidade · materialidade · autoria · rito e prazos penais (**!=** 3 dias civeis).
- **Defesa de contas:** fatos contabeis · fontes · desfecho pedido **sem** converter em cassacao sem base.

## Tom
Tecnico, objetivo, assertivo. **Side-aware:** linguagem de quem move **nao** e a de quem responde com a mesma lista invertida. Ataque: indicios + gravidade + sancao da via. Defesa: onus, prova insuficiente, via/sancao errada, prazo.

## Dual na redacao
- Abrir com: "Lado processual: **move** / **responde**."
- Nunca "o candidato sempre e vitima" nem "o impugnante sempre tem razao".
- MP e polo real quando a lei legitima; o plugin atende candidato/partido/federacao/coligacao.

## Guard
Toda citacao passa por `validador-eleitoral`. Gate final `suprema-corte-eleitoral` (R1-R4). Checklist falhou = peca volta para correcao.
