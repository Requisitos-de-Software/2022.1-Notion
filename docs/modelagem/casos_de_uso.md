# Caso de Uso

Nessa seção, vamos definir e apresentar o diagrama de casos de uso referente ao app escolhido. Iremos definir primeiro *Caso de Uso*.

## 1. Definição

Um caso de uso é uma espécie de classificador comportamental (um classificador que pode ter comportamentos definidos em seu contexto) que especifica uma unidade completa de uma funcionalidade útil executada por um ou mais assuntos aos quais o caso de uso se aplica em colaboração com um ou mais atores e que produz um resultado observável que é de algum valor para aqueles atores (ou outras partes interessadas) de cada assunto. 

Os casos de uso permitem capturar requisitos de sistemas sob projeto ou consideração, descrevendo a funcionalidade fornecida por esses sistemas e determinar os requisitos que os sistemas impôem em seu ambiente.

Para a organização e representação desses Casos de Uso, são usados os Diagramas de Caso de Uso. 


  
## 2. Diagrama de Caso de Uso

Na Linguagem de Modelahem Unificada (UML), o diagrama de caso de uso resume os detalhes dos usuários do seu sistema (também conhecidos como atores) e as interações deles com o sistema, dando . Para criar um diagrama, um conjunto de símbolos e conectores especializados são utilizados.

Um bom diagrama de uso é capaz de ajudar uma equipe a representar e discutir:
-   Cenários em que o sistema ou aplicativo interage com pessoas, organizações ou sistemas externos.
-   Metas que o sistema ou aplicativo ajuda essas entidades a atingir.
-   O escopo do sistema.

O kit de símbolos pode ser visto na _Tabela 1_ abaixo.

| Símbolo | Significado | Representação Gráfica |
|:--:|:--:|:--:|
| Forma Oval Rotulada | Caso de Uso: Representam os diferentes usos que um usuário pode ter.| <img class="img_table" src="./_media/usecase.png"></img> |
| Bonecos Palito | Atores: Representando as pessoas que realmente executam os casos de uso. |<img class="img_table" src="./_media/ator.png"></img>|
| Linha entre Ator e Caso de Uso | Participação do Ator no Sistema: Nos diagramas complexos, é importante saber quais atores estão associados a quais casos de uso.  |<img class="img_table" src="./_media/interacao.png"></img>|
| Retângulo englobando os Casos de  Uso (Forma Oval Rotulada)  | Limite do Sistema: Define um escopo do sistema para os casos de uso. |<img class="img_table" src="./_media/fronteira.png"></img>|

_Tabela 1: Coleção de Elementos do Kit UML para criação do Diagrama de Casos de Uso_

<br/>
<br/>

Para uma melhor percepção do sistema, podemos incluir também relações do diagrama. Essas relações são representadas por um texto entre <<>> e é composta de dois casos, onde é explicado na _Tabela 2_ a seguir.

|Relação|Significado
|:--:|:--:|
| include | Relação de um caso de uso que para ter sua funcionalidade executada precisa chamar outro caso de uso |
| extend | Relação que identifica uma similaridade entre casos de uso porém com alguns passos novos inseridos no caso de uso extendido |

_Tabela 2: Coletânea de Relações em um Diagrama de Caso de Uso e seus significados_

<br/>
<br/>

Após análise do app selecionado e tomando como base os requisitos elicitados na seção [Elicitação](../elicitacao/resultado.md), a construção dos Diagramas de Casos de Uso foi feita e pode ser vista nas imagens abaixo:

### 2.1 UC-Conta
| ![US_Conta](../_media/us_conta.png)                                                   |
|---------------------------------------------------------------------------------------|
| Figura 1: Diagrama de Casos de Uso referentes a Autenticação; Fonte: autoria própria. |

### 2.1.1 Caso de Uso 1 - Fazer Login

| Informação      | Descrição                                                                                                                     |
|-----------------|-------------------------------------------------------------------------------------------------------------------------------|
| Nome            | Fazer Login                                                                                                                   |
| Descrição       | O usuário faz o login com a sua conta no app do notion                                                                        |
| Ator            | Usuário                                                                                                                       |
| Pré-condição    | Ter uma conta no notion                                                                                                       |
| Fluxo Principal | -  Clica no app do notion<br/>- Inserir o e-mail com o qual fez o cadastro<br/>- Inserir senha<br/>- Apertar na tecla 'enter' |
| Pós-condição    | Estar logado no app e poder ter acesso às funcionalidades                                                                     |

