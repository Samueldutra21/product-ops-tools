# Pilar 3b: Processos do PM, Toolkits e Ferramentas

> **Quando ler:** para padronizar o trabalho do PM (gestão de ideias, roadmaps por audiência, status de desenvolvimento, templates de discovery, estratégia e GTM), montar onboarding, Community of Practice ou guild, ou avaliar a stack de ferramentas.

## Sumário
1. Processo na medida certa · 2. Gestão de ideias · 3. Roadmaps por audiência · 4. Status de desenvolvimento (Discovery → GA) · 5. Toolkits e templates · 6. Onboarding e treinamento · 7. Community of Practice · 8. Ferramentas de habilitação · 9. Manutenção contínua

## 1. Processo na medida certa
- Para não virar "process people", **não padronize tudo**. Padronize o que (a) **atravessa áreas** ou (b) é **usado por muitas pessoas**.
- Antiexemplo (Spotify, há cerca de uma década): cada time decidia tudo, com processo de release, ferramenta de tracking e roadmapping próprios. Resultado: zero visibilidade e trocar de time exigia reaprender o sistema.
- Áreas centrais a padronizar: **gestão de ideias, roadmapping, toolkits de produto e onboarding**.
- Nada disso substitui PMs qualificados: processo só ajuda se o input é bom.
- Entregue **estrutura, não mandato**: um template de roadmap padroniza **como se comunica**, não **como se decide** o roadmap. PMs costumam sentir alívio por não reinventar a roda.

## 2. Gestão de ideias
As melhores ideias vêm de todo lugar (vendas, marketing, engenharia, suporte, clientes). "Icebox" e "parking lot" costumam não funcionar. Preserve o **porquê por trás do quê** (origem e contexto).

**Plano em 3 perguntas:**
1. **Onde** parceiros e clientes submetem ideias?
2. **Como** garantir um formato útil?
3. **Como** devolver o status a quem pediu?

**Diretrizes:**
- Use a ferramenta que já existe (ex.: ProdPad tem portal de ideias e status); sem ferramenta, crie um formulário e uma regra de roteamento (manual ou automática).
- Pedidos chegam com cara de **solução**; o formulário deve extrair o **problema**. Use um formato de "complete as lacunas" (*Mad Libs*). Diferença: "deixe o botão amarelo" × "não acho o botão de enviar".
- **Feche o loop:** diga o que esperar (resposta, atualização, progresso, status no backlog) e, ao recusar, **explique o porquê e os critérios** usados.
- Sem ferramenta de produto? Estenda as de vendas e suporte (Salesforce, Zendesk) via API para levar a informação ao sistema de produto.

Ver `templates/formulario-ideias.md`.

## 3. Roadmaps por audiência
Não existe um roadmap que sirva para tudo; roadmap é **ferramenta de comunicação**. ProdOps não decide o conteúdo, mas traz simplicidade e estrutura a **como** ele é mostrado.

| Audiência | Conteúdo | Horizonte e granularidade |
|---|---|---|
| Times de desenvolvimento | Detalhado; compromissos de engenharia por trimestre; status de discovery e delivery | Cerca de 1 trimestre |
| Vendas | Menos detalhe; problemas resolvidos; janela aproximada; **narrativa e proposta de valor** por item | Trimestre ou semestre |
| Liderança | Camada iniciativa → intenção estratégica; dependências; capacidade | Trimestral |

- Todo item liga a uma **justificativa** de por que o fazemos e como move o negócio, rastreável até as ideias e inputs de origem.
- Publique num lugar acessível (wiki ou ferramenta); os donos mantêm atualizado.
- Implementação de referência: ferramenta de roadmap com os níveis de estratégia replicados (intenção → iniciativa → opção), **template de escrita para cada nível** e diretrizes de escopo por nível. Assim, relatórios saem direto para cada fórum: o review cross-funcional mostra o que está em alpha ou além, com discovery detalhado; o review de produto mostra tudo; a liderança vê iniciativas e progresso rumo às intenções. Muitas ferramentas geram esses relatórios prontos.

