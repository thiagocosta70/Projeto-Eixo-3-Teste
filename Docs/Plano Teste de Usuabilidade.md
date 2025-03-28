# Plano de Testes de Usabilidade

Os testes de usabilidade são uma etapa essencial no desenvolvimento do aplicativo, pois permitem avaliar sua eficiência e garantir uma experiência satisfatória para os usuários finais. Esta fase consiste em procedimentos estruturados que simulam situações reais de uso para identificar possíveis melhorias na interface e funcionalidades.

## Objetivos do Teste

- Avaliar a facilidade de uso do aplicativo pelos usuários finais.
- Identificar eventuais problemas de usabilidade que possam impactar a experiência do usuário.
- Coletar feedback para orientar ajustes e otimizações na interface e funcionalidades do sistema.

## Participantes do Teste

Os participantes serão selecionados de forma criteriosa para representar adequadamente o público-alvo do aplicativo. A escolha considerará a diversidade de perfis dos usuários e priorizará indivíduos sem contato prévio com o sistema, possibilitando a obtenção de métricas mais precisas sobre a curva de aprendizado.



## Requisitos para a Realização dos Testes

- Um dispositivo móvel compatível com sistemas Android ou iOS.
- Conexão estável com a internet para acesso ao aplicativo.

## Roteiro de Testes

O roteiro de testes abrangerá um conjunto de tarefas específicas que os participantes deverão executar. Cada tarefa será analisada com base nos seguintes critérios:

- **Taxa de conclusão**: Percentual de usuários que conseguiram concluir a tarefa com sucesso.
- **Erros cometidos**: Quantidade e tipos de erros observados durante a execução.
- **Tempo de execução**: Duração necessária para concluir cada tarefa.

Os resultados obtidos serão utilizados para aprimorar a experiência do usuário e garantir um aplicativo mais intuitivo e acessível.



| Nº  | Plano de Teste | Descrição | Passos | Objetivo do Teste | Critério de Êxito |
|----|-------------------------|------------------------------------------|-----------------------------------------------------------------|------------------------------------|-----------------------------------------------|
| 1  | Teste de Registro de Usuário | Avaliar a facilidade e clareza do processo de registro de novos usuários. | 1. Acessar a tela de registro. 2. Escolher entre praticante ou personal trainer. 3. Preencher os dados necessários. 4. Confirmar o cadastro. | Verificar se os usuários conseguem completar o registro sem dificuldades. | Todos os campos obrigatórios devem ser preenchidos corretamente e o usuário deve ser redirecionado para a tela inicial. |
| 2  | Teste de Login | Avaliar a facilidade do processo de login. | 1. Acessar a tela de login. 2. Inserir e-mail e senha cadastrados. 3. Confirmar login. | Avaliar se os usuários conseguem acessar suas contas com sucesso. | O usuário deve ser autenticado e redirecionado para a tela inicial. |
| 3  | Teste de Registro de Treino | Avaliar a eficácia do processo de registro de treinos. | 1. Fazer login. 2. Acessar a área de treinos. 3. Adicionar um novo treino informando exercícios, séries, repetições e cargas. 4. Salvar o treino. | Verificar se os usuários conseguem registrar seus treinos corretamente. | O treino deve ser salvo e aparecer no histórico do usuário. |
| 4  | Teste de Histórico de Treinos | Avaliar a clareza e acessibilidade do histórico de treinos. | 1. Fazer login. 2. Acessar o histórico de treinos. 3. Verificar se os treinos registrados estão listados corretamente. | Garantir que os usuários consigam visualizar seus treinos anteriores de maneira clara. | O usuário deve visualizar todos os treinos registrados corretamente. |
| 5  | Teste de Gráficos e Estatísticas | Avaliar a usabilidade e precisão dos gráficos e estatísticas de evolução. | 1. Fazer login. 2. Acessar a seção de estatísticas. 3. Verificar a exibição de dados sobre evolução do usuário. | Certificar que os gráficos são compreensíveis e úteis para o usuário. | Os gráficos devem refletir corretamente os dados registrados pelo usuário. |
| 6  | Teste de Rotinas de Treino | Avaliar a facilidade na criação e reutilização de rotinas de treino. | 1. Fazer login. 2. Criar uma nova rotina de treino personalizada. 3. Salvar e reutilizar essa rotina em novos treinos. | Verificar se os usuários conseguem criar e reaproveitar rotinas de treino. | As rotinas devem ser salvas e estar disponíveis para reutilização futura. |
| 7  | Teste de Notificações de Treino | Avaliar a eficiência das notificações de lembrete de treino. | 1. Fazer login. 2. Configurar um lembrete de treino. 3. Aguardar o horário programado. | Testar se os usuários recebem lembretes de treino conforme programado. | O usuário deve receber notificações na hora correta. |
| 8  | Teste de Cadastro de Treino pelo Personal Trainer | Avaliar a funcionalidade de cadastro de treinos por personal trainers. | 1. Fazer login como personal trainer. 2. Acessar a área de gestão de alunos. 3. Criar e atribuir um treino a um aluno. | Verificar se os personal trainers conseguem cadastrar e atribuir treinos aos alunos. | O treino deve ser salvo e aparecer no perfil do aluno correspondente. |
| 9  | Teste de Acompanhamento de Alunos | Avaliar a funcionalidade de acompanhamento de evolução dos alunos. | 1. Fazer login como personal trainer. 2. Acessar a área de evolução dos alunos. 3. Analisar gráficos e dados de progresso. | Certificar que os personal trainers consigam visualizar a evolução dos alunos de forma clara. | Os dados devem refletir corretamente os treinos e evolução dos alunos. |
| 10 | Teste de Feedbacks do Personal Trainer | Avaliar a funcionalidade de envio de recomendações para alunos. | 1. Fazer login como personal trainer. 2. Selecionar um aluno. 3. Enviar um feedback personalizado. | Verificar se os personal trainers conseguem enviar recomendações e comentários facilmente. | O feedback deve ser salvo e estar visível para o aluno. |
| 11 | Teste de Edição de Perfil | Avaliar a facilidade no processo de edição de perfil e preferências. | 1. Fazer login. 2. Acessar a área de perfil. 3. Editar informações pessoais e preferências de treino. 4. Salvar alterações. | Verificar se os usuários conseguem editar seus dados sem dificuldades. | As informações devem ser atualizadas corretamente no perfil do usuário. |
| 12 | Teste de Exportação e Compartilhamento de Treinos | Avaliar a funcionalidade de exportação de treinos. | 1. Fazer login. 2. Acessar a área de treinos. 3. Exportar ou compartilhar um treino. | Verificar se os usuários conseguem compartilhar seus treinos com facilidade. | O treino deve ser exportado corretamente e estar acessível no formato escolhido. |

