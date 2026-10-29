# Template: Alocação de P&D por Tema (sem timesheet)

> Uso: dar visibilidade de onde vai o esforço de engenharia e confrontá-lo com a estratégia. Base: `references/pilar-1-dados-insights.md`, seções 6 e 9.

## 1. Buckets (definições acordadas com engenharia)
| Bucket | Inclui | Não inclui |
|---|---|---|
| Estratégico / inovação | Trabalho ligado a iniciativas e OKRs | |
| Dívida técnica e plataforma | Refatoração, performance, plataforma | Bugs de cliente (vão em Bugs) |
| BAU / KLO | Operação, suporte, manutenção, compliance recorrente | |
| Bugs | Correções de defeitos | |

*(Opcional, para capitalização: mapear cada bucket para capitalizar ou lançar como despesa com Finanças.)*

## 2. Coleta semanal (tech lead, 5 minutos)
| Semana | Time | Estratégico % | Dívida % | BAU % | Bugs % | Observação |
|---|---|---|---|---|---|---|

Regras: percentuais agregados do time, não por pessoa · sem punição por número "feio" · revisar a classificação no 1º mês (é comum mascarar bugs como dívida).

## 3. Leitura mensal
| Time / portfólio | Estratégico real × alvo | Tendência | Métrica de produto correspondente | Leitura |
|---|---|---|---|---|

**Perguntas:** o esforço estratégico está nos produtos e segmentos que a estratégia prioriza? Bugs altos indicam pressão por velocidade e qualidade baixa? O investimento está movendo as métricas de produto e de negócio?

## 4. Sinais de alerta e decisões típicas
- Estratégico abaixo do alvo acordado por vários meses → rever compromissos e capacidade *(o livro não fixa um percentual; defina o alvo com a liderança)*
- Bugs e dívida dominando → considerar um trimestre de estabilidade (caso Pipeline 3K)
- Alocação alta em produto com uso ou receita em queda → discutir descontinuação

## 5. Cálculo de capitalização (se aplicável)
Custo mensal do time × % alocado a projetos capitalizáveis × (1 − % manutenção) = valor capitalizado
Ex.: $100 mil × 50% × (1 − 50%) = $25 mil
