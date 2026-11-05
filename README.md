# IA para Diretores — kit de ativação

Kit privado para iniciar **um piloto supervisionado de um contrato** no ChatGPT/Codex. Contém instruções, papéis, prompts, um exemplo inteiramente fictício e critérios de validação. Não instala programas, conecta contas ou executa agentes sozinho.

## Comece por aqui

1. Leia [Ativação no Windows](docs/01-ativacao-windows.md) e abra esta pasta no Codex.
2. Leia [Segurança e permissões](docs/02-seguranca.md) antes de selecionar dados reais.
3. Execute o [primeiro exercício](docs/03-primeiro-piloto.md) somente com os arquivos de `exemplos/`.
4. Use o [prompt de início](prompts/01-inicio.md) e confira a saída contra o [modelo de quadro](modelos/quadro-semanal.md).
5. Só depois escolha, com o responsável, um contrato e quais fontes podem ser lidas. Consulte a [matriz de integrações](docs/04-integracoes.md).

## O que deve sair do piloto

Um quadro semanal de uma página com fato, fonte, restrição, impacto, responsável, prazo e próxima ação. Toda afirmação vem com origem verificável. Envio de mensagens, atualização de sistemas e criação de compromissos exigem revisão e autorização explícita da pessoa responsável.

Os arquivos em `agentes/` definem **papéis de análise**. Eles não provam que há vários agentes autônomos rodando, nem são configuração de uma integração. Na primeira rodada, o Codex pode executar os papéis em sequência, sob supervisão.

## Estado atual

| Item | Estado deste repositório |
| --- | --- |
| Instruções e prompts | Preparados, sem dados reais |
| Exemplo | Fictício e verificável manualmente |
| Google (Drive/Gmail/Agenda) | Acesso não configurado nem testado neste kit |
| WhatsApp | Acesso não configurado nem testado neste kit |
| Dot/computador | Demonstração depende da disponibilidade e permissão na conta do usuário |
| Operação automática | Não implementada |

## Fontes oficiais para a instalação

- [ChatGPT desktop app para Windows](https://learn.chatgpt.com/docs/windows/windows-app)
- [Primeiros passos](https://learn.chatgpt.com/docs/quickstart)
- [Instruções de projeto com AGENTS.md](https://learn.chatgpt.com/docs/agent-configuration/agents-md)

## Manutenção

Revise `AGENTS.md`, os prompts e a matriz de permissões quando o fluxo mudar. Não coloque neste repositório documentos de clientes, conversas, segredos ou resultados reais. O arquivo `.gitignore` ajuda a evitar inclusão acidental, mas não substitui a revisão do que será enviado ao GitHub.
