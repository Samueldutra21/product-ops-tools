# Template: Especificação de Dashboards (baseline manual → automação)

> Uso: desenhar os dashboards de time de produto e executivo antes de construir. Base: `references/pilar-1-dados-insights.md`, seções 2, 7 e 8.

## 1. Perguntas que o dashboard responde
| Nível | Pergunta | Decisão que ela informa | Público |
|---|---|---|---|
| Intenção estratégica | | | Executivos |
| Iniciativa | | | Líderes de produto |
| Opção | | | Times |

## 2. Métricas → fontes
| Métrica | Definição exata | Segmentação (produto, segmento, coorte, geografia) | Fonte (sistema) | Dono do dado | Frequência | Leading/lagging |
|---|---|---|---|---|---|---|

## 3. Dashboard do time de produto
- [ ] Roadmap por feature/opção (Agora / Próximo / Depois), com status e responsável (nome)
- [ ] Uso e adoção por persona, por feature
- [ ] Progresso dos KPIs por opção → meta da iniciativa
- [ ] Progresso das metas de receita por produto
- [ ] Métricas projetadas para os itens perto do lançamento
- ✗ Não incluir velocity e métricas de projeto

## 4. Dashboard executivo e de board
- [ ] Roadmap de alto nível por intenção estratégica (Agora / Próximo / Depois)
- [ ] ARR por segmento e por produto
- [ ] Ponte de receita por iniciativa e produto
- [ ] Bookings por produto
- [ ] Receita e P&D: meta × real
- [ ] Alocação por portfólio e por tipo (estratégico, dívida técnica, bugs, KLO)
- [ ] Dívida de vendas, dívida técnica e visão de custo
- [ ] Alinhamento às prioridades: farol (atinge / risco baixo a moderado / alto risco) + racional

## 5. Higiene
- [ ] Nomes de responsáveis visíveis
- [ ] Todo time com seu trabalho representado
- [ ] Período compatível com a cadência da reunião em que é usado
- [ ] Definição de cada métrica acessível (dicionário)

## 6. Plano baseline manual → automação
| Etapa | Critério de saída | Prazo |
|---|---|---|
| Mockups acordados com os usuários | Aprovação dos usuários-chave | |
| Ciclo manual 1 | Dados extraídos e conferidos | |
| Ciclos manuais 2 e 3 | Métricas estáveis e úteis | |
| Regras de tagueamento na fonte | Dados capturados corretamente nos sistemas | |
| BI automatizado (fonte única de verdade) | Atualização sem trabalho manual | |
| Refinamento (4 a 6 meses) | Uso recorrente nos fóruns | |
| Revisão trimestral | Métrica não acionável é removida | |
