# Anexo — Resoluções TSE ciclo 2026: mapa base→alteração

> Anexo de referência do plugin **eleitoral-adv-os**. Tabela-mestra do pacote 2026, forma canônica de citação e trechos citáveis.
> **Fontes-mãe TSE:** índice Eleições 2026 + resoluções compiladas (links no corpo).
> **Captura:** 04/08/2026.
>
> **Legenda:** ✅ lido na fonte oficial · 🟡 existe mas inteiro teor não lido integralmente · 🔴 pendente / sub judice / revogado / armadilha.
> **Como usar:** `grep` do dispositivo e leia a **faixa**. Nunca despeje o anexo inteiro.
> **Origem:** transformado das frentes em `_planning/eleitoral/fontes/` (captura 04/08/2026). **Proibido inventar** o que não está no corpus — vira GAP no próprio anexo.


---

## ⛔ TRAVA OBRIGATÓRIA NESTE ANEXO

1. **Homônimo art. 105:** o limite de instruções é **Lei 9.504/1997, art. 105 e §3º** ✅. **Código Eleitoral art. 105 = REVOGADO pela Lei 14.211/2021** 🔴. Sempre nomear a **lei** na linha.
2. **Base 2019 + alteração 2026:** citar a base **com** a resolução alteradora de 2026. Citar 2019 “pura” como texto final de 2026 = defasagem.
3. **FEFC 30/08 ✅ vs 08/09 🟡:** notícia 03/08/2026; ato formal **não localizado**. **Proibido** afirmar 08/09 como vigente.

---

## 0. Fonte-mãe do pacote (índice oficial)

| Fonte | URL | Selo |
|---|---|---|
| Normas e documentações – Eleições 2026 | https://www.tse.jus.br/eleicoes/eleicoes-2026-content/normas-e-documentacoes | ✅ |
| Índice resoluções 2026 (compiladas) | https://www.tse.jus.br/legislacao/compilada/res/2026 | ✅ |
| Notícia: 14 resoluções publicadas | https://www.tse.jus.br/comunicacao/noticias/2026/Marco/eleicoes-2026-tse-publica-todas-as-resolucoes-que-orientarao-o-pleito (04/03/2026; atualizada 08/07/2026) | ✅ |
| Notícia: alterações pontuais (03/08/2026) | https://www.tse.jus.br/comunicacao/noticias/2026/Agosto/plenario-aprova-alteracoes-pontuais-em-resolucoes-das-eleicoes-2026 | ✅ |

✅ O TSE declara ter aprovado **14 resoluções** que disciplinam as Eleições Gerais 2026, em sessões de **26/02/2026** e **02/03/2026**, publicadas em edição extra do DJE-TSE **nº 30, de 04/03/2026**.

⚠️ **Modelo estrutural do ciclo 2026 (lido no hub oficial):** o TSE **não reeditou do zero** a maioria das normas de registro/propaganda/contas. Mantém as resoluções-base de **2019** (e algumas de 2021/2024) e **altera** por resolução numerada em **2026**. Citar só o número de 2019 sem a alteração de 2026 = **defasagem**.

---

## 1. O limite temporal das instruções — Lei 9.504/97, art. 105 (correção crítica do brief)

### 1.1 O que o brief pediu vs o que a fonte diz

O brief pede confirmação do **Código Eleitoral, art. 105**.  
Na fonte primária do Planalto:

✅ **Código Eleitoral (Lei 4.737/1965), art. 105 — REVOGADO pela Lei nº 14.211/2021.**  
URL: https://www.planalto.gov.br/ccivil_03/leis/l4737compilado.htm (snippet oficial de busca Planalto: `Art. 105. (Revogado pela Lei nº 14.211, de 2021)`).

O prazo de expedição de instruções para a eleição **não está no CE art. 105**. Está na **Lei das Eleições**:

### 1.2 Lei 9.504/1997, art. 105 — texto capturado (fonte TSE + Planalto)

✅ **Lei nº 9.504/1997, art. 105** (texto no portal TSE da Lei das Eleições e espelhado no Planalto):

> **Art. 105.** Até o dia 5 de março do ano da eleição, o Tribunal Superior Eleitoral, atendendo ao caráter regulamentar e sem restringir direitos ou estabelecer sanções distintas das previstas nesta lei, poderá expedir todas as instruções necessárias para sua fiel execução, ouvidos, previamente, em audiência pública, os delegados ou representantes dos partidos políticos.

