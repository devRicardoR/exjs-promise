Este projeto demonstra o uso de Promessas (`Promise`) em JavaScript para simular uma operação assíncrona, com manipulação de estados de sucesso e erro, exibidos na interface de usuário.

- Botão de Ação: Um botão na interface permite iniciar uma operação simulada, que é representada por uma promessa (`Promise`).
  - Quando o botão é clicado, o texto "Processando..." é exibido enquanto a operação está em andamento.

- Simulação de Operação Assíncrona:
  - A função `promessa()` retorna uma `Promise` que simula uma operação demorada (3 segundos) usando `setTimeout`.
  - Dependendo do valor de `resultado`, a `Promise` será resolvida com sucesso ou rejeitada com erro.

- Atualização da Interface:
  - Se a operação for bem-sucedida, o texto "Deu tudo certo!" é exibido, e a interface visual é atualizada para indicar sucesso (adicionando a classe `ok`).
  - Se a operação falhar, o texto "Deu tudo errado!" é exibido, e a interface visual é atualizada para indicar erro (adicionando a classe `erro`).
