# Pilar 2: Insights de Cliente e Mercado

> **Quando ler:** para estruturar voz do cliente, fluxo de feedback de vendas e suporte para produto, pesquisa com usuários (acesso, repositório, democratização), análise de mercado (TAM/SAM/SOM) ou inteligência competitiva.

## Sumário
1. Princípio · 2. Por que PMs não falam com clientes · 3. Os 3 objetivos de customer insights · 4. Mapear o que já existe · 5. Organizar a pesquisa com usuários · 6. Papéis · 7. Pesquisa de mercado e sizing · 8. Inteligência competitiva · 9. Caso Fidelity (Research Ops) · 10. Primeiros passos

## 1. Princípio
> "Iniciativas de pesquisa não valem nada se o time de produto não consegue usar o resultado." (Hugo Froes, OLX)

O pilar 1 trata do que geramos **internamente**; este pilar facilita e agrega o que vem de **fora**, tornando o insight acessível e reutilizável. Comece onde estão as maiores lacunas; em geral, primeiro o fluxo de **customer insights**, depois a pesquisa de mercado.

## 2. Por que PMs ainda não falam com clientes
- **Logística:** a entrevista é a parte fácil; recrutar, agendar e interpretar é que pesa.
- **Guardiões:** vendas e CS restringem acesso a clientes (renovações, relações sensíveis).
- **Medo de incomodar:** a gestão bloqueia "pedidos demais" e o PM recorre a pesquisas menos eficazes.
- **Câmara de eco:** o time recorre sempre ao mesmo cliente simpático (o "Saasify" do caso) e decide com base num subconjunto pequeno; ninguém fala com quem é da persona mas **não** é cliente.
- **Aprendizado isolado:** o aprendizado fica no time que pesquisou.

Nada disso justifica não pesquisar; justifica **montar o sistema**.

## 3. Os 3 objetivos de customer insights
1. Levar o dado que **já existe** sobre clientes (em vários times) ao PM certo.
2. Facilitar agendar e conduzir pesquisa generativa e avaliativa quando necessário.
3. Tornar a pesquisa **acessível e reutilizável** por todos os times.

**Fontes que já existem, sem nova pesquisa:** win/loss de vendas · reviews públicos · chamados e e-mails de suporte · pesquisas de outros times · pesquisas antigas que já respondem à pergunta atual.

**Não só entrevistas:**
- Se o CEO diz "já pesquisamos muito", levante o que já se sabe e mostre quais **lacunas** as entrevistas vão preencher. Isso acelera e gera aprovação.
- Se a empresa pesquisa "até a morte" antes de decidir, defina diretrizes breves com um **limiar de pesquisa** e um acordo de que a decisão sai ali. Em geral, a partir da 9ª entrevista o feedback começa a se repetir.

## 4. Mapear o que já existe (feedback interno)
**Passo a passo:**
1. Reúna os times que falam com cliente: vendas, account management, suporte, UX, GTM e PMs.
2. Comece **pelos times** e depois mapeie **os sistemas** onde anotam. Monte a tabela de ativos (`templates/tabela-ativos-insights.md`).
3. Inspecione a **qualidade**: o que vendas e AMs registram serve ao PM? Muitas vezes não sabem o que produto precisa (ex.: registram "perdemos para o concorrente" sem o **motivo**: preço, paridade de features, encaixe). Ajuste tags com Sales Ops e suporte.
4. Com dados limpos e tagueados: relatórios recorrentes por time de produto, automação do fluxo e **deep dives** com as áreas de origem.
5. Mantenha a rastreabilidade **ideia de produto → input de origem**: é a melhor arma de buy-in.

Exemplo de tabela (Pipeline 3K):

| Time | Dados coletados | Sistema | Frequência |
|---|---|---|---|
| Vendas | Win/loss, análise competitiva, gaps de feature, personas de venda | CRM | Diária |
| Account managers | Upsell e cross-sell, problemas de adoção, feedback de produto | CRM | Mensal |
| Suporte | Bugs, problemas de UX, gambiarras documentadas, pedidos ad hoc | Helpdesk | Diária |
| PMs | Desejabilidade, validação de problema e solução, pesquisa avaliativa | Docs | Mensal |
| UX Research | Generativa, avaliativa, personas, problemas, clientes voluntários | Docs | Semanal |

