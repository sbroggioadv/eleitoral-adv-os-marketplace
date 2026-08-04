---
name: condicoes-de-elegibilidade
description: "CF art. 14 §3o item a item; distincao rigida condicao x inelegibilidade; idade por cargo (Lei 9.504 art. 11 §2o Lei 15.230). Afericao LC 64 art. 26-D. Use quando disser condicao de elegibilidade, idade minima, filiacao, domicilio eleitoral, nacionalidade, direitos politicos, falta de condicao no registro ou RCED."
---

> **Escolhas = botoes:** cargo pretendido · *falta de condicao* · *confusao com inelegibilidade*.

# CONDICOES-DE-ELEGIBILIDADE

> Camada C2. Requisitos **positivos** do CF art. 14, §3o. Confundir com inelegibilidade (impedimento) **destroi** AIRC e RCED.

## Anexos obrigatorios (context/)
- `context/cf-14-elegibilidade.md` — §3o I-VI; tabela condicao x inelegibilidade; art. 26-D — **grep + ler**.
- `context/lei-9504-destaques.md` — art. 11 §1o (docs) e §2o (idade Lei 15.230) — **grep + ler**.
- `context/lc-64-ficha-limpa.md` — art. 26-D; armadilha condicao x inelegibilidade — **grep + ler**.
- `context/contencioso-eleitoral-vias.md` — AIRC/RCED por falta de condicao — **grep + ler**.
- `context/metodologia-eleitoral.md` — **grep + ler**.

## Distincao fundante (sempre no preambulo da peca)

| | Condicao de elegibilidade | Inelegibilidade |
|---|---|---|
| Natureza | Requisito **positivo** que o candidato **deve preencher** | Causa **impeditiva** que **incide** |
| Fonte | CF art. 14, **§3o** (+ lei na forma da lei) | CF art. 14, **§§4o-9o** + **LC 64** art. 1o |
| Efeito no registro | Indeferimento por **ausencia de requisito** | Indeferimento por **causa impeditiva** |
| Afericao 2026 | LC 64 **art. 26-D** (registro + superveniente favoravel ate diplomacao) | Idem 26-D |

**Proibido** fundar AIRC/RCED "por ficha limpa" usando so o §3o, ou o inverso.

## Rol CF art. 14, §3o (verbatim-ancorado)
I — nacionalidade brasileira  
II — pleno exercicio dos direitos politicos  
III — alistamento eleitoral  
IV — domicilio eleitoral na circumscricao  
V — filiacao partidaria  
VI — idade minima:
- **a)** 35 anos — Presidente, Vice, Senador  
- **b)** 30 anos — Governador e Vice (Estado/DF)  
- **c)** 21 anos — Dep. Federal/Estadual/Distrital, Prefeito, Vice, juiz de paz  
- **d)** 18 anos — Vereador  

**Direitos politicos (contexto do II):** CF art. 15 — vedada cassacao; perda/suspensao so nos incisos I-V do art. 15 (ler `cf-14-elegibilidade.md`). Nao inventar hipotese.

## Idade — marco de afericao (Lei 15.230/2025)
**Lei 9.504/1997, art. 11, §2o** (redacao Lei 15.230/2025):
- **I** — data da **posse** — cargos do **Poder Executivo**;
- **II** — data-limite do **pedido de registro** — **Camaras Municipais**;
- **III** — **posse presumida** (ate 90 dias da eleicao da Mesa Diretora) — demais Casas Legislativas; vedadas reducoes/prorrogacoes regimentais para esse fim.

**Erro de treino:** devolver "sempre na data da posse" para vereador/deputado. **Conferir cargo → inciso.**

## Documentos que provam a condicao (ponte registro)
Checklist do art. 11 §1o em `rrc-drap-dce-registro` (titulo/certidao, filiacao, quitacao, etc.). Falta documental pode ser **diligencia 72h** (art. 11 §3o) — 🔴 **GAP** do *dies a quo* operacional: o corpus so diz que o juiz "abrira prazo de setenta e duas horas"; **nao** sela "da intimacao" sem fonte integral — confira texto/autos. Nao e "inelegibilidade".

## Afericao e superveniencia
- **Vivo:** LC 64 art. **26-D** — condicoes **e** causas aferidas na formalizacao do registro; reconhecimento de alteracoes que afastem/extinguam inelegibilidade ate diplomacao.
- **Morto:** Lei 9.504 art. 11 **§10** revogado pela LC 219/2025.
- ⚠️ **PENDENTE — Súmula 70 × LC 64 art. 26-D:** declarar a tensao (detalhe em `defesa-em-inelegibilidade`); nao usar §10 como base nem "escolher lado".

## Lado dual
- **Move (AIRC/RCED por falta de condicao):** provar ausencia de I-VI no marco legal; dies a quo da via (`airc` 5d edital/pedido; `rced` 3d apos ultimo dia limite da diplomacao — CE art. 262).
- **Responde:** provar preenchimento no marco (idade com inciso correto; filiacao e domicilio na circumscricao; direitos politicos); atacar confusao com alinea de Ficha Limpa.

## Inelegibilidades constitucionais (contraste — nao sao §3o)
§4o inalistaveis/analfabetos · §5o reeleicao executivo · §6o renuncia 6 meses · §7o parentesco (SV 18) · §8o militar · §9o remete a LC. Detalhe de alinea LC 64 = `ficha-limpa-e-inelegibilidades` / `defesa-em-inelegibilidade`.

## Metodologia
1. Cargo → quais incisos do §3o e qual marco de idade.
2. Separar: falta de condicao x incidencia de inelegibilidade.
3. Grep CF + art. 11 §2o + 26-D.
4. Via processual: registro (`airc` / `rrc`) ou diploma (`rced-contra-diploma`).
5. Fechar por `suprema-corte-eleitoral` + `validador-eleitoral`.

## Entrega obrigatoria final
(a) cargo; (b) checklist §3o I-VI com status; (c) idade com inciso do art. 11 §2o; (d) se a tese e condicao ou inelegibilidade; (e) via e dies a quo; (f) docs faltantes.

## Guard
Nunca misturar §3o com art. 1o LC 64. Nunca idade "sempre na posse". Nunca §10 da 9.504 vigente. Nunca SV 18 ao contrario. Fecha por `suprema-corte-eleitoral` + `validador-eleitoral`.