> **§ 1º** O Tribunal Superior Eleitoral publicará o código orçamentário para o recolhimento das multas eleitorais ao Fundo Partidário, mediante documento de arrecadação correspondente.

> **§ 2º** Havendo substituição da Ufir por outro índice oficial, o Tribunal Superior Eleitoral procederá à alteração dos valores estabelecidos nesta lei pelo novo índice.

> **§ 3º** Serão aplicáveis ao pleito eleitoral imediatamente seguinte apenas as resoluções publicadas até a data referida no caput.

**Fontes:**  
- https://www.tse.jus.br/legislacao/codigo-eleitoral/lei-das-eleicoes/lei-das-eleicoes-lei-nb0-9.504-de-30-de-setembro-de-1997 (lido, art. 105 + §§) ✅  
- https://www.planalto.gov.br/ccivil_03/leis/l9504.htm#art105 (existente; *caput* confirmado em snippet oficial) ✅/*caput*  
- Notícia TSE 04/03/2026: publicação em 04/03 cumpriu o prazo que “somente terminaria” em **05/03** — art. 105 da Lei 9.504 ✅

✅ **Consequência para o plugin (âncora de anti-defasagem):**  
**Só resoluções publicadas até 5 de março do ano eleitoral** se aplicam ao pleito daquele ano (**Lei 9.504/97, art. 105, § 3º**). Resoluções posteriores de **ajuste pontual** (ex.: 03/08/2026) existem, mas o *pacote principal* do ciclo é o de fev/mar 2026; o plugin deve citar o **texto consolidado vigente** da base + alterações 2026, e **nunca** a resolução “nua” de 2019/2022/2024 como se fosse a última.

🟡 **Nuance:** a notícia de 03/08/2026 descreve ajustes em Res. 23.607/2019, 23.673/2021 e 23.760/2026 **após** 5 de março. Inteiro teor da *nova* resolução/portaria de agosto **não** foi localizado no índice `/res/2026` com número novo na data desta captura — ver GAPS. Tratar o conteúdo da notícia como 🟡 (oficial, mas não o ato normativo formal lido).

---

## 2. Mapa do pacote 2026 (14 + satélites)

### 2.1 Tabela-mestra: tema × base herdada × resolução 2026 × ciclo

