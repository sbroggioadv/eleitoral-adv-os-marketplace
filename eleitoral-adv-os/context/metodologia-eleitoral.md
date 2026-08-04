# Metodologia do plugin eleitoral-adv-os

> Anexo mestre. O “como pensar” antes do “o que escrever”: dual **move × responde**, as **3 travas**, assimetrias de ônus, mapa das camadas e o contrato de anti-alucinação.
> É o arquivo que o `eleitoral-master`, o `anti-alucinacao-eleitoral`, o `validador-eleitoral` e a `suprema-corte-eleitoral` consultam para não escorregar.
> **Corpus de origem:** `_planning/eleitoral/fontes/` A–E + `.aiox/orca/GOAL-eleitoral.md` + `_planning/eleitoral/DESIGN-SPEC.md` (04/08/2026).
> **Captura das fontes:** Planalto e TSE, em **04/08/2026**.
>
**Legenda:** ✅ lido na fonte oficial · 🟡 existe mas inteiro teor não lido integralmente · 🔴 pendente / sub judice / revogado / armadilha.
**Como usar:** `grep` do dispositivo e leia a **faixa**. Nunca despeje o anexo inteiro no contexto.
**Regra de origem:** só o que está nas 5 frentes `_planning/eleitoral/fontes/`. O que falta vira **GAP DECLARADO** no próprio anexo — **proibido inventar**.


---

## 1. ⛔ A REGRA DE LEITURA DOS ANEXOS (vale para TODAS as skills)

**Faça `grep` do dispositivo e leia a FAIXA. Nunca despeje um anexo inteiro no contexto.**

Formato do ponteiro dentro de cada skill:

```
`context/<arquivo>.md` (arts. X e Y — grep o artigo e leia a faixa)
```

**Por quê:** os anexos são densos de propósito. Carregar um arquivo inteiro para citar um artigo desperdiça contexto e aumenta a chance de puxar dispositivo revogado ou base 2019 sem alteração 2026.

**Toda skill referencia pelo menos um anexo.** Nunca cite dispositivo “de cabeça”: **o anexo é a prova**.

---

## 2. OS PILARES

1. **Porta única** — todo caso entra pelo `eleitoral-master`, que identifica **lado** (move | responde | ambos), **fase**, **via** e **prazo**, e roteia. Toda peça fecha pela **`suprema-corte-eleitoral` (R1–R4)** + **`validador-eleitoral`**.
2. **Dual (decisão do Doc, 04/08/2026)** — o plugin **não** é “defesa do candidato only”. É **contencioso eleitoral pelos dois lados**. Toda skill de contencioso é **side-aware** (ataque + defesa, ônus e risco de cada polo).
3. **Standalone-first** — recursos e bases no próprio plugin; zero dependência de API em runtime para o núcleo citável.
4. **Anti-alucinação por design** — nenhum dispositivo, súmula, resolução ou prazo entra em peça sem âncora no `context/`. Itens 🟡 entram **sempre** como “a confirmar”, nunca como fato.
5. **Lei e resolução VIGENTES 2026** — a captura de fonte oficial **supera o treino do modelo**. Homônimos, revogações e base+alteração 2026 são armadilhas estruturais.

---

## 3. DUAL — protocolo de lado

```
pedido do usuário
   │
   ├─→ 1. LADO: move | responde | ambos (parecer) | ambíguo → botões
   ├─→ 2. FASE: pré-registro · registro · campanha · pós-1º/2º turno · pós-diplomação
   ├─→ 3. VIA: AIRC | AIJE | AIME | rep. 30-A/41-A/73/96 | resposta | RCED | contas | penal | recurso | partidário
   ├─→ 4. PRAZO: dies a quo + se peremptório / contínuo (calendário + LC 64 art. 16)
   ├─→ 5. skill side-aware + guard anti-alucinacao-eleitoral
   └─→ 6. suprema-corte-eleitoral R1–R4 + validador-eleitoral
```

**O dual NÃO significa:**
- simetria de sanções (AIJE comina 8 anos no art. 22, XIV; AIME no CF §10 **não** comina 8 anos no texto);
- redigir peça do **Ministério Público** como “cliente” (MP entra como polo processualmente real; o plugin atende candidato/partido/federação/coligação que move ou responde);
- inventar legitimidade: se o corpus diz quem pode impugnar (LC 64 art. 3º), a skill **move** só para legitimados.

