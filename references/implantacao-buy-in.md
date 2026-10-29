# Implantação: Por Onde Começar, Business Case e Buy-in

> **Quando ler:** para decidir se e por onde começar Product Ops, montar business case, responder objeções, ganhar PMs e stakeholders, rodar listening tour e quick wins, ou liderar a iniciativa sem autoridade formal.

## Sumário
1. Quando faz sentido · 2. Qual pilar primeiro · 3. Business case (memo) · 4. Objeções e respostas · 5. Consenso com PMs · 6. Proposta de valor por stakeholder · 7. Roadshow · 8. Os primeiros 30 a 60 dias (caso Amplitude) · 9. Apoio executivo · 10. Liderar sem autoridade formal · 11. Primeiros passos

## 1. Quando faz sentido
Um coach dizer que "depende só do tamanho do time" é um conselho ruim. Os sinais reais são:
- Passagem de scale-up para enterprise; o que funcionava deixa de sustentar o crescimento.
- A comunicação precisa mudar: não dá mais para virar e perguntar "no que vocês estão trabalhando?".
- O portfólio escala: decisões rápidas com muito mais dados e governança apertada para muitos fluxos em paralelo.
- Estratégia e processos ficaram complexos e o líder perdeu o pulso.

## 2. Qual pilar primeiro
Aprofunde em um ou combine poucos. Comece pela **maior dor** e faça um roadmap a partir dela.

**Comece por Dados e Insights se:**

| Dor | ProdOps habilita |
|---|---|
| "Não sei se os PMs fazem roadmaps e decisões baseados em dados." | Acesso em autosserviço a dados de performance de produto |
| "Não sei o que recebo pelo gasto de P&D." | Reporting que liga as apostas aos resultados, para decidir financiamento |
| "Não tenho visão da performance da estratégia para decidir sobre produto." | Função quantitativa que contextualiza métricas de negócio para monitorar crescimento |

**Comece por Cliente e Mercado se:**

| Dor | ProdOps habilita |
|---|---|
| O feedback de vendas, suporte e pesquisa não chega aos times de produto. | Fluxo de informação de volta para PMs e decisores |
| Não fazemos boa pesquisa porque é difícil contatar usuários. | Sistema de acesso a usuários |
| Não calculamos o impacto potencial de produtos novos em mercados. | Capacidade de pesquisa de mercado (concorrência, sizing) |
| PMs pesquisam, mas a pesquisa fica no desktop deles. | Atomizar e taguear entrevistas num repositório comum |

**Comece por Governança e Modelo Operacional se:**

| Dor | ProdOps habilita |
|---|---|
| Não sei no que os times trabalham nem consigo reconciliar com a estratégia de portfólio. | Roadmaps acessíveis que sobem para a visão do portfólio e descem por produto |
| Cercamos os PMs dos insumos quantitativos e qualitativos para fazer estratégia? | Framework transparente de criação e desdobramento de estratégia |
| Viramos um portfólio; como garantir uma abordagem unificada? | Governança que cresce com escala e necessidade |

**Padrão observado:** *scale-ups* tendem a começar por **dados** (decisões rápidas de crescimento); *enterprises*, por **governança** (precisam de transparência antes de decidir). O que importa é que ajude.

## 3. Business case: memo para o gestor
Funciona mesmo sem dados duros. Estrutura em 4 blocos (`templates/memo-business-case.md`):

1. **Dores:** só as mais agudas, não uma lista de defeitos. Conecte às prioridades e projetos de estimação do gestor ou CEO.
2. **Impacto das dores:** evidência concreta, de preferência quantitativa:
   - receita perdida ou incremental (mesmo direcional, com asterisco: "estimativa de guardanapo");
   - atrasos em iniciativas estratégicas por falta de dados → vendas perdidas (sem número, cite a frustração expressa por CEO, gestor, stakeholders e PMs; efeitos em retenção e satisfação de pessoas);
   - roadmaps rasos, sem inputs, gerando entregas que não movem o ponteiro.
