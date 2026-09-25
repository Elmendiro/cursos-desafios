# Desafio Criativo: Extraindo Insights do Feedback de Clientes Bancários

## Prompt Final

Atue como analista de dados e experiência do cliente em um banco.

Sua tarefa é analisar feedbacks de clientes bancários sobre aplicativo, Pix, cartão de crédito e atendimento por chat para identificar reclamações frequentes, elogios e oportunidades de melhoria.

Contexto: Estou trabalhando com feedbacks de clientes bancários relacionados ao aplicativo, Pix, cartão de crédito e atendimento por chat. A análise será usada por uma equipe de experiência do cliente para apoiar melhorias no aplicativo e nos canais de atendimento, priorizando ações de maior impacto.

Dados disponíveis: A base contém data do comentário, canal de atendimento, texto do feedback, produto citado e nota de satisfação de 1 a 5 (ver tabela abaixo).

Instruções de análise:

- Classifique os feedbacks por tema, sentimento, urgência e produto citado.
- Identifique os principais padrões, problemas, elogios e oportunidades.
- Aponte evidências nos dados fornecidos, usando exemplos curtos de comentários.
- Sugira ações práticas para a equipe de experiência do cliente e para o time responsável pelos canais digitais.

Formato da resposta: Entregue um resumo executivo com até 5 linhas, uma tabela com tema, sentimento, evidência e ação sugerida, além de uma lista final com as 3 prioridades mais importantes.

Restrições:

- Use apenas os dados fornecidos.
- Não invente números, causas ou conclusões.
- Não exponha dados pessoais ou sensíveis.
- Informe limitações quando os dados não forem suficientes.
- Use linguagem simples, direta e voltada para tomada de decisão.

## Base de Dados (fictícia)

| Data | Canal | Feedback | Produto | Nota |
|---|---|---|---|---|
| 2026-08-02 | App | O Pix demorou mais de 10 minutos para cair, fiquei preocupado se o dinheiro tinha sumido | Pix | 2 |
| 2026-08-03 | Chat | Atendente resolveu meu problema de fatura em poucos minutos, muito ágil | Cartão de crédito | 5 |
| 2026-08-04 | App | O aplicativo trava toda vez que tento ver o extrato completo | Aplicativo | 1 |
| 2026-08-05 | Chat | Fiquei 40 minutos esperando resposta no chat e ninguém me atendeu | Atendimento | 1 |
| 2026-08-06 | App | Consegui aumentar o limite do cartão direto pelo app, muito prático | Cartão de crédito | 5 |
| 2026-08-07 | App | Chave Pix cadastrada errada e não encontrei opção fácil para corrigir | Pix | 2 |
| 2026-08-08 | Chat | Bom atendimento, mas demorou para transferir para o setor certo | Atendimento | 3 |
| 2026-08-09 | App | Login com biometria falha com frequência, preciso digitar senha toda vez | Aplicativo | 2 |
| 2026-08-10 | Chat | Cobraram anuidade do cartão mesmo eu tendo isenção, atendente corrigiu na hora | Cartão de crédito | 4 |
| 2026-08-11 | App | Notificação de Pix recebido não chega, só vejo quando abro o app | Pix | 2 |
| 2026-08-12 | Chat | Não consegui cancelar o cartão pelo chat, disseram que só na agência | Cartão de crédito | 2 |
| 2026-08-13 | App | App ficou muito mais rápido depois da última atualização | Aplicativo | 5 |
| 2026-08-14 | Chat | Fui bem tratado, mas o problema do Pix não foi realmente resolvido | Pix | 3 |
| 2026-08-15 | App | Fatura do cartão com cobrança duplicada, isso é sério e recorrente | Cartão de crédito | 1 |
| 2026-08-16 | Chat | Atendente muito atencioso, explicou tudo sobre o parcelamento | Cartão de crédito | 5 |