### 2.1.2 Caso de Uso 2 - Fazer Logout

| Informação      | Descrição                                                               |
|-----------------|-------------------------------------------------------------------------|
| Nome            | Fazer Logout                                                            |
| Descrição       | O usuário sai da sua conta cadastrada no app                            |
| Ator            | Usuário                                                                 |
| Pré-condição    | Estar logado                                                            |
| Fluxo Principal | - Usuário clica na workspace onde ele está<br/>- Clica em 'Log out all' |
| Pós-condição    | O usuário não está mais conectado com sua conta no app                  |

### 2.1.3 Caso de Uso 3 - Cadastrar Conta

| Informação      | Descrição                                                                                     |
|-----------------|-----------------------------------------------------------------------------------------------|
| Nome            | Cadastrar Conta                                                                               |
| Descrição       | O usuário cadastra uma conta no notion, onde poderá fazer uso das funcionalidades do app      |
| Ator            | Usuário                                                                                       |
| Pré-condição    | Estar conectado na internet                                                                   |
| Fluxo Principal | - Usuário abre o app<br/>- Clica em cadastrar conta<br/>- Preenche os campos necessários<br/> |
| Pós-condição    | O usuário tem um cadastro no app do notion                                                    |

### 2.2 UC-Documento
| ![US_Conta](../_media/us_documento.png)                                             |
|-------------------------------------------------------------------------------------|
| Figura 2: Diagrama de Casos de Uso referentes a Documentos; Fonte: autoria própria. |

### 2.2.1 Caso de Uso 4 - Editar Página

| Informação      | Descrição                                                                    |
|-----------------|------------------------------------------------------------------------------|
| Nome            | Editar Página                                                                |
| Descrição       | O usuário digita ou modifica a página como quiser, dada as restrições do app |
| Ator            | Usuário                                                                      |
| Pré-condição    | Estar logado e ter uma página criada                                         |
| Fluxo Principal | - Abrir a página que deseja editar<br/>- Digitar o que quiser nela           |
| Pós-condição    | Ter uma página alterada                                                      |

### 2.2.2 Caso de Uso 5 - Ver Atualizações da Página

| Informação      | Descrição                                                                                         |
|-----------------|---------------------------------------------------------------------------------------------------|
| Nome            | Ver Atualizações da Página                                                                        |
| Descrição       | O usuário pode ver todas as atualizações que fora feitas na página, incluindo o dia que foi feita |
| Ator            | Usuário                                                                                           |
| Pré-condição    | Ter uma página criada e te-la editado                                                             |
| Fluxo Principal | - Abrir a página que deseja ver as atualizações<br/>- Clicar no icone de relógio                  |
| Pós-condição    | Ter visualizado o historico de atualizações da página                                             |

### 2.2.3 Caso de Uso 6 - Favoritar Página

| Informação      | Descrição                                                                                                |
|-----------------|----------------------------------------------------------------------------------------------------------|
| Nome            | Favoritar Página                                                                                         |
| Descrição       | O usuário favorita a página que ele deseja e ela passa a aparecer em uma seção separada do barra lateral |
| Ator            | Usuário                                                                                                  |
| Pré-condição    | Ter uma página                                                                                           |
| Fluxo Principal | - Abrir a página que deseja favoritar<br/>- Clicar no icone de estrela                                   |
| Pós-condição    | Ter a página favoritada na seção de 'favorites' na barra laterial                                        |

### 2.2.4 Caso de Uso 7 - Pesquisar Páginas

| Informação      | Descrição                                                                                                                   |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------|
| Nome            | Pesquisar Páginas                                                                                                           |
| Descrição       | O usuário pesquisa a página que quiser para ter acesso mais rápido a ela                                                    |
| Ator            | Usuário                                                                                                                     |
| Pré-condição    | Ter a página criada                                                                                                         |
| Fluxo Principal | - Clicar no a opção de pesquisa na barra laterial<br/>- Digitar o nome da página que deseja pesquisar<br/>- Apertar 'enter' |
| Pós-condição    |  Ter acesso a página pesquisada                                                                                             |

