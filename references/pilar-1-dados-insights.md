# Pilar 1: Dados e Insights de Negócio

> **Quando ler:** para definir métricas, dashboards, instrumentação, baseline manual, automação em BI, alocação de P&D ou capitalização de software, ou para conectar dados de produto a resultados financeiros.

## Sumário
1. Objetivo do pilar · 2. Os 5 passos · 3. Cascata de estratégia e perguntas por camada · 4. Catálogo de métricas · 5. Instrumentação · 6. Alocação de P&D · 7. Baseline manual e dashboards · 8. Automação · 9. Capitalização (caso athenahealth) · 10. Primeiros passos · 11. Ponte com a cadeia de indicadores

## 1. Objetivo do pilar

Coletar e analisar dados internos para **criar e monitorar estratégia**. Dá aos líderes uma visão que acompanha a evolução dos resultados para reconciliar gasto de P&D com ROI, e contextualiza métricas de negócio (ARR, retenção) com métricas de produto.

- Produto não é **dono** dos dados; Product Ops é o **tecido conectivo** que monta a visão 360° de tudo que afeta a estratégia e as receitas (topline e bottom line).
- Se o time de dados vive fora de produto, ProdOps garante o fluxo consistente de dados **com contexto de produto**. Se não existe time de dados, comece a capacidade dentro de ProdOps.
- Dado sem contexto é um show de improviso; nas mãos certas, conta uma história. Amarre sempre o dado à estratégia, seja para formá-la ou para executá-la.

**Duas lentes do CEO:**

| Foco em crescimento de receita (topline) | Foco em EBITDA (eficiência) |
|---|---|
| Rentabilidade mensal por produto | Custo dos esforços |
| Uso por usuário ou empresa | Composição do investimento |
| Status de produtos novos e em andamento | Atividades alinhadas a metas e iniciativas |
| Dados de mercado (adjacências, concorrentes) | Eficiência operacional |
| KPIs de cliente por segmento | Chamados de suporte e defeitos |
| Oportunidades de expansão de TAM | |

Esses dados costumam ser monitorados em silos (suporte vê defeitos, chief of staff vê eficiência). ProdOps une tudo numa visão única, em tempo real, também útil para as outras áreas.

## 2. Os 5 passos para montar a capacidade

1. **Perguntas:** quais perguntas precisamos responder para informar a estratégia em cada nível?
2. **Dados:** quais dados respondem a essas perguntas?
3. **Fontes:** em quais sistemas os dados estão e como extraí-los?
4. **Baseline manual:** montar a primeira visão puxando os dados à mão.
5. **Automação:** conectar os sistemas a uma ferramenta de BI com atualização contínua.

> Comece pelo fim desejado (a decisão que precisa ser tomada), não pelo dado disponível.

## 3. Cascata de estratégia e perguntas por camada

| Nível | Pergunta central | Quem define | Horizonte |
|---|---|---|---|
| Visão da empresa | O que queremos ser em 5 a 10 anos? Valor ao cliente, posição, forma do negócio | CEO e alta liderança | 5 a 10 anos |
| Intenções estratégicas | Que desafios de negócio impedem a visão? | Diretos do CEO (CPO com CRO, CFO, CTO) | 1 a 3 anos |
| Estratégia e iniciativas de portfólio | Que problemas atacamos, do ponto de vista do portfólio, para cumprir as intenções? | CPO e VPs | 1 a 3 anos |
| Estratégia e iniciativas de produto | Que problemas atacamos em cada produto? | VPs e diretores | 6 a 12 meses |
| Opções | Que soluções diferentes posso criar para esses problemas? | Times de desenvolvimento | 3 a 6 meses |

Exemplo (Pipeline 3K, empresa fictícia do livro):
- **Visão:** suíte de produtos fáceis que permite a recrutadores e candidatos assumirem o controle de achar ou preencher vagas.
- **Intenção estratégica:** recuperar o segmento mid-market e voltar a crescer, +30% de receita.
- **Iniciativa:** aumentar em 60% a adoção da capacidade de rede (indicação) no mid-market.
- **Opção:** redesenhar o funil de onboarding para mostrar o valor da rede de imediato.

