# 📚 Manual de Estilização para Commits

Este documento define a convenção de mensagens de commit utilizada neste repositório. O objetivo é manter o histórico de versões **organizado, compreensível e padronizado**.

## 🧩 Estrutura da mensagem
**Obrigatório:**<br>
\<tipo\>: \<mensagem\>

**Opcional:**<br>
\<emoji\>\<tipo\>(escopo): \<mensagem\>

**Exemplos:**
````bash
git commit add "✨ funcionalidade: adicionar árvore de habilidades"
git commit add "🐛 correção(clientes): corrigir bug de animação"
git commit add "♻️ refatoração: renomear variáveis"
git commit add "🧪 teste(menu): customizar personagem"
````
O uso de emojis para cada tipo deve ser **OBRIGATORIAMENTE** escolhido a partir da descrição prevista no site [gitmoji](https://gitmoji.dev/).

---

## 🏷️ Tipos de commit

| Tipo | Descrição |
|-|-|
| `início` | Primeiro commit, estrutura inicial do projeto. |
| `funcionalidade` | Nova funcionalidade adicionada ao sistema. |
| `correção` | Correção de bugs/erros. |
| `documentação` | Alterações em arquivos de documentação (README, comentários, etc.). |
| `estilo` | Mudanças visuais ou de formatação, sem impacto na lógica do código. |
| `refatoração` | Melhorias internas no código sem alteração de comportamento. |
| `teste` | Adição ou modificação de testes. |
| `tarefas` | Tarefas de manutenção, como atualização de dependências, configs, etc. |
| `desempenho` | Otimizações que melhoram a performance. |
| `construção` | Mudanças no sistema de build ou scripts automatizados. |
| `reversão` | Reversão de commits anteriores. |

---

> [!TIP]
> - Use mensagens claras e objetivas.
> - Sempre escreva a mensagem no imperativo ou forma direta (ex.: "adicionar", "corrigir").
> - Emojis são opcionais, mas podem ajudar na leitura visual do histórico.

---

👤 **Autor:** Carlos Daniel<br>
📅 Data da última atualização: 24/05/2025 17:42