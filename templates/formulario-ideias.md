# Template: Formulário de Ideias e Pedidos (focado no problema)

> Uso: entrada única de ideias de clientes e áreas, que extrai o **problema** e não a solução, com retorno de status. Base: `references/pilar-3b-processos-ferramentas.md`, seção 2.

## Formulário ("complete as lacunas")
1. Eu sou **[papel/área]** e estou falando em nome de **[cliente/segmento/área interna]**.
2. Quando **[situação/contexto]**, eles tentam **[objetivo]**, mas **[o que impede]**.
3. Hoje eles contornam fazendo **[gambiarra]**, o que custa **[tempo/dinheiro/risco]**.
4. Isso afeta **[nº de clientes/usuários, ARR envolvido, deal em jogo]**.
5. Saberemos que resolvemos quando **[resultado observável]**.
6. (Opcional) Uma ideia de solução: **[sugestão]**. *Ela não é obrigatória; o time vai investigar o problema.*
7. Evidência: **[links: CRM, ticket, gravação]** · Urgência: ☐ deal em risco ☐ churn em risco ☐ melhoria

## Roteamento
| Tipo | Vai para | Triagem por | Prazo de 1ª resposta |
|---|---|---|---|
| Bug | Suporte/engenharia | | |
| Problema de produto [área X] | PM da área X | | |
| Estratégico, entre áreas | Líder de produto | | |

## Status devolvido a quem pediu
| Status | Significado | Mensagem padrão |
|---|---|---|
| Recebido | Na fila de triagem | "Recebemos; resposta até __." |
| Em avaliação | Problema sendo analisado | |
| Em discovery / roadmap | Virou trabalho (indicar status Discovery → GA) | |
| Não seguiremos agora | Recusado com critério | "Não priorizamos porque [critério do framework]. Revisitamos se [condição]." |
| Entregue | Disponível | "Está no ar: [release note]." |

> Exemplo da diferença: "deixe o botão amarelo" (solução) × "não acho o botão de enviar" (problema).