**Dois fluxos de trabalho** (comece pelo 1, de alavancagem mais imediata):
- **Fluxo 1, organizar e reportar o feedback:** revisar CRM e tags com Sales Ops; criar com vendas e suporte um canal para inputs a produto; relatório mensal por time de produto; cadência de troca vendas, suporte e produto sobre roadmap e lançamentos; orientar quais perguntas fazer aos clientes.
- **Fluxo 2, liderar a pesquisa com usuários:** treinar em boa pesquisa, com playbook curto e revisão de planos; definir onde os resultados ficam; recomendar ferramentas; organizar a base de contatos para pesquisa e testes.

## 5. Organizar a pesquisa com usuários
Duas iniciativas-chave (athenahealth, com cerca de 5 mil pessoas):

**Conselho ou painel de usuários (*User Research Council*):** base de mais de 3 mil usuários voluntários, com:
- tipos de pesquisa que aceitam (entrevista, teste de produto novo...) e frequência;
- account manager responsável, **último contato** e outros dados relevantes;
- acesso para PMs, pesquisadores e designers.

Resultado: menos risco de saturar clientes e pesquisa mais diversa e de qualidade.

**Repositório de pesquisa:** notas, vídeos, dados qualitativos e quantitativos (surveys) **pesquisáveis**, para ver se a pergunta já foi respondida. Ferramentas: Dovetail, Notion, Google Docs ou solução própria.

**Onde a função mora:**
- Em empresa grande com UX forte, pode ficar em **Design Ops** ou **Research Ops** (ex.: athenahealth com centenas de pessoas de UX para mais de 350 squads; design system vira divisor de águas).
- Em time pequeno, designe alguém com forte background de pesquisa e foque no **repositório** e no **acesso a clientes**.
- Seja qual for o formato, ProdOps e DesignOps trabalham juntos de forma constante.

## 6. Papéis: pesquisador × PM × Product Ops

| Papel | Responsabilidade |
|---|---|
| UX Researcher | Dono da **metodologia**; conduz grandes estudos generativos e, em times grandes, muitas entrevistas focadas |
| PM | **Consumidor** da pesquisa; também desenha e conduz a própria pesquisa e participa com frequência das sessões; com poucos pesquisadores, pede orientação e executa |
| Product Ops | **Facilita**: ferramentas e sistemas para que os outros foquem no conteúdo, não no processo |

ProdOps não substitui o pesquisador. Quanto menor a empresa, mais o PM e o designer fazem tudo.

## 7. Pesquisa de mercado e sizing de oportunidade
**Papel correto:** entender o valor de um mercado potencial (o quadro geral, não entrevistas individuais): concorrentes, tendências e quanto valor existe em cada mercado. Um bom time de market research **não** "toma" as entrevistas dos PMs.

**Por que importa:** "como priorizamos?" é a pergunta mais comum. Modelos de pontuação e Kano funcionam para trade-offs de feature, mas **decisões grandes de negócio** pedem entender a oportunidade, sobretudo em expansão. Bons modelos acabam com brigas de hipótese ("vamos parar de brigar por hipotéticos").

**Perguntas antes de expandir:**
- Qual é o tamanho de mercado de cada opção?
- Conseguimos penetrar ou o mercado está saturado?
- Qual é a duração dos contratos dos concorrentes? Teremos de esperar 3 anos para vencerem?

**TAM, SAM e SOM:**
- **TAM:** valor total se capturássemos o mercado inteiro (ex.: todas as empresas que usam ou podem usar ferramentas de pipeline de contratação).
- **SAM:** parte do TAM atendível com produtos atuais ou futuros, dado o alcance geográfico, sem considerar concorrência (ex.: empresas nos EUA com mais de 500 funcionários).
- **SOM:** parte do SAM realisticamente capturável, considerando tempo de desenvolvimento, concorrência e capacidade de vendas (ex.: as anteriores com orçamento e intenção de trocar de ferramenta em 6 meses).

> Executivos se empolgam com o TAM ("oportunidade de $200MM!") e esquecem o SOM.

**Caso (empresa de energia migrando de consultoria para SaaS):** o MVP de workflow completo para um novo dataset demorava, e a empresa estava ficando cética. A pesquisa revelou **duas personas**: quem usa workflow e quem quer dados diretos para os próprios modelos. O cálculo de SOM (duração de contratos, risco de churn, o que dava para lançar em 1 a 2 anos) mostrou **cerca de $2MM em 2 anos** focando no workflow contra **cerca de $30MM no ano seguinte** realocando parte do time para **APIs**. Os números mudaram a conversa do CEO.

**Perfil para o trabalho:** o cálculo é trabalhoso (tipos de empresa, gasto com software similar, contratos, geografia; cenários de melhor e pior caso conforme capacidade de vendas e prazo). Bom perfil: analista com 2 a 3 anos de consultoria (Deloitte, McKinsey...), forte com grandes volumes de dados, muitas vezes querendo virar PM. Você dá as perguntas e o contexto de produto; ele traz as respostas.

