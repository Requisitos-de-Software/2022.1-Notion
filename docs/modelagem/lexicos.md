# Léxicos

## 1. Introdução

Nessa sessão serão apresentados os léxicos desenvolvidos durante a disciplina. Léxicos tratam-se de uma técnica que procura descrever os símbolos de uma linguagem, o principal objetivo a ser perseguido pelos engenheiros de Requisitos é a identificação de palavras ou frases peculiares ao meio social da aplicação sob estudo. Cada símbolo tem zero ou mais sinônimos, uma ou mais noções e um ou mais impactos. (SERRANO, Requisitos - Aula 10)

## 2. Metodologia

Os léxicos seguem a tabela 1 como modelo referência:

| Tipo   | Noção                                                              | Impacto                                                                                 | Sinônimos            |
| ------ | ------------------------------------------------------------------ | --------------------------------------------------------------------------------------- | -------------------- |
| Verbo  | Quem realiza, quando acontece e quais procedimentos são envolvidos | Quais os reflexos da ação                                                               | Sinônimos do símbolo |
| Objeto | Definir o objeto e outros objetos com os quais se relaciona        | Ações que podem ser aplicadas ao objeto                                                 | Sinônimos do símbolo |
| Estado | O que significa e quais ações levaram a esse estado                | Identificar outros estados e ações que podem ocorrer a partir do estado que se descreve | Sinônimos do símbolo |

_Tabela 1: Modelo para os léxicos (SERRANO, Requisitos - Aula 10)_

## 3. Léxicos

### 3.1 Verbos

#### Cadastro

| Tipo  | Noção                               | Impacto                                                                                                      | Sinônimos            |
| ----- | ----------------------------------- | ------------------------------------------------------------------------------------------------------------ | -------------------- |
| Verbo | O usuário se cadastra na plataforma | O usuário conseguirá fazer login a partir da conta cadastrada e terá acesso as funcionalidades do aplicativo | Registrar, inscrever |

#### Criar

| Tipo  | Noção                                                       | Impacto                                                                          | Sinônimos          |
| ----- | ----------------------------------------------------------- | -------------------------------------------------------------------------------- | ------------------ |
| Verbo | O usuário cria uma página na plataforma quando ele precisar | A página do usuário será salva na base de dados relacionada ao cadastro do mesmo | Produzir, fabricar |

#### Compartilhar

| Tipo  | Noção                                                                | Impacto                                                                                              | Sinônimos |
| ----- | -------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | --------- |
| Verbo | O usuário pode compartilhar algo quando quiser exportar suas páginas | Outras pessoas teriam acesso a página que um certo usuário criou, porém fora do sistema da aplicação | Partilhar |

#### Comentar

| Tipo  | Noção                                                                    | Impacto                                                                                                                                                                             | Sinônimos |
| ----- | ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| Verbo | O usuário pode comentar a página de outra pessoa quando achar necessário | O criador do arquivo conseguirá visualizar os comentários feitos na página dele a partir da lista de notificações do sistema, e então editar de acordo com o comentário caso queira | Partilhar |

#### Convidar

| Tipo  | Noção                                           | Impacto                                                                                                                                                                   | Sinônimos |
| ----- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| Verbo | O usuário convida outro usuário para uma página | A pessoa que foi convidada teria acesso a página e também poderia ter a possibilidade de editar o documento, dependendo da permissão que o usuário que o convidou lhe deu | Partilhar |

#### Deletar

| Tipo  | Noção                                                         | Impacto                                                                                                                                 | Sinônimos         |
| ----- | ------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| Verbo | O usuário deleta uma página na plataforma quando ele precisar | A página é deletada da sua lista principal de páginas criadas, porém, ainda é possível visualizá-la na página de deletados recentemente | Excluir, Eliminar |

#### Editar

| Tipo  | Noção                                                        | Impacto                                                                                                         | Sinônimos          |
| ----- | ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------- | ------------------ |
| Verbo | O usuário edita uma página na plataforma quando ele precisar | A edição feita pelo usuário será salva na base de dados e ele passará a ver o arquivo com o resultado da edição | Atualizar, alterar |

#### Login

| Tipo  | Noção                                               | Impacto                                                                             | Sinônimos |
| ----- | --------------------------------------------------- | ----------------------------------------------------------------------------------- | --------- |
| Verbo | O usuário realiza login com sua conta já cadastrada | O usuário terá acesso a sua conta e poderá tomar as devidas ações dentro do sistema | Acessar   |

