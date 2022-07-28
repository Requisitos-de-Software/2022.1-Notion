# Histórias de Usuário

## 1. Introdução

Histórias de usuário descrevem funcionalidades com o objetivo de agregar valor ao cliente e à equipe de desenvolvimento.
São basicamente compostas de três aspectos:
- Descrição escrita usada tanto para planejamento quanto para documentação
- Conversações sobre histórias servem para detalhar os aspectos da história
- Testes que representam a compreensão do requisito, e estabelecem critérios de aceitação. Além disso transmitem e documentam
detalhes que são usados quando a história está completa.

Em vista das histórias de usuário serem tradicionalmente escritas à mão em um papel
de anotação, Ron Jeffries nomeou estes três aspectos de CCC: Cartão, Conversação e
Confirmação (Cohn, 2004). O cartão representa o texto da história, os detalhes são descritos
na conversação e a documentação é feita na confirmação. Elas devem ser curtas, simples e claras. Nelas devem ser especificadas o ator, a ação e
a funcionalidade desejada seguindo a seguinte estrutura proposta por (Cohn, 2004)

Dessa maneira conseguimos escrever histórias de usuários com cenários de aceitação
a partir de uma estrutura que especifica o ator, a ação e a funcionalidade desejada.
- Ator: O interessado naquela funcionalidade, geralmente identificado com um papel.
- Ação: É o que o ator quer fazer. Utilizando aquela ação ele espera alcançar seu
objetivo dentro do sistema.
- Funcionalidade: É o que o ator espera que aconteça ao realizar a ação. Ou seja, é o
resultado de executar a ação segundo a ótica do ator. Também pode ser visto como
justificativa.

Alguns dos motivos para utilizar hitórias de usuários são (Cohn, 2004):
- Enfatizam comunicação verbal;
- São compreensivas para todos;
- Do tamanho certo para planejamento;
- Trabalham com desenvolvimento iterativo;
- Incentivam o adiantamento dos detalhes;
- Estimulam o projeto participativo.

## 2. Resultados

