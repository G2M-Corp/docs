# Manual de Boas Práticas - G2M Corp

Este documento define os padrões de nomenclatura de branch e commits utilizados na G2M Corp, garantindo consistência e clareza no desenvolvimento de software.

---

## Padrões de Nomenclatura de Branch

As branches devem seguir o formato:
```
<prefixo>/<descrição>-<número-da-issue>
```
- Sempre em **letra minúscula**.
- O `número-da-issue` deve corresponder ao ID da tarefa no sistema de gerenciamento de projetos.

### Prefixos permitidos:

| Prefixo   | Uso                                                             |
|-----------|-----------------------------------------------------------------|
| `feat`    | Adição de uma nova funcionalidade ao projeto.                   |
| `fix`     | Correção de um bug no código.                                   |
| `chore`   | Alterações de manutenção, sem impacto no código de produção.    |
| `docs`    | Atualizações na documentação.                                   |
| `style`   | Mudanças estéticas, como formatação ou espaçamento.             |
| `refactor`| Melhorias na estrutura do código sem alterar funcionalidade.    |
| `test`    | Adição ou modificação de testes automatizados.                  |
| `ci`      | Configurações e ajustes no pipeline de integração contínua.     |

**Exemplo:**
```
feat/autenticacao-5
```

---

## Padrões de Commit

Os commits devem seguir o formato:
```
<prefixo>: <descrição-da-alteração>
```
- Sempre em **letra minúscula**.
- A descrição deve ser curta e objetiva, utilizando o tempo verbal no imperativo (exemplo: "adicionar validação", "corrigir erro", "melhorar layout").

### Prefixos permitidos:

| Prefixo   | Uso                                                             |
|-----------|-----------------------------------------------------------------|
| `feat`    | Adição de uma nova funcionalidade ao projeto.                   |
| `fix`     | Correção de um bug no código.                                   |
| `chore`   | Alterações de manutenção, sem impacto no código de produção.    |
| `docs`    | Atualizações na documentação.                                   |
| `style`   | Mudanças estéticas, como formatação ou espaçamento.             |
| `refactor`| Melhorias na estrutura do código sem alterar funcionalidade.    |
| `test`    | Adição ou modificação de testes automatizados.                  |
| `ci`      | Configurações e ajustes no pipeline de integração contínua.     |

**Exemplos:**
```
feat: adicionar botão de login
fix: corrigir erro no envio de formulário
refactor: otimizar função de cálculo de frete
```
