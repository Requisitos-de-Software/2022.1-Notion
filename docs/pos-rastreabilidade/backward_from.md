## 1. Introdução

## 2. Backward-from

## Metodologia

Para a criação do elos foram utilizados o Meta-modelo de Toranzo, Onde São categorizados em quatro níveis:
- ambiental: refere-se ao ambiente onde a organização está inserida
- organizacional: informações pertencentes à organização (missão,objetivos e estratégias)
- gerencial: : informações que auxiliam a gerência do projeto,
- desenvolvimento: informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento

E são providos de descrição dos elos de rastreabilidade:

- Satifação:  classe origem tem dependência de satisfação com a classe destino.
- Recurso: classe origem tem dependência de recurso com a classe destino.
- Responsabilidade: representa a ação de pessoas sobre os artefatos.
- Representação:  captura a representação ou modelagem dos requisitos em outras linguagens.
- Alocado:  classe origem está relacionada à classe destino, que representa um subsistema.
- Agregação: indica “composição” de elementos.

### 2.1 Matriz

A partir da definição de rastreabilidade foward-from, foi possível construir a _tabela 1_, a qual é responsável por conectar os requisitos com os respectivos artefatos de desenho e implementação, tais quais os cenários, casos de uso e histórias de usuário. Na descrição dos requisitos também foi realizado um link para os léxicos.

| Código | Requisitos Funcionais                                                                                      | Técnica        | Persona |
|--------|------------------------------------------------------------------------------------------------------------|----------------|----------------|
| RF1    | O usuário deve poder criar uma página.                                                                     | Introspecção   | Carlos da Silva |
| RF2    | O usuário deve poder encontrar uma página criada previamente.                                              | Introspecção   | Marina Costa |
| RF3    | O usuário deve poder editar uma página.                                                                    | Introspecção   | Marina Costa |
| RF4    | O usuário deve poder excluir uma página quando desejado.                                                   | Introspecção   | Marcelo Araújo |
| RF5    | O usuário deve poder ser autenticado no sistema.                                                           | Introspecção   | Marcelo Araújo |
| RF6    | O usuário deve poder pesquisar as páginas já criadas pelo nome delas.                                      | Introspecção   | Marcelo Araújo |
| RF7    | O usuário deve poder escolher em qual fonte editar suas páginas.                                           | Introspecção   | Marcelo Araújo |
| RF8    | O usuário deve poder escolher entre o tamanho de fonte grande e pequena.                                   | Introspecção   | Marina Costa |
| RF9    | O usuário deve poder escolher se o texto ocupa toda a largura da página ou se fica centralizado na página. | Introspecção   | Marina Costa |
| RF10   | O usuário deve poder ver o histórico de alterações da página.                                              | Introspecção   | Marina Costa |
| RF11   | O usuário deve poder favoritar a página.                                                                   | Introspecção   | Marina Costa |
| RF12   | O usuário deve poder compartilhar o link para a página.                                                    | Introspecção   | Carlos da Silva |
| RF13   | O usuário deve poder escolher a aparência do sistema.                                                      | Introspecção   | Carlos da Silva |
| RF14   | O usuário deve poder escolher uma foto de identificação para cada página.                                  | Introspecção   | Carlos da Silva |
| RF15   | O usuário deve poder escolher uma foto de identificação para o workspace.                                  | Introspecção   | Carlos da Silva |
| RF16   | O usuário deve poder ter quantos workspaces desejar.                                                       | Introspecção   | Marcelo Araújo |
| RF17   | O usuário deve poder escolher entre opções de templates para uma página criada.                            | Introspecção   | Carlos da Silva |
| RF18   | O usuário deve poder ver o histórico de páginas deletadas.                                                 | Introspecção   | Marina Costa |
| RF19   | O usuário deve poder importar páginas de outras plataformas ou aplicativos.                                | Introspecção   | Carlos da Silva |
| RF20   | O usuário deve poder adicionar fotos a página.                                                             | Introspecção   | Marcelo Araújo |
| RF21   | O usuário deve poder referenciar outras páginas dentro de uma página.                                      | Introspecção   | Marina Costa |
| RF22   | O usuário deve poder adicionar outros perfis para editar uma página.                                       | Introspecção   | Carlos da Silva |
| RF23   | O usuário deve poder adicionar uma legenda às imagens da página.                                           | Introspecção   | Marcelo Araújo |
| RF24   | O usuário deve poder escrever comentários nas páginas.                                                     | Introspecção   | Marcelo Araújo |
| RF25   | O usuário deve poder criar blocos de markdown para editar as páginas.                                      | Introspecção   | Marina Costa |
| RF26   | O usuário deve poder escolher entre opções de edição do bloco de markdown.                                 | Introspecção   | Marina Costa |
| RF27   | O usuário deve poder ter uma agenda para visualizar afazeres do dia.                                       | Questionário   |  - |
| RF28   | O usuário deve poder criar Formulas matemáticas.                                                           | Brainstorming  | Todas |
| RF29   | O usuário deve poder criar seu próprio quadro kanban personalizado.                                        | Brainstorming  | Todas |
| RF30   | O usuário pode escrever blocos de código.                                                                  | Brainstorming  | Todas |
| RF31   | O usuário deve ser informado da situação do clima em sua região.                                           | Brainstorming  | Todas |
| RF32   | O usuário deve conseguir criar uma conta                                                                   | Brainstorming  | Todas |
| RF33   | O usuário deve conseguir realizar logout                                                                   | Brainstorming  | Todas  |
_Tabela 1: Requisitos funcionais resultado_

