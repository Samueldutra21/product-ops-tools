# Pilar 3a: Modelo Operacional, Governança e Planejamento

> **Quando ler:** para desenhar ou avaliar o Product Operating Model, cadências de decisão (QBR, roadmap reviews), priorização entre stakeholders e planejamento anual, trimestral ou contínuo. Para templates, roadmaps, gestão de ideias e ferramentas, veja `pilar-3b-processos-ferramentas.md`.

## Sumário
1. Processo sem alergia · 2. O que é o Product Operating Model · 3. Componentes e autoavaliação · 4. Governança · 5. Cadências de discussão estratégica · 6. Priorização · 7. Papel de ProdOps na governança · 8. Planejamento anual rumo ao contínuo · 9. Caso Oscar Health · 10. Primeiros passos

## 1. Processo sem alergia
- "Processo" é uma palavra carregada: alívio do caos para uns, burocracia para outros. Calibre o peso ao contexto.
- Fale em **método** ou **serviço**; trate ops como uma API com métodos versionados, descontinuando o que não é usado (Simon Hilton).
- O objetivo é trabalhar de forma mais inteligente: remover barreiras de colaboração e **aumentar a velocidade e a qualidade das decisões**, para que os times façam o trabalho em vez de gastar ciclos discutindo regras de convivência.

## 2. O que é o Product Operating Model
É **como a empresa codifica a tradução da estratégia de negócio e de produto em trabalho realizado**. Os pilares 1 e 2 informam a estratégia; o modelo operacional orienta a execução.
- O **CPO** define princípios, cultura e valores do time de produto.
- **ProdOps** ajuda a definir e pôr em prática **processo e governança**.
- Resultado: diretrizes de como o time de produto trabalha entre si e com outras áreas (roadmapping, revisão de estratégia, gestão de ideias, planejamento anual) e alinhamento da empresa em torno do desenvolvimento de produto.

## 3. Componentes e autoavaliação

| Componente | Itens |
|---|---|
| Papéis e responsabilidades | Descrições de cargo; trilhas de carreira; fronteiras entre PM e as outras funções |
| Processo para times de produto | Templates; discovery; roadmapping; stack de ferramentas; SDLC codificado |
| Diretrizes para trabalhar com outros times | Gestão e fluxo de ideias; SDLC explicado aos stakeholders; diretrizes de release e GTM |
| Governança e planejamento | Cadências e tipos de reunião; pontos de contato cross-funcionais |

**Autoavaliação por nota** (como a CPO do caso fez):
- Papéis (A−): cargos e trilhas padronizados com RH, mais um roadshow com outras áreas sobre as fronteiras. Efeito: designers pararam de disputar a pesquisa, vendas parou de prometer demais e envolveu PMs mais cedo.
- Processo dos times (B): faltavam templates e roadmaps consistentes.
- Diretrizes cross-funcionais (B): status de release já resolvia o "overselling"; faltava o fluxo de ideias.
- Governança e planejamento (F): reporting ad hoc a cada pedido de executivo, review trimestral virando arena, planejamento anual como maratona de uma semana que ficava obsoleta em 3 meses.

> Dê uma nota de A a F a cada componente e ataque o pior **que esteja bloqueando o momento atual** (ali, era época de planejamento anual).

## 4. Governança
**Definição:** supervisão de produto, mecanismos de revisão, gestão de risco, compliance, **ponto único de responsabilidade** e melhoria contínua. É como se gere inovação ligando processos a estratégia, modelo de negócio e capacidades. Insights e analytics são a espinha de monitoramento e alinhamento.

Perguntas de teste:
- OKRs e KPIs são revisados com **cadência consistente**?
- Dá para mudar o curso a tempo se não estão sendo atingidos?
- As **pessoas certas** (que decidem) estão na sala, ou os times só reportam sem ação?

**Duas peças:** (1) cadências de discussão estratégica e (2) pontos de contato cross-funcionais.

## 5. Cadências de discussão estratégica
Governança dá **foco**, e foco é dizer não a centenas de boas ideias (Steve Jobs). Reuniões mal desenhadas são caras e até nocivas.

**Antipadrão (Pipeline 3K):** roadmap readout trimestral aberto à empresa inteira. Planejado para meio dia, durou **2 dias**, com a empresa parada. Executivos sem contexto "sabatinavam" líderes de produto diante de mil pessoas; havia sugestões que ninguém ia executar e nenhum mecanismo de feedback. Pessoas erradas, detalhe demais, nenhuma saída acionável.

**Cadência de referência** (ajuste ao seu contexto):

