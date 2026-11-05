# 2. Segurança, permissões e aprovação

Antes de usar um contrato real, registre respostas para os itens abaixo fora deste repositório, em local aprovado pela organização.

## Checklist de decisão

- [ ] Quem é o proprietário dos dados e quem pode autorizar o piloto?
- [ ] Qual contrato e quais pastas, mensagens e datas entram no teste?
- [ ] Há dados pessoais, financeiros, estratégicos ou de terceiros que exigem exclusão ou tratamento específico?
- [ ] A conta e o plano usados são aprovados pela organização para esses dados?
- [ ] O acesso é somente leitura? Quem pode autorizar escrita, envio e agenda?
- [ ] Onde ficam os resultados e registros? Por quanto tempo e quem pode vê-los?
- [ ] Há uma matriz aprovada de responsáveis, substitutos e canais de contato?
- [ ] Qual pessoa revisa os fatos e libera cada ação externa?

## Regras de operação

1. Comece com dados fictícios. Na primeira rodada real, use o menor conjunto de arquivos necessário.
2. Mostre a fonte de cada fato. Se duas fontes divergirem, registre a divergência; não escolha silenciosamente uma versão.
3. Classifique toda saída como `rascunho`, `validado` ou `enviado/executado`. Um rascunho não é uma comunicação realizada.
4. Não envie mensagens, edite sistemas ou aceite permissões amplas por iniciativa do agente. Revise texto, destinatários, anexos e efeito antes de autorizar.
5. Mantenha documentos reais, tokens OAuth, cookies e arquivos de configuração de contas fora do GitHub. Verifique o conteúdo antes de qualquer commit.
6. Se a conexão falhar, use entrada manual identificada como tal. Não descreva a simulação como captura automática.
7. Organizar por contrato não autoriza mover, renomear ou criar pastas em um sistema externo. Primeiro liste os originais e confirme destino, permissões e versão. Qualquer automação futura deve evitar duplicatas e nunca sobrescrever silenciosamente uma fonte.