### 3.1 Perguntas para informar intenções estratégicas
- Use no máximo 3 intenções priorizadas.
- Comece pelo estado atual do negócio: ARR, ASP (preço médio de venda), ACV (valor anual de contrato), custo.
- Números agregados não dão foco ("crescimento desacelerou"). **Segmente** por segmento ou persona, coorte e geografia.
- Exemplo de achados que geram foco: ARR desacelerando no total, mas crescendo em enterprise; contrato enterprise custa 3× mais para fechar, mas tem ACV 10× maior; mid-market caiu 20%, exceto no setor financeiro.

### 3.2 Perguntas para informar iniciativas de produto
Acrescente o corte por produto, feature e pacote:
- A receita por produto e feature é compatível com o gasto?
- Personas diferentes compram pacotes diferentes?
- Qual é a retenção de quem compra produtos diferentes?
- Que % dos clientes compra cada produto ou feature?
- A receita bate com os segmentos-alvo? O gasto bate com o foco estratégico?
- Todos os produtos têm uso suficiente ou devemos descontinuar algum para concentrar recursos?

Essas respostas levam à pergunta maior: **por quê?** Responder ao porquê formula a iniciativa. Estratégia não se impõe só de cima para baixo: ela se comunica para cima, para baixo e para os lados.

### 3.3 Perguntas para informar opções
Os times quebram iniciativas em problemas menores entendendo profundamente métricas e comportamento. Indicadores antecedentes (leading):
- Queda de NPS sinaliza aumento futuro de churn.
- Aumento de uso de feature antecipa receita (em assinatura).
- Aumento de adoção entre produtos sinaliza oportunidade de cross-sell e upsell.

Segmente métricas por tipo de cliente e coorte; encontre gargalos de uso, adoção e funil; rastreie o leading até o resultado de negócio. A iniciativa vira **lente de priorização** do backlog: "A ou B gera mais valor para a iniciativa?"

## 4. Catálogo de métricas (visão granular)

| Grupo | Métricas | Aplica a |
|---|---|---|
| Receita | Total, recorrente, não recorrente, ARR, ACV e TCV | Produtos que geram receita |
| Bookings | Total; novo × upsell × cross-sell × downsell; novos logos | Produtos que geram receita |
| Retenção | Retenção líquida e bruta, churn, churn de logos | Produtos que geram receita |
| Engajamento | NPS, adoção de features | Todos os produtos |
| Custo de P&D | Custo total de P&D; custos indiretos de produto em outros orçamentos | Todos os produtos |
| Custo de atividade | Custos internos (ex.: onboarding); custo por métrica de throughput | Ferramentas internas |

**Eixos de segmentação:** produto, pacote ou bundle · segmento de cliente (vertical e porte) · coorte · geografia.

## 5. Instrumentação de métricas de produto

**Diagnóstico do estado atual:**
- Os dados de engajamento estão habilitados? Em que ferramenta?
- Quando os eventos foram implementados? Que métricas conseguimos ver?
- Medimos engajamento em todos os produtos e features?
- Qual seria o estado ótimo de captura?

**Sem ferramenta** (ex.: Amplitude, Pendo): peça a engenharia uma estimativa de esforço (LOE), traduza em sprints e custo. Se passar de **cerca de 3 meses de engenharia**, faça business case ao CEO, com a visão de um time orientado a dados e exemplos de decisões ruins tomadas sem dados.

**Métricas centrais de engajamento** (SaaS e D2C):
- Stickiness (DAU/WAU/MAU)
- Frequência (ex.: logins por cliente)
- Taxa de adoção de feature e taxa de retenção de feature
- Uso: **profundidade** (uso por tempo, funil...) e **amplitude** (nº de usuários ativos)

ProdOps costuma ser dono dos dados de engajamento: garanta que a organização saiba o que se mede, por que e o que é acionável.

## 6. Alocação de recursos de P&D

Objetivo: saber se o investimento está indo para onde a estratégia diz.

**Como medir sem timesheet** (timesheet minuto a minuto mata a moral e gera turnover):
- Tech leads reportam **semanalmente horas agregadas por tema** do time.
- Buckets: **Estratégico** (ligado às iniciativas) · **Dívida técnica e plataforma** · **BAU/KLO** (manter as luzes acesas) · **Bugs**.

