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

| História de Usuário | Rastreabilidade | Eu, como usuário, gostaria de...                                                               | Para poder...                                                                                                   | Prioridade |
| ------------------- | --------------- | ---------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ---------- |
| US1                 | RF1             | Criar uma página                                                                               | Escrever minhas anotações                                                                                       | M          |
| US2                 | RF2             | Encontrar uma página criada previamente                                                        | Ver as informações escritas nela                                                                                | M          |
| US3                 | RF3             | Editar uma página                                                                              | Para ter controle total sobre ela caso falhe em algum item e precise editá-lo                                   | M          |
| US4                 | RF4             | Excluir uma página                                                                             | Remover ela das páginas existentes                                                                              | M          |
| US5                 | RF5             | Me autenticar no sistema para ter acesso às funcionalidades do app                             | Ter acesso às funcionalidades do app                                                                            | M          |
| US6                 | RF6             | Pesquisar por uma página                                                                       | Encontrar ela mais rapidamente                                                                                  | C          |
| US7                 | RF7             | Escolher em qual fonte editar minha página                                                     | Escrever texto com a fonte desejada                                                                             | S          |
| US8                 | RF8             | Escolher entre tamanho de fonte grande ou pequena                                              | Escrever texto com tamanho de fonte desejada                                                                    | C          |
| US9                 | RF9             | Escolher se o texto da página ocupa toda a largura da página ou se fica centralizado na página |                                                                                                                 | C          |
| US10                | RF10            | Visualizar o histórico de alterações da página                                                 | Verificar as alterações feitas                                                                                  | S          |
| US11                | RF11            | Favoritar uma página                                                                           | Salvar ela na aba de favoritos                                                                                  | C          |
| US12                | RF12            | Compartilhar o link de uma página                                                              | Liberar que outros usuários tenham acesso a ela                                                                 | M          |
| US13                | RF13            | Escolher a aparência do sistema                                                                | Mudar a temática de cores do design do sistema                                                                  | W          |
| US14                | RF14            | Escolher uma foto de identificação da página                                                   | Identificar uma página                                                                                          | W          |
| US15                | RF15            | Escolher uma foto de identificação do workspace                                                | Identificar um workspace                                                                                        | C          |
| US16                | RF16            | Criar quantos workspaces que eu quiser                                                         | Organizar meus workspaces com conteúdo similar                                                                  | S          |
| US17                | RF17            | Poder escolher entre opções de templates de uma página criada                                  | Criar páginas padronizadas sem muito esforço                                                                    | M          |
| US18                | RF18            | Ver o histórico de páginas deletadas                                                           | Gerenciar suas deleções e até recuperar alguma                                                                  | S          |
| US19                | RF19            | Importar páginas de outras plataformas ou aplicativos                                          | Ter uma versão editável de uma página que ele se interessou                                                     | C          |
| US20                | RF20            | Adicionar fotos a página                                                                       | Visualizar de maneira melhor um item que ele estava digitando mas precisaria de uma imagem para entender melhor | S          |
| US21                | RF21            | Referenciar outras páginas dentro de uma página                                                | Ter acesso a outras páginas que complementem o tópico abordado                                                  | C          |
| US22                | RF22            | Adicionar outros perfis para editar uma página                                                 | Ter a opinião/visão de um outro alguém no tópico abordado                                                       | C          |
| US23                | RF23            | Adicionar uma legenda às imagens da página                                                     | Saber do que a imagem se trata                                                                                  | C          |
| US24                | RF24            | Escrever comentários nas páginas                                                               | Posteriormente checar alguma anotação ou observação feita                                                       | W          |
| US25                | RF25            | Criar blocos de markdown para editar as páginas                                                | Construir itens que na digitação comum não se apresentam com tanta facilidade, como tabelas                     | M          |
| US26                | RF26            | Escolher entre opções de edição do bloco de markdown                                           | Editar o bloco criado como desejado                                                                             | M          |
| US27                | RF27            | Ter uma agenda                                                                                 | Visualizar afazeres do dia desejado                                                                             | S          |
| US28                | RF28            | Criar fórmulas matemáticas                                                                     | Ter facilidade caso necessite anotar alguma fórmula                                                             | S          |
| US29                | RF29            | Criar seu próprio quadro kanban personalizado                                                  | para gerenciar suas tarefas com facilidade                                                                      | S          |
| US30                | RF30            | Escrever blocos de código                                                                      | Entender a sintaxe do código sem se perder na linguagem padrão ou não estilizada                                | C          |
| US31                | RF31            | Ser informado da situação do clima na minha região                                             | Saber como está o tempo sem precisar minimizar minha aplicação                                                  | W          |


## Critérios de Aceitação das Histórias de Usuário

### US01 - Criar uma página

&emsp;&emsp;Eu, como usuário, devo ser capaz de criar uma página para escrever minhas anotações.

#### Criterios de aceitação
- Deve ter um opção de criar nova página na seção onde ficam as páginas.


### US02 - Encontrar uma página
&emsp;&emsp;Eu, como usuário, devo ser capaz de encontrar uma página criada préviamente para ver as informações escritas nela

#### Criterios de aceitação
- As páginas criadas devem ficar em uma seção no lado esquerdo da tela do usuário.