## 4. Status de desenvolvimento (Discovery → Alpha → Beta → GA)
**Causa raiz do "vendas promete demais":** vendas não distingue os estágios, e um protótipo clicável **parece pronto**. A solução não é esconder o roadmap; é dar transparência com regras.

| Status | Significado | Regra para vendas |
|---|---|---|
| **Discovery** | Problema ou solução ainda não validados; protótipos, experimentos, pesquisa; baixa chance de virar entrega | **Não fala** com cliente |
| **Alpha** | Problema validado, boa direção de solução, software sendo construído e testado com um grupo pequeno; muda muito | Pode falar do **problema**, não prometer solução |
| **Beta** | Solução validada; testa escala. Beta fechado (até cerca de 10% dos usuários, cientes do teste) → beta aberto (mais personas) | Pode **demonstrar** e dizer que está chegando (lançamento em cerca de 1 trimestre e formato parecido) |
| **GA** | Em produção, disponível para todos | Vende e implanta |

A probabilidade de entrega cresce da esquerda para a direita. Todo item de roadmap (no nível de opção) recebe um status. Efeito: vendas ganha visibilidade do pipeline e produto ganha regras claras do que pode ser vendido; a desconfiança dos PMs em relação a "roadmap na mão de vendas" se dissolve.

## 5. Toolkits e templates
Função: dar orientação de método e expectativas (ex.: "fale com 3 a 5 clientes") para o time focar no trabalho de alto impacto, não em detalhes de formato. Também comunicam aos stakeholders **como** eles se plugam no processo de produto.

**Perguntas para decidir o que padronizar** (percorra o ciclo de vida do produto e as cadências com stakeholders):
- Há software usado com frequência nesta fase que justifica licença corporativa?
- Que informação sai do time de produto, e quando?
- Que informação **não** é compartilhada de forma consistente e causa problemas?
- Quem é a audiência de cada template?
- Como padronizar o modo como outros times trabalham conosco?

**Toolkit de Discovery**
- Templates: **resultado de experimento** (hipótese, experimento, resultado, próximos passos), num wiki aberto à empresa e compartilhado com quem pediu a ideia; **personas vivas** no wiki, com template para novas.
- Software: consolidar prototipação (de 10 ferramentas para uma low-fi e uma hi-fi com licença geral); ferramenta de recrutamento para testes de usabilidade; A/B só com terceiros se a ferramenta interna não bastar.

**Toolkit de Estratégia**
- **Strategy memos** (2 a 3 páginas) para cada intenção estratégica, iniciativa de portfólio e de produto: apresentam o conceito para feedback e depois ficam como referência.
- **Visões e briefs de produto** para produtos novos: como a solução deve funcionar e como o cliente usará; às vezes com protótipo ou deck de visão.
- **Templates de strategy review:** cada participante preenche antes e ProdOps consolida num deck mestre; todos cobrem o essencial.
- A ferramenta de roadmap guarda a estratégia ligada ao roadmap e ao plano de recursos.

**Toolkit de Go-to-Market**
- **Plano mestre de lançamento:** cronograma, responsáveis, material de treinamento, segmentação de clientes; checklist que vira pauta semanal e, perto do lançamento, diária.
- **Release notes:** formato padrão para clientes e times internos.
- **Demos internas:** cadência e template.
- Antiexemplo: empresa de life sciences com mais de 10 verticais e um processo de GTM por vertical; vendas passava duas semanas aprendendo as regras de cada time antes de começar.

Ver `templates/experimento.md`, `templates/strategy-memo.md`, `templates/one-pager-iniciativa.md`, `templates/gtm-launch-kit.md`.

## 6. Onboarding e treinamento
ProdOps é parceiro do líder de produto em coaching e padrões, principalmente para os mais juniores.

