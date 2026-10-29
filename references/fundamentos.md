# Fundamentos de Product Operations

> **Quando ler:** para explicar o que é ProdOps, defender a função, diferenciá-la de PM, PMO ou outras "Ops", ou alinhar o vocabulário antes de qualquer trabalho.

## 1. Definição operacional

**Product Operations é a disciplina que ajuda a função de gestão de produto a escalar bem, cercando o time dos insumos essenciais para definir estratégia, priorizar e simplificar as formas de trabalho.**

- É uma **função de habilitação** (enablement): não toma a decisão, mas torna o processo de decisão mais fácil e transparente e, com isso, eleva a qualidade das decisões.
- É "o PM do PM": define o **modelo operacional** de como produto é feito na empresa e garante que a função de PM tenha o que precisa para ser saudável e gerar valor.
- Faz duas coisas: (1) reúne a informação espalhada pela empresa numa visão cross-funcional para líderes e PMs decidirem; (2) organiza a empresa em torno de **como** atingir as metas.

## 2. Por que a função surge

Padrão típico de crescimento:
1. Um produto, time pequeno, todo mundo sabe de tudo.
2. Segundo, terceiro, enésimo produto → mais gente → **feudos**: cada divisão olha para a própria linha, retém informação e cria seus próprios processos.
3. Ninguém consegue mais "juntar tudo" para continuar crescendo. O Agile quebrou o silo entre negócio e tecnologia, mas vendas e marketing continuam sem saber trabalhar com o desenvolvimento de produto.

Enquanto isso, o escopo do PM só cresce: ser orientado a dados, priorizar bem, manter roadmap por resultados, ser diplomata com stakeholders, parceiro de engenharia e UX, falar com clientes, garantir discovery, criar processos, dominar delivery... Quando faltam funções, o PM ou o líder as assume "nas horas vagas" e **queima**. PMs são caros e difíceis de contratar; perdê-los custa caro.

Ops funcionais não são novidade: Sales Ops e Marketing Ops existem há anos porque vendas e marketing eram o motor de crescimento. Na transição de *sales-led* para *product-led*, Product Ops é quem habilita o novo motor.

## 3. O que Product Ops libera

| Quem | Passa a focar em |
|---|---|
| PMs | Crescimento, metas de negócio, valor para o cliente, alinhamento com stakeholders |
| Líderes de produto | Decisão estratégica, com ferramentas para fazê-la bem e de forma consistente |
| Empresa | Um time que trabalha junto para construir os melhores produtos |

**Problemas típicos que resolve:**
- "Como eu, líder de vendas, contribuo com o roadmap?"
- "Cada time de produto tem um processo diferente de go-to-market."
- "Como fazer o planejamento anual orientado a dados e comunicar a estratégia?"
- "Como eu, CEO ou CPO, conecto o que os times fazem aos resultados que queremos?"

## 4. Os três pilares

| Pilar | Natureza | Se a maior dor é... | Product Ops habilita... |
|---|---|---|---|
| **Dados e insights de negócio** | Dados gerados **internamente** (receita, custo, uso, alocação) | Decisões orientadas a dados para gerir um portfólio complexo | Mais velocidade e qualidade de decisão |
| **Insights de cliente e mercado** | Pesquisa **externa** (clientes, usuários, mercado, concorrência) | Produtos lançados sem clareza do problema do cliente | Sistemas que levam insights aos times, com produtos centrados no cliente |
| **Processos e práticas** | Modelo operacional, governança, ferramentas | Times gastando ciclos decidindo **como** fazer em vez de fazer | Remoção de barreiras de colaboração e formas de trabalho consistentes |

- Cada pilar ajuda sozinho; **juntos** mudam o jogo.
- Se a empresa já tem capacidades de dados ou pesquisa espalhadas, pode valer reposicioná-las sob Product Ops.
- A estrutura varia por empresa, e isso é esperado.

## 5. PM × Product Operations Manager

