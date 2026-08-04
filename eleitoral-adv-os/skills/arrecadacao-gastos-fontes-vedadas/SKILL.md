---
name: arrecadacao-gastos-fontes-vedadas
description: "Arrecadacao e gastos de campanha: fontes vedadas Lei 9.504 art. 24 + Res. 23.607/2019+23.752/2026 art. 31 (PJ, estrangeiro, permissionario), origem nao identificada art. 32 Res., doacoes PF art. 23 (10% rendimentos; recursos proprios 10% do limite), excesso de gastos art. 18-B, limites Port. 449/2026 sem inventar valores. Dual auditoria move x compliance responde. Use em fonte vedada, doacao de empresa, origem nao identificada, caixa 2, limite de gastos, /contas arrecadacao, e quando disserem pode receber de PJ, doacao acima do limite, o que e ONI, Portaria 449."
---

# ARRECADACAO-GASTOS-FONTES-VEDADAS

> Camada **C5**. Compliance e ataque sobre **origem e gasto**. Desfecho/30-A = `defesa-contas-desaprovadas` + `contas-de-campanha`. FEFC/FP = `fefc-e-fundo-partidario`.

## Anexos obrigatorios (context/)
- `context/contas-e-fefc-2026.md` - art. **24**, **23**, **18-B**, Res. **31-32**, Port. **449** [Y] - **grep + ler**.
- `context/lei-9504-destaques.md` - art. 24 se colado; ponte 30-A - **grep + ler**.
- `context/resolucoes-tse-2026-mapa.md` - 23.607+23.752; limites **23.766 + Port. 449** - **grep + ler**.
- `context/metodologia-eleitoral.md` - proibicao de inventar teto - **grep + ler**.

## Objetivo
Classificar recurso (licito / fonte vedada / ONI / excesso), mandar devolver ou recolher, e dualizar auditoria (move) vs defesa do prestador (responde) **sem inventar valores da Port. 449**.

## Lado
- **responde:** campanha/partido que recebeu ou gastou.
- **move:** quem denuncia fonte vedada, ONI, excesso de limite, doacao irregular (impugnacao de contas / 30-A / representacao cabivel).
- **ambos:** due diligence pre-doacao e pre-gasto.

## Fundamento

### 1) Fontes vedadas - Lei 9.504 art. 24 (verbatim no annex)
Vedado a partido e candidato receber, direta ou indiretamente, doacao em dinheiro ou estimavel, inclusive publicidade, de:
I entidade/governo estrangeiro; II orgao da adm. direta/indireta ou fundacao com recursos publicos; III concessionario/permissionario de servico publico; IV entidade privada com contribuicao compulsoria legal; V utilidade publica; VI entidade de classe ou sindical; VII PJ sem fins lucrativos com recursos do exterior; VIII beneficentes e religiosas; IX esportivas; X ONGs com recursos publicos; XI OSCIPs; XII (VETADO).
- par.4o: quem receber de fonte vedada ou origem nao identificada deve **devolver** ou, se impossivel identificar, **transferir a conta unica do Tesouro Nacional**.

### 2) Res. 23.607/2019 art. 31 (c/ 23.752/2026)
Vedado doar/receber de: **I pessoas juridicas**; **II origem estrangeira**; **III pessoa fisica permissionaria de servico publico**. Devolucao imediata; se impossivel, GRU ao Tesouro; juros/correcao salvo espontaneidade.

**Tensao textual (declarar, nao "resolver"):** art. 24 lista entidades; art. 31 I veda **PJ de forma ampla** (regime pos-doacao empresarial). Em peca: citar **lei + resolucao do ciclo**. ADI 4650/STF = [Y] ate inteiro teor aberto.

### 3) Origem nao identificada - Res. art. 32
Recursos de ONI **nao podem ser usados**; transferencia ao Tesouro.

### 4) Doacoes de pessoas fisicas - Lei 9.504 art. 23
- Caput: pessoas fisicas podem doar (redacao 12.034/2009).
- Limite: **10% dos rendimentos brutos** do doador no ano anterior (Lei 13.165/2015).
- Recursos proprios do candidato: par.2o-A - ate **10%** do limite de gastos do cargo (Lei 13.878/2019).

