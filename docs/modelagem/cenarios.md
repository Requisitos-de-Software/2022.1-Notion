# Introdução

A engenharia de requisitos utiliza, dentra suas várias estratégias para elicitação de requisitos, a de cenários. O foco dela 
está em prover uma descrição concreta e evolutiva de uma situação na qual o usuário engaja, provendo assim contexto para a tarefa de 
elicitação e, segundo o SWEBOK, um framework para as questões levantadas junto aos stakeholders sobre as tarefas do sistema, permitido 
assim que questionamentos na ordem de <i>e se</i> e <i>como isso é feito</i> sejam levantados.

# 1.0 Cenários

Cenários, são, grosso modo, modelos conceituais utilizados para descrever e melhor entender um software. Dentre as diversas 
estratégias de modelagem documentadas (diagramas de caso de uso, por exemplo), optou-se por utilizar a notação baseada em uma linguagem natural semi-estrututurada proposta
por Leite [9] e fundamentada nos seguintes elementos:

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

### 1.1 C01 - Cadastrar usuário através do Gmail

<table>
    <thead>
        <tr>
            <td>Elemento</td>
            <td>Descrição</td>
            <td>Restrições</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Título</td>
            <td>Cadastro de usuário no site do Notion através do Gmail</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Criar um usuário no Notion utilizando um email do Gmail</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
                <ul style="list-style: none">
                    <li>Local: Tela de login ou cadastro</li>
                    <li>Tempo: 2 minutos</li>
                    <li>Pré-condição: Possuir um email do gmail ao qual tenha acesso</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none">
                    <li>Não possuir email cadastrado no gmail</li>
                    <li>Ter perdido acesso ao email</li>
                    <li>Não dispor do tempo necessário</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Computador ou smartphone com acesso a internet e com um navegador web instalado</td>
            <td>
                <ul style="list-style: none">
                    <li>Usuário não possui acesso a internet</li>
                    <li>Usuário não possui computador ou smartphone</li>
                    <li>Usuário não possui navegador instalado em seus dispositivos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário ou organização que desejem se cadastrar</td>
            <td>
              -
            </td>
        </tr>
        <tr>
            <td>Episódio</td>
            <td>
                <ol>
                    <li>O usuário aceso a página inicial do Notion</li>
                    <li>O usuário seleciona as opções <i>Try Notion for Free</i> ou <i>Log in</i></li>
                    <li>O Usuário seleciona a opção <i>Continue With Google</i></li>
                    <li>O Usuário seleciona seu email ou o insere manualmente</li>
                    <li>Caso tenha selecionado o email, aguarda o cadastro. Senão, insere a senha.</li>
                    <li>O usuário informa qual tipo de trabalho faz</li>
                    <li>O usuário informa qual é sua profissão</li>
                    <li>O usuário informa o que deseja fazer no Notion</li>
                    <li>O usuário informa com quem pretende utilizar o Notion</li>
                    <li>O usuário clica em <i>Take Me to Notion</i></li>
                </ol>
            </td>
            <td>-</td>
        </tr>
    </tbody>
</table>

## Histórico de Versões

| Versão | Data       | Descrição                  | Autor             |
| ------ | ---------- | -------------------------- | ----------------- |
|   1.0     |  16/07/2022  | Criação do documento e início da escrita | Nícolas Georgeos Mantzos |
