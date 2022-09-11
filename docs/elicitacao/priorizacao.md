# Priorização

A tarefa de priorização de requisitos consiste em determinar a necessidade relativa de cada requisito, levando em conta que todos os requisitos são obrigatórios e que alguns são mais importantes do que outros. Para realizar essa tarefa, podemos nos utilizar de diversas técnicas de priorização e com essas técnicas é possível dividir os requisitos em duas categorias básicas
1.  Requisitos que trarão grandes impactos e que podem colocar em risco o sistema inteiro se não forem implementados.
2.  Requisitos que terão impactos/consequências menores caso não sejam implementados corretamente. (ACHIMUGU et al., 2007).

Existem várias formas de estabelecer a prioridade de requisitos, porém, normalmente são utilizadas tabelas, nas quais os requisitos são categorizados em sendo de: Alta Prioridade, Média Prioridade e Baixa Prioridade. Essa categorização não depende somente da percepção do Engenheiro de Software, mas também e principalmente das expectativas dos usuários.

---

Dentre as técnicas de priorização, podemos citar algumas:


## 1. First Things First

Consiste em uma técnica mais elaborada que analisa o benefício relativo de cada recurso, a penalidade que o negócio sofreria caso o recurso não fosse incluído, o custo relativo da implementação da funcionalidade e o grau relativo de risco. Após essa análise, pode-se calcular a prioridade para cada requisito utilizando da seguinte formúla:

prioridade = valor (%) / custo (%) * peso(custo) + riscos (%) * peso(risco),

sendo valor = beneficio * peso(relativo) + penalidade * peso(relativo)

---

##  2. ROI (_Return On Investiment_)

O ROI consiste numa técnica onde é feita uma estimativa dos benefícios financeiros de um determinado investimento em uma tarefa. Esse indicador é geralmente calculado através de metodologias que comparam o lucro obtido/previsto contra o capital investindo, demonstrando seu resultado em valores quantificáveis e assim podemos fazer uma lista dos requisitos mais rentáveis para o projeto (FIGUEIREDO, ALMEIDA, ALENCAR).

Essa técnica, apesar de simples, é perigosa ao ser utilizada nos projetos por conta dos seguintes fatores:
1.  Tendência ao Custo: Tende a favorecer os requisitos que resultam na diminuição do custo, à custa de requisitos que prometem o crescimento de receita.
2.  Tendência a reflexos internos: O ROI mede apenas o retorno que a empresa pode ver dentro de suas operações internas, não mede os benefícios de produtividade para clientes e parceiros.
3.  Tendência Unidimensional: Requer que todos os requisitos sejam traduzidos em termos financeiros e nem todos os retornos são retornos financeiros em curto prazo.

Existem técnicas para solucionar esse problema, porém aumenta muito a complexidade dessa técnica de priorização.

---
A Técnica escolhida para a priorização dos requisitos identificados foi a técnica denominada MoSCoW. A explicação e o motivo da escolha podem ser observadas logo abaixo.

## 3. MoSCoW

Essa técnica é muito simples. Consiste em atribuir uma das quatro letras M,S,C ou W para cada item do backlog do produto. Os significados de cada letra pode ser encontrado na _Tabela 1_ abaixo.

| Letra   | Significado                                                                                                                                                                                                                                                                               |
|:-------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    M    | Must: Essa letra é atribuída para os requisitos prioritários/críticos para o negócio. Como por exemplo: requisitos que atendam normas legais (ex: normativas da bolsa de valores, Banco Central e Receita Federal).                                                                       |  
|    S    | Should: Representa os requisitos que são importantes, mas não são necessários (do ponto de vista estratégico) para entrega na sprint atual. O requisito com essa atribuição pode-se esperar um pouco para ser trabalhado ou pode-se ter outro meio de atender a necessidade classificada. | 
|    C    | Could: Consiste nos requisitos desejáveis, mas não necessários (do ponto de vista estratégico) e podem melhorar a satisfação do cliente com algum esforço de desenvolvimento. Dada a disponibidade de tempo e recursos, esses itens são atendidos.                                        |  
|    W    | Would/Want/Won't: São os requisitos menos críticos, com menor retorno sobre o investimento ou não adequados para serem realizados.                                                                                                                                                        | 

_Tabela 1: Tabela contendo o significado das letras da técnica MoSCow e em quais requisitos elas devem ser atribuidas. Fonte: autoria própria._ 

Essa técnica foi a escolhida pois apresenta vantagens mais benéficas frente às outras técnicas, sendo elas:
-   Fácil compreensão;
-   Fácil de se trabalhar;
-   Linguagem simples;
-   Permite a participação de todos os interessados;
-   Não requer conhecimento prévio da técnica
A confirmação ou não da prioridade dos requisitos é de cunho do cliente, logo, o contato com ele deve ser frequente.

### 3.1 Resultados

Ao analisar todos os requisitos identificados com o uso das técnicas de elicitação, foram definidas as prioridades que podem ser vistas na _Tabela 2_ a seguir.