### 5) Excesso de limite de gastos - art. 18-B
Multa de **100%** do que ultrapassar o limite, sem prejuizo de abuso (LC 64 art. 22).  
Res. 23.607/2019 art. 6o (red. 23.752/2026): recolhimento em **5 dias uteis** da intimacao.

### 6) Limites 2026 - Res. 23.766/2026 + Portaria 449/2026
- Art. 1o Res. 23.766: limite de gastos 2026 = o das eleicoes gerais **2022**.
- par.1o: 2o turno majoritario - acrescimo de **50%** do teto do 1o turno.
- par.2o: valores por **portaria** da Presidencia do TSE ate **20/07/2026** - **Port. 449/2026** existe e vincula.
- [Y] **Inteiro teor da tabela (valores por cargo/UF) NAO lido** no corpus.  
  **PROIBIDO** inventar teto em R$. Em peca: "conforme Portaria-TSE 449/2026 e DivulgaCandContas / portal oficial" + abrir a linha do cargo/UF.

### 7) Pix e recibo
**Res. 23.607/2019, art. 7 §6-A, redacao Res. 23.752/2026:** recibo dispensado em FEFC/FP transferido pelo partido e em doacoes **Pix** (ainda assim: identificar doador e respeitar limites/fontes).

## Dual

### RESPONDE (compliance / defesa)
1. Rastrear CPF do doador, data, valor, meio (Pix/TED/estimavel).
2. Se fonte vedada/ONI: **devolver** ou GRU Tesouro (par.4o art. 24 / arts. 31-32 Res.) - espontaneidade mitiga juros na Res.
3. Excesso de gasto: calcular sobre o **teto oficial aberto** (nao inventado); recolher 100% do excedente em 5 dias uteis da intimacao se intimado.
4. Estimavel: documentar bem/servico e valor de mercado **sem** fabricar nota.
5. Teses: doador e PF; dentro de 10% dos rendimentos (prova com declaracao - nao inventar IR); recurso proprio dentro de 10% do limite do cargo; devolucao tempestiva.

### MOVE (auditoria / impugnacao)
1. Cruzar extratos x doadores x PJ (CNPJ) x permissionarios.
2. Indicio de PJ "por interposta PF", ONI, caixa paralelo -> contas + **30-A** + eventual abuso.
3. Excesso de teto: comparar gasto total com Port. 449 **lida** + 50% se 2o turno.
4. Pedidos: desaprovacao / devolucao / multa 18-B / 30-A se ilicito de arrecadacao/gasto com pedido de diploma.
5. **Onus do move** no 30-A: provar o ilicito (ver `defesa-contas-desaprovadas`).

## Assimetria
- Receber de fonte vedada gera dever de **devolver** mesmo sem ma-fe - defesa nao e "nao sabia" como se bastasse, mas espontaneidade e documentacao contam no rito.
- Cassacao de diploma continua sendo **30-A**/abuso, nao o mero estorno.

## Prazos
| Ato | Prazo | Dies a quo |
|---|---|---|
| Devolucao fonte vedada/ONI | Imediata / na forma da Res. 31-32 | 🔴 **GAP** — anexo so diz **devolucao imediata**; *dies* operacional (ciencia etc.) **nao capturado** — confira texto integral / autos |
| Recolhimento excesso (art. 6o Res.) | **5 dias uteis** | Intimacao |
| 30-A | 15 dias | Diplomacao |

## GAPS
- Valores da **Port. 449/2026** linha a linha.
- Inteiro teor ADI 4650.
- Criterios numericos de "interposta pessoa" na jurisprudencia - nao inventar presuncao.

## Entrega obrigatoria
Classificacao do recurso (licito/vedada/ONI/excesso) + lado + ato (devolver/recolher/impugnar/30-A) + base (24 / 31 / 32 / 18-B / 23) + **sem numero de teto inventado**. Fecha: Suprema Corte + validador.

## Guard
- Nunca autorizar doacao de **PJ** (Res. art. 31 I).
- Nunca cravar valor de limite sem Port. 449 / portal.
- Nunca usar ONI em campanha.
- Nunca dizer que estorno sozinho cassa diploma.
- Sempre 23.607 + 23.752.