**Caso Pipeline 3K:** 1º mês com estratégico 25%, dívida técnica 40%, BAU 10%, bugs 20%. Investigando, bugs graves estavam sendo lançados como dívida técnica (o time temia parecer desleixado). A causa raiz era pressão do board por features rápidas, que gerava releases apressados, produto instável e cancelamentos. Decisão: um trimestre focado em bugs e estabilidade. Dois trimestres depois: estratégico 35%, dívida técnica 25%, BAU 10%, bugs 25% (com classificação mais honesta).

**Lições:**
- Combine **alocação + métricas de produto** para saber se o investimento está no lugar certo.
- O número inicial quase sempre está errado; o valor está na conversa honesta que ele provoca.
- Não precisa de precisão de minutos; precisa de **% por bucket**.

## 7. Baseline manual e dashboards

### 7.1 Baseline manual
Propósito: **concordar sobre as visões** necessárias para informar e monitorar a estratégia **antes** de automatizar.
1. Revise as perguntas de cada nível de estratégia (seção 3).
2. Com os usuários dos dados, defina a visualização mais eficaz; faça mockups de gráficos e relatórios.
3. Acordado o desenho, extraia os dados manualmente de cada sistema e monte com dado real.
4. Rode **2 a 3 ciclos mensais** para confirmar que mede a coisa certa e que os feeds manuais funcionam.
5. Use o período para mostrar às áreas parceiras como os dados delas estão sendo usados.

Fontes típicas: CRM (transações, bookings, pipeline, win/loss) · ERP financeiro (receita, ARR, COGS, P&L, folha, nuvem) · suporte (tickets) · analytics de produto (engajamento, MAU) · Jira (projetos, épicos, tickets) · ferramentas de pesquisa (estudos, base de participantes) · RH (headcount do time de produto). Tudo converge para uma ferramenta de visualização (Looker, Tableau, Power BI...).

> A primeira baseline leva tempo (a CPO do caso levou 5 semanas para o primeiro board). Paciência.

### 7.2 Dois dashboards mínimos

**Dashboard do time de produto** (PMs e líderes): manter o time alinhado ao trabalho mais importante e mostrar como ele sobe para as iniciativas.
- Métricas de produto: uso por persona, conversão, métricas de fluxo
- Status do roadmap e métricas projetadas para cada item perto do lançamento
- Responsável por cada item
- Exemplo: roadmap por feature (Agora / Próximo / Depois) · adoção por persona e feature · progresso dos KPIs por opção · progresso das metas de receita por produto
- **Evite** métricas de projeto como velocity; elas vivem no planejamento de sprint e capacidade.

**Dashboard executivo e de board:** confiança total de que o time entrega valor ao cliente e resultado de negócio; visão de portfólio, de alto nível, entendível de relance, mostrando qual **deveria** ser o número.
- Status do roadmap por iniciativa, subindo até a intenção estratégica
- ARR por segmento e por produto
- Ponte de receita (*revenue bridge*) por iniciativa e produto
- Bookings por produto
- Visão de dívida de vendas, dívida técnica e custos
- Alocação por portfólio
- Exemplo de blocos: roadmap de alto nível por intenção · financeiros-chave (receita meta × real, P&D meta × real) · investimento por tipo (inovação, dívida, bugs, KLO) · "alinhamento às prioridades" com farol verde, amarelo ou vermelho e racional

> Executivo vasculhando o Jira é sintoma de falta deste dashboard.

### 7.3 Higiene de dashboard
- Use **nomes de pessoas** sempre que possível (responsabilização e empoderamento).
- Todo membro do time precisa ver seu trabalho representado.
- Períodos coerentes com a cadência dos check-ins (ano contra ano não engaja em reunião mensal).

## 8. Automação de dados e insights

**Valor:** acesso a informação em tempo real · acompanhar a realização das ações priorizadas · comparar fotografias no tempo · validar e demonstrar progresso · previsibilidade e forecast · entrega com custo eficiente.

**Do manual ao automatizado:**
1. Escolha uma ferramenta de BI (Looker, Tableau, Metabase...) para agregar os dados cross-funcionais.
2. Implemente **regras de tagueamento** (alocação de custo, rastreio estratégico de tarefas) com base no aprendizado do baseline, garantindo a captura correta **na fonte**.
3. Conte com **4 a 6 meses** de descoberta e melhoria; depois, revise **trimestralmente** se as métricas continuam acionáveis.
4. Crie fatias diferentes da mesma fonte única de verdade: time de produto → executivo → vendas, marketing, finanças.