### Assimetria canônica (AIJE / AIME) — texto fixo

> Em AIJE e AIME, o **ônus de provar o abuso** (e demais fatos constitutivos do pedido) é de **quem move**. Isso **não** é detalhe didático: é **tese de defesa** de primeira linha (falta de prova / indícios insuficientes / ausência de gravidade no art. 22, XVI). Os lados **não** são espelhos de sanção nem de ônus.

---

## 4. AS TRÊS TRAVAS (carregadas em toda peça / R2–R3)


## ⛔ TRAVA (a) — `art. 105` é HOMÔNIMO

| Diploma | art. 105 | Status |
|---|---|---|
| **Código Eleitoral (Lei 4.737/1965)** | art. 105 | 🔴 **REVOGADO pela Lei nº 14.211/2021** — **não existe** como norma viva |
| **Lei das Eleições (Lei 9.504/1997)** | art. 105 e §3º | ✅ **VIVO** — prazo de instruções do TSE (5 de março do ano da eleição) e só resoluções publicadas até essa data se aplicam ao pleito |

**Forma canônica em peça:** sempre **nomear a lei na mesma linha** — ex.: *“Lei nº 9.504/1997, art. 105, § 3º”*.  
**Proibido:** “CE art. 105” / “Código Eleitoral art. 105” como se fosse o “5 de março”.



## ⛔ TRAVA (b) — base 2019 **+** alteração 2026 (o TSE não “reedita do zero”)

O ciclo 2026 **mantém** resoluções-base de **2019/2021/2024** e as **altera** por resolução numerada em **2026**.  
**Erro a bloquear:** citar Res. 23.609 / 23.610 / 23.607 / 23.608 / 23.600 / 23.605 **“puras”** como texto final de 2026.

**Forma canônica:** `Res.-TSE 23.609/2019, com as alterações da Res.-TSE 23.754/2026` (e análogos).  
**Calendário:** somente **Res. 23.760/2026** (não reutilizar calendário 2022/2024).


### Mapa mínimo base → alteração 2026

| Tema | Base | Alteração 2026 | Forma de citação |
|---|---|---|---|
| Registro | 23.609/2019 | **23.754/2026** | 23.609/2019 + 23.754/2026 |
| Propaganda / internet / IA | 23.610/2019 (+ 23.732/2024) | **23.755/2026** | 23.610 + 23.732 + 23.755 |
| Contas de campanha | 23.607/2019 | **23.752/2026** | 23.607/2019 + 23.752/2026 |
| FEFC | 23.605/2019 | **23.749/2026** | 23.605/2019 + 23.749/2026 |
| Pesquisas | 23.600/2019 | **23.747/2026** | 23.600/2019 + 23.747/2026 |
| Representações / resposta | 23.608/2019 | **23.756/2026** | 23.608/2019 + 23.756/2026 |
| Ilícitos | 23.735/2024 | **23.757/2026** | 23.735/2024 + 23.757/2026 |
| Calendário | — | **23.760/2026** (autônoma) | **somente** 23.760/2026 |


## ⛔ TRAVA (c) — FEFC 30/08 ✅ vs 08/09 🟡

| Afirmação | Selo | Fonte |
|---|---|---|
| Distribuição dos percentuais mínimos FEFC (mulheres/negros/indígenas) **até 30 de agosto** do ano eleitoral | ✅ | Res. 23.607 art. 17 §9º (redação 23.752/2026) + calendário 23.760 |
| Plenário TSE **03/08/2026** aprovou mudar para **08/09** (notícia) | 🟡 | Notícia TSE — **ato formal (nº de resolução/portaria) NÃO localizado** nas frentes |
| Afirmar **08/09 como vigente** em peça | 🔴 **PROIBIDO** enquanto o ato formal não for lido no DJE/índice TSE |

Até o ato formal: citar **30/08 ✅**; se mencionar a notícia, selo **🟡** e ressalva de ato formal pendente.


### Prazo peremptório + dies a quo (trava de peça)

Toda peça com prazo: **dispositivo + dies a quo + se contínuo/peremptório + se 3 dias / 24h / 5 dias / 15 dias**. Sem dies a quo = não sela.

---

## 5. VERDADES DURAS (do corpus — build não contraria)

