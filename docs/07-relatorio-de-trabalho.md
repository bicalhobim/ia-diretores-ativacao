# Relatório de trabalho e desenvolvimento

**IA para Diretores — versão para revisão antes de eventual apresentação a Francisco**
**Data:** 05/11/2026

## Objetivo

Organizar uma primeira rotina assistida para que Francisco obtenha, a partir de fontes autorizadas de **um contrato**, um quadro de restrições, responsáveis, prazos e decisões com referências verificáveis. A proposta é começar pequeno, revisar a qualidade da informação e ampliar somente após validação.

## Trabalho documentado até aqui

1. **Diagnóstico e direção do piloto.** A apresentação AS-IS de 12/06 descreveu fragmentação entre mensagens, e-mails, planilhas e relatórios. A sessão de 01/07 orientou adoção em blocos e escolha de um contrato inicial. Francisco disse em 06/07 que o diagnóstico era preciso e validou a arquitetura proposta. Isso é feedback sobre o desenho, não aceite da implantação. [Histórico com fontes](06-historico-e-fontes.md).
2. **Material de gestão e necessidade expressa.** Um e-mail de 13/07 enviado a Francisco contém links para vídeo e Miro com assunto “Modelos LPS”; não se verificou se o Miro continha os templates solicitados. Francisco pediu um formato de reporte para os gerentes, adaptação do ciclo de médio e curto prazo a ordens de serviço de manutenção/reforma e clareza sobre captura, processamento e armazenamento dos dados sensíveis. A aplicação em contrato real não foi verificada.
3. **Avaliação da via Hermes.** O guia Drive/Hermes de 26 páginas foi encaminhado em 03/08; Francisco disse que abriu o arquivo e não o entendeu bem. O guia E1 v0.3 recebido por Lucas em 06/08 descreve WhatsApp e Gmail, e há registro de mensagem/documento da Etapa 1 enviada a Francisco, sem o anexo binário no export. Esses registros mostram comunicação e dificuldade de ativação; não comprovam integração funcional no ambiente dele.
4. **Preparação do kit atual.** Foram escritos roteiro Windows, regras de segurança, matriz de integrações, quatro papéis de análise, quatro prompts, modelo de quadro e arquivos inteiramente fictícios. A capa apresenta a arquitetura como proposta. Links locais, conteúdo de exemplo e ausência de credenciais no kit foram revisados. [Estado de validação](05-validacao.md).
5. **Evolução didática de 05/11.** A capa revisada põe Codex no centro e mostra seis etapas com aprovação humana. O [mapa do fluxo](08-fluxo-didatico.md) explica cada caixa, inclusive o que é apenas possibilidade futura. O reporte de gerente para a OS-17, a [governança](../GOVERNANCA.md) e o [registro da rodada](../modelos/registro-execucao.md) aproximam o exercício do pedido de Francisco sem depender de Hermes ou NotebookLM. A capa anterior segue preservada. A [análise de origem e limites](06-historico-e-fontes.md) evita apresentar o PDF técnico como integração comprovada.

## Resultado disponível para demonstração

O exercício fictício permite montar um quadro de uma página e uma minuta **sem envio**. O diretor confere cada afirmação na fonte, corrige divergências e decide o próximo passo. Essa preparação local não mede redução de tempo nem comprova integração de contas.

O feedback de Francisco muda o teste de utilidade: a primeira demonstração deve partir de um reporte simples de gerente sobre ordens de serviço, pendências críticas e responsável, mostrar o rito quinzenal de restrições e explicitar o trajeto de cada dado. O exemplo DEMO-001 agora inclui um reporte fictício da OS-17, suficiente para ensaiar a passagem gerente → diretor; ainda falta Francisco julgar se representa sua rotina de manutenção/reformas. A continuidade deve reduzir instruções de instalação antes de produzir um quadro útil.

Na conversa de 03/07, Francisco disse que assinava Claude e ChatGPT e se sentia perdido com sobreposição de ferramentas e perda de histórico. Esse é um relato datado, não confirmação das assinaturas atuais. A ativação deve explicar por que cada aplicativo entra no fluxo e testar o acesso atual antes de propor migração ou nova assinatura.

## Pendências para um piloto real

| Decisão ou teste | Responsável a confirmar | Evidência de conclusão esperada |
| --- | --- | --- |
| Escolher contrato, rotina e horizonte de análise | Francisco | Escopo do piloto registrado |
| Autorizar fontes, conta, retenção e pessoas com acesso | Francisco e responsável pela informação/TI | Permissões documentadas |
| Verificar disponibilidade de Codex, Dot e conectores no ambiente dele | Francisco com apoio de Lucas | Teste controlado com fonte permitida |
| Rodar um ciclo com dados reais e conferir fatos, prazos e responsáveis | Francisco | Quadro revisado com fontes e correções |
| Conciliar a proposta de mentoria anterior com sessões e materiais efetivamente entregues | Lucas e Francisco | Registro de pendências, aceite e condição financeira |
| Validar com Francisco o formato de reporte e o tratamento dos dados sensíveis | Lucas e Francisco, com responsável por TI/dados quando aplicável | Exemplo de reporte aceito, fontes permitidas e mapa de captura, processamento, armazenamento e acesso |

## Critério para considerar o novo piloto validado

Francisco consegue repetir o fluxo em um contrato autorizado, verificar cada fato na origem, identificar ao menos uma restrição útil e aprovar ou rejeitar a ação sugerida. Envio, edição de sistemas e novas integrações só entram em etapa posterior, com autorização própria.

**Situação de fechamento:** este relatório organiza o trabalho e as evidências disponíveis. O export de WhatsApp preservado fora do repositório inclui áudios, imagens e documentos omitidos; não se inferiu o conteúdo desses itens. Não há comprovação de terceira sessão, funcionamento do NotebookLM na conta de Francisco, aceite final ou quitação da mentoria anterior. Esses pontos dependem de conferência com Francisco e registros financeiros.
