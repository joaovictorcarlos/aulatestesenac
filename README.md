## Exercício 1 - Criando um Histórico de Commits com Mensagens Detalhadas

**Objetivo**: Aprender a criar um histórico de commits organizado e detalhado usando mensagens de commit.

**Passos**:

1. Criei uma nova pasta chamada(mkdir) `git-historico`.
2. Inicializei essa pasta como um repositório Git:
   ```
   git init
   ```
3. Criei três arquivos diferentes(vscode):
   - `notas.txt`: Inclua algum conteúdo relevante.
   - `resumo.md`: Adicione um resumo ou descrição.
   - `tarefa.txt`: Descreva uma tarefa ou objetivo.

4. Adicionei o commit de cada arquivo separadamente, usando mensagens de commit detalhadas que expliquem o conteúdo e a intenção de cada mudança:
   ```
   git add notas.txt
   git commit -m "commit 1"

   git add resumo.md
   git commit -m "commit 2"

   git add tarefa.txt
   git commit -m "commit 3"
   ```
5. Exibindo o histórico de commits para verificar as mensagens:
   ```
   git log
   ```

   ## Exercício 2: Desfazendo Alterações com `git reset` e `git restore`

   ## Exercício 3: Manipulando Branches e Fazendo Merge