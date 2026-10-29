# Casos Reais: Padrões Reutilizáveis

> **Quando ler:** para citar exemplos em business case, roadshow ou apresentação, ou para buscar inspiração para um problema específico. Cada caso traz contexto, o que foi feito, resultado e o **padrão reutilizável**. Os detalhes completos estão nas referências indicadas.

## athenahealth: capitalização de software via Jira
- **Contexto:** mais de 200 squads; finanças pedia, 6 vezes por ano, a classificação do trabalho em planilha (mais de 400 h/ano de líderes). Timesheet foi descartado por questão cultural. ProdOps tinha credibilidade baixa (atendia poucos times).
- **Feito:** hierarquia padrão Iniciativa → Feature → Épico → História; 2 tipos de Feature; campo de categoria (Nova feature e Tecnologia fundacional são capitalizadas; Confiabilidade reativa e Experimental vão para despesa); roadshow de educação; cerca de 35 mil histórias vinculadas; piloto de 6 meses validado com auditoria.
- **Resultado:** mais de 400 h/ano economizadas, maior precisão e um ativo de dados que habilita gestão de portfólio. ProdOps ganhou respeito.
- **Padrão:** resolver uma dor administrativa de alto custo **e** usar a solução como alavanca de padronização e visibilidade de portfólio. Ver `pilar-1-dados-insights.md`, seção 9.

## athenahealth (DesignOps): conselho de usuários e repositório
- Base de mais de 3 mil usuários voluntários com preferências de pesquisa, account manager e último contato; repositório de notas e vídeos pesquisável.
- **Padrão:** acesso a usuários + repositório = menos saturação de clientes e pesquisa diversa e reutilizável. Ver `pilar-2-cliente-mercado.md`, seção 5.

## Fidelity: Research Ops e democratização
- **Contexto:** centenas de squads e 65 pesquisadores; ambiente regulado.
- **Feito:** framework de pesquisa por fase; Usefulness Assessment; sistema de acesso a usuários (recrutamento de 2 meses para 2 dias); programa de democratização com certificação e buddies (mais de 300 certificados, mais de 600 estudos, fila de 14 para 3 dias); repositório "Lighthouse" ("consulte antes de pedir").
- **Padrão:** escalar pesquisa ensinando os times a pescar, com controle de qualidade, em vez de contratar um pesquisador por time. Ver `pilar-2-cliente-mercado.md`, seção 9.

## Oscar Health: planejamento anual
- **Contexto:** 15 product ops managers, cerca de 65 PMs, 50 pods, ambiente regulado.
- **Feito:** rascunho "de tudo" → cerca de 20 one-pagers → "One-Pager Rager" → linha de corte → OKRs e estimativa bottom-up (120% de capacidade → alvo de cerca de 90%) → 6 categorias de investimento → "phone a friend" → hype slides → checagem cruzada com as áreas.
- **Resultado:** "o planejamento anual mais eficaz em anos" (CPO); um risco de integração com fornecedor detectado em março em vez de no 3º ou 4º trimestre.
- **Padrão:** ProdOps desenha a cadência de inputs, decisões e comunicação, com reuniões curtas e resultado definido. Ver `pilar-3a-governanca-planejamento.md`, seção 9.

## Amplitude: quick wins da primeira pessoa
- **Feito:** listening tour (cerca de 35 conversas) → agrupamento → matriz impacto × esforço; recuou do "grandão" (framework de lançamento) para quick wins: newsletter mensal (nº 1 em valor para o GTM), piloto do processo de lançamento com 1 pod (os PMs evangelizaram), fechamento de loop com quem relatou dores; revisão trimestral de processos (ranking de 1 a 10).
- **Padrão:** comece pequeno, ache promotores, diga não e mostre valor em semanas. Ver `implantacao-buy-in.md`, seção 8.

## Uber: tecido conectivo entre produto e cidades
- **Contexto (2015):** expansão de cidades; desconexão crescente entre times de produto e operações locais.
- **Feito:** dezenas de conversas; charter acima e abaixo da linha; newsletter quinzenal global (até para quem acabou de entrar); time formado por operadores de cidade com anos de casa pareados com PMs; programas centrais em evolução (anúncios → newsletter → apresentações mensais → roadmap universal com visões regionais → OKRs consolidados).
- **Resultado:** mais de 70 pessoas; colaboração acelerada e adoção de novos produtos.
- **Padrão:** recrutar ProdOps entre operadores que conhecem o negócio na ponta. Ver `estruturar-escalar.md`, seção 7.

## Stripe: programas centrais e modelo pago
- **Feito:** charter no 1º mês; calendário único de lançamentos prototipado manualmente em 1 dia; modelo híbrido (embarcado e central em paralelo); financiamento passou a ser pago pelas áreas (PoP) com one-pager de valor.
- **Resultado:** mais de 50 pessoas.
- **Padrão:** "fazer em vez de descrever"; programas centrais elevam a maré com pouca gente. Ver `estruturar-escalar.md`, seção 7.

## Pendo: de diretora de produto a time de 11
- **Feito:** fonte única de verdade de estratégia e roadmap; explicação do "porquê" ao time de receita; loop de feedback de clientes e suporte → PMs; depois, governança, centro de excelência e padrões de analytics.
- **Padrão:** nascer "caseiro", a partir da dor bidirecional vendas ↔ produto. Ver `estruturar-escalar.md`, seção 1.

## Sam's Club: ProdOps puxado pelo CPO
- Cerca de 350 PMs e designers; o CPO viu trabalho inconsistente entre times e propôs ProdOps (visibilidade de portfólio, ferramentas, padronização, programa de APM); o CEO entendeu de imediato a alavancagem para otimizar o investimento em tecnologia. Organograma com contratações escalonadas, começando pelo senior director.
- **Padrão:** plano de staffing sequenciado com valor explícito em cada etapa.

## Doodle: dados conectados ao flywheel
- Data warehouse com BI (Power BI, PopSQL) e todos treinados para autosserviço em cerca de 1 ano; priorização semanal de novos pedidos de captura; o flywheel liga métricas de produto (ex.: nº de reuniões) à receita.
- **Padrão:** dado financeiro e de produto acoplados mostram o impacto no topline do que é entregue.

## Empresa de energia: SOM muda a estratégia
- TAM de "$200MM" empolgava o CEO; o cálculo de SOM mostrou cerca de $2MM em 2 anos (workflow) contra cerca de $30MM no ano seguinte (APIs para a persona que queria dados diretos).
- **Padrão:** sizing realista tira a discussão do hipotético. Ver `pilar-2-cliente-mercado.md`, seção 7.

## Outros sinais citados
- **OLX Motors (Hugo Froes):** time de um com alta influência; vendor management entrou no escopo como extensão da gestão de ferramentas; "evite virar papel de preenchimento".
- **FullStory (Becky Asch):** pesquisa de saúde colaborativa da tríade PM, UX e Eng como baseline do processo de priorização.
- **Segment/Twilio (Tina Laungani):** listening tour com mais de 80 pessoas apresentando o charter.
- **OutSystems (Anabela Cesario):** "ProdOps é um mini time de produto cujos clientes são os PMs"; promoção de VP de ProdOps a VP de PM.
- **Spotify (antiexemplo):** autonomia total sem padrão algum, com zero visibilidade e troca de time dolorosa.
- **Life sciences SaaS (antiexemplo):** mais de 10 verticais com GTMs diferentes; vendas perdia 2 semanas por time só para aprender as regras.
