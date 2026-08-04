---
name: lei-dos-partidos-base
description: "Fundacao da Lei 9.096/1995 no corpus: estrutura (criacao, fusao, incorporacao, federacao), filiacao e prazo minimo, fidelidade, fundo partidario (arts. 38-44), contas anuais (arts. 30-37) e janela (art. 22-A). Nao redige peca: sustenta C6 e cruzamentos com registro. Use antes de skill partidaria ou de filiacao/domicilio, ou quando disserem fundo partidario, desfiliacao, federacao, contas anuais do partido, janela partidaria."
---

# LEI-DOS-PARTIDOS-BASE — Fundacao Lei 9.096/1995

> Camada 1. Mapa estrutural da Lei dos Partidos **como no corpus**. Nao redige peca de C6: entrega o endereco normativo.

## Quando ativa / trilha
Antes de C6 (partidario), `filiacao-domicilio-e-janela`, `fundo-partidario-regime`, contas anuais, e quando o registro exige filiacao (CF 14 §3o IV-V + 9.096).

## Anexos obrigatorios (context/)
- `context/lei-9096-partidos.md` — compilado / estrutura / filiacao / fundo — **grep o artigo e leia a faixa**.
- `context/contas-e-fefc-2026.md` §5 — contas anuais 30-37 — **grep + faixa**.
- `context/calendario-eleitoral-2026.md` — janela migracao 5 mar–3 abr (art. 22-A, III) — **grep + faixa**.
- `context/cf-14-elegibilidade.md` — filiacao e domicilio como condicao — **grep + faixa**.

## Base legal ancorada

### Estrutura e organizacao
- ✅ Lei 9.096: criacao, funcionamento, fusao, incorporacao; federacao no regime do compilado (grep arts. de federacao no anexo — ex. desfiliacao de partido que integra federacao).
- ✅ Estatutos: filiacao/desligamento, direitos/deveres, **fidelidade e disciplina** (materias de estatuto no inventario do anexo).
- 🟡 ADI 6.230 e outras anotacoes "Vide ADI" no compilado — citar so o que o anexo marca ✅; ADI pendente/nao lida = 🟡.

### Filiacao (nucleo do registro)
- ✅ **Art. 16**: so se filia eleitor no pleno gozo dos direitos politicos.
- ✅ **Art. 17**: filiacao considerada deferida nos termos do texto; comprovante ao filiado.
- ⛔ **Art. 18** ("pelo menos um ano" de filiacao para candidatura) — **REVOGADO pela Lei 13.165/2015**. **Proibido** ressuscitar. Marco 2026 de filiacao/domicilio: **4 de abril** (calendario-eleitoral-2026.md / 6 meses antes do 1o turno) — grepar calendario, nao o art. 18.
- ✅ **Art. 19** (e redacoes vizinhas no compilado): relacao de filiados a JE; insercao no sistema eletronico; ciencia em mudanca de partido de filiado eleito.
- ⛔ Nao inventar prazo de "janela" fora do texto: calendario 2026 cita janela **5 mar – 3 abr** para dep. fed./est./distr. com justa causa **art. 22-A, III**, Lei 9.096 — grepar calendario + anexo.

### Contas anuais (estrutura)
- ✅ **Arts. 30–37** — dever de prestacao de contas anuais do partido (detalhe em `contas-e-fefc-2026.md` §5).
- 🟡 Res. 23.604 (contas partidarias) — se o corpus marca inteiro teor parcial, skill de peca carrega ressalva 🟡.

### Fundo partidario
- ✅ **Arts. 38–44** — destinacao, quotas, vedacoes (grep faixa).
- Cruzar **Lei 9.504 art. 25** e cotas FEFC/FP em `contas-e-fefc-2026.md` quando a peca misturar campanha e partido.
- Sancoes por contas irregulares: devolver ao anexo de contas + skill `fundo-partidario-regime` / `defesa-contas-desaprovadas`.

### Fidelidade
- ✅ Deveres de fidelidade/disciplina no estatuto e dispositivos do compilado (grep "fidelidade").
- ⛔ Nao inventar sumula ou tese de perda de mandato por infidelidade **sem** ancora ✅ no corpus — se nao estiver no anexo, **GAP / checar ao vivo**.

## Passo a passo / o que produzir
1. Classificar: filiacao · janela · criacao/fusao/federacao · fundo · contas anuais · fidelidade.
2. Grep + ler faixa em `lei-9096-partidos.md` (e contas se aplicavel).
3. Entregar quadro: dispositivo · efeito · ponte C6 / registro.

## Postura honesta
- Compilado Planalto e longo: **nunca** despejar o anexo; so a faixa.
- Ultima alteracao anotada no HTML do corpus pode nao cobrir 2023–2026 alem do marcado — se a peca depender de reforma recente nao listada, **CHECAR AO VIVO**.
- Contas anuais Res. 23.604 🟡 quando o corpus assim marcar.

## Cross-link e fechamento
C6 skills operacionais. Registro/filiacao → `condicoes-de-elegibilidade` + `rrc-drap-dce-registro`. Fundo/FEFC → C5. Gates: Suprema Corte + validador.