| Código | Requisitos Não Funcionais                                            | Técnica       | Persona |
| ------ | -------------------------------------------------------------------- | ------------- | ------------- |
| RNF1   | Deve ser possível instalar a aplicação em dispositivos android       |   Introspecção | Marcelo Araújo |
| RNF2   | A interface do sistema deve ser responsiva                           | Introspecção  | Marina Costa |
| RNF3   | O aplicativo deve ser cross-plataform                                | Questionário  | - |
| RNF4   | As Formulas Matemáticas devem seguir o formato LaTeX.                | Brainstorming | Todas | 
| RNF5   | A sintaxe dos códigos devem seguir uma das linguagens mais recentes. | Brainstorming |  Todas |
_Tabela 2: Requisitos não funcionais resultado_

### 2.1 Elos

## E1 (RF1)

**Categoria**: Desenvolvimento

**Elo**:

Satifação: [C05](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/cenarios?id=c05-cadastro-de-p%c3%a1gina-em-branco) e [LX02](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=criar).

## E2 (RF3)

**Categoria**: Desenvolvimento

**Elo**:

Satifação: [LX07](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=editar)

## E3 (RF4)

**Categoria**: Desenvolvimento

**Elo**:

- Satifação: [LX06](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=deletar)

## E4 (RF5)

**Categoria**: Desenvolvimento

**Elo**:

- Satifação: [LX01](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=cadastro)

## E5 (RF10)

**Categoria**: Desenvolvimento

**Elo**:
- Satisfação: <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/casos_de_uso?id=uc-documento">US-Documento</a>

## E6 (RF11)

**Categoria**: Desenvolvimento

**Elo**:
- Satisfação: <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/casos_de_uso?id=uc-documento">US-Documento</a>

## E7 (RF12)

**Categoria**: Desenvolvimento

**Elo**:
- Satisfação: <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/casos_de_uso?id=uc-workspace">US-Workspace</a> e <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=compartilhar">LV-Compartilhar</a>

## E8 (RF13)

**Categoria**: Desenvolvimento

**Elo**:
- Satisfação: <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/casos_de_uso?id=uc-documento">US-Documento</a> e <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/cenarios?id=c03-cadastro-de-workspace">C03-Cadastro de workspace</a>

## E9 (RF14)

**Categoria**: Desenvolvimento

**Elo**:
- Satisfação: <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/casos_de_uso?id=uc-documento">US-Documento</a> e <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=editar">LV-Editar</a>

## E10 (RF15)

**Categoria**: Desenvolvimento

**Elo**:
- Satisfação: <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/casos_de_uso?id=uc-documento">US-Documento</a>

## E11 (RF17)

**Categoria**: Desenvolvimento

**Elo**:
- Satisfação: <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/cenarios?id=c07-cadastro-de-p%c3%a1gina-a-partir-de-template">C7 - Cadastro de página a partir de template</a>

## E12 (RF18)

**Categoria**: Desenvolvimento

**Elo**:
- Satisfação: <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=deletados-recentemente">LO - Deletados recentemente</a>

## E13 (RF19)

**Categoria**: Desenvolvimento

**Elo**:
- Satisfação: <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/cenarios?id=c09-cadastro-de-p%c3%a1gina-a-partir-de-base-de-dados">C9 - Cadastro de página a partir de base de dados</a>

## E14 (RF20)

**Categoria**: Desenvolvimento

**Elo**:
- Satisfação: <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/casos_de_uso?id=uc-documento">US-Documento</a>

## E15

**Categoria**: Desenvolvimento

**Elo**:
- Satisfação: [UC02](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/casos_de_uso?id=uc-documento) satifaz RF6, RF7, RF8.

## Elos
Os elos de rastreabilidade agilizam Na identificação de componentes atingidos por mudanças de versão do sistema operacional e/ou na troca de hardware, Reutilização de componentes, sendo os elos de rastreabilidade fortes aliados na criação de bibliotecas de componentes, pois deixam evidentes as correlações entre código e demais artefatos, sejam de desenho e/ou de requisitos, auxiliando na gerência de qualidade dos artefatos.

## Referências Bibliográficas

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 26. 1º/2020. 44 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de Versões

| Versão | Data       | Descrição         | Autor            |
| ------ | ---------- | ----------------- | ---------------- |
| 1.0    | 23/08/2022 | Criação da página e escrita das seções *Introdução* e *Backward-from* | Arthur Lima e Nícolas Georgeos Mantzos |
| 1.0    | 23/08/2022 | Criação dos Elos 1 a 9 | Arthur Lima e Nícolas Georgeos Mantzos |