| # | Tema (mínimo do brief) | Base (herdada) | Resolução ciclo 2026 | Data | Tipo | Substitui / relação com ciclo anterior | URL 2026 | Selo |
|---|---|---|---|---|---|---|---|---|
| 1 | **Calendário eleitoral 2026** | — (nova do ciclo) | **23.760/2026** | 02/03/2026 | **Ciclo 2026 (autônoma)** | Equivalente funcional ao calendário do ciclo 2024 (ex. Res. calendário 2024); **não** é “herança” da 23.609 etc. | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-760-de-2-de-marco-de-2026 | ✅ |
| 2 | **Registro de candidatura** | 23.609/2019 | **23.754/2026** | 02/03/2026 | **Alteração 2026 da base 2019** | Altera 23.609/2019 (já alterada em ciclos anteriores, ex. 23.729/2024 citada no próprio texto) | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-754-de-2-de-marco-de-2026 | ✅ |
| 3 | **Propaganda (internet, IA, deepfake)** | 23.610/2019 | **23.755/2026** | 02/03/2026 | **Alteração 2026** | Altera 23.610/2019; 2024 já tinha 23.732/2024; **2026 reforça** IA/desinformação | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-755-de-2-de-marco-de-2026 | ✅ |
| 4 | **Arrecadação, gastos e prestação de contas de campanha** | 23.607/2019 | **23.752/2026** | 26/02/2026 | **Alteração 2026** | Altera 23.607/2019 | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-752-de-26-de-fevereiro-de-2026 | ✅ |
| 5 | **FEFC** | 23.605/2019 | **23.749/2026** | 26/02/2026 | **Alteração 2026** | Altera 23.605/2019; revoga §1º art. 6º e arts. 10 e 11 da base | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-749-de-26-de-fevereiro-de-2026 | ✅ |
| 6 | **Pesquisas eleitorais** | 23.600/2019 | **23.747/2026** | 26/02/2026 | **Alteração 2026** | Altera 23.600/2019 | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-747-de-26-de-fevereiro-de-2026 | ✅ |
| 7 | **Limites de gastos (satélite)** | — | **23.766/2026** | 01/07/2026 | **Ciclo 2026 (autônoma)** | Limite = o de **2022**; portaria de valores: Port. **449/2026** | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-766-de-1o-de-julho-de-2026 | ✅ |
| 8 | Representações / reclamações / direito de resposta | 23.608/2019 | **23.756/2026** | 02/03/2026 | **Alteração 2026** | Altera 23.608/2019 | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-756-de-2-de-marco-de-2026 | ✅ |
| 9 | Ilícitos eleitorais (abuso, condutas vedadas, IA no ilícito) | 23.735/2024 | **23.757/2026** | 02/03/2026 | **Alteração 2026 da base 2024** | Altera 23.735/2024 (ciclo municipal 2024 → gerais 2026) | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-757-de-2-de-marco-de-2026 | ✅ |
| 10 | Atos gerais do processo eleitoral | — | **23.751/2026** | 26/02/2026 | **Ciclo 2026 (autônoma)** | Substitui, para 2026, a lógica das resoluções de “atos gerais” de ciclos anteriores | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-751-de-26-de-fevereiro-de-2026 | ✅ |
| 11 | Cronograma operacional do Cadastro | — | **23.750/2026** | 26/02/2026 | **Ciclo 2026 (autônoma)** | Idem, ciclo a ciclo | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-750-de-26-de-fevereiro-de-2026 | ✅ |
| 12 | Fiscalização e auditoria da urna | 23.673/2021 | **23.758/2026** | 02/03/2026 | **Alteração 2026** | Altera 23.673/2021 | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-758-de-2-de-marco-de-2026 | ✅ |
| 13 | Sistemas majoritário/proporcional, totalização, diplomação | 23.677/2021 | **23.748/2026** | 26/02/2026 | **Alteração 2026** | Altera 23.677/2021 | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-748-de-26-de-fevereiro-de-2026 | ✅ ementa; 🟡 corpo (não lido inteiro) |
| 14 | Consolidação normas ao cidadão | — | **23.759/2026** | 02/03/2026 (URL com slug 26/02) | **Ciclo 2026 (autônoma)** | Novidade de 2026 | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-759-de-26-de-fevereiro-de-2026 | ✅ ementa; 🟡 corpo |
| 15 | Transporte especial / “Seu Voto Importa” | — | **23.753/2026** | 26/02/2026 | **Ciclo 2026 (autônoma)** | Novidade de 2026 | https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-753-de-26-de-fevereiro-de-2026 | ✅ ementa; 🟡 corpo |

### 2.2 Como citar em peça (regra prática)

✅ Para **registro** em 2026: citar **Res.-TSE 23.609/2019, com as alterações da Res.-TSE 23.754/2026** (e, se aplicável, alterações 2024 ainda vigentes e não revogadas pelo art. 2º da 23.754).  
✅ Para **propaganda**: **23.610/2019 + 23.732/2024 + 23.755/2026** (a 755 é a última alteração lida do ciclo geral).  
✅ Para **contas**: **23.607/2019 + 23.752/2026** (+ eventual ajuste de ago/2026 — 🟡).  
✅ Para **calendário**: **somente 23.760/2026** (não reutilizar calendário 2022/2024).

---

## 3. Calendário 2026 — marcos citáveis (Res. 23.760)

✅ Fonte: texto da Res. 23.760/2026 aberto e lido (Anexo I).  
URL: https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-760-de-2-de-marco-de-2026

| Marco | Data 2026 | Fundamento no calendário (verbatim resumido do ato) | Selo |
|---|---|---|---|
| 1º turno | **4 de outubro de 2026** | Confirmado também em Res. 23.751 art. 2º (atos gerais) | ✅ |
| 2º turno | **25 de outubro de 2026** | Onde houver | ✅ |
| Data-limite instruções TSE (art. 105 LE) | **5 de março** | “Data-limite para o Tribunal Superior Eleitoral publicar as instruções relativas às Eleições Gerais de 2026 (Lei nº 9.504/1997, art. 105, caput e § 3º)” | ✅ |
| Janela de migração partidária (dep. fed./est./distr.) | **5 mar – 3 abr** | Justa causa art. 22-A, III, Lei 9.096/1995 | ✅ |
| Domicílio + filiação / desincompatibilização Executivo | **4 de abril** (6 meses antes) | | ✅ |
| Fechamento cadastro (alistamento etc.) | **6 de maio** | Lei 9.504 art. 91 | ✅ |
| Financiamento coletivo prévio | a partir de **15 de maio** | | ✅ |
| FEFC: União disponibiliza / renúncia partidos | **1º de junho** | | ✅ |
| Condutas vedadas “3 meses” (publicidade, transferências, etc.) | a partir de **4 de julho** | Lei 9.504 art. 73, V e VI etc. | ✅ |
| Convenções partidárias | **20 de julho a 5 de agosto** | Lei 9.504 art. 8º | ✅ |
| **Registro de candidatura (DRAP/RRC)** | até **15 de agosto, 19h**, via internet | Lei 9.504 art. 11; Res. 23.609/19 art. 19 §2º (redação 23.754) | ✅ |
| Contagem de prazos contínuos (eleições) | a partir de **15 de agosto** | LC 64/90 art. 16 | ✅ |
| Pesquisas: lista com todos registrados | a partir de **20 de julho** (com edital de registro) | Res. 23.600 art. 3º (redação 23.747) | ✅ |