#### Logout

| Tipo  | Noção                                        | Impacto                                                                     | Sinônimos |
| ----- | -------------------------------------------- | --------------------------------------------------------------------------- | --------- |
| Verbo | O usuário realiza logout após uso do sistema | O usuário não terá mais acesso à sessão que ele estava logado anteriormente | Sair      |

#### Pesquisar

| Tipo  | Noção                                               | Impacto                                                                                                                                                                   | Sinônimos         |
| ----- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| Verbo | O usuário pode pesquisar algo quando for necessário | O retorno serão especificamente os títulos de documentos criados previamente pelo usuário, sendo que esses títulos podem ser de caráter primário, secundário ou terciário | Explorar, Filtrar |

### 3.2 Objetos

#### Arquivados

| Tipo   | Noção                                                   | Impacto                                                                                                               | Sinônimos |
| ------ | ------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | --------- |
| Objeto | Página que mostra as atualizações arquivadas do usuário | A página de arquivado irá apresentar para o usuário qualquer modificação que alguma caixa de entrada arquivada sofrer |           |

#### Caixa de entrada

| Tipo   | Noção                                 | Impacto                                                                                                                                                           | Sinônimos |
| ------ | ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| Objeto | Página da caixa de entrada do usuário | A caixa de entrada notifica o usuário sempre que ele for mencionado, quando alguém responder algum comentário dele ou quando ele for convidado para alguma página |           |

#### Configurações

| Tipo   | Noção                                                                     | Impacto                                                                                                                          | Sinônimos |
| ------ | ------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | --------- |
| Objeto | A página de configurações contém as configurações da aplicação do usuário | As configurações podem ser modificadas pelo usuário como ele bem entender, tendo como base as configurações cedidas pelo sistema |           |

#### Deletados recentemente

| Tipo   | Noção                                                         | Impacto                                                                                                          | Sinônimos |
| ------ | ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | --------- |
| Objeto | Página que mostra as páginas que foram deletadas recentemente | A página de deletados recentemente permite que o usuário possa deletar permanentemente um arquivo ou restaurá-lo |           |

#### Página

| Tipo   | Noção                                                                                 | Impacto                                                                                         | Sinônimos |
| ------ | ------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | --------- |
| Objeto | Uma página é um artefato criado pelo usuário que contém as informações que ele deseja | A página pode ser editada, deletada, criada, compartilhada pelo usuário quando achar necessário |           |

#### Seguindo

| Tipo   | Noção                                                                     | Impacto                                                                              | Sinônimos |
| ------ | ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | --------- |
| Objeto | Página que mostra as atualizações feitas nas páginas que o usuário seguiu | A página apresenta ao usuário as alterações que o arquivo que o usuário segue sofreu |           |

#### Todas as atualizações

| Tipo   | Noção                                          | Impacto                                                                                                   | Sinônimos |
| ------ | ---------------------------------------------- | --------------------------------------------------------------------------------------------------------- | --------- |
| Objeto | Página com as informações das ações do usuário | A página notifica o usuário das ações que ele tomou dentro do sistema, como deleção e criação de arquivos |           |

### 3.3 Estados

#### Alterado

| Tipo   | Noção                               | Impacto                                                                 | Sinônimos           |
| ------ | ----------------------------------- | ----------------------------------------------------------------------- | ------------------- |
| Estado | O arquivo foi alterado pelo usuário | Toda alteração do arquivo é registrada na página de todas as alterações | Editado, atualizado |

#### Arquivado

| Tipo   | Noção                                         | Impacto                                                                                                                                               | Sinônimos |
| ------ | --------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| Estado | A caixa de entrada foi arquivada pelo usuário | A caixa de entrada arquivada é apresentada em uma tela diferente das outras caixas, ela pode ser restaurada para a caixa de entrada normal do sistema |           |

#### Deletado

| Tipo   | Noção                                          | Impacto                                                                                                                                                             | Sinônimos |
| ------ | ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| Estado | O arquivo foi deletado pelo usuário do sistema | Quando o usuário restaura o arquivo ele volta para a lista de arquivos principais, mas já quando o usuário deleta permanentemente o arquivo é deletado por completo | Excluído  |

## Referências Bibliográficas

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 10. 1º/2019. 35 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de Versões

| Versão | Data       | Descrição         | Autor            |
| ------ | ---------- | ----------------- | ---------------- |
| 1.0    | 19/07/2022 | Criação da página | Cícero Fernandes |