| Frequência | Fórum | Participantes | Foco |
|---|---|---|---|
| Anual | Company Kick-Off (CKO) | Empresa toda | Estratégia de portfólio e produto e roadmap; história de sucessos e não sucessos |
| Trimestral | Quarterly Business Review (QBR) | Executivos e líderes cross-funcionais | OKRs e KPIs, progresso contra o plano, escalações antecipadas; **resultados e metas, não design ou detalhes** |
| Trimestral | Roadmap review cross-funcional (de portfólio) | Engenharia, vendas, marketing, CS, jurídico (líderes) | Progresso, riscos, interdependências entre iniciativas, feedback de alto nível, próximos passos |
| Mensal | Roadmap review (de produto) | Time de produto (PM, dev, design) e líderes cross-funcionais-chave | Opções do roadmap, direção, progresso rumo ao lançamento; fora de escopo: bugs e alocação |
| Mensal | Demo Days | Vendas, marketing, CS | Fase (alpha ou beta), quando pode ser vendido, o que há de novo |
| Quinzenal | Rituais ágeis do time | Engenharia e scrum lead | Sprint, riscos, dependências, bloqueios; **só o time** |

- O ponto não é seguir o ritual à risca, mas ter uma cadência que **force conversas e decisões difíceis** (Brian Bhuta, CPO da Forsta).
- Em empresas rápidas, um QBR pode ser pouco para vendas.
- Ajuste contínuo: convide **menos gente** para o QBR (quem não decide só assiste) e crie **outro canal** para coletar inputs fora da diretoria.

## 6. Priorização entre stakeholders
- Sem framework, prioriza-se **quem grita mais alto ou escala para o C-level**.
- Um framework **acordado por todos** força os stakeholders a considerar **trocas** em vez de só empilhar pedidos.
- Pode misturar resultados (mais flexibilidade e exploração) e features (mais controle e talvez velocidade).
- Recomendação dos autores: **pontuação ponderada (*weighted scoring*) combinada com custo do atraso (*cost of delay*)**, nos níveis de portfólio e de produto. Mais importante do que escolher o framework "perfeito" é escolher um que **alinhe** PM, engenharia, UX e stakeholders.
- Cultura-alvo: **"isto OU aquilo"**, não "sim, e também...". Empilhar trabalho sobre resultados já acordados leva a nada entregue ou a times espalhados em tudo (*peanut butter*), "entregando" sem valor real.
- O framework entra **na pauta** de cada fórum de governança; é o que permite ao PM dizer não com critério.

Ver `templates/priorizacao.md`.

## 7. Papel de ProdOps na governança
ProdOps **organiza**, mas não necessariamente **é dono** de cada reunião (ex.: o CPO conduz o portfolio review; ProdOps prepara tudo para que seja eficaz).
- Desenha a cadência e apresenta o contexto aos stakeholders; garante as pessoas certas na sala.
- Cria e distribui **com antecedência** templates de cada fórum (formato de report de OKR, business case de nova iniciativa).
- Monta a pauta, registra discussões e ações.
- Conduz a **retrospectiva** e a melhoria contínua da cadência.
- Torna **transparentes** para a organização as escolhas feitas; implanta as ferramentas para isso.
- Ajuda a escolher o framework de priorização e garante que iniciativas maiores sigam processo e cadência consistentes.
- Mede a **saúde colaborativa da tríade PM, UX e Eng** com pesquisa periódica (FullStory): o processo de priorização se conecta à estratégia? Dá para subir do que priorizo até a estratégia?

## 8. Planejamento anual rumo ao contínuo
**Custo:** segundo pesquisa da Dragonboat na comunidade ProductOps HQ (2023), de 25% a 50% das pessoas de produto e engenharia ficam envolvidas no planejamento trimestral por semanas ou meses; mesmo time pequeno pode custar cerca de um milhão de dólares. Por ser caro, faz-se uma vez por ano e perde-se a capacidade de ajustar à realidade e à concorrência.

**Meta:** com boa governança e software, o planejamento vira **contínuo**.
- Intenções estratégicas (de 2 a 3 anos) são revistas no **QBR**; quando uma está perto de ser atingida, o QBR abre a definição da próxima.
- Pré-requisito: **financiar times de produto, não iniciativas** (de mentalidade de projeto para mentalidade de produto).
- Transição prática: ao iniciar o ciclo, anuncie que **este é o último planejamento anual**; depois, migre para o trimestral.
- Planejamento não é seguir processo; é cadência para **conversas vitais** que tornam a empresa responsiva.

**Se ainda precisa do anual (e está atrasado):** não reinvente tudo; revise o que existia e melhore pontualmente. Perguntas de partida:
1. Que resultados centrais queremos com o planejamento anual?
2. Como produto e a organização colaboraram no passado?
3. Que processos existentes dá para aproveitar?

O que os stakeholders mais pedem: saber **qual é o processo**, **como** contribuir e **quando** contribuir. Templates de roadmap, orçamento e alocação trazem valor imediato. Faça parceria com o CFO.