✅ **Hoje (04/08/2026):** último dia de propaganda intrapartidária pré-convenção (item calendário) e véspera do fim das convenções (05/08). **Registro fecha 15/08 19h** — prazo peremptório.

---

## 4. Registro de candidatura — Res. 23.754/2026 (sobre 23.609/2019)

✅ Lido o texto da 23.754 (alterações + revogações).  
URL: https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-754-de-2-de-marco-de-2026  
Publicação: DJE-TSE extra 04/03/2026; **republicada** DJE 06/03/2026.

### 4.1 Ementa e fundamento

> Altera a Resolução nº 23.609, de 18 de dezembro de 2019, que dispõe sobre a escolha e o registro de candidatas e candidatos para as eleições.

Fundamento normativo no preâmbulo: CE art. 23, IX; Lei 9.096 art. 61; **Lei 9.504 art. 105**.

### 4.2 Trechos citáveis (verbatim da alteração 2026)

**CANDex obrigatório (art. 8º-A — novo/renovado):**

> Art. 8º-A. A ata, a respectiva lista de presença e o pedido de registro de candidatura serão elaborados obrigatoriamente via internet, por meio do CANDex, disponível nos sítios eletrônicos dos tribunais eleitorais.

**Prazo de registro (art. 19, § 2º):**

> § 2º A apresentação do DRAP e do RRC far-se-á mediante transmissão pela internet, até as 19 (dezenove) horas do dia 15 de agosto do ano da eleição, com a emissão de recibo consignando o horário em que foi transmitido o pedido de registro.

**RDE — Requerimento de Declaração de Elegibilidade (art. 9º-B) — LC 219/2025:**

> Art. 9º-B. O pré-candidato, ou o partido político ao qual estiver filiado, que demonstrar dúvida razoável sobre sua capacidade eleitoral passiva poderá dirigir à Justiça Eleitoral Requerimento de Declaração de Elegibilidade (RDE) a qualquer tempo, podendo a postulação ser impugnada em 5 (cinco) dias por qualquer partido político ou federação com órgão de direção em atividade na circunscrição.

> § 11. Em caso de não apresentação do registro de candidatura até o dia 15 de agosto do ano da eleição, o RDE será extinto sem resolução de mérito, nos termos do art. 485, IV, do Código de Processo Civil, ressalvado o disposto no art. 29, caput, desta Resolução.

**Aferição de elegibilidade/inelegibilidade (art. 52 — LC 64 art. 26-D, LC 219/2025):**

> Art. 52. As condições de elegibilidade e as causas de inelegibilidade devem ser aferidas no momento de formalização do registro de candidatura, sem prejuízo do reconhecimento pela Justiça Eleitoral, de ofício ou mediante provocação, das alterações fáticas ou jurídicas supervenientes que afastem ou extingam a inelegibilidade, incluído o encerramento do seu prazo, desde que constituídas até a data da diplomação. (Lei Complementar nº 64/1990, art. 26-D, incluído pela Lei Complementar nº 219/2025)

**Idade mínima (art. 9º, § 2º — Lei 15.230/2025):**

> § 2º A idade mínima constitucionalmente estabelecida como condição de elegibilidade será aferida (Lei nº 9.504/1997, art. 11, § 2º, com redação dada pela Lei nº 15.230/2025):  
> I - para os cargos do Poder Executivo, na data da posse;  
> II - para o cargo de vereador, no dia 15 de agosto do ano da eleição;  
> III - para os demais cargos, na data da posse presumida, assim considerada aquela ocorrida dentro do prazo de até 90 (noventa) dias, contado da eleição da Mesa Diretora da Casa Legislativa [...]

