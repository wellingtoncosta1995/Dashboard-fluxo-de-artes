# Instruções do projeto

- Sempre que o usuário pedir uma alteração de código neste projeto, aplique a edição e, em seguida, faça o commit automaticamente (`git add` dos arquivos alterados + `git commit` com mensagem descritiva), sem pedir confirmação para esses dois passos.
- Nunca faça `git push` automaticamente. Antes de dar o push, informe ao usuário o que foi alterado (resumo do diff/commit) e peça confirmação explícita.
- Só execute o `git push` depois que o usuário confirmar.
- Sempre que fizer uma alteração de código, atualize também as constantes `APP_VERSION` e `APP_VERSION_DATE` (perto do topo do `<script>` em index.html) para refletir a versão do commit — esse valor aparece no cabeçalho do app.
