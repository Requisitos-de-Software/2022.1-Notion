# Introdução

A engenharia de requisitos utiliza, dentra suas várias estratégias para elicitação de requisitos, a de cenários. O foco dela 
está em prover uma descrição concreta e evolutiva de uma situação na qual o usuário engaja, provendo assim contexto para a tarefa de 
elicitação e, segundo o SWEBOK, um framework para as questões levantadas junto aos stakeholders sobre as tarefas do sistema,  
permitido assim que questionamentos na ordem de <i>e se</i> e <i>como isso é feito</i> sejam levantados.

# Cenários

Cenários, são, grosso modo, modelos conceituais utilizados para descrever e melhor entender um software. Dentre as diversas 
estratégias de modelagem documentadas (diagramas de caso de uso, por exemplo), optou-se por utilizar a notação baseada em uma linguagem natural semi-estrututurada proposta
por Leita [9] e fundamentada nos seguintes elementos:

<table>
    <thead>
        <tr>
            <td>Elemento</td>
            <td>Finalidade</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Título (<i>title</i>)</td>
            <td>Idenficar o cenário</td>
        </tr>
        <tr>
            <td>Objetivo (<i>goal</i>)</td>
            <td>Estabelecer a finalidade do cenário</td>
        </tr>
        <tr>
            <td>Contexto (<i>context</i>)</td>
            <td>Descrever o estado inicial, as pré-condições, o local e o tempo do cenário</td>
        </tr>
        <tr>
            <td>Recurso (<i>resource</i>)</td>
            <td>Identificar os recursos passivos com os quais os atores lidam</td>
        </tr>
        <tr>
            <td>Ator (<i>actor</i>)</td>
            <td>Identificar qualquer pessoa ou estrutura que tem um papel no cenário</td>
        </tr>
        <tr>
            <td>Episódio (<i>episode</i>)</td>
            <td>
                Representar uma ação realizada por um ator junto a outros atores utilizando os 
                recursos disponíveis.
            </td>
        </tr>
        <tr>
            <td>Restrição (<i>constraint</i>)</td>
            <td>
                Representar imposições que restrinjam um episódio, recurso ou contexto do cenário.
            </td>
        </tr>
    </tbody>
</table>

## Histórico de Versões

| Versão | Data       | Descrição                  | Autor             |
| ------ | ---------- | -------------------------- | ----------------- |
|   1.0     |  16/07/2022  | Criação do documento e início da escrita | Nícolas Georgeos Mantzos |
