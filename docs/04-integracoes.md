# 4. Contas e integrações: verificação por canal

Uma conexão feita no ambiente de demonstração não existe automaticamente na conta do usuário. Registre o resultado de cada teste no ambiente autorizado antes de marcar o canal como operacional.

| Canal | Primeiro uso seguro | Para operar de verdade | Estado inicial |
| --- | --- | --- | --- |
| Arquivos locais | Pasta com exemplo fictício | Pasta do contrato aprovada, permissões e versões | Pronto para ensaio local |
| Google Drive | Documento fictício salvo manualmente | Conta e conector autorizados, escopo de leitura, teste de busca e citação | Não configurado |
| Gmail | E-mail fictício em arquivo local | Conta aprovada, permissão mínima, teste de leitura; envio só após aprovação | Não configurado |
| Google Agenda | Data fictícia no quadro | Conta aprovada, fuso e calendário conferidos; criação só após revisão | Não configurado |
| WhatsApp | Copiar uma mensagem de teste e rotular como entrada manual | Confirmar canal autorizado, mecanismo suportado, consentimento, limites e teste; não presumir API oficial | Não configurado |
| Dot/operação de telas | Mostrar no ambiente do facilitador com dados fictícios | Verificar disponibilidade na conta e no computador do usuário, permissões e limites por sistema | Não configurado |

## Teste de cada conexão

1. Registrar proprietário da conta, objetivo, permissões concedidas e data do teste.
2. Ler uma fonte de teste previamente autorizada. Conferir se a referência abre para o usuário certo.
3. Checar que o agente não alcança outras pastas ou conversas por engano.
4. Gerar apenas um rascunho e confirmar que nada foi enviado ou alterado.
5. Se houver escrita ou envio no futuro, testar com destino de teste e aprovação explícita.

**WhatsApp:** o pareamento por QR de uma sessão WhatsApp Web em outro produto não equivale à API oficial do WhatsApp e não demonstra suporte deste kit. Não importe credenciais ou sessões de um produto anterior.
