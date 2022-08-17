# Verificação do Caso de Uso

## 1. Contexto 


- Técnica utilizada: Inspeção com checklist.
- Autor do documento: Guilherme Brito.
- Inspetor: Leonardo Vitoriano.

O documento verificado está <a href="https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/casos_de_uso">aqui</a>


## 2. Checklist

Visando avaliar os Casos de Uso sobre o Notion, tendo como base a definição de *Serrano* sobre as principais características e elementos no qual um Casos de Uso deve conter, a seguinte checklist foi criada:

1. Possui ator(es)?
2. O(s) ator(es) esta(ão) do lado correto do limite do sistema?
3. O(s) ator(es) possuem associação com Caso de Uso?
4. Existe multiplicidade entre ator(es) e Caso de Uso?
5. Possui relação de extend ou include?
6. Os Casos de Uso estão no infinitivo? 
7. Existe limite do sistema?
8. O fluxo principal está correto?
9. O fluxo de exceção está correto?
10. A notação do diagrama é respeitada?
11. Possui rastreabilidade?
12. Uso de linguagem compreensível ao público?

### 2.1 Resultado 

O resultado da checklist do item 2 pode ser encontrado na *tabela 1* abaixo: 

| Item da Checklist | UC-Conta | UC-Documento | UC-Workspace  |
| - | --- | --- | --- |    
| 1 | Sim | Sim | Sim |   
| 2 | Sim | Sim | Sim |   
| 3 | Sim | Sim | Sim |   
| 4 | Não | Não | Não |   
| 5 | Sim | Sim | Sim |   
| 6 | Sim | Sim | Não |   
| 7 | Sim | Sim | Sim |   
| 8 | Sim | Sim | Sim |   
| 9 | Não | Não | Não |   
| 10| Sim | Sim | Não |
| 11| Não | Não | Não |
| 12| Sim | Sim | Não |  


*Tabela 1: Resultado da Checklist*

### 2.2 Dados percentuais de Acerto

Tendo como base a *tabela 1* do item 2.1, é possível descrever a porcentagem de sucesso dos Casos de Uso com relação aos 12 itens definidos na Checklist. A porcentagem de sucesso é descrita da *tabela 2*.

| UC | Porcentagem de Sucesso | 
| - | --- | 
| Conta | 75% |  
| Documento | 75% |  
| Workspace | ~67%  |

*Tabela 2: Porcentagem de sucesso dos Casos de Uso*

## 3. Conclusão

De acordo com a verificação utilizando a checklist desenvolvida, é possível notar que os itens 4, 9, 10 e 11 da Checklist em Casos de Uso não foram cumpridos, portanto o artefato Casos de Uso necessita de correções.

## Referência Bibliográfica

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. 50 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de Versões
| Versão | Data       | Descrição                            | Autor             |
|--------|------------|--------------------------------------|-------------------|
| 1.0    | 15/08/2022 | Criação do Contexto, Checklist e Conclusão| Leonardo Vitoriano|