**Ciclo:** alteração **2026** sobre base **2019**. **Não** usar resoluções de registro do ciclo 2022 (ex. minutas antigas) como se fossem o texto atual.

---

## 5. Propaganda eleitoral + internet + IA/deepfake — Res. 23.755/2026 (sobre 23.610/2019)

✅ Lido o texto da 23.755.  
URL: https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-755-de-2-de-marco-de-2026  
Notícia institucional (resumo): https://www.tse.jus.br/comunicacao/noticias/2026/Marco/tse-aprova-calendario-eleitoral-e-regulamenta-uso-de-ia-nas-eleicoes-2026

### 5.1 Rotulagem de conteúdo sintético (art. 9º-B — origem 23.732/2024, reforçado 2026)

> Art. 9º-B. A utilização na propaganda eleitoral, em qualquer modalidade, de conteúdo sintético multimídia gerado por meio de inteligência artificial ou tecnologia equivalente para criar, substituir, omitir, mesclar ou alterar a velocidade ou sobrepor imagens ou sons, impõe ao responsável pela propaganda o dever de informar, de modo explícito, destacado e acessível, que o conteúdo foi fabricado ou manipulado e qual tecnologia foi utilizada.

**Janela de silêncio de deepfake pré/pós-pleito (§ 3º-A — 2026):**

> § 3º-A. Ficam vedadas a publicação e a republicação, ainda que gratuitas, bem como o impulsionamento pago de novos conteúdos sintéticos produzidos ou alterados por inteligência artificial ou por tecnologias equivalentes que utilizem imagem, voz ou manifestação de candidata ou candidato ou de pessoa pública, mesmo que rotulados e em conformidade com as demais exigências deste artigo, no período compreendido entre as 72 (setenta e duas) horas que antecedem e as 24 (vinte e quatro) horas que sucedem o término do pleito.

### 5.2 Vedações expressas (art. 9º-E, incisos V–VII — 2026)

> V - de divulgação ou compartilhamento de conteúdo sintético gerado ou modificado por inteligência artificial ou por tecnologia equivalente, em desacordo com as regras de rotulagem ou incidente nas vedações previstas nesta Resolução;  
> VI - de publicações que reproduzam, no todo ou em parte, conteúdo idêntico ou substancialmente equivalente àquele que já tenha sido objeto de ordem de indisponibilização pela Justiça Eleitoral [...];  
> VII - de violência política contra a mulher.

### 5.3 Inversão do ônus da prova em representação sobre IA (art. 9º-I — 2026)

> Art. 9º-I. Nas representações que versem sobre o uso de conteúdo sintético gerado por inteligência artificial ou por tecnologia equivalente que apurem violações aos arts. 9º-B, 9º-C, 9º-D e 9º-E desta Resolução, o juiz poderá, motivadamente, inverter o ônus da prova quando, em razão da dificuldade técnica de comprovação da manipulação digital, for excessivamente oneroso ao autor demonstrar a irregularidade do conteúdo.

### 5.4 Provedores de IA (art. 28, § 1º-C — 2026)

> § 1º-C. É vedado aos provedores de aplicação que ofertem sistemas de inteligência artificial ou por tecnologia equivalente, ainda que solicitado pela(o) usuária(o):  
> I - ranquear, recomendar, sugerir ou priorizar candidatas(os), campanhas, partidos políticos, federações ou coligações;  
> II - emitir opiniões, indicar preferência eleitoral, recomendar voto ou realizar qualquer forma de favorecimento ou desfavorecimento político-eleitoral [...];  
> III - criar ou promover alterações em fotografia, vídeo ou outro registro audiovisual que contenha cena de sexo, nudez ou pornografia envolvendo candidata ou candidato;  
> IV - formular publicidade eleitoral que represente ato de violência política contra a mulher.

### 5.5 Ciclo e armadilha

✅ Base **23.610/2019** + alteração municipal **23.732/2024** + alteração geral **23.755/2026**.  
🔴 Modelo treinado tende a citar só 23.610/2019 ou só regras 2022 → **errado para 2026**.

---

## 6. Prestação de contas / arrecadação e gastos — Res. 23.752/2026 (sobre 23.607/2019)

✅ Lido o texto da 23.752.  
URL: https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-752-de-26-de-fevereiro-de-2026

### 6.1 Pontos citáveis

**Contas parciais (art. 47, § 4º):**

> § 4º A prestação de contas parcial de campanha deve ser encaminhada por meio do Sistema de Prestação de Contas a que se refere o art. 54, pela internet, entre os dias 9 e 13 de setembro do ano eleitoral, dela constando o registro da movimentação financeira e/ou estimável em dinheiro ocorrida desde o início da campanha até o dia 8 de setembro do mesmo ano.

