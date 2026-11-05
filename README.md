# IA para Diretores

**Um contrato. Fontes rastreáveis. Decisões sob controle do diretor.**

![AI OS para Diretores: entradas autorizadas, organização por contrato, Codex, análise, revisão humana e acompanhamento](assets/capa-ai-os-diretores-revisada.png)

> **Mapa didático, não implantação.** WhatsApp, e-mail e Google Drive aparecem como origens ou destino possíveis, ainda sem integração comprovada na conta de Francisco. NotebookLM é opcional se já existir e for autorizado. O piloto começa com arquivos fictícios locais; o diretor valida qualquer ação. A [capa anterior](assets/capa-ia-diretores.png) fica preservada como referência histórica.

Este kit privado reúne o roteiro de ativação no Windows, instruções para Codex, papéis de análise, prompts reutilizáveis e um exercício seguro. Seu resultado pretendido é um **quadro semanal de uma página**: fato, fonte, restrição, impacto, responsável, prazo e próxima ação. Francisco revisa os fatos e aprova qualquer decisão ou comunicação antes da execução.

## Comece por aqui

1. Veja o [mapa do fluxo e dos sistemas](docs/08-fluxo-didatico.md), depois leia [Ativação no Windows](docs/01-ativacao-windows.md), [Governança](GOVERNANCA.md) e [Segurança e permissões](docs/02-seguranca.md).
2. Abra esta pasta no Codex e confira as [instruções do projeto](AGENTS.md).
3. Faça o [exercício com dados fictícios](docs/03-primeiro-piloto.md), começando pelo [prompt de início](prompts/01-inicio.md).
4. Revise o resultado com o [modelo de quadro](modelos/quadro-semanal.md), o [registro da rodada](modelos/registro-execucao.md) e os [critérios de validação](docs/05-validacao.md).
5. Só então escolha um contrato e confira as permissões na [matriz de integrações](docs/04-integracoes.md).

| No kit | Finalidade |
| --- | --- |
| [Quatro papéis](agentes/01-leitor.md) | Ler fontes, analisar restrições, redigir e revisar em sequência supervisionada |
| [Prompts](prompts/01-inicio.md) | Repetir o fluxo com saídas consistentes |
| [Exemplo fictício](exemplos/contrato-ficticio.md) | Ensaiar sem documentos de clientes ou contas conectadas |
| [Histórico e fontes](docs/06-historico-e-fontes.md) | Distinguir o que foi apresentado, enviado, desenvolvido e ainda não comprovado |
| [Relatório de trabalho](docs/07-relatorio-de-trabalho.md) | Revisar o avanço e as pendências antes de tratar a entrega como concluída |
| [Mapa didático](docs/08-fluxo-didatico.md) | Explicar o caminho das fontes até a decisão e os limites de cada sistema |

## Estado em 05/11/2026

| Componente | Estado verificável |
| --- | --- |
| Roteiro, prompts e exemplos | Preparados e revisados localmente; o exercício ainda depende de execução com o usuário |
| Papéis de análise | Definidos como instruções; não são agentes autônomos implantados |
| Arquivos locais fictícios | Prontos para ensaio, sem acesso a contas |
| Google Drive, Gmail e Agenda | Não configurados nem testados na conta de Francisco |
| WhatsApp | Não configurado nem testado; mensagem copiada manualmente deve ser identificada como tal |
| Dot e operação de telas | Dependem de disponibilidade e permissões no ambiente de Francisco |
| Contrato real e quadro aprovado | A escolher e validar com Francisco |

O [guia de validação](docs/05-validacao.md) registra o que falta comprovar. O pareamento de WhatsApp Web descrito em material anterior não equivale à API oficial nem estabelece uma integração neste kit.

## Continuidade da mentoria

O diagnóstico e as conversas anteriores sugeriram começar por **um contrato**, adaptar o horizonte de planejamento ao tipo de obra e testar o fluxo com supervisão humana. Há evidência de sessões e de modelos LPS enviados; o [histórico](docs/06-historico-e-fontes.md) registra cada item com seu grau de comprovação. O kit atual é uma **preparação técnica local** e não comprova aceite, implantação, encerramento contratual ou quitação da mentoria anterior.

## Referências úteis

- [Proposta anterior compartilhada com Francisco](https://docs.google.com/document/d/1_T-Ddnb286hQ-FLREvBz66VoeabR9fkGprzHe4GXFvo/edit) — referência de escopo, sujeita a conciliação com o que foi efetivamente entregue.
- [Notas da mentoria de 01/07](https://docs.google.com/document/d/1QTT_oX2nKkff3SGZR2rS2E0dCgk5inUIdOeevw72VR8/edit) — contexto para a adoção em blocos.
- [Aplicativo ChatGPT para Windows](https://learn.chatgpt.com/docs/windows/windows-app), [primeiros passos](https://learn.chatgpt.com/docs/quickstart) e [instruções AGENTS.md](https://learn.chatgpt.com/docs/agent-configuration/agents-md) — documentação oficial para a ativação.

**Uso e privacidade:** este repositório deve permanecer privado. Não coloque nele contratos reais, conversas, credenciais ou resultados de clientes. Toda leitura de conta, envio ou escrita em sistema requer permissão específica e revisão humana.
