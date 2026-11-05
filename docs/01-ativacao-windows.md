# 1. Ativação no Windows

Este roteiro orienta uma sessão com o dono da conta. **O repositório não ativa um “chip” por si só.** Cada login e permissão deve ser feito e conferido no computador dele.

## Preparação

- [ ] Computador Windows atualizado, com acesso à Microsoft Store ou ao instalador autorizado pela empresa.
- [ ] Conta ChatGPT que será usada pelo diretor. Confirme com a TI qual conta e plano são permitidos.
- [ ] Pasta de trabalho separada para este piloto. Não misture documentos pessoais ou de outros contratos.
- [ ] Git é opcional para o primeiro exercício. O GitHub permite baixar o repositório como ZIP; para manter versões com colaboração, a equipe pode configurar Git depois.

## Passo a passo

1. Abra a [página oficial do app para Windows](https://learn.chatgpt.com/docs/windows/windows-app). Instale pela opção aprovada pela TI. A documentação oficial também mostra o comando `winget install --id 9PLM9XGG6VKS -s msstore` para quem prefere o gerenciador do Windows. **Não execute este comando sem concordância do responsável pelo computador.**
2. Abra o app e entre na conta ChatGPT escolhida. Confirme o nome da conta e o espaço de trabalho antes de conectar arquivos.
3. Receba acesso a este repositório privado pelo proprietário, ou receba um ZIP revisado. Copie ou extraia o kit em uma pasta local dedicada. Não coloque documentos reais no Git.
4. No app, selecione Codex e abra a pasta do kit como projeto/local de trabalho. O arquivo `AGENTS.md` orienta o Codex quando a pasta é aberta como raiz do projeto. Confira se o app mostra a pasta correta.
5. Cole o texto de `prompts/01-inicio.md` numa conversa nova. Peça para o Codex listar os arquivos de exemplo e resumir as instruções carregadas.
6. Faça o exercício de `docs/03-primeiro-piloto.md`. Revise cada fato no arquivo original antes de considerar o resultado válido.

## Se algo não aparecer

- Se Codex não carregar `AGENTS.md`, abra a pasta correta como projeto e inicie uma conversa nova. [Como o Codex descobre AGENTS.md](https://learn.chatgpt.com/docs/agent-configuration/agents-md).
- Se o app ou um conector não estiver disponível, registre a limitação e continue com os arquivos fictícios locais. Não use conta pessoal como atalho para acessar dados da empresa.
- Acesso ao Google, WhatsApp e operação de telas são etapas separadas; consulte `docs/04-integracoes.md`.