**Contas finais (art. 49):**

> Art. 49. As prestações de contas finais de candidatas e candidatos, bem como de partidos políticos, referentes ao primeiro turno, em todas as esferas, devem ser apresentadas à Justiça Eleitoral, por meio do Sistema de Prestação de Contas a que se refere o art. 54, até o 30º dia posterior à realização das eleições (Lei nº 9.504/1997, art. 29, III).

**Dispensa de recibo eleitoral em Pix e FEFC/FP (art. 7º, § 6º-A):**

> § 6º-A. É dispensada a emissão do recibo eleitoral nas seguintes hipóteses:  
> I - doações do Fundo Especial de Financiamento de Campanha e do Fundo Partidário por meio de transferência bancária efetuada pelo partido às candidatas e aos candidatos;  
> II - doações recebidas por meio de Pix por partidos, candidatas e candidatos.

**Cotação FEFC para mulheres / negros / indígenas (art. 17, § 4º e § 9º):**

> § 4º [...] II - para as candidaturas de pessoas negras, o percentual não poderá ser inferior a 30%.  
> II-A. - para as candidaturas de pessoas indígenas, o percentual corresponderá, no mínimo, à proporção de: a) mulheres indígenas e não indígenas do gênero feminino do partido; b) homens indígenas e não indígenas do gênero masculino do partido.  
> § 9º Os recursos correspondentes aos percentuais previstos no § 4º deste artigo devem ser distribuídos pelos partidos até **30 de agosto** do ano eleitoral.

🟡 **Ajuste posterior (notícia 03/08/2026):** o Plenário aprovou alterar o prazo de distribuição dos percentuais mínimos FEFC de “até 30 de agosto” para “**até 8 de setembro** do ano eleitoral”, e permitir transferência FEFC a majoritários de 2º turno até o 5º dia após o 1º turno. **Inteiro teor do ato formal de agosto: GAP DECLARADO** (não localizado número de resolução nova no índice `/res/2026` nesta captura). Para peça: preferir o texto consolidado da 23.607 **depois** de publicar o DJE do ato de agosto; até lá, a 23.752 diz **30 de agosto** ✅ e a notícia de 03/08 é 🟡.

**Gasto com violência política / segurança (art. 35, XVI):**

> XVI - despesas com prevenção, repressão e combate à violência política, bem como com a contratação de segurança para proteção de candidatas e de candidatos, observadas, no que couberem, as disposições da Lei nº 14.967/2024.

---

## 7. FEFC — Res. 23.749/2026 (sobre 23.605/2019)

✅ Lido.  
URL: https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-749-de-26-de-fevereiro-de-2026

> Art. 4º No âmbito do TSE, a Secretaria de Planejamento, Orçamento, Finanças e Contabilidade (SOF) será responsável pela distribuição dos recursos aos diretórios nacionais dos partidos políticos.

> Art. 6º [...] § 7º A verba do Fundo Especial de Financiamento de Campanha (FEFC) destinada ao custeio das candidaturas de mulheres, pessoas negras e indígenas deve ser aplicada exclusivamente nessas campanhas, sendo ilícito seu emprego no financiamento de outras campanhas não contempladas nas cotas a que se destinam.

Art. 2º: **revoga** na 23.605/2019 o § 1º do art. 6º e os arts. 10 e 11.

---

## 8. Limites de gastos — Res. 23.766/2026 + Portaria 449/2026

✅ Lido.  
URL: https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-766-de-1o-de-julho-de-2026

> Art. 1º O limite de gastos para os cargos eletivos em disputa nas eleições de 2026 será aquele adotado nas eleições gerais de 2022.  
> § 1º Na hipótese de realização de segundo turno, o limite de gastos dos cargos majoritários em disputa será acrescido de 50% (cinquenta por cento) do teto de gastos fixado para o primeiro turno.  
> § 2º Os valores serão divulgados por portaria da Presidência do Tribunal Superior Eleitoral, cuja publicação deverá ocorrer até o dia 20 de julho de 2026 [...].

✅ Remissão na própria página: **Portaria nº 449/2026** (20/07/2026) divulga os valores.  
URL: https://www.tse.jus.br/legislacao/compilada/prt/2026/portaria-no-449-de-20-de-julho-de-2026  
🟡 Inteiro teor da Portaria 449 (tabela de valores por cargo/UF) **não lido** nesta frente — só a existência e o vínculo.

