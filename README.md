# Relatório TaskFlow
Nome: Giovanni Higino Rocha
Turma: 3B

Relatório – Implementação de princípios de acessibilidade em aplicações front-end

Durante a atividade foram realizadas melhorias de acessibilidade na aplicação TaskFlow utilizando recursos de ARIA, navegação por teclado e ajustes de contraste visual.

1. Implementação de atributos ARIA

Foram adicionados atributos aria-label nos botões e no campo de texto da aplicação para facilitar a identificação dos elementos por leitores de tela.

Exemplos implementados:
- aria-label="Campo para digitar nova tarefa"
- aria-label="Adicionar nova tarefa"
- aria-label="Marcar tarefa como concluída"
- aria-label="Excluir tarefa"

Também foi utilizado o atributo aria-live="polite" para informar dinamicamente quando uma nova tarefa é adicionada.

2. Navegação por teclado

Foram adicionados atributos tabindex="0" para melhorar a navegação utilizando a tecla TAB.

Também foram implementadas funções para melhorar a acessibilidade via teclado:
- tecla ENTER para adicionar tarefas;
- atalho CTRL + N para focar automaticamente no campo de nova tarefa.

3. Melhorias de contraste

As cores da aplicação foram ajustadas para melhorar a legibilidade e atender aos critérios mínimos de contraste.

Foram realizadas as seguintes melhorias:
- texto com cor mais escura;
- botões com contraste mais forte;
- bordas mais visíveis nos campos;
- melhoria visual nas tarefas concluídas.

Conclusão

Com as alterações realizadas, a aplicação ficou mais acessível para usuários com deficiência visual, usuários que utilizam leitores de tela e pessoas que navegam apenas utilizando o teclado.
