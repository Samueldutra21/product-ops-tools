# Template: Framework de Priorização (pontuação ponderada + custo do atraso)

> Uso: acordar critérios de trade-off entre PMs, engenharia, UX e stakeholders e levá-los para a pauta dos fóruns de governança.
> O livro recomenda **combinar weighted scoring e cost of delay** nos níveis de portfólio e de produto, mas não detalha fórmulas. As fórmulas abaixo são **complemento** (prática comum de mercado, ex.: WSJF/SAFe). O que importa é o **acordo** sobre o framework.

## 1. Regras do jogo (acordar antes de pontuar)
- Toda nova demanda entra **no lugar de** algo: cultura "isto ou aquilo", não "sim, e também".
- Critérios e pesos são aprovados em [fórum] e revistos a cada [trimestre].
- Pontuação feita por [quem], com evidência (dados, pesquisa, sizing), não por opinião.
- Quem pede recebe o resultado e o critério, inclusive quando a resposta é não.

## 2. Pontuação ponderada (alinhamento estratégico)
| Critério | Peso | Escala (1, 3, 5, 8, 13) e guia |
|---|---|---|
| Contribuição para a intenção estratégica / OKR | 30% | |
| Valor ao cliente (dor validada, alcance) | 25% | |
| Impacto financeiro (receita, custo, risco) | 25% | |
| Confiança na evidência | 10% | |
| Habilita outras iniciativas (plataforma) | 10% | |

## 3. Custo do atraso (urgência econômica)
Custo do atraso = valor ao negócio + criticidade de tempo + redução de risco ou habilitação de oportunidade
**Prioridade (WSJF) = custo do atraso ÷ tamanho (esforço)**

| Item | Valor (1-13) | Tempo (1-13) | Risco/oport. (1-13) | CoD | Esforço (1-13) | WSJF | Score ponderado | Decisão |
|---|---|---|---|---|---|---|---|---|

## 4. Leitura
- **Alto score ponderado + alto WSJF:** prioridade.
- **Alto score ponderado + baixo WSJF:** importante, mas pode esperar ou deve ser fatiado.
- **Baixo score ponderado + alto WSJF:** urgente e pouco estratégico; questione ou faça um corte mínimo.
- Discordâncias vão para o fórum com os critérios na mesa, não para escalação.

## 5. Sinais de que o framework não está funcionando
Tudo "8 ou 13" · itens que furam a fila sem passar pelo framework · pontuação sem evidência · times espalhados em muitas frentes ("peanut butter").