---

## 9. Pesquisas eleitorais — Res. 23.747/2026 (sobre 23.600/2019)

✅ Lido.  
URL: https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-747-de-26-de-fevereiro-de-2026

> Art. 2º A partir de 1º de janeiro do ano da eleição, as entidades e as empresas que realizarem pesquisas de opinião pública são obrigadas, para cada pesquisa, a registrar, no Sistema de Registro de Pesquisas Eleitorais (PesqEle), até 5 (cinco) dias antes da divulgação [...]

Novidades 2026 (entre outras): declaração do estatístico (inciso IX), consultas populares no escopo (art. 1º), delimitação geográfica/setores censitários (§§ 7º-E/F), prazo adicional de 3 dias para complementação sob pena de “não registrada” (§§ 7º-C/D).

> Art. 3º A partir da publicação dos editais de registro, os nomes das candidatas e dos candidatos cujo registro tenha sido requerido deverão constar da lista apresentada às pessoas entrevistadas durante a realização das pesquisas.

> Art. 23. É vedada, após o dia 15 de agosto do ano da eleição, a realização de enquetes relacionadas ao respectivo processo eleitoral. (Lei nº 9.504/1997, art. 36, caput).

---

## 10. Representações — Res. 23.756/2026 (sobre 23.608/2019)

✅ Lido.  
URL: https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-756-de-2-de-marco-de-2026

**Definição de representações especiais (art. 44):**

> Art. 44. Para os fins desta resolução, consideram-se representações especiais aquelas cuja causa de pedir corresponda às hipóteses previstas nos arts. 23, 30-A, 41-A, 45, VI e § 1º, 73, 74, 75 e 77 da Lei nº 9.504/1997, às quais se aplicará o procedimento do art. 22 da Lei Complementar nº 64/1990 e, supletiva e subsidiariamente, o Código de Processo Civil.

**Prazos contínuos (art. 7º):**

> Art. 7º Os prazos relativos a representações fundadas no art. 96 da Lei nº 9.504/1997, reclamações administrativas eleitorais e pedidos de direito de resposta são contínuos e peremptórios [...] entre 15 de agosto do ano da eleição e as datas fixadas no calendário eleitoral [...].  
> § 2º Às representações especiais [...] não se aplicam as disposições do caput deste artigo.

---

## 11. Ilícitos — Res. 23.757/2026 (sobre 23.735/2024)

✅ Lido.  
URL: https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-757-de-2-de-marco-de-2026

> Art. 2º As medidas para o enfrentamento da desinformação que atente contra a integridade do processo eleitoral serão realizadas nos termos da legislação de regência e de resolução deste Tribunal Superior.

> Art. 6º [...] § 4º A utilização da internet, inclusive serviços de mensageria, para difundir informações falsas ou descontextualizadas em prejuízo de adversária(o) ou em benefício de candidata(o), ou a respeito do sistema eletrônico de votação e da Justiça Eleitoral, assim como o uso de conteúdo sintético gerado ou modificado por inteligência artificial ou tecnologias equivalentes em violação às normas eleitorais, configura uso indevido dos meios de comunicação e, pelas circunstâncias do caso, também abuso dos poderes político e econômico.

---

## 12. Atos gerais — Res. 23.751/2026 (datas do pleito)

✅ Lido trecho inicial e ementa.  
URL: https://www.tse.jus.br/legislacao/compilada/res/2026/resolucao-no-23-751-de-26-de-fevereiro-de-2026

> Art. 2º Serão realizadas, simultaneamente, em todo o país, em **4 de outubro de 2026**, no primeiro turno, e em **25 de outubro de 2026**, no segundo turno, onde houver, por sufrágio universal e por voto direto e secreto, eleições para os cargos de Presidente e Vice-Presidente da República, Governador e Vice-Governador de Estado e do Distrito Federal, Senador, Deputado Federal, Estadual e Distrital [...].

🟡 Corpo completo (200+ arts.) não foi lido linha a linha nesta frente; datas de votação e ementa estão ✅.

---

## 13. GAPS DECLARADOS

