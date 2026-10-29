# Estruturar e Escalar o Time de Product Ops

> **Quando ler:** para decidir a primeira pessoa, montar um time de um ou de vários, desenhar cargos e perfis, escolher entre modelo central, embarcado ou híbrido, definir o modelo de financiamento ou as métricas de sucesso da própria função.

## Sumário
1. Começar sem headcount novo · 2. Time de um · 3. Time de vários e evolução · 4. Perfis por papel · 5. O líder de ProdOps · 6. Modelos de organização · 7. Lições de Blake Samic (Uber, Stripe, OpenAI) · 8. Métricas de sucesso de ProdOps · 9. Futuro da função · 10. Primeiros passos

## 1. Começar sem headcount novo
- Mapeie as **lacunas de capacidade por pilar**; a linha de tendência aponta a primeira contratação. Marque as lacunas que podem virar quick win, como hipóteses.
- Pode nascer de um **PM atual**: troque cerca de 50% do portfólio dele por um foco específico de ProdOps e defina limiares de valor para virar tempo integral.
- Pode **pegar emprestado** (a CPO do caso pegou uma analista de Sales Ops por algumas semanas e depois ela ficou de vez).
- Caso Pendo: a diretora de produto Christine Itwaru resolvia a comunicação bidirecional vendas ↔ produto; o CPO a convidou para ser a 1ª de ProdOps. Primeiras ações: explicar ao time de receita o **porquê** das mudanças de estratégia e roadmap; criar um **hub fonte única de verdade** com estratégia e roadmap atualizados; criar o mecanismo de feedback de clientes e suporte para os PMs. Cresceu para governança, centro de excelência e padrões de analytics, de 1 para 11 pessoas em menos de 2 anos. Filosofia: ser indispensável, mas buscar **resolver o problema e seguir em frente** para o próximo valor.

## 2. Time de um
- É mais fácil aprovar uma pessoa do que um time, e uma pessoa **consegue virar o jogo**.
- **Seja "um pouco egoísta" no início:** defina visão, missão e estratégia de ProdOps antes de sair resolvendo tudo; caso contrário, vira papel de preenchimento. Aprenda a **dizer não**, mas fique aberto a encaixes inesperados no escopo (ex.: gestão de fornecedores como extensão da gestão de ferramentas).
- **Plano de 18 a 24 meses:** mostre confiança no valor e disciplina para escalar. Use stage gates de valor realizado → novas capacidades → papéis necessários, com faixa salarial estimada.
- Alto impacto típico de time de um: **centralizar a informação numa fonte única de verdade** (Gerisha Nadaraju).
- **Você é o padrão:** o valor que você entrega define o tom da função. Resolva problemas difíceis e torne o valor visível.

## 3. Time de vários e evolução
Com time, dá para atacar vários pilares mais cedo. Com mais gente, o time deixa de reportar direto ao CPO e precisa de um líder de ProdOps.

**Evolução ilustrativa:**

| Estágio | Horizonte | Estrutura |
|---|---|---|
| Time de um | 6 a 12 meses | CPO → Product Ops Lead |
| Time de vários | 12 a 24 meses | CPO → Diretor(a) de ProdOps (processo e governança) → Product Tools Manager, Product Data Analyst, User/Market Insights Analyst |
| Função madura | 24 a 36 meses | CPO → VP de ProdOps → 3 diretorias: **Embarcados** (product data analysts em pods selecionados) · **Processo e governança** (analista de processo e governança, gestor de ferramentas e templates, community of practice e coaching) · **Insights quali e quanti** (analista de negócio e dados, analista de usuário e mercado, product tools manager) |

Ajuste ao que já existe: se a empresa já tem dados em autosserviço, não precisa do analista embarcado. Exemplo: o CPO da Sam's Club (cerca de 350 PMs e designers) desenhou organograma com contratações escalonadas de diretores e começou pelo **senior director de ProdOps**; o pacote incluía visibilidade de portfólio, ferramentas, padronização e um programa formal de **APM** (*associate product manager*).

## 4. Perfis por papel
Os perfis variam muito: quem brilha em dados não necessariamente brilha em governança (caso real: analistas excelentes falharam ao assumir otimização de processo por falta de vivência em product management).