Aproveite premissas, visões e metadados do esforço manual. Referência: na Doodle, o time de dados conectou tudo num data warehouse com BI, treinou todos para autosserviço e liga o **flywheel** do negócio à receita, mostrando o impacto financeiro do que é construído.

## 9. Capitalização de software (caso athenahealth)

**Conceito:** pelo GAAP, o custo de desenvolver software de uso prolongado é **capitalizado** (vira ativo no balanço e é depreciado na vida útil; no caso, 4 anos) em vez de lançado como despesa; isso impacta o EBITDA e o valuation. Construir funcionalidade nova ou melhorar uma existente é capitalizável; corrigir bugs é despesa.

**Problema:** 6 vezes por ano, líderes classificavam o trabalho de mais de 200 squads numa planilha, com entrevistas: **mais de 400 horas por ano** e mais de 3.000 linhas para finanças conferir. Timesheet foi descartado (mataria a cultura).

**Solução liderada por ProdOps:**
1. Hierarquia padrão no Jira: Iniciativa de roadmap (problema) → Feature (container de roadmap e release) → Épico (cerca de 1 ciclo de release) → História, tarefa, bug e subtarefa (1 a 2 sprints). Todo trabalho aninhado a uma Feature.
2. Dois tipos de Feature: uma para melhorias e features novas que exigem teste com usuário e gestão de mudança; outra ("Type 2") para trabalho operacional de release mais rápido.
3. Campo de **categoria** obrigatório:

| Tratamento | Categoria | Exemplos |
|---|---|---|
| Capitalizar | Nova feature | Funcionalidade nova para o usuário final |
| Capitalizar | Tecnologia fundacional | Blocos de base; dívida técnica que resulta em nova funcionalidade |
| Despesa | Confiabilidade reativa | Correção de bugs; performance (salvo se melhora muito o produto) |
| Despesa | Desenvolvimento experimental | Pesquisa e teste de viabilidade |

4. Roadshow de educação sobre os buckets e o básico do GAAP; vínculo de cerca de 35 mil histórias, 3 mil épicos e 800 features.
5. **Piloto de 6 meses** com finanças, validando a qualidade exigida pela auditoria, antes de virar o processo oficial.

**Cálculo ilustrativo:** time de 10 engenheiros a $10 mil/mês = $100 mil; 4 projetos de $25 mil, 2 capitalizáveis; 50% do tempo em manutenção → capitaliza $12,5 mil + $12,5 mil = **$25 mil** no mês.

**Resultado:** mais de 400 h/ano economizadas, maior precisão e, de bônus, um **ativo de dados e cadência operacional** que habilita gestão de portfólio, dependências e decisões em todos os níveis. A padronização certa do Jira "vai longe".

## 10. Primeiros passos (do livro)
1. **Foque nas métricas que importam:** de 3 a 5 métricas financeiras e de produto ligadas aos resultados desejados (receita, adoção por segmento, retenção, custos de P&D e de atividade).
2. **Faça parceria com Finanças:** cadência regular para entender os números e reduzir silos; peça a Finanças para educar PMs em métricas de receita e na diferença entre indicadores leading e lagging.
3. **Entenda a alocação de P&D:** comece pela visão de capitalização (se houver) e evolua para o rastreio por buckets.

## 11. Lição transversal: conecte todos os dados
Dados de uso sozinhos enganam. Exemplo: o uso de uma feature cresce mês a mês, mas vem do segmento que a empresa quer descontinuar, enquanto o segmento estratégico caiu 20%. **Ligue uso a receita, churn e custo**, e cruze com os insights de cliente e mercado (pilar 2). Meta: toda decisão vira decisão de ROI, não emocional.

## 12. Ponte com a cadeia de indicadores (complemento, fora do livro)
O livro conecta KPI de opção → iniciativa → intenção estratégica (negócio). Isso é compatível com a leitura de indicadores em 3 níveis, **feature → produto → negócio**, em que um indicador se conecta ao outro (Diego Eis, "O que é um produto, uma solução e uma feature"). Ao desenhar dashboards, garanta que cada métrica de feature tenha uma métrica-pai de produto, e esta, uma métrica de negócio.