| ID   | História de Usuário                                                                                                                | Critérios de Aceitação                                                                                                                                                                                                                                     | ID do Requisito | Requisito                                                                                                  | Prioridade |
|------|------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------|------------|
| US1  | Eu, como usuário, devo ser capaz de criar uma página para escrever minhas anotações                                                | 1. Deve ter um opção de criar nova página na seção onde ficam as páginas.                                                                                                                                                                                  | RF1             | O usuário deve poder criar uma página.                                                                     | M          |
| US2  | Eu, como usuário, devo ser capaz de encontrar uma página criada préviamente para ver as informações escritas nela                  | 1. As páginas criadas devem ficar em uma seção no lado esquerdo da tela do usuário.                                                                                                                                                                        | RF2             | O usuário deve poder encontrar uma página criada previamente.                                              | M          |
| US3  | Eu, como usuário, devo ser capaz de excluir uma página para remover ela das páginas existentes                                     | 1. A opção de excluir a página deve aparecer quando seleciona o "três pontinhos" ao lado do titulo da página na seção de páginas criadas e nos "três pontinhos" na parte de cima da interface da página.                                                   | RF4             | O usuário deve poder excluir uma página quando desejado.                                                   | M          |
| US4  | Eu, como usuário, devo ser capaz de me autenticar no sistema para ter acesso às funcionalidades do app                             | 1. Deve ter um email/conta do google/conta da apple válida.                                                                                                                                                                                                | RF5             | O usuário deve poder ser autenticado no sistema.                                                           | M          |
| US5  | Eu, como usuário, devo ser capaz de pequisar por uma página para achar ela mais rapidamente                                        | 1. O mecanismo de pesquisa deve ficar nas primeiras opções de funcionalidade do workspace, ou seja, na parte de cima do barra lateral.                                                                                                                     | RF6             | O usuário deve poder pesquisar as páginas já criadas pelo nome delas.                                      | C          |
| US6  | Eu, como usuário, devo ser capaz de escolher em qual fonte editar minha página                                                     | 1. As opções de fonte devem aparecer quando o usuário acessa os "três pontinhos" na parte de cima da interface da página.                                                                                                                                  | RF7             | O usuário deve poder escolher em qual fonte editar suas páginas.                                           | S          |
| US7  | Eu, como usuário, devo ser capaz de escolher entre tamanho de fonte grande ou pequena                                              | 1. As opções de tamanho de fonte devem aparecer quando o usuário acessa os "três pontinhos" na parte de cima da interface da página.                                                                                                                       | RF8             | O usuário deve poder escolher entre o tamanho de fonte grande e pequena.                                   | C          |
| US8  | Eu, como usuário, devo ser capaz de escolher se o texto da página ocupa toda a largura da página ou se fica centralizado na página | 1. Essa opção deve apareccer quando o usuário acessa os "três pontinhos" na parte de cima da interface da página.                                                                                                                                          | RF9             | O usuário deve poder escolher se o texto ocupa toda a largura da página ou se fica centralizado na página. | C          |
| US9  | Eu, como usuário, devo ser capaz de ver o histórico de alterações da página                                                        | 1. O histórico deve ser acessado a partir da funcionalidade com simbolo de relógio na parte de cima da interface da página.                                                                                                                                | RF10            | O usuário deve poder ver o histórico de alterações da página.                                              | S          |
| US10 | Eu, como usuário, devo ser capaz de favoritar a página para deixar ela na aba de favoritos                                         | 1. A opção de favoritar a página deve ser representada por uma estrela na parte superior da página.<br/>2. As páginas favoritadas devem aparecer em uma seção na barra lateral da interface.                                                               | RF11            | O usuário deve poder favoritar a página.                                                                   | C          |
| US11 | Eu, como usuário, devo ser capaz de compartilhar o link da página para que outros usuários tenham acesso a ela                     | 1. A opção de compartilhar o link deve ficar no canto superior da página quando se aperta na palavra "share" e deve aparecer, também, quando se aperta os "três pontinhos" na parte superior da interface da página.                                       | RF12            | O usuário deve poder compartilhar o link para a página.                                                    | M          |
| US12 | Eu, como usuário, devo ser capaz de escolher a aparência do sistema para mudar a tematica de cores do design do sistema            | 1. A opção de mudar a aparência do sistema deve aparecer na parte de "notification and settings" das condigurações do sistema, que pode ser acessada na barra lateral da interface.                                                                        | RF13            | O usuário deve poder escolher a aparência do sistema.                                                      | W          |
| US13 | Eu, como usuário, devo ser capaz de escolher uma foto de identificação para cada página para aparecer do lado do titulo da página  | 1. A opção de escolher foto para a página deve aparecer no topo da interface da página, logo acima do titulo.<br/>2. A foto deve aparece tanto no topo da interface da página como ao lado do titulo na barra lateral onde se encontram as páginas criadas | RF14            | O usuário deve poder escolher uma foto de identificação para cada página.                                  | W          |
| US14 | Eu, como usuário, devo ser capaz de escolher uma foto de identificação do workspace para aparecer do lado do titulo do workspace   | 1. A opção de escolher foto para o workspace deve aparecer nas configurações do sistema na seção de workspace.<br/>2. A foto deve aparecer ao lado do nome do workspace.                                                                                   | RF15            | O usuário deve poder escolher uma foto de identificação para o workspace.                                  | C          |
| US15 | Eu, como usuário, devo ser capaz de ter quantos workspace que eu quiser                                                            | -                                                                                                                                                                                                                                                          | RF16            | O usuário deve poder ter quantos workspaces desejar.                                                       | S          |

## Referências Bibliográficas

Andrade, Edson; Uma Comparação Voltada a Interpretação Entre Casos de Uso e Histórias
de Usuário com Cenário de Aceitação; RS, 2016.


## Histórico de Versões

| Versão | Data       | Descrição                                              | Autor             |
|--------|------------|--------------------------------------------------------|-------------------|
| 1.0    | 26/07/2022 | Criação da Página e Incorporação de Texto Introdutório | Bernardo Pissutti |
| 1.1    | 28/07/2022 | Adição das historias de usuário US1 - US15             | Bernardo Pissutti |