| Papel | Perfil ideal | Títulos |
|---|---|---|
| **Dados e insights** | Background de consultoria ou análise; mestre de Excel e modelagem; SQL é diversão; acha "pepitas" escondidas; **transforma análise em história**; confortável com PMs e C-level. Pode ser novo em produto (você o ensina). | Product Operations Analyst · Product Data Analyst |
| **Governança e modelo operacional** | Conhece ferramentas de desenvolvimento e insight e como habilitam processos; adora selecionar, implantar e otimizar ferramentas. PM pleno apaixonado por eficiência, ou chief of staff que entende desenvolvimento de produto. Já fez coaching e mentoria, criou rituais e boas práticas, ama melhoria contínua. **Alta inteligência emocional**, influência em matriz, coach de ágil e lean. | Product Operations Manager (Process) |
| **Insights de cliente e mercado** | Empresa grande com research forte: pode ficar sob o líder de UX ou Research Ops. Pesquisa fraca ou inexistente: pesquisador ou designer muito experiente com mentalidade de produto, que gosta de escalar e "produtizar"; consultores encaixam bem. Reporta ao líder de ProdOps. | Product Operations Lead, User Insights · Head of Research Operations |
| **Dados (embarcado)** | Mesmo perfil de dados, com foco em um pod ou área | Product Data Analyst |

## 5. O líder de ProdOps
Com time formado, contrate **diretor ou VP de ProdOps** conforme o porte. Raramente se acha quem já montou a função do zero; boas origens são **ex-diretores de produto** (empatia com as dores do PM) e **chiefs of staff** (empatia com todas as áreas).

Traços buscados:
- Orientado a processo; decompõe problemas e conduz programas grandes e complexos
- Já motivou e liderou times
- Alta inteligência emocional com outros líderes
- Campeão de ProdOps como **multiplicador de força**
- Curiosidade insaciável e tenacidade para resolver problemas
- **Contador de histórias baseado em evidência**
- Visão de quick wins e de médio e longo prazo
- Estuda como outros praticantes estruturaram seus times

## 6. Modelos de organização
Não há certo ou errado; um grande banco alternou central → embarcado → central desde 2019.

| | Central / serviço compartilhado | Embarcado nos times | Híbrido |
|---|---|---|---|
| **Descrição** | Um time de ProdOps que cria sistemas que escalam para todos | Analistas embarcados em divisões e times, com pelo menos um dedicado; reporta ao líder de produto | Serviço compartilhado mais analistas embarcados estrategicamente nos times de maior necessidade |
| **Necessidade típica** | Programas que escalam para a maioria dos casos | Dados e insights dispersos e inconsistentes; times precisam de ajuda dedicada para reporting ad hoc | Necessidades de dados variadas, mas a função inteira precisa de um programa de "Voz do Cliente" |
| **Prós** | Foco em infraestrutura e autosserviço de impacto amplo; parceiros aprendem entre si e aplicam globalmente | Solução sob medida para cada time; insights quanti e quali para o time | Suporte direcionado sem sacrificar métodos centrais; embarque temporário quando preciso |
| **Contras** | Pode exagerar no processo; necessidades únicas de cada pod ficam descobertas | Vira "pau para toda obra" (triagem de bug, falar com cliente); sem líder único surgem silos | Exige guardrails de escopo do embarcado; pode faltar gente para dedicar |

**Como escolher:** se os PMs já têm muito autosserviço de dados e pesquisa → **central**. Se já há processos sólidos → comece **embarcado**, de forma direcionada. Se precisa dos dois → **híbrido**. Ajuste conforme a empresa evolui.

## 7. Lições de Blake Samic (Uber, Stripe, OpenAI)
Fundou a função na Uber (2015) e na Stripe (2018), chegando a mais de 70 e mais de 50 pessoas.

**Charter acima e abaixo da linha:** nas primeiras semanas, dezenas de conversas; classifique as contribuições em **acima da linha** (quick wins viáveis agora) e **abaixo da linha** (alto valor, exige headcount). Exemplo de responsabilidades na Uber:
- Trazer e priorizar insights globais do negócio (inovações locais das cidades para o planejamento; descasamentos de KPI entre tech e operações)
- Garantir viabilidade global no desenho e construção (rollout global; transparência de metas e resultados)
- Gerir rollout, suporte e otimização (comunicação interna, educação, gestão de projeto; impacto em suporte; feedback rápido e iteração)

**Programas centrais cedo:** "há coisas centrais que elevam a maré de todos os times com pouca gente." Exemplos na Uber: anúncios de lançamento → newsletter global quinzenal → apresentações mensais → roadmap universal com visões por líder regional → consolidação dos OKRs de tecnologia. Na Stripe, um **calendário único de lançamentos**: protótipo manual em cerca de 1 dia com dado real; o CPO respondeu "não tinha essa visão desde que éramos pequenos" e aprovou o investimento (e a gente para escalar).