**Onboarding de PMs novos:**
- Treinamento básico de product management
- Par com PM experiente ou coach (suporte, dúvidas, contexto)
- Templates e toolkits padronizados
- Acesso e treinamento nas ferramentas

Em empresas maiores, o líder de ProdOps pode dar coaching complementar a ICs. Ver `templates/onboarding-pm.md`.

## 7. Community of Practice (guild de produto)
Espaço para quem tem o mesmo papel desenvolver habilidades avançadas e compartilhar desafios. Atividades típicas:
- Lunch-and-learns internos
- Demos "Como você fez isso?" entre colegas
- Programação trimestral com especialistas externos
- Espaço online com eventos externos (webinars, conferências)
- Desenvolvimento profissional consistente (treinamentos direcionados)

A CoP também **mantém os playbooks de boas práticas e os toolkits**: é o mecanismo de governança do próprio padrão.

## 8. Ferramentas de habilitação
- Ferramenta **habilita, não resolve**: "quando tivermos o software, o roadmapping estará resolvido" é uma armadilha. A ferramenta reforça o processo, não o substitui.
- Ferramenta é tão boa quanto seu input ("Jira com 80 níveis de tickets, todos marcados como épico"). Treine de forma consistente.

**Como gerir:**
1. **Inventário** de licenças em todos os times (prepare-se para "a gente paga por isso?").
2. Mapeie processos atuais e próximos e onde uma ferramenta acrescentaria alavancagem.
3. Defina um **dono** da stack (procurement, treinamento, licenças, onboarding, habilitação).
4. Mantenha um **roadmap de ferramentas** de curto e longo prazo, com o que existe e o que pode vir.
5. Crie um **grupo de trabalho cross-funcional** para avaliar e recomendar ferramentas com critérios consistentes (`templates/avaliacao-ferramentas.md`).

**Categorias e exemplos do livro:**

| Categoria | Uso | Exemplos |
|---|---|---|
| Engajamento de produto | Dados acionáveis centrados no produto | Amplitude, Pendo |
| Testes e experimentação | Experimentos, personalização, feature flags | Optimizely, Eppo |
| Analytics visual | Dashboards | Looker, Tableau |
| Roadmap e portfólio | Fatiar visões de roadmap | Productboard, Dragonboat |
| Gestão de ideias | Coletar ideias da organização | Aha!, Notion |
| Tagueamento de eventos e CDP | Instrumentar uma vez no código | Segment, Tealium |
| Adoção digital e surveys in-app | Onboarding integrado, sentimento | Appcues, WalkMe |
| Repositório de pesquisa | Reaproveitar pesquisa entre PMs | Dovetail, Notion |
| OKRs e metas | Alinhar times às prioridades | Workboard, Perdoo |

Na prática, a gestão da stack pode puxar **gestão de fornecedores e orçamento** para o escopo de ProdOps (caso OLX); é uma extensão natural, não desvio.

## 9. Manutenção contínua (não deixe o processo apodrecer)
- "Se você não revisita uma ferramenta ou processo de forma proativa, espere que quebre" (Matsui, Amplitude): uma ferramenta de feedback "que funcionava" acumulou 1.000 tickets, os PMs pararam de atualizar o roadmap e o GTM se irritou.
- **Revisão trimestral de processos e ferramentas** (30 minutos com alguns PMs e a liderança): liste todos (planejamento anual e trimestral, syncs, newsletter, ferramenta de feedback...) e peça um ranking de 1 (mais útil) a 10 (menos útil) e sugestões. Dobre a aposta no topo; melhore ou **mate** o fundo. Compartilhe o resultado com transparência. Ver `templates/revisao-trimestral-processos.md`.
- Prefira **princípios** a regras rígidas: dê espaço para os times aplicarem do seu jeito e ofereça coaching quando não conseguirem (Froes).