## 9. Caso Oscar Health: planejamento anual bem orquestrado
Contexto: 15 product ops managers, cerca de 65 PMs, 250 engenheiros, 15 designers e 50 squads ("pods"), em ambiente regulado. ProdOps conduz o planejamento: desenha a cadência de inputs, decisões e comunicação; cria urgência; junta as pessoas certas; prepara reuniões objetivas com resultado definido; dá templates de alto engajamento e baixo esforço.

**Anatomia do planejamento:**

| Camada | Frequência |
|---|---|
| Visão da empresa | Uma vez |
| Estratégia de longo prazo | A cada poucos anos |
| Estratégia de curto prazo e metas | Anual (com discovery contínuo nas iniciativas locais) |
| Iniciativas **globais** (centrais, conhecidas da liderança, com subiniciativas, reservam espaço no roadmap dos pods) e **locais** (do pod, ligadas às mesmas metas, menos dependências) | Anual, com ajustes |
| Key Results | Anual, com ajustes |
| Roadmaps (alta confiança no próximo trimestre, visibilidade parcial depois) | Trimestral |
| Planos de recursos (épicos estimados em semanas; real × estimado no fim do trimestre) | Anual e trimestral |

> Iniciativas locais dão autonomia: um trabalho de grande valor (automatizar o pagamento a corretores) nunca seria priorizado se só existissem as globais.

**Calendário:**
- **Novembro, início:** documento "de tudo" (tudo o que precisa acontecer e por quê, inspirado em *The Phoenix Project*), validado com VPs e diretores. Agrupado em cerca de 20 iniciativas, com **one-pagers** (na prática, de 2 a 5 páginas), autores definidos e prioridade "must do / will do / should do". Kick-off conjunto de produto e engenharia com uma rodada rápida pelas iniciativas.
- **Dezembro, foco:** one-pagers com business case e marcos (que viraram cerca de 80 subiniciativas). "**One-Pager Rager**" de 4 horas: cada VP aprofunda de 4 a 5 iniciativas como pré-trabalho; votação em planilha do que discutir ao vivo; quem não vota, aprova como está. Definição da **linha de corte**.
- **Janeiro, proposta:** OKRs por iniciativa (planilha socializada para negociar conflitos) e **estimativa bottom-up** de recursos por pod, em engenheiros-ano com incrementos de 0,25 (um "chute científico", sem pretensão de precisão). A primeira passada consumia **120% da capacidade**; o alvo é **cerca de 90%**. Trocas em 3 perguntas: onde **estender prazo**, onde **reduzir escopo** e onde gerar impacto **sem engenharia** (processo, treinamento). Para executivos: 20 iniciativas agrupadas em **6 categorias de investimento** alinhadas às metas da empresa (incluindo KTLO). "**Phone a friend**": enquete com líderes de outras áreas sobre a alocação ideal, mostrando mais alinhamento do que divergência. Slides de aprofundamento por iniciativa prontos para as perguntas.
- **Fevereiro, adesão da linha de frente:** reunião conjunta com **"hype slide"** de 1 a 2 frases por iniciativa (foco na narrativa; OKRs no apêndice).
- **Março, checagem cruzada:** reuniões com as 3 maiores áreas parceiras (operações, receita e marketing, jurídico e compliance), cada uma trazendo sua lista de prioridades. Pegou uma integração com fornecedor que ninguém de tecnologia tinha no radar e que seria crítica no 3º ou 4º trimestre. Aprovação final virou carimbo.
- **Lição de melhoria:** falar com as áreas parceiras **antes** das estimativas (fim de novembro).

**Artefatos e reuniões que ProdOps entregou:** template de one-pager · framework de donos e revisão · tracker de OKRs · estimativa bottom-up · template de roadmap de pod · rascunho "de tudo" · slide de alocação de investimento · slides de aprofundamento · roll-ups e updates trimestrais · kick-off · One-Pager Rager · "sharpen the pencils" (CPO e CTO) · revisão do 1º rascunho com a liderança · overview de roadmap para a linha de frente · checagens cruzadas · revisão final.

## 10. Primeiros passos (do livro)
1. **Avalie os componentes atuais** do modelo operacional (seção 3), rascunhe os que faltam e refine com o CPO.
2. **Crie fóruns de decisão:** mapa de reuniões. Onde as decisões realmente acontecem? Quais juntam a empresa toda sem resultado? Comece pelo anual e desça em cascata: quem participa, foco, o que se discute e o que não, saídas esperadas (`templates/mapa-governanca.md`).
3. **Mapeie o feedback bidirecional** (1 hora): como o feedback do cliente vai do vendedor ao PM, ao backlog e à implementação? E o inverso: da ideação do PM até a atualização de vendas? Os buracos maiores viram prioridade.