1. **Inteiro teor da Portaria TSE nº 449/2026** (tabela de limites de gastos por cargo/UF) — existência ✅; valores 🟡/GAP para citação numérica.  
2. **Ato formal (número de resolução/portaria) das alterações pontuais de 03/08/2026** (FEFC 30/08→08/09; auditoria art. 66; redação calendário plantão) — notícia TSE ✅/🟡; texto normativo no DJE **não aberto**.  
3. **Texto consolidado “compilado”** das bases 23.609/23.610/23.607 **já com** todas as alterações 2026 embutidas — o site oferece abas “Texto consolidado / compilado”; usei as resoluções **alteradoras** de 2026 lidas ✅; consolidado HTML não varrido artigo por artigo.  
4. **Corpos inteiros** de Res. 23.748, 23.750, 23.753, 23.758, 23.759 — ementa e links ✅; leitura integral 🟡.  
5. **CE art. 105 “vigente”** — **não existe** (revogado); o brief pedia CE 105; a norma correta é **Lei 9.504 art. 105** (✅).  
6. **Mapeamento 1:1 “qual resolução de 2022 esta 2026 revogou”** para peças autônomas (calendário 2022, atos gerais 2022) — os números antigos **não foram abertos** nesta frente; o hub 2026 lista a base **2019/2021/2024**, não republica “substitui a Res. X/2022”. GAP: número exato do calendário 2022/2024 substituído pela 23.760.  
7. **Deepfake** como *verbum* isolado no dispositivo — a resolução fala em **“conteúdo sintético”** / IA / tecnologia equivalente; a proibição de deepfake é efeito da regulação de conteúdo sintético + notícias TSE. Não inventar inciso que diga só “deepfake”.

---

## 14. ARMADILHAS (onde o modelo treinado erra neste ramo)

1. **Citar CE art. 105** como prazo das instruções → artigo **revogado** (Lei 14.211/2021). O correto é **Lei 9.504/1997 art. 105 + § 3º**.  
2. **Citar Res. 23.609/2019 ou 23.610/2019 “puras”** sem as alterações **23.754/2026** e **23.755/2026** (e, em propaganda, sem 23.732/2024).  
3. **Reaproveitar calendário 2022/2024** (datas de convenção, registro, 1º/2º turno). Em 2026: convenções **20/07–05/08**; registro **15/08 19h**; 1º turno **04/10**; 2º **25/10**.  
4. **Prazo FEFC 30 de agosto** vs **8 de setembro** (ajuste plenário 03/08/2026) — risco de citar o prazo antigo depois da publicação do ato de agosto.  
5. **Limites de gastos “atualizados IPCA 2024”** — a 23.766 manda usar o **mesmo teto de 2022** (+50% no 2º turno majoritário).  
6. **Confundir “14 resoluções do pacote”** com todas as Res. no índice `/res/2026` (há também resoluções internas de cargos, PSI, etc., 23.761–23.765, fora do pacote eleitoral).  
7. **Tratar base 2019 como “morta”** — ela continua a **norma principal**; 2026 é **alteração**, não reescrita completa com novo número.  
8. **RDE** (LC 219/2025 + art. 9º-B da 23.609 via 23.754) — inexistente em treinos pré-2025; extingue se não houver registro até 15/08.

---

## 15. O QUE MUDOU RECENTEMENTE (treino 2025 / início 2026 provavelmente não tem)

| Mudança | Quando | Fonte | Selo |
|---|---|---|---|
| Pacote 14 resoluções Eleições 2026 | fev–mar/2026, DJE 04/03/2026 | Notícia + índice TSE | ✅ |
| Regulamentação reforçada de **IA / conteúdo sintético** + inversão de ônus + vedações a provedores de IA | Res. **23.755/2026** | Texto lido | ✅ |
| **RDE** no registro (LC 219/2025 operacionalizada) | Res. **23.754/2026** art. 9º-B | Texto lido | ✅ |
| Aferição elegibilidade até diplomação (art. 26-D LC 64 / LC 219) | Res. **23.754** art. 52 | Texto lido | ✅ |
| Idade mínima por Lei **15.230/2025** | Res. **23.754** art. 9º §2º | Texto lido | ✅ |
| Contas: Pix sem recibo; segurança/violência política como gasto; cotas indígenas FEFC | Res. **23.752/2026** | Texto lido | ✅ |
| Limites de gasto = **2022** | Res. **23.766/2026** (01/07) + Port. 449/2026 | Texto lido | ✅ |
| Ajustes pontuais FEFC/auditoria/calendário | Plenário **03/08/2026** | Notícia TSE | 🟡 |
| Programa **Seu Voto Importa** (transporte especial) | Res. **23.753/2026** | Ementa | ✅/🟡 |
| Consolidação normas ao cidadão | Res. **23.759/2026** | Ementa | ✅/🟡 |

---