**Fazer em vez de descrever:** um serviço manual com dado real convence muito mais que a promessa.

**Sinais de que precisa crescer:**
- Muitos times lançando em paralelo; as áreas não acompanham o que vem
- Produto complexo, problemas complexos e treinamento extra para o GTM
- Muito trabalho manual repetitivo para virar playbook e depois automação
- Feedback de usuários chegando por todos os lados (vendas, suporte, formulários, Slack, e-mail)

**Priorização da própria demanda:** defina as **atividades centrais** de ProdOps (ex.: gestão de beta, prontidão de lançamento, conexão produto e GTM) × **prioridades estratégicas da empresa** × **metas das áreas de produto** = onde alocar suporte para o maior impacto. Num modelo central, **despriorizar áreas** faz parte; você vê todas as necessidades e otimiza globalmente. Mantenha a lista do que "não dá para fazer agora": ela vira argumento de investimento.

**Modelo de financiamento:** a Stripe passou de "serviço gratuito" (orçamento central) para "pago" (cada área financia seu **ProdOps Partner, PoP**). O que viabilizou: um **one-pager de valor** com o que o time recebe e o impacto em outros times (resultados, receita, tempo economizado, eficiência, satisfação dos PMs), para o gestor decidir entre "mais um engenheiro, mais um PM ou um PoP".

**Do embarcado ao híbrido:** na Uber o modelo era majoritariamente embarcado (com % do tempo para trabalho transversal), mas a profundidade nos times comia o tempo central. Na Stripe, montou **embarcados e centrais em paralelo**: o time embarcado é como uma pequena startup e, se prova um método, ele escala via o central.

**Discuta crescimento já:** deixe claro desde o início que a visão é maior que um time de um e que os primeiros ganhos são **provas de conceito**; combine sinais de inflexão (sem compromisso, como diálogo contínuo).

## 8. Métricas de sucesso de ProdOps
Gerencie ProdOps **com lente de PM**: seus clientes são PMs e líderes; você entrega um produto (ou um conjunto deles).

**Níveis (Hugo Froes):**
- **Organização:** eficiência (cycle time, throughput); efetividade (ideias geradas × que chegam à produção; iterações pós-lançamento até resultado positivo; experimentos conclusivos × inconclusivos).
- **Time de ProdOps:** redução de desperdício (economia, redução de "tempo até X"); aumento de valor (pesquisa de engajamento, saúde do time, qualidade de decisão).
- **Iniciativa:** como o trabalho sobe para metas de pod, time e empresa.

**Perguntas aos clientes (Simon Hilton):**
1. O líder de produto se sente mais conectado aos times, direção e prioridades?
2. As visões de dados importantes estão a tempo e corretas para board e roadmap reviews?
3. Os PMs passam mais tempo com clientes?

**Equilíbrio (Matsui):** a execução é forma legítima de medir; não perca os **microssucessos** (satisfação dos PMs, relações cross-funcionais mais fortes). Ligue as vitórias de execução às metas de negócio.

**Regra prática:** escolha **3 a 5 métricas**, com uma mistura de entregas de execução que sobem aos objetivos de negócio e métricas quantificáveis (cycle time, redução de tempo, turnaround de pesquisa, eficiência do PM). Defina a persona primária (PM ou liderança).

## 9. Futuro da função (visão dos autores)
- Mais adoção em enterprises com múltiplos produtos (estimativa de cerca de 20% hoje, podendo dobrar em 5 anos, segundo Samic).
- Tendência a **centralizar** sistemas com mais **automação** e observabilidade; o embarcado vira o "**concierge**" (resolver manualmente para entender, depois automatizar), liberando gente para o próximo valor.
- Enterprises virando empresas de software (bancos) ganham mais.
- Times com rigor operacional **absorvem funções adjacentes** (engineering ops, onboarding); há também o risco de serem absorvidos por uma mega-área de operações. Os autores preferem Ops separadas, com tensão saudável e conselho trimestral.
- **Carreira:** não é retrocesso. Anabela Cesario foi de VP de ProdOps a VP de Product Management, com ProdOps reportando a ela. Muitos CPOs já não aceitam vaga sem ProdOps ou sem poder criá-lo.

## 10. Primeiros passos (do livro)
1. **Quem pode ser a 1ª pessoa?** Alguém com tendência natural ou interesse no pilar prioritário, que já sentiu a dor. Monte a visão acima e abaixo da linha: dedicação parcial × contratação integral.
2. **Descrição de cargo:** áreas de alavancagem esperadas e, ao lado, resultados tangíveis para a empresa.
3. **3 a 5 métricas de sucesso** (seção 8).