### 2.2.5 Caso de Uso 8 - Excluir Página

| Informação      | Descrição                                                                                            |
|-----------------|------------------------------------------------------------------------------------------------------|
| Nome            | Excluir Página                                                                                       |
| Descrição       | O usuário remove da sua conta uma página que ele não deseja mais                                     |
| Ator            | Usuário                                                                                              |
| Pré-condição    | A página deve existir                                                                                |
| Fluxo Principal | - Clicar com o butão direito do mouse na página que deseja excluir<br/>- Clicar na opção de 'Delete' |
| Pós-condição    | Não terá mais a página excluida na conta                                                             |

### 2.2.6 Caso de Uso 9 - Adicionar Página

| Informação      | Descrição                                      |
|-----------------|------------------------------------------------|
| Nome            | Adicionar Página                               |
| Descrição       | O usuário adiciona uma página na conta dele    |
| Ator            | Usuário                                        |
| Pré-condição    | Estar logado                                   |
| Fluxo Principal | - Clicar no simbolo de 'mais' na barra lateral |
| Pós-condição    | Ter uma nova página na conta                   |

### 2.3 UC-Workspace
| ![US_Conta](../_media/us_workspace.png)                                             |
|-------------------------------------------------------------------------------------|
| Figura 3: Diagrama de Casos de Uso referentes a Workspaces; Fonte: autoria própria. |

### 2.3.1 Caso de Uso 10 - Criar Workspace

| Informação      | Descrição                                                                                                                                                |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Nome            | Criar Workspace                                                                                                                                          |
| Descrição       | Ter outro workspace na conta para dividir melhor as categorias das páginas                                                                               |
| Ator            | Usuário                                                                                                                                                  |
| Pré-condição    | Estar logado                                                                                                                                             |
| Fluxo Principal | - Clicar no workspace atual<br/>- Clicar nos três pontinhos do lado do e-mail<br/>- Clicar em 'Join or create workspace'- Escolher a opção 'For myself'  |
| Pós-condição    | Ter um workspace a mais na conta                                                                                                                         |

### 2.3.2 Caso de Uso 11 - Deletar Workspace

| Informação      | Descrição                                                                                           |
|-----------------|-----------------------------------------------------------------------------------------------------|
| Nome            | Deletar Workspace                                                                                   |
| Descrição       | O usuário exclui o workspace                                                                        |
| Ator            | Usuário                                                                                             |
| Pré-condição    | Estar logado e ter mais de uma workspace                                                            |
| Fluxo Principal | - Clicar em 'settings & member'<br/>- Clicar em 'setting'<br/>- Clicar em 'Delete entire workspace' |
| Pós-condição    | Ter o workspace apagado                                                                             |

### 2.3.3 Caso de Uso 12 - Juntar a um Workspace

| Informação      | Descrição                                                                                                                                                 |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Nome            | Juntar a um Workspace                                                                                                                                     |
| Descrição       | O usuário se junta a um workspace criado por outro usuário                                                                                                |
| Ator            | Usuário                                                                                                                                                   |
| Pré-condição    | Ter uma conta                                                                                                                                             |
| Fluxo Principal | - Clicar no workspace atual<br/>- Clicar nos três pontinhos do lado do e-mail<br/>- Clicar em 'Join or create workspace'- Escolher a opção 'With my team' |
| Pós-condição    | Ter uma workspace compartilhado com outras pessoas                                                                                                        |


## Referências Bibliográficas

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. 50 slides. Material apresentado para a disciplina
de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

LUCIDCHART - Diagrama de Caso de Uso UML -  https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml.

UML DIAGRAMS - Use Case Diagrams -  https://www.uml-diagrams.org/use-case-diagrams.html


## Histórico de Versões

| Versão | Data        | Descrição                                               | Autor             | Revisor |
|--------|-------------|---------------------------------------------------------|-------------------|---------|
| 1.0    | 19/07/2022  |  Criação da Página e Incorporação de Texto Introdutório | Guilherme Brito   | Arthur  |
<style>
    .img_table{
        height: 150px;
        width: 165px;
    }
</style>