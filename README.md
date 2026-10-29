# product-operations (skill)

Base de conhecimento e playbooks práticos de **Product Operations**, construída a partir do livro *Product Operations: How Successful Companies Build Better Products at Scale* (Melissa Perri & Denise Tilles, 2023), em PT-BR e com escrita executiva.

## Como instalar
- **Claude (app):** em Configurações → Capacidades → Skills, faça upload do arquivo `product-operations.skill` (ou de um .zip desta pasta).
- **Claude Code:** copie a pasta para `~/.claude/skills/product-operations/` (pessoal) ou `.claude/skills/product-operations/` (projeto).

## Como foi desenhada (otimizada para janela de contexto)
- `SKILL.md` (cerca de 2 mil tokens) é só o **roteador**: postura, modelo mental, tabela "pedido → arquivo", fluxos de trabalho e antipadrões.
- `references/` (de 1 a 4 mil tokens cada) é carregado **sob demanda**; cada arquivo abre com "Quando ler" e um sumário.
- `templates/` (de 200 a 900 tokens cada) traz entregáveis preenchíveis que a skill usa como ponto de partida.

## Estrutura
| Pasta | Conteúdo |
|---|---|
| `references/fundamentos.md` | Definição, 3 pilares, PM × ProdOps, ecossistema de Ops |
| `references/pilar-1-dados-insights.md` | Cascata de estratégia, métricas, instrumentação, alocação de P&D, baseline, dashboards, capitalização |
| `references/pilar-2-cliente-mercado.md` | Voz do cliente, pesquisa, repositório, democratização, TAM/SAM/SOM, concorrência |
| `references/pilar-3a-governanca-planejamento.md` | Operating model, governança, cadências, priorização, planejamento anual (Oscar) |
| `references/pilar-3b-processos-ferramentas.md` | Ideias, roadmaps por audiência, status Discovery→GA, toolkits, onboarding, CoP, ferramentas |
| `references/implantacao-buy-in.md` | Por onde começar, business case, objeções, stakeholders, primeiros 60 dias |
| `references/estruturar-escalar.md` | Time de um a função madura, perfis, modelos de organização, métricas de sucesso |
| `references/licoes-e-roteiros.md` | 5 lições, checklist de antipadrões, roteiros de implantação e evolução |
| `references/casos.md` | athenahealth, Fidelity, Oscar, Amplitude, Uber, Stripe, Pendo e outros |
| `references/glossario.md` | Siglas e termos |
| `templates/` | 21 templates práticos |

## Notas
- Conteúdo parafraseado e organizado para uso prático; não substitui a leitura do livro.
- Trechos marcados como **complemento** (ex.: fórmulas de WSJF, ponte com a cadeia de indicadores de Diego Eis) não vêm do livro.
