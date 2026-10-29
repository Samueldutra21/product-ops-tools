# Lições Aprendidas e Roteiros de Implantação

> **Quando ler:** para checar armadilhas antes de propor algo, montar o roteiro de implantação (do zero) ou de evolução (função existente), ou fazer uma revisão crítica de uma iniciativa de ProdOps.

## 1. As 5 lições aprendidas

| Lição | Essência | Como aplicar |
|---|---|---|
| **1. Garanta apoio executivo** | Gerenciar para cima é o nome do jogo; ProdOps trabalha para a organização inteira, não só para produto | Mostre ProdOps informando e monitorando estratégia nas reuniões executivas; mantenha CFO e CEO no circuito; "mesmo lado, mesmo objetivo: otimizar recursos para crescer" (Christine Mullin, Texthelp); antecipe recessões embutindo ProdOps no fluxo de construção |
| **2. Cultura conta** | O aspecto cultural pesa tanto quanto o técnico (Helmut Stueber, Tricentis) | Listening tour amplo (Tina Laungani falou com mais de 80 pessoas na Segment, apresentando o charter); líderes devem **usar** os dados de ProdOps de forma repetível (QBRs, planejamento); resolva rápido tensões com PMs ou Sales Ops (crie um conselho de operações); roadshow; narrativa consistente e repetida; caminhos claros para cada área contribuir |
| **3. Foque em todos os dados** | Engajamento sozinho não diz o impacto no negócio | Ligue uso a receita, churn e custo; cruze com insights de cliente e mercado; toda decisão vira decisão de ROI, não emocional |
| **4. Chegue ao impacto rápido** | ProdOps é centro de custo; precisa provar valor sempre | Quick wins nas dores mais agudas; diga não; não copie "boas práticas" de curso ou de outra empresa sem atacar a dor real; mostre como os quick wins constroem a visão |
| **5. Equilibre processo e agilidade** | Formas de trabalho para fazer o trabalho, não processo pelo processo | Princípios > regras; coaching quando o time não consegue aplicar; revisão trimestral de processos e ferramentas; "se não revisita, espere que quebre" |

## 2. Checklist de antipadrões
Use como revisão crítica de qualquer proposta:
- [ ] A proposta ataca uma dor validada (listening tour) ou é "boa prática" importada?
- [ ] Há piloto com um time antes do rollout geral?
- [ ] Cada processo novo tem dono, propósito, métrica e data de revisão?
- [ ] A ferramenta proposta reforça um processo que já funciona manualmente?
- [ ] Os dados de produto estão conectados a métricas de negócio?
- [ ] Os fóruns têm pessoas que decidem, entradas e saídas definidas e feedback de volta?
- [ ] ProdOps está habilitando a decisão ou decidindo pelo PM?
- [ ] Há algo "abaixo da linha" explícito, ou ProdOps está aceitando tudo?
- [ ] O valor entregue está sendo comunicado de forma recorrente a executivos e PMs?
- [ ] A pesquisa evita a câmara de eco (sempre os mesmos clientes)?
- [ ] A alocação de P&D é medida por buckets agregados, sem timesheet invasivo?

## 3. Os 4 takeaways finais do livro
1. **ProdOps é multiplicador de força em organizações de qualquer porte:** equipa PMs para o que foram contratados, ou seja, decisões melhores pelo negócio e pelo cliente. "É um fator para mudar a mentalidade da organização para ser orientada a resultados" (Siamak Khorrami).
2. **Os 3 pilares são o framework de comunicação:** a "regra de três" é memorável; use-a para explicar a função e dividir para conquistar.
3. **Defina como medir sucesso**, com lente de PM (`estruturar-escalar.md`, seção 8).
4. **Dicas:** **paciência** (é iterativo, não "faz uma vez e pronto"); **não procrastine** (fundação cedo habilita crescimento lucrativo; a 1ª baseline manual leva semanas, mas vale); **buy-in cross-funcional** é o que libera o poder total; adapte à empresa. "Entenda o terreno, o negócio, a estratégia, como as funções operam, o que funciona e o que não; aí foque no que precisa e pode ser resolvido" (Sarah Stolovitch).