## 8. Inteligência competitiva
- **Não duplique Product Marketing**, que cuida de posicionamento, tendências e concorrência. ProdOps cobre o que falta para o PM: features novas de concorrentes, expansão para novos mercados.
- Sem Product Marketing: assine relatórios de mercado (Gartner, Forrester); é baixo esforço para entrar no contexto.
- **Experimente o concorrente:** ProdOps centraliza logins e contas demo para uso da empresa.
- Sem acesso: peça a prospects ou clientes considerando trocar que **compartilhem a tela** do concorrente e expliquem os motivos; grave e guarde no repositório.
- Alertas (ex.: Google Alerts) só arranham a superfície.

## 9. Caso Fidelity: Research Ops e democratização
Contexto: centenas de squads e 65 pesquisadores; não dá (nem é desejável) ter um pesquisador por time. Meta da Research Ops: **aumentar a velocidade de aprendizado** sem virar gargalo.

**Para pesquisadores:**
- **Framework de pesquisa por fase do ciclo de produto**, que educa os times e qualifica os pedidos:

| Fase | Pergunta central | Entregáveis | Métodos |
|---|---|---|---|
| Descobrir | Que necessidades priorizar? Como as pessoas resolvem hoje? | Análise de necessidades, mapa de experiência | Entrevistas, JTBD, surveys, análise competitiva |
| Definir | As experiências atuais atendem às necessidades? | Usefulness Assessment, análise de fricção digital, teste de usabilidade | Elicitação de tarefas, teste moderado, avaliação heurística |
| Desenhar | As propostas têm valor para o público? | Teste de conceito (qualitativo e quantitativo) | Entrevistas, surveys, cocriação |
| Desenvolver | São fáceis de usar? | Teste de usabilidade | Moderado e não moderado, card sorting, tree testing |
| Implantar | Por que as pessoas se comportam assim? Como melhorar resultados? | Usabilidade, fricção digital | Não moderado, heurística, síntese de feedback |

- **Usefulness Assessment:** matriz de necessidades do usuário ranqueadas × produtos ou features (atendida, parcial, não atendida). Revela sobreposições e "fragmentos de boas experiências" que, unidos, teriam mais impacto.
- **Sistema de acesso a usuários:** painéis e modos de contato (estudos *blind* e *branded*) dentro das regras de compliance. Recrutamento caiu de **até 2 meses para 2 dias**.

**Para não pesquisadores:**
- **Programa de democratização:** treina e certifica para teste de usabilidade não moderado. Foram mais de 300 certificados e mais de 600 estudos; a fila caiu de no mínimo **14 para 3 dias**. Dois pilares: **educação contextual** (o aluno chega com uma agenda real de aprendizado e aplica enquanto aprende) e **buddies** (cada formado tem um pesquisador que revisa o trabalho).
- **Repositório "Lighthouse":** inclui pesquisa de UX, mercado, CX, marca e pesquisa licenciada de terceiros. Regra: **consulte o repositório antes de abrir um pedido de pesquisa**; o resultado novo volta para o repositório.

**Dicas para começar (Jen Cardello):**
- Faça um **listening tour**: dores, necessidades, percepção sobre insights, entendimento de product management.
- Com pesquisadores: analise **6 a 12 meses de pesquisas** por "fase" e "pergunta respondida". Em geral há usabilidade avaliativa demais; leve a pesquisa **para montante**, influenciando o que é útil (product-market fit).
- Democratize mesmo sem ter centenas de squads.
- Sem pesquisadores: monte com os líderes uma **agenda de aprendizado** (necessidades → testes de conceito → usabilidade) para priorizar sem se afogar.
- Métricas de sucesso: taxa de **insight → ação**, crescimento de certificações e aceleração de cronogramas, sobretudo de recrutamento.

## 10. Primeiros passos (do livro)
1. **Tabela de ativos de insights:** por time, tipo de dado, sistema e frequência; revela lacunas (e muitas vezes que a situação é melhor do que parecia).
2. **Atualize-se em tendências de mercado:** descubra quais assinaturas existem (Gartner, Forrester...); a senha às vezes está com alguém que já saiu.
3. **Avalie as ferramentas de pesquisa** (prototipação, surveys, pesquisa): **Catalogar** (que recursos existem?) → **Contextualizar** (qual era a intenção ou hipótese de cada canal?) → **Criar** (até onde chegamos numa visão 360° com o que existe?). Dá para montar essa visão em cerca de **90 dias**, sem começar do zero.