| Product Manager | Product Ops Manager |
|---|---|
| Toma a decisão | Habilita a decisão com dados e insights |
| Define visão e estratégia | Apoia com dados e comunica internamente |
| É orientado a dados | Disponibiliza os dados em autosserviço |
| Valida problemas e soluções | Dá suporte prático à implementação e ao acompanhamento de experimentos |
| Define a proposta de valor para o GTM | É o elo cross-funcional para alinhar o GTM |
| Identifica áreas de expansão de mercado | Identifica requisitos específicos de mercado e experimentos de otimização por região |

Frase-síntese (Anabela Cesario, OutSystems): o time de Product Ops funciona como um **mini time de produto cujos clientes são os PMs**, resolvendo os problemas deles com técnicas, métodos e mentalidade de produto.

## 6. O que Product Ops NÃO é

- **Não é substituto de PM pouco qualificado.** É preciso contratar ou treinar PMs capazes de pesquisa, análise, resolução de problemas e experimentação; ProdOps dá a infraestrutura para que exerçam essas habilidades.
- **Não é "process people".** Marty Cagan (SVPG) alertou em 2021 para "pessoas de processo" usando ProdOps como veículo; depois esclareceu que não se opõe à função como multiplicador de força. Resposta da comunidade (Blake Samic): o foco é **alavancagem operacional**, não ditar como o time faz tudo.
- **Não é só program manager nem PMO.** Status e cronograma são uma fração; o núcleo é insumo para decisão e modelo operacional.
- **Não é catch-all.** "Se ninguém quer fazer, manda para ProdOps" é o caminho para virar papel de preenchimento (Hugo Froes, OLX).

## 7. Mentalidades úteis

- **Ops como API** (Simon Hilton): trate ProdOps como um conjunto de métodos ou serviços versionados. O que não é usado nem útil deve ser descontinuado. Evite a palavra "processo" quando ela gera alergia; fale em "método" ou "serviço".
- **O sistema é parte do produto** (John Cutler, citado por Shintaro Matsui): os sistemas e processos que criam o produto são tanto o produto quanto o próprio produto. Lançamento ruim ou vazamento de feedback geram produto pior.
- **Tecido conectivo** (Blake Samic): ligar os times que constroem a tecnologia aos times que interagem com os usuários.
- **Velocidade e qualidade de decisão** (Srinivas Somayajula, Calendly) é a métrica-mãe da função.
- **Como dívida técnica** (Adrian Leung, ATB): investir em ProdOps é difícil de medir, mas faz o time andar mais rápido depois; quem tem, não volta atrás.

## 8. Ecossistema de "Ops"

| Função | Foco | Interseção com Product Ops |
|---|---|---|
| Sales Ops | Habilitar a linha de frente de vendas a vender melhor e mais rápido | Dados de vendas: receita, churn, retenção, upsell e downsell, win/loss |
| Design Ops / Research Ops | Apoiar design e pesquisa para que foquem no ofício | Repositório de pesquisa, discovery, acesso a usuários |
| Engineering Ops | Melhorar como engenharia trabalha, removendo gargalos | Processos de squad, SDLC, hierarquia de trabalho |
| **Product Ops** | Cercar o time de produto dos insumos para estratégia forte e decisão mais rápida e melhor | Conecta todas as anteriores |

- Evite "ops até o infinito": use automação e ferramentas onde agregam valor de verdade.
- Promova um **conselho de operações** (os autores chamam de *superfriends*) trimestral: roadmaps de cada Ops, progresso, desafios, sobreposições e dependências. A tensão entre Ops funciona como freio e contrapeso, e isso é desejável.

## 9. Quando faz sentido (resumo)

O gatilho não é só o tamanho do time, mas **estágio e complexidade**:
- Passagem de *scale-up* para *enterprise*; múltiplos produtos em paralelo.
- Não dá mais para "virar para o lado e perguntar o que estão fazendo".
- Decisões precisam ser rápidas e com muito mais dados.
- Planejamento e governança precisam acompanhar vários fluxos de trabalho.
- Estratégia e processos ficaram complexos demais para o líder sentir o pulso sozinho.

O livro foca em *scale-ups* (pós-série A, receita recorrente, crescimento agressivo) e *enterprises*, mas as práticas valem para qualquer estágio. Detalhes de diagnóstico estão em `implantacao-buy-in.md`.