## 4. Roteiro A: implantar Product Ops pela primeira vez

| # | Etapa | Pode ser |
|---|---|---|
| 1 | **Por que você acha que precisa de ProdOps?** | Cultura de produto em silos; roadmaps "no feeling"; relações cross-funcionais se deteriorando |
| 2 | **Qual é a maior necessidade hoje?** | Dados e insights · cliente e mercado · processo e práticas |
| 2a | **Discovery sprint: dores e oportunidades** | Validar as hipóteses de 1 e 2; entrevistas com PMs e áreas |
| 3 | **Identificar quick wins** | Template unificado de roadmap; baseline dos dados existentes para um dashboard v1; empacotar a pesquisa existente para uso fácil pelos PMs |
| 4 | **Como alocar gente?** | % de alocação de PMs atuais; "burst" (pessoa atual 100% por tempo limitado); business case ao executivo para realocação ou headcount |
| 5 | **Visão e roadmap de ProdOps** | Enquadrado em quick wins e necessidades de longo prazo; áreas de valor e topologia de time sequenciada |
| 6 | **Vender a visão e o roadmap** | Roadshow: o que é bom ProdOps? Como beneficia [audiência]? Visão agora, próximo, depois |
| 7 | **Compartilhar vitórias e lições** | Atualização programada em all-hands, all-hands de produto, QBRs, review mensal |
| 8 | **Retro trimestral de sistemas** | Revisão trimestral de ferramentas e processos; executivos e PMs ranqueiam do mais ao menos útil |

## 5. Roteiro B: evoluir uma função existente

| # | Etapa | Pode ser |
|---|---|---|
| 1 | **O que está indo bem?** | Time pequeno montado; foco definido; maior lacuna atacada (ex.: dados); avanços em capitalização com finanças |
| 2 | **O que poderia ser melhor?** | PMs usando os dashboards menos que o esperado; pedidos muito além do escopo; falta de gente |
| 2a | **Discovery sprint** | Validar hipóteses; entrevistas com PMs e áreas; como o escopo deve evoluir no médio e longo prazo? |
| 3 | **Quick wins** | Refazer o roadshow para clarear escopo e valor; ProdOps na pauta regular do all-hands; revisar dashboards para adequação ao propósito |
| 4 | **Repensar metas de médio e longo prazo** | Plano de staffing de 18 a 36 meses com resultados que destravam headcount; refazer o roadmap de ProdOps |
| 5 | **Check-in executivo semestral** | Apresentar ao CEO e executivos as vitórias, desafios e destaques e o plano de staffing; reforçar o valor entregue |
| 6 | **Revisão trimestral de visão e roadmap** | Refinar o "agora, próximo, depois" |
| 7 | **Compartilhar vitórias e lições** | Atualização programada (all-hands, QBR, mensal) |
| 8 | **Retro trimestral de sistemas** | Ranking de ferramentas e processos |

## 6. Padrão de narrativa da jornada (Pipeline 3K)
Sequência que se repete em casos reais e serve de modelo de comunicação:
1. **Dor visível no topo** (CPO leva 5 semanas para montar o board e o dado já nasce obsoleto).
2. **Recurso emprestado** resolve o dado crítico (analista de Sales Ops → fonte única de verdade e visões-chave).
3. **Head de ProdOps** contratado; 30 dias de entendimento antes de agir.
4. **Pilar urgente pelo calendário:** o planejamento anual atrasado puxa a governança antes do customer insights.
5. **Quick wins por pilar** e o plano "escalar no próximo trimestre" (automatizar dados, analista de pesquisa, analista de processo e governança, organização para 12 a 24 meses).
6. **Métricas de saúde da função de PM** (pesquisas de percepção → dashboard) para provar maturidade na revisão anual.