3. **Solução e recomendação:** definição de ProdOps, os 3 pilares, qual pilar primeiro e por quê, e referências (Uber, Stripe, Sam's Club, Oscar, Pendo, athenahealth). Formato: nova contratação **ou** alocação de cerca de 50% de um PM atual, explicando como os outros 50% serão redistribuídos e em que **limiares de valor** a pessoa vira tempo integral.
4. **Valor esperado:** prometa menos e entregue mais, mas desenhe a visão de resultados tangíveis do pilar escolhido **com o trimestre estimado** de entrega.

Circule, esteja aberto à conversa e preparado para perguntas.

## 4. Objeções e respostas

| Objeção | Resposta |
|---|---|
| "PMs deveriam fazer a própria implementação de analytics e as análises." | Concordo que PMs devem saber analisar. Com alavancagem de um analista, eles fazem mais trabalho estratégico que move o resultado-chave. O analista cuida da implementação de analytics no nível do portfólio, com consistência e precisão, e participa de cada lançamento para garantir os eventos. Mais importante: é um **parceiro objetivo**, próximo do produto, mas não próximo demais, que acha oportunidades nos dados. |
| "Uma função nova para criar processo e regra? Já temos overhead demais." | Stripe, Uber, athenahealth e Pendo viveram a fratura da comunicação cross-funcional ao escalar rápido e criaram ProdOps para isso. Esses times **reduzem** processo: avaliam regularmente o que é necessário, ajustam ou descontinuam e evitam excesso. |
| "Os PMs já falam com clientes." | Muitos falam com os **mesmos poucos** clientes e correm o risco de uma visão enviesada, ignorando expansão e novos clientes. ProdOps sistematiza a pesquisa, cria toolkits e gestão de usuários. Se já houver pesquisa, mostre como ProdOps faz parceria para alavancar insights em toda a empresa. |
| "Por que os PMs não cobrem isso?" (CEO) | Já cobrem, e estão queimando. PM é caro e difícil de contratar; ProdOps devolve tempo para crescimento, metas e valor ao cliente e evita turnover. |
| "Só precisamos de um program manager." | Program management resolve cronograma e status. ProdOps resolve **insumo para decisão** (dados, cliente, mercado) e **modelo operacional**. Mostre a tabela PM × ProdOps e entenda de onde vem a resistência. |

> As duas últimas linhas são sínteses de outros capítulos do livro, não da tabela original.

## 5. Consenso com PMs
Nem todo PM compra a ideia. Medos e armadilhas comuns:
- ProdOps vai "tomar" o trabalho de produto.
- ProdOps vira quem pega o que cai da mesa do PM: reativo, sem estratégia de habilitação.
- "Só precisamos de um program manager."

Resolve-se com **educação**, e a mensagem central é: **ProdOps não decide; habilita a decisão.** Use a tabela PM × ProdOps (`fundamentos.md`) e explique como as Ops (Sales, Design, Eng, Product) coexistem.

## 6. Proposta de valor por stakeholder
Influência = acertar a proposta de valor **para cada audiência**:

| Stakeholder | Dor | O que ganha |
|---|---|---|
| UX e pesquisa | PMs dependem deles para tudo sobre o cliente; projetos se acumulam | Ponte com os PMs; repositório e acesso a usuários em autosserviço ("ensinar a pescar") |
| Vendas e marketing | Produto como caixa-preta | Cola no GTM: insights do cliente fluem para produto; transparência de roadmap; dados de uso antes e depois; temas e aprendizados que ajudam a vender |
| Data science | Análises que ninguém consome | Aplicação sistemática nas decisões; papel de "produto" ao criar dashboards e repositórios de autosserviço |
| Suporte | Feedback negativo sem resposta | Coleta, estrutura e distribuição do feedback do cliente |
| Engenharia | Método muda de time para time | Metodologias consistentes; entrar mais cedo no planejamento de roadmap |

## 7. Roadshow
Envolva PMs e stakeholders **cedo**. Pauta:
- O que é Product Ops e por que ajuda a **nossa** organização
- Como ProdOps trabalha com cada área
- Resultados possíveis
- Exemplos de outras empresas (casos em `casos.md`)
- Roadmap de implantação ("agora, próximo, depois")

Construa uma **narrativa consistente**, compartilhe vitórias recentes e **repita**: repetição é chave.

## 8. Os primeiros 30 a 60 dias (caso Amplitude)
Shintaro Matsui, primeira pessoa de ProdOps na Amplitude, evitou "ferver o oceano":

1. **Listening tour:** cerca de 35 conversas individuais (recomenda de 15 a 20) com produto, UX, engenharia, GTM, vendas, CS e executivos. Pergunta de abertura: *"O que é doloroso para você na relação com product management?"*. ("Me senti um terapeuta.")
2. **Agrupar por impacto:** agrupe as dores por time e pergunte "se eu pudesse resolver uma ou duas coisas para você, quais seriam?".
3. **Matriz impacto × esforço:** no exemplo, comunicação e documentação tinham alto impacto; GTM e SDLC, alto impacto e alto esforço; roadmapping e democratizar pesquisa, menor prioridade naquele momento.
4. Tentou primeiro o "grandão" (novo framework de lançamento com todos os stakeholders) e, na 2ª semana, viu que tinha mordido mais do que podia mastigar. **Pivotou para quick wins.**

**Quick wins:**
- **Newsletter de produto** (1ª semana): mensal, "super básica", com lançamentos e alphas e betas em andamento, cerca de 5 minutos por PM para preencher. O GTM a elegeu nº 1 em valor (PMs não gostam de preencher; o GTM ama). Reduziu perguntas ad hoc. Automatize lembretes e cobranças.
- **Confiança via piloto:** cada time lançava produto de um jeito. Desenharam com stakeholders uma versão alpha do processo de lançamento e **pilotaram com um único pod**, iterando. Discurso: "o processo não é meu, é de vocês; eu só pastoreio". No fim, **os próprios PMs** apresentaram e evangelizaram (adoção de baixo para cima).
- **Fechar o loop:** volte a quem relatou a dor: "Você me contou isto; lançamos aquilo; está atendendo?". Divulgue quando a solução beneficiar outros.

**Dicas:** comece pequeno (um pod) · ache **promotores** cedo · **diga não** e leve ao gestor um slide do que é viável hoje e do que outra contratação destravaria.

## 9. Apoio executivo
- Pode nascer do executivo (ex.: CPO da Sam's Club com plano de staffing sequenciado aprovado pelo CEO) ou de baixo (um PM vê o gap e vira ProdOps).
- **CPO:** garanta que CEO e pares entendam como ProdOps melhora a colaboração; mostre ProdOps informando e monitorando a estratégia **nas reuniões executivas**.
- **Diretor:** ajude o CPO a visualizar o estado ideal de visibilidade de portfólio.
- **PM:** exponha gaps, arregace as mangas, junte quick wins. Fala: *"Imagine se tivéssemos uma pessoa dedicada a [oportunidade]."*
- Use o executivo como "ás" para destravar resistência só depois de esgotar a influência.
- **Recessão:** funções de habilitação são aposta de longo prazo e as primeiras a serem questionadas. Mostre todo dia o retorno dos quick wins e das apostas, e **embuta ProdOps no fluxo de construção** (ex.: todo release exige a instrumentação garantida por ProdOps; cortar fica impensável).
- Lição: **gerenciar para cima** é o nome do jogo.

## 10. Liderar sem autoridade formal
Cenário comum: alguém lidera o tema de ProdOps (muitas vezes como PM, squad leader ou líder de um time) sem ter os demais PMs como subordinados. O livro mostra caminhos que funcionam:
- **Caminho "caseiro":** começar resolvendo um problema discreto como projeto paralelo e virar ProdOps (Christine Itwaru, na Pendo, era diretora de produto e saiu de 1 para 11 pessoas em menos de 2 anos).
- **Influência > mandato:** cocrie o processo com os PMs ("é o processo de vocês"), pilote com um time e deixe os promotores evangelizarem.
- **Mostre fazendo:** protótipo manual com dado real convence mais que descrição (calendário de lançamentos montado em 1 dia na Stripe).
- **Defina visão, missão e escopo primeiro** para não virar papel de preenchimento; aprenda a dizer não.
- **Patrocinador:** amarre a iniciativa a um executivo e às metas dele.
- **Ritual visível:** fórum recorrente (guild, product talk) onde as vitórias e os próximos passos aparecem.

## 11. Primeiros passos (do livro)
1. **Forças e deficiências:** use os 3 pilares para ver onde a empresa sobra e onde falta (tabelas da seção 2; `templates/diagnostico.md`).
2. **Proposta de valor de ProdOps:** poucas frases sobre desafios e oportunidades do pilar prioritário e como ProdOps dá alavancagem.
3. **Pitch ao gestor:** conversa casual primeiro ("estou lendo sobre isso e vi padrões que se parecem com os nossos em [pilar]"), depois proponha um one-pager de como ProdOps pode gerar alavancagem.
