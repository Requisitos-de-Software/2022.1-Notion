## 1. Introdução

## 2. Backward-from

A partir da definição de rastreabilidade foward-from, foi possível construir a _tabela 1_, a qual é responsável por conectar os requisitos com os respectivos artefatos de desenho e implementação, tais quais os cenários, casos de uso e histórias de usuário. Na descrição dos requisitos também foi realizado um link para os léxicos.

| Número | Requisito                                                                                                                                                                                                                                                                                                                 | Técnica                                                                                                                                           |                                                                                                         |  
|--------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------| 
| 1      | O usuário deve poder <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=criar">criar</a> uma <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a>                                                                           |  <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/cenarios?id=c05-cadastro-de-p%c3%a1gina-em-branco">C05</a>           |   
| 2      | O usuário deve poder encontrar uma <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina"><a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a></a> criada previamente                                              | -                                                                                                                                                 | 
| 3      | O usuário deve poder <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=editar">editar</a> uma <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a>                                                                         | -                                                                                                                                                 |  
| 4      | O usuário deve poder excluir uma <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a> quando desejado                                                                                                                                                           |                                                                                                                                                    |
| 5      | O usuário deve poder ser autenticado no sistema                                                                                                                                                                                                                                                                           | -                                                                                                                                                 |
| 6      | O usuário deve poder <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=pesquisar">pesquisar</a> as <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a>s já criadas pelo nome delas                                        | -                                                                                                                                                 | 
| 7      | O usuário deve poder escolher em qual fonte <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=editar">editar</a> suas <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a>s                                                | -                                                                                                                                                 | 
| 8      | O usuário deve poder escolher entre o tamanho de fonte grande e pequena                                                                                                                                                                                                                                                   | -                                                                                                                                                 | 
| 9      | O usuário deve poder escolher se o texto ocupa toda a largura da <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a> ou se fica centralizado na <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a> | |
| 10     | O usuário deve poder ver o histórico de alterações da <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a>                                                                                                                                                      | |
| 11     | O usuário deve poder favoritar a <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a>                                                                                                                                                                           | |
| 12     | O usuário deve poder <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=compartilhar">compartilhar</a> o link para a <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a>                                                   | |
| 13     | O usuário deve poder escolher a aparência do sistema                                                                                                                                                                                                                                                                      |  |
| 14     | O usuário deve poder escolher uma foto de identificação para cada <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a>                                                                                                                                          | |
| 15     | O usuário deve poder escolher uma foto de identificação para o workspace                                                                                                                                                                                                                                                  | |
| 16     | O usuário deve poder ter quantos workspaces desejar                                                                                                                                                                                                                                                                       |  |
| 17     | O usuário deve poder escolher entre opções de templates para uma <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=p%c3%a1gina">página</a> criada                                                                                                                                    | |

_Tabela 1: Foward-From_


## Elos
Os elos de rastreabilidade agilizam Na identificação de componentes atingidos por mudanças de versão do sistema operacional e/ou na troca de hardware, Reutilização de componentes, sendo os elos de rastreabilidade fortes aliados na criação de bibliotecas de componentes, pois deixam evidentes as correlações entre código e demais artefatos, sejam de desenho e/ou de requisitos, auxiliando na gerência de qualidade dos artefatos.


### Metodologia

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

  
### Conteúdo

Categoria: Desenvolvimento Elo:

Representação: RF1 representa [C05](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/cenarios?id=c05-cadastro-de-p%c3%a1gina-em-branco) e [LX02](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=criar).

#### Categoria: Desenvolvimento Elo:

Satifação: RF3 Satifaz [LX07](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=editar)

#### Categoria: Desenvolvimento Elo:

Satifação: RF4 Satifaz [LX06](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=deletar)

#### Categoria: Desenvolvimento Elo:

Satifação:  [LX01](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/lexicos?id=cadastro) satifaz RF5

#### Categoria: Desenvolvimento Elo:

Satifação: [UC02](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/casos_de_uso?id=uc-documento) satifaz RF6, RF7, RF8



## Referências Bibliográficas

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 26. 1º/2020. 44 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de Versões

| Versão | Data       | Descrição         | Autor            |
| ------ | ---------- | ----------------- | ---------------- |
| 1.0    | 23/08/2022 | Criação da página e escrita das seções *Introdução* e *Backward-from* | Arthur Lima e Nícolas Georgeos Mantzos |
| 1.0    | 23/08/2022 | Criação dos Elos 1 a 9 | Arthur Lima e Nícolas Georgeos Mantzos |
