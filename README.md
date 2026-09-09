# Defesa e qualificação: como se preparar (MirandasTech)

Manual em formato de slides (44) para o exame de qualificação e a defesa de dissertação ou tese: o que a Resolução CNE/CES 7/2017 fixa e o que fica com o regimento do programa (tempos, banca, arguição, prazos, formatos), com cinco regimentos públicos lado a lado como exemplos; o texto antes da banca; a apresentação com roteiro por bloco e tempo (`apresentacao_defesa.py`, Beamer compilado de verdade), Beamer, Impress e Apresentações Google; ensaios cronometrados (`ensaio_defesa.py`), banca simulada e como responder; checklist antes, no dia e depois (`checklist_defesa.py`), ata, correções, versão final e depósito; erros comuns, checklist, glossário com popovers e referências. Capturas reais e datadas (09/09/2026) sem login; nenhuma sessão de defesa foi gravada; o regimento do programa do leitor prevalece.

**Manual on-line:** https://defesa.mirandastech.com.br/ · **PDF:** https://defesa.mirandastech.com.br/manual.pdf

Manuais irmãos: **Ciência aberta** — https://cienciaaberta.mirandastech.com.br/ · **Bibliometria** — https://bibliometria.mirandastech.com.br/ · **Análise de dados** — https://dados.mirandastech.com.br/ · **Git e GitHub** — https://git.mirandastech.com.br/ · **LaTeX** — https://latex.mirandastech.com.br/ · **Busca em bases** — https://busca.mirandastech.com.br/ · **Revisão sistemática com PRISMA 2020** — https://prisma.mirandastech.com.br/ · **Zotero** — https://zotero.mirandastech.com.br/ · **Metodologia** — https://metodologia.mirandastech.com.br/ · **Gemini Notebook** — https://notebook.mirandastech.com.br/ · **Uso de IA na pesquisa** — https://manual.mirandastech.com.br/ · **Plugin Pesquisa** — https://plugin.mirandastech.com.br/ · Hub: https://www.mirandastech.com.br/pesquisa

| Pasta | O que há |
|---|---|
| `manual/` | deck HTML autônomo, PDF, fonte do artefato e `fatos_verificados.md` (fontes e execuções conferidas em 09/09/2026) |
| `site/` | o que o servidor serve (`index.html`, `manual.pdf`) |
| `capturas/` | 18 capturas reais, 09/09/2026 (páginas públicas de programas e órgãos; Beamer compilado; 2 figuras de terminal com saídas reais) |
| `scripts/apresentacao_defesa.py` | esqueleto Beamer com um frame por bloco, tempo previsto e nota do apresentador; compila com latexmk |
| `scripts/ensaio_defesa.py` | cronômetro de ensaio por bloco com diferença para o previsto e CSV |
| `scripts/checklist_defesa.py` | checklist antes/no dia/depois com datas sugeridas e coluna para o prazo do regimento |
| `scripts/gerar_deck.py` | regenera HTML e PDF a partir do fonte |
| `skills/defesa-qualificacao/` | skill do agente (cópia sincronizada do plugin Pesquisa MirandasTech) |
| `Dockerfile` · `Caddyfile` · `railway.json` | deploy estático (Caddy) |
| `.github/workflows/verificar.yml` | CI: integridade do deck e capturas referenciadas |

## Os manuais juntos
Este manual cobre a **banca**: o texto vem dos manuais de Metodologia, LaTeX e Análise de dados; as objeções vêm da skill `banca-simulada`; depois da defesa entram o Git (versão final) e a Ciência aberta (depósito com DOI). No plugin **Pesquisa MirandasTech**, a skill `defesa-qualificacao` organiza roteiro, ensaios e checklist; o aluno apresenta e decide.

## Como citar
MATIAS, J. P. M. *Defesa e qualificação: como se preparar.* MirandasTech, v1.0, set. 2026. CC BY 4.0.

## Declaração de uso de IA
Escrito com assistência de IA (Claude, Anthropic) na estruturação, redação, automação das capturas e execução dos scripts. Fatos conferidos em páginas públicas em 09/09/2026 (lista em `manual/fatos_verificados.md`); nenhuma captura com login; os regimentos citados são exemplos e o do programa do leitor prevalece. O autor responde integralmente pelo conteúdo. CAPES, MEC/CNE, IBICT, as universidades citadas, CTAN/Beamer, Overleaf, The Document Foundation, Google, Vitae e os demais serviços citados são marcas, órgãos e projetos de terceiros; este manual não tem vínculo com eles.