|  ID  | Requisito                                                                                                  | Prioridade |
|:----:|------------------------------------------------------------------------------------------------------------|:-----------|
| RF1  | O usuário deve poder criar uma página.                                                                     | M          |
| RF2  | O usuário deve poder encontrar uma página criada previamente.                                              | M          |
| RF3  | O usuário deve poder editar uma página.                                                                    | M          |
| RF4  | O usuário deve poder excluir uma página quando desejado.                                                   | M          |
| RF5  | O usuário deve poder ser autenticado no sistema.                                                           | M          |
| RF6  | O usuário deve poder pesquisar as páginas já criadas pelo nome delas.                                      | C          |
| RF7  | O usuário deve poder escolher em qual fonte editar suas páginas.                                           | S          |
| RF8  | O usuário deve poder escolher entre o tamanho de fonte grande e pequena.                                   | C          |
| RF9  | O usuário deve poder escolher se o texto ocupa toda a largura da página ou se fica centralizado na página. | C          |
| RF10 | O usuário deve poder ver o histórico de alterações da página.                                              | S          |
| RF11 | O usuário deve poder favoritar a página.                                                                   | C          |
| RF12 | O usuário deve poder compartilhar o link para a página.                                                    | M          |
| RF13 | O usuário deve poder escolher a aparência do sistema.                                                      | W          |
| RF14 | O usuário deve poder escolher uma foto de identificação para cada página.                                  | W          |
| RF15 | O usuário deve poder escolher uma foto de identificação para o workspace.                                  | C          |
| RF16 | O usuário deve poder ter quantos workspaces desejar.                                                       | S          |
| RF17 | O usuário deve poder escolher entre opções de templates para uma página criada.                            | M          |
| RF18 | O usuário deve poder ver o histórico de páginas deletadas.                                                 | S          |
| RF19 | O usuário deve poder importar páginas de outras plataformas ou aplicativos.                                | C          |
| RF20 | O usuário deve poder adicionar fotos a página.                                                             | S          |
| RF21 | O usuário deve poder referenciar outras páginas dentro de uma página.                                      | C          |
| RF22 | O usuário deve poder adicionar outros perfis para editar uma página.                                       | C          |
| RF23 | O usuário deve poder adicionar uma legenda às imagens da página.                                           | C          |
| RF24 | O usuário deve poder escrever comentários nas páginas.                                                     | W          |
| RF25 | O usuário deve poder criar blocos de markdown para editar as páginas.                                      | M          |
| RF26 | O usuário deve poder escolher entre opções de edição do bloco de markdown.                                 | M          |
| RF27 | O usuário deve poder ter uma agenda para visualizar afazeres do dia.                                       | S          |
| RF28 | O usuário deve poder criar Formulas matemáticas.                                                           | S          |
| RF29 | O usuário deve poder criar seu próprio quadro kanban personalizado.                                        | S          |
| RF30 | O usuário pode escrever blocos de código.                                                                  | C          |
| RF31 | O usuário deve ser informado da situação do clima em sua região.                                           | W          |
| RF32 | O usuário deve conseguir criar uma conta.                                                                  | M          |
| RF33 | O usuário deve conseguir realizar logout                                                                   | M          |
| RNF1 | Deve ser possível instalar a aplicação em dispositivos android                                             | S          |
| RNF2 | A interface do sistema deve ser responsiva                                                                 | S          |
| RNF3 | O aplicativo deve ser cross-plataform                                                                      | S          |
| RNF4 | As Formulas Matemáticas devem seguir o formato LaTeX.                                                      | M          |
| RNF5 | A sintaxe dos códigos devem seguir uma das linguagens mais recentes.                                       | M          |

_Tabela 2: Tabela contendo os requisitos e suas respectivas prioridades. Fonte: autoria própria._

## 4. 100 pontos

O método dos 100 dolares é ótimo para priorizar requisitos com multiplos stakeholders. Ele se baseia em
cada stakeholder destribuir 100 pontos, atribuindo maior pontuação aos requisitos considerados mais importantes.(Gomes, Aline. 2011)

Para proseguir com a priorização foi realizada um entrevista que está desponível a seguir:

### 4.1 Resultados

## Referências Bibliográficas

ACHIMUGU, P. et al. A Systematic Literature Review of Software Requirements Prioritization
Research. Information and software technology, Elsevier, v. 56, n. 6, p. 568–585, 2014.

SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 07

FIGUEIREDO, André; ALMEIDA, Rodrigo; ALENCAR, Vitruvio; Um Conjunto de práticas para auxiliar o cálculo de ROI em processos de software. p.2

Gomes, Aline; Policani, André; Priorização de requisitos e avaliação da qualidade de software segundo a percepção dos usuários; Rj, 2011.

## Histórico de Versões

| Versão | Data       | Descrição                                  | Autor                             | Revisor           |
|--------|------------|--------------------------------------------|-----------------------------------|-------------------|
| 1.0    | 13/07/2022 | Criação do Artefato                        | Guilherme Brito                   | Bernardo Pissutti |
| 1.1    | 13/07/2022 | Realização da priorização dos Requisitos   | Guilherme Brito e Bernardo Chaves | Bernardo Pissutti |
| 1.2    | 26/07/2022 | Documentação do método dos 100 pontos      | Bernardo Pissutti                 | -                 |
| 1.3    | 28/07/2022 | Adição da coluna de requisitos na Tabela 2 | Bernardo Pissutti                 | -                 |