### US03 - Editar uma página
&emsp;&emsp;Eu, como usuário, devo ser capaz de editar uma página criada para alterar as informações escritas nela

#### Criterios de aceitação
- As páginas editada deve ser salva com as alterações realizadas.


### US04 - Excluir uma página
&emsp;&emsp;Eu, como usuário, devo ser capaz de excluir uma página para remover ela das páginas existentes

#### Criterios de aceitação
- A opção de excluir a página deve aparecer quando seleciona o "três pontinhos" ao lado do titulo da página na seção de páginas criadas e nos "três pontinhos" na parte de cima da interface da página.

### US05 - Login
&emsp;&emsp;Eu, como usuário, devo ser capaz de me autenticar no sistema para ter acesso às funcionalidades do app

#### Criterios de aceitação
- Deve ter um email/conta do google/conta da apple válida.


### US06 - Pesquisar uma página
&emsp;&emsp;Eu, como usuário, devo ser capaz de pequisar por uma página para achar ela mais rapidamente

#### Criterios de aceitação
- O mecanismo de pesquisa deve ficar nas primeiras opções de funcionalidade do workspace, ou seja, na parte de cima do barra lateral.

### US07 - Escolher fonte
&emsp;&emsp;Eu, como usuário, devo ser capaz de escolher em qual fonte editar minha página

#### Criterios de aceitação
- As opções de fonte devem aparecer quando o usuário acessa os "três pontinhos" na parte de cima da interface da página.

### US08 - Escolher tamanho de fonte
&emsp;&emsp;Eu, como usuário, devo ser capaz de escolher entre tamanho de fonte grande ou pequena

#### Criterios de aceitação
- As opções de tamanho de fonte devem aparecer quando o usuário acessa os "três pontinhos" na parte de cima da interface da página.

### US09 - Centralizar texto
&emsp;&emsp;Eu, como usuário, devo ser capaz de escolher se o texto da página ocupa toda a largura da página ou se fica centralizado na página

#### Criterios de aceitação
- Essa opção deve apareccer quando o usuário acessa os "três pontinhos" na parte de cima da interface da página.

### US10 - Visualizar histórico 
&emsp;&emsp;Eu, como usuário, devo ser capaz de ver o histórico de alterações da página.

#### Criterios de aceitação
- O histórico deve ser acessado a partir da funcionalidade com simbolo de relógio na parte de cima da interface da página.

### US011 - Favoritar página
&emsp;&emsp;Eu, como usuário, devo ser capaz de favoritar a página para deixar ela na aba de favoritos

#### Criterios de aceitação
- A opção de favoritar a página deve ser representada por uma estrela na parte superior da página.<br/>2. As páginas favoritadas devem aparecer em uma seção na barra lateral da interface.

### US12 - Compartilhar link da página
&emsp;&emsp;Eu, como usuário, devo ser capaz de compartilhar o link da página para que outros usuários tenham acesso a ela.

#### Criterios de aceitação
- A opção de compartilhar o link deve ficar no canto superior da página quando se aperta na palavra "share" e deve aparecer, também, quando se aperta os "três pontinhos" na parte superior da interface da página.

### US13 - Escolher aparência do sistema
&emsp;&emsp;Eu, como usuário, devo ser capaz de escolher a aparência do sistema para mudar a tematica de cores do design do sistema

#### Criterios de aceitação
- A opção de mudar a aparência do sistema deve aparecer na parte de "notification and settings" das condigurações do sistema, que pode ser acessada na barra lateral da interface.

### US14 -  Escolher foto identificação da página
&emsp;&emsp;Eu, como usuário, devo ser capaz de escolher uma foto de identificação para cada página para aparecer do lado do titulo da página

#### Criterios de aceitação
- A opção de escolher foto para a página deve aparecer no topo da interface da página, logo acima do titulo.
- A foto deve aparece tanto no topo da interface da página como ao lado do titulo na barra lateral onde se encontram as páginas criadas.

### US15 -  Escolher foto identificação do workspace
&emsp;&emsp;Eu, como usuário, devo ser capaz de escolher uma foto de identificação do workspace para aparecer do lado do titulo do workspace

#### Criterios de aceitação
- A opção de escolher foto para o workspace deve aparecer nas configurações do sistema na seção de workspace.
- A foto deve aparecer ao lado do nome do workspace.


### US16 -  Criar workspace
&emsp;&emsp;Eu, como usuário, devo ser capaz de ter quantos workspace que eu quiser

#### Criterios de aceitação
- 




## Referências Bibliográficas

Andrade, Edson; Uma Comparação Voltada a Interpretação Entre Casos de Uso e Histórias
de Usuário com Cenário de Aceitação; RS, 2016.

## Histórico de Versões

| Versão | Data       | Descrição                                              | Autor              |
| ------ | ---------- | ------------------------------------------------------ | ------------------ |
| 1.0    | 26/07/2022 | Criação da Página e Incorporação de Texto Introdutório | Bernardo Pissutti  |
| 1.1    | 28/07/2022 | Adição das histórias de usuário US1 - US15             | Bernardo Pissutti  |
| 1.2    | 01/08/2022 | Reformulação da tabela de Histórias de Usuários        | Leonardo Vitoriano |
| 1.3    | 02/08/2022 | Adição das histórias de usuário US16 - US31            | Cícero Fernandes   |
