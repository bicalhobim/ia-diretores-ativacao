# 3. Primeiro piloto: um contrato, uma decisão

## Exercício seguro

Use apenas `exemplos/contrato-ficticio.md`, `exemplos/reporte-gerente-ficticio.md`, `exemplos/mensagem-ficticia.md` e `exemplos/matriz-responsaveis-ficticia.csv`. Os nomes, valores e datas são inventados. Consulte o [mapa visual do fluxo](08-fluxo-didatico.md) para distinguir a demonstração das conexões futuras.

1. Abra os quatro arquivos e rode `prompts/01-inicio.md`.
2. Execute `prompts/02-quadro.md` para preencher `modelos/quadro-semanal.md`.
3. Confira manualmente cada citação e cada data no arquivo de origem.
4. Execute `prompts/03-minuta.md`. O resultado deve permanecer como **rascunho**, sem envio.
5. Execute `prompts/04-revisao.md` e registre o que falta ou diverge.

## Resultado esperado do exemplo

O contrato fictício prevê o marco M1 em 18/11/2026. O reporte do gerente descreve a OS-17 de instalação e a disponibilidade não confirmada de 40 luminárias; a mensagem fictícia pede confirmação até 12/11/2026. O quadro deve distinguir o marco do prazo de resposta e indicar que o impacto ainda requer validação. A matriz fictícia identifica quem acompanha a restrição, mas não autoriza disparo automático de cobrança.

## Entrada gradual em dados reais

1. Escolha um único contrato e uma rotina semanal. Adapte o horizonte do planejamento ao tipo de contrato, inclusive 30 dias quando fizer mais sentido.
2. Registre fontes, versão, responsáveis e permissões. Teste leitura de um documento e uma mensagem permitidos.
3. Produza um quadro, revise os fatos e corrija erros antes de repetir.
4. Durante uma semana, meça tempo de preparação, fontes ausentes, restrições detectadas e utilidade percebida.
5. Só depois decida sobre novos canais, outros contratos e automação recorrente.

**Critério de aceite:** o diretor consegue reproduzir uma síntese rastreável, identificar uma restrição útil e revisar a próxima ação antes de qualquer execução externa. O piloto não promete redução percentual de tempo, integração permanente ou previsão automática de cronograma.