1. 🔴 **art. 105** = homônimo; CE revogado; vivo = Lei 9.504/1997.
2. 🔴 **Base 2019 + alteração 2026** — não “reedição do zero”.
3. 🟡 FEFC 30/08 ✅ vs 08/09 🟡 (ato formal não localizado).
4. 🔴 Consequências **não** intercambiáveis: cassação de **registro** ≠ **diploma** ≠ impugnação de **mandato** (AIME) ≠ inelegibilidade de **8 anos**.
5. 🔴 **Condição** (CF 14 §3º) × **inelegibilidade** (CF 14 §§4º–9º + LC 64) — confundir destrói AIRC e RCED.
6. 🔴 Art. 11 §10 Lei 9.504 **REVOGADO** pela LC 219/2025; superveniência favorável → **LC 64 art. 26-D** (+ tensão Súmula-TSE 70).
7. 🔴 Boca de urna = **Lei 9.504 art. 39, §5º** — **não** CE art. 39 / 337 como “o” tipo.
8. 🔴 Crime **299 CE** ≠ captação ilícita **41-A** (reclusão × multa+cassação).
9. 🔴 Desaprovação de contas ≠ cassação de diploma; quitação impedida na não prestação ≠ desaprovação automática.
10. Prazo eleitoral é **peremptório**; muita via recursal em **3 dias**; representações art. 96 / resposta em **24h**.
11. AIJE genérica: prazo **final de ajuizamento** do abuso art. 22 **não está no art. 22** lido → **GAP**.
12. AIME: CF 14 §§10–11 = 15 dias da diplomação; **rito e legitimados** não estão na CF → **GAP** de rito legal.
13. LC 219/2025 reescreve marcos de várias alíneas; alínea **d** da alteração = **VETADA** (permanece LC 135) — se no corpus.
14. Calendário 2026 (23.760): registro até **15/08 19h**; 1º turno **04/10**; 2º **25/10**.

---

## 6. MAPA DOS ANEXOS `context/`

| Arquivo | Conteúdo |
|---|---|
| `metodologia-eleitoral.md` | Este arquivo — dual, travas, verdades |
| `codigo-eleitoral-crimes-e-processo.md` | CE crimes 289–354-A + processo 355–364 + recursos 215–282 |
| `lei-9504-destaques.md` | Lei 9.504 destaques citáveis (incl. **art. 105 LE**) |
| `lei-9096-partidos.md` | Lei dos Partidos |
| `lc-64-ficha-limpa.md` | LC 64 + LC 135 + LC 219 + súmulas |
| `cf-14-elegibilidade.md` | CF art. 14 condição × inelegibilidade + AIME §§10–11 |
| `resolucoes-tse-2026-mapa.md` | Tabela-mestra base→2026 + trechos |
| `calendario-eleitoral-2026.md` | Res. 23.760 marcos |
| `contencioso-eleitoral-vias.md` | AIRC/AIJE/AIME/rep./RCED/recursos |
| `contas-e-fefc-2026.md` | Contas, FEFC, fontes vedadas, desfechos |

---

## 7. SUPREMA CORTE R1–R4 (checklist rápido)

| R | Pergunta |
|---|---|
| **R1** | Fatos e **fase** do ciclo batem com a via? |
| **R2** | Fundamento **vigente**? Diploma **nomeado**? Base **+** alteração 2026? |
| **R3** | Prazo com **dies a quo** e natureza (contínuo/peremptório)? |
| **R4** | Via correta para a **consequência** pedida (registro × diploma × mandato × 8 anos)? |

---

## 8. GAPS QUE O PRODUTO CARREGA (não preencher por dedução)

Ver gaps declarados em cada anexo e nas frentes A–E. Exemplos estruturais:
- prazo final de ajuizamento da AIJE genérica (abuso art. 22);
- rito/legitimados AIME fora da CF;
- ato formal FEFC 08/09 (notícia 03/08/2026);
- Portaria 449/2026 (valores) inteiro teor;
- Súmula STF 728 (HTTP 403 na captura).

---

## 9. O QUE ESTE ANEXO RECUSOU

- Inventar skill, command, hook ou número sem âncora nas 5 frentes.
- Afirmar 08/09 FEFC como vigente.
- Citar CE art. 105 como norma viva do “5 de março”.
- Achatar ônus de AIJE/AIME entre move e responde.
