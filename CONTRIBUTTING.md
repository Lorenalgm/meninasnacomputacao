# Contribuindo

1. Faça o fork (<https://github.com/Lorenalgm/meninasnacomputacao/fork>)
2. Crie a branch da sua feature (`git checkout -b feature/name`)
3. Commit suas mudanças (`git commit -am feat: Added feature "x"'`)
4. Faça push para branch (`git push origin feature/name`)
5. Crie um Pull Request

## Commmit

- Use modo participio ("Added feature" não "Adding feature" ou "Add feature")
- Primeira linha deve ter no máximo 70 caracteres
- Considere descrever em detalhes no corpo do commit
- Obrigatório o uso de um _conventional commit type no começo da mensagem de commit

| Tipo do commit    | Título                | Descrição
|:------------------|:----------------------|:----------
| `feat`            | Funcionalidades       | Uma nova funcionalidade
| `fix`             | Correção de bugs      | Uma correção de bug
| `docs`            | Documentação          | Alterações apenas na documentação
| `style`           | Estilos               | Alterações que não afetam o significado do código (espaço em branco, formatação, ponto-e-vírgula ausente, etc)
| `refactor`        | Refatoração de código | Uma mudança de código que não corrige um bug nem adiciona um recurso
| `perf`            | Performance           | Uma mudança de código que melhora o desempenho
| `test`            | Testes                | Adicionar testes ou corrigir testes existentes
| `build`           | Builds                | Mudanças que afetam o sistema de compilação ou dependências externas (escopos de exemplo: gulp, broccoli, npm)
| `ci`              | Integração contínua   | Mudanças em arquivos e scripts de configuração de CI (escopos de exemplo: Travis, Circle, BrowserStack, SauceLabs)
| `chore`           | Tarefas               | Outras mudanças que não modificam os arquivos src ou de teste
| `revert`          | Reverte               | Reverte um commit anterior