# Priorização

A tarefa de priorização de requisitos consiste em determinar a necessidade relativa de cada requisito, levando em conta que todos os requisitos são obrigatórios e que alguns são mais importantes do que outros. Para realizar essa tarefa, podemos nos utilizar de diversas técnicas de priorização e com essas técnicas é possível dividir os requisitos em duas categorias básicas
1.  Requisitos que trarão grandes impactos e que podem colocar em risco o sistema inteiro se não forem implementados.
2.  Requisitos que terão impactos/consequências menores caso não sejam implementados corretamente. (ACHIMUGU et al., 2007).

Existem várias formas de estabelecer a prioridade de requisitos, porém, normalmente são utilizadas tabelas, nas quais os requisitos são categorizados em sendo de: Alta Prioridade, Média Prioridade e Baixa Prioridade. Essa categorização não depende somente da percepção do Engenheiro de Software, mas também e principalmente das expectativas dos usuários.

---

Dentre as técnicas de priorização, podemos citar algumas:


## First Things First

Consiste em uma técnica mais elaborada que analisa o benefício relativo de cada recurso, a penalidade que o negócio sofreria caso o recurso não fosse incluído, o custo relativo da implementação da funcionalidade e o grau relativo de risco. Após essa análise, pode-se calcular a prioridade para cada requisito utilizando da seguinte formúla:

prioridade = valor (%) / custo (%) * peso(custo) + riscos (%) * peso(risco),

sendo valor = beneficio * peso(relativo) + penalidade * peso(relativo)

---

##  ROI (_Return On Investiment_)

O ROI consiste numa técnica onde é feita uma estimativa dos benefícios financeiros de um determinado investimento em uma tarefa. Esse indicador é geralmente calculado através de metodologias que comparam o lucro obtido/previsto contra o capital investindo, demonstrando seu resultado em valores quantificáveis e assim podemos fazer uma lista dos requisitos mais rentáveis para o projeto (FIGUEIREDO, ALMEIDA, ALENCAR).

Essa técnica, apesar de simples, é perigosa ao ser utilizada nos projetos por conta dos seguintes fatores:
1.  Tendência ao Custo: Tende a favorecer os requisitos que resultam na diminuição do custo, à custa de requisitos que prometem o crescimento de receita.
2.  Tendência a reflexos internos: O ROI mede apenas o retorno que a empresa pode ver dentro de suas operações internas, não mede os benefícios de produtividade para clientes e parceiros.
3.  Tendência Unidimensional: Requer que todos os requisitos sejam traduzidos em termos financeiros e nem todos os retornos são retornos financeiros em curto prazo.

Existem técnicas para solucionar esse problema, porém aumenta muito a complexidade dessa técnica de priorização.

---
A Técnica escolhida para a priorização dos requisitos identificados foi a técnica denominada MoSCoW. A explicação e o motivo da escolha podem ser observadas logo abaixo.

## MoSCoW

Essa técnica é muito simples. Consiste em atribuir uma das quatro letras M,S,C ou W para cada item do backlog do produto. Os significados de cada letra pode ser encontrado na tabela abaixo.

| Letra | Significado    |
|:--------:|:-----|
| M    | Must: Essa letra é atribuída para os requisitos prioritários/críticos para o negócio. Como por exemplo: requisitos que atendam normas legais (ex: normativas da bolsa de valores, Banco Central e Receita Federal). |  
| S    | Should: Representa os requisitos que são importantes, mas não são necessários (do ponto de vista estratégico) para entrega na sprint atual. O requisito com essa atribuição pode-se esperar um pouco para ser trabalhado ou pode-se ter outro meio de atender a necessidade classificada. | 
| C    | Could: Consiste nos requisitos desejáveis, mas não necessários (do ponto de vista estratégico) e podem melhorar a satisfação do cliente com algum esforço de desenvolvimento. Dada a disponibidade de tempo e recursos, esses itens são atendidos.|  
| W    | Would/Want/Won't: São os requisitos menos críticos, com menor retorno sobre o investimento ou não adequados para serem realizados.| 

> Tabela 1: Tabela contendo o significado das letras da técnica MoSCow e em quais requisitos elas devem ser atribuidas. 

Essa técnica foi a escolhida pois apresenta vantagens mais benéficas frente às outras técnicas, sendo elas:
-   Fácil compreensão;
-   Fácil de se trabalhar;
-   Linguagem simples;
-   Permite a participação de todos os interessados;
-   Não requer conhecimento prévio da técnica
A confirmação ou não da prioridade dos requisitos é de cunho do cliente, logo, o contato com ele deve ser frequente.

## Resultados

Ao analisar todos os requisitos identificados com o uso das técnicas de elicitação, foram definidas as prioridades que podem ser vistas na tabela a seguir (Tabela 2).

| Requisito | Prioridade |
|:--------:|:-----|
| RF1    | M|
| RF2    | M|
| RF3    |M|
| RF4    |M|
| RF5    | M|
| RF6    | C |
| RF7    | S|
| RF8    | C|
| RF9    | C|
| RF10   | S|
| RF11   | C |
| RF12   | M|
| RF13   | W|
| RF14   | W|
| RF15   | C |
| RF16   | S|
| RF17   | M|
| RF18   | S|1
| RF19   |C|
| RF20   | S|
| RF21   |C|
| RF22   | C|
| RF23   | C|
| RF24   | W|
| RF25   | M |
| RF26   |M|
| RF27   |S|
| RF28   | S |
| RF29   | S |
| RF30   | C |
| RF31   | W |
| RNF1   | S  |
| RNF2   |S  |
| RNF3   | S|
| RNF4   | M |
| RNF5   | M |

>Tabela 2: Tabela contendo os requisitos e suas respectivas prioridades
## Referências Bibliográficas

ACHIMUGU, P. et al. A Systematic Literature Review of Software Requirements Prioritization
Research. Information and software technology, Elsevier, v. 56, n. 6, p. 568–585, 2014.

SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 07

FIGUEIREDO, André; ALMEIDA, Rodrigo; ALENCAR, Vitruvio; Um Conjunto de práticas para auxiliar o cálculo de ROI em processos de software. p.2

## Histórico de Versões
| Versão | Data       | Descrição         | Autor    |
|--------|------------|-------------------|----------|
| 1.0       | 13/07/2022           |      Criação do Artefato             |   Guilherme Brito       |
| 1.1       | 13/07/2022           |      Realização da priorização dos Requisitos             |   Guilherme Brito e Bernardo Chaves       |
