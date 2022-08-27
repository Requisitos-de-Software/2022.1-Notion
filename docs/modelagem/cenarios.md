# Cenários

## 1. Introdução

A engenharia de requisitos utiliza, dentre suas várias estratégias para elicitação de requisitos, a de cenários; cujo foco
está em prover uma descrição concreta e evolutiva [1] de uma situação na qual o usuário engaja, provendo assim contexto para a tarefa de
elicitação e, segundo o SWEBOK [2], um framework para as questões levantadas junto aos stakeholders sobre as tarefas do sistema, permitido
assim que questionamentos na ordem de <i>e se</i> e <i>como isso é feito</i> sejam levantados.

## 2. Construção dos Cenários

Cenários são, de grosso modo, modelos conceituais utilizados para descrever e melhor entender um software. Dentre as diversas 
estratégias de modelagem documentadas (diagramas de caso de uso, por exemplo), optou-se por utilizar a notação baseada em uma linguagem natural semi-estrututurada proposta
por Leite [1] e fundamentada nos elementos da Tabela 1.

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
    <caption style="caption-side: bottom">Tabela 1: Elementos da abordagem textual semi-estruturada</caption>
</table>

### C01 Cadastro de usuário utilizando um email de qualquer provedor

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
            <td>Cadastro de usuário no site do Notion através de email</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Criar um usuário no Notion utilizando um email</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Local: Tela de login ou cadastro</li>
                    <li>Tempo: 2 minutos</li>
                    <li>Pré-condição: Possuir um email ao qual tenha acesso</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Não possuir nenhum email</li>
                    <li>Ter perdido acesso ao email ao qual tem acesso</li>
                    <li>Não dispor do tempo necessário</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Computador ou smartphone com acesso a internet e com um navegador web instalado</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não possui acesso a internet</li>
                    <li>Usuário não possui computador ou smartphone</li>
                    <li>Usuário não possui navegador instalado em seus dispositivos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário ou organização que desejem se cadastrar</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Episódio</td>
            <td>
                <ol>
                    <li>O usuário acesso a página inicial do Notion</li>
                    <li>O usuário clica nos botões <i>Try Notion for Free</i> ou <i>Log in</i></li>
                    <li>O usuário insere seu email no campo dedicado</li>
                    <li>O usuário clica no botão <i>Continue with email</i></li>
                    <li>O usuário consulta o email inserido para  obter o código temporário de login</li>
                    <li>O usuário insere o código que recebeu no campo dedicado</li>
                    <li>O usuário clica no botão <i>Continue with login code</i></li>
                    <li>O usuário informa seu nome</li>
                    <li>O usuário cria uma senha </li>
                    <li>O usuário informa qual tipo de trabalho faz</li>
                    <li>O usuário informa qual é sua profissão</li>
                    <li>O usuário informa o que deseja fazer no Notion</li>
                    <li>O usuário clica em <i>Continue</i></li>
                    <li>O usuário informa com quem pretende utilizar o Notion</li>
                    <li>O usuário clica em <i>Take Me to Notion</i></li>
                </ol>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não consegue encontrar os botões <i>Try Notion for Free</i> ou <i>Log in</i></li>
                    <li>Erro de autenticação por parte do Notion</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### C02 Cadastro de usuário utilizando o Gmail

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
                <ul style="list-style: none; padding-left: 0">
                    <li>Local: Tela de login ou cadastro</li>
                    <li>Tempo: 2 minutos</li>
                    <li>Pré-condição: Possuir um email do gmail ao qual tenha acesso</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
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
                <ul style="list-style: none; padding-left: 0">
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
                    <li>O usuário acesso a página inicial do Notion</li>
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
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não consegue encontrar os botões <i>Try Notion for Free</i> ou <i>Log in</i></li>
                    <li>Erro de autenticação por parte do Notion</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### C03 Cadastro de workspace

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
            <td>Cadastro de workspace</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Cadastrar um novo workspace</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Local: Tela inicial de um workspace</li>
                    <li>Tempo: 1 minuto</li>
                    <li>Pré-condição: Estar logado na aplicação</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Não estar logado na aplicação</li>
                    <li>Não dispor do tempo necessário</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Computador ou smartphone com acesso a internet e com um navegador web instalado</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não possui acesso a internet</li>
                    <li>Usuário não possui computador ou smartphone</li>
                    <li>Usuário não possui navegador instalado em seus dispositivos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário ou organização que já estejam cadastrados e desejem criar um novo workspace</td>
            <td>
              -
            </td>
        </tr>
        <tr>
            <td>Episódio</td>
            <td>
                <ol>
                    <li>O usuário acessa um workspace</li>
                    <li>O usuário localiza e clica no botão que contém o nome do workspace no qual está</li>
                    <li>O Usuário localiza e clica em três pontos que estão no pop-up que abriu</li>
                    <li>O usuário clica no botão <i>Join or create workspace</i></li>
                    <li>O usuário informa se deseja utilizar o workspace de forma individual ou coletiva</li>
                    <li>O usuário localiza e clica no botão <i>Take Me to Notion</i></li>
                </ol>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não consegue encontrar os botões</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### C04 Alteração de nome de workspace

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
            <td>Alteração de nome de workspace</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Alterar o nome do workspace</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Local: Tela inicial de um workspace</li>
                    <li>Tempo: 1 minuto</li>
                    <li>Pré-condição: Estar logado na aplicação</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Não estar logado na aplicação</li>
                    <li>Não dispor do tempo necessário</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Computador ou smartphone com acesso a internet e com um navegador web instalado</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não possui acesso a internet</li>
                    <li>Usuário não possui computador ou smartphone</li>
                    <li>Usuário não possui navegador instalado em seus dispositivos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário ou organização que já estejam cadastrados e desejem alterar o nome de algum workspace criado</td>
            <td> - </td>
        </tr>
        <tr>
            <td>Episódio</td>
            <td>
                <ol>
                    <li>O usuário acessa um workspace</li>
                    <li>O usuário clica no botão <i>Settings & Members</i></li>
                    <li>O usuário localiza e clica na subseção <i>settings</i> da seção <i>workspace</i></li>
                    <li>O usuário insere o nome que desejar no campo dedicado e clica em <i>Update</i></li>
                </ol>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não consegue encontrar os botões</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### C05 Cadastro de página em branco

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
            <td>Cadastro de página em branco</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Cadastrar uma nova página em branco/td>
            <td>-</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Local: Tela inicial de um workspace</li>
                    <li>Tempo: 30 s</li>
                    <li>Pré-condição: Estar logado na aplicação e ter ao menos um workspace cadastrado</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Não estar logado na aplicação</li>
                    <li>Não dispor do tempo necessário</li>
                    <li>Não ter nenhum workspace cadastrado</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Computador ou smartphone com acesso a internet e com um navegador web instalado</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não possui acesso a internet</li>
                    <li>Usuário não possui computador ou smartphone</li>
                    <li>Usuário não possui navegador instalado em seus dispositivos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário ou organização que já estejam cadastrados e desejem criar uma nova página em branco</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Episódio</td>
            <td>
                <ol>
                    <li>O usuário acessa um workspace</li>
                    <li>O usuário clica nos botões <i>Add a page</i> ou <i>New page</i></li>
                    <li>O usuário coloca um nome para a página no campo dedicado e clica em <i>Empty</i></li>
                </ol>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não consegue encontrar os botões</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### C06 Cadastro de página em branco com ícone

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
            <td>Cadastro de página em branco com ícone</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Cadastrar uma nova página em branco com ícone/td>
            <td>-</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Local: Tela inicial de um workspace</li>
                    <li>Tempo: 25s</li>
                    <li>Pré-condição: Estar logado na aplicação e ter ao menos um workspace cadastrado</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Não estar logado na aplicação</li>
                    <li>Não dispor do tempo necessário</li>
                    <li>Não ter nenhum workspace cadastrado</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Computador ou smartphone com acesso a internet e com um navegador web instalado</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não possui acesso a internet</li>
                    <li>Usuário não possui computador ou smartphone</li>
                    <li>Usuário não possui navegador instalado em seus dispositivos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário ou organização que já estejam cadastrados e desejem criar uma nova página em branco com ícone</td>
            <td> - </td>
        </tr>
        <tr>
            <td>Episódio</td>
            <td>
                <ol>
                    <li>O usuário acessa um workspace</li>
                    <li>O usuário clica nos botões <i>Add a page</i> ou <i>New page</i></li>
                    <li>O usuário coloca um nome para a página no campo dedicado e clica em <i>Empty with icon</i></li>
                </ol>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não consegue encontrar os botões</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### C07 Cadastro de página a partir de template

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
            <td>Cadastro de página a partir de template</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Cadastrar uma nova página a partir de templates do Notion</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                  <li>Local: Tela inicial de um workspace</li>
                  <li>Tempo: 30 s</li>
                  <li>Pré-condição: Estar logado na aplicação e ter ao menos um workspace cadastrado</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Não estar logado na aplicação</li>
                    <li>Não dispor do tempo necessário</li>
                    <li>Não possuir nenhum <i>workspace</i> cadastrado</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Computador ou smartphone com acesso a internet e com um navegador web instalado</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não possui acesso a internet</li>
                    <li>Usuário não possui computador ou smartphone</li>
                    <li>Usuário não possui navegador instalado em seus dispositivos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário ou organização que já estejam cadastrados e desejem criar um novo workspace</td>
            <td>
              -
            </td>
        </tr>
        <tr>
            <td>Episódio</td>
            <td>
                <ol>
                    <li>O usuário acessa um workspace</li>
                    <li>O usuário clica nos botões <i>Add a page</i> ou <i>New page</i></li>
                    <li>O usuário digita um nome no campo dedicado e clica em <i>Templates</i></li>
                    <li>O usuário clica no template que desejar</li>
                    <li>O usuário clica no botão <i>Use this template</i></li>
                </ol>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não consegue encontrar os botões</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### C08 Cadastro de página a partir de arquivo

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
            <td>Cadastro de página a partir de arquivo</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Cadastrar uma nova página a partir de arquivos</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                  <li>Local: Tela inicial de um workspace</li>
                  <li>Tempo: 2 min</li>
                  <li>Pré-condição: Estar logado na aplicação e ter ao menos um workspace cadastrado</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Não estar logado na aplicação</li>
                    <li>Não dispor do tempo necessário</li>
                    <li>Não possuir nenhum <i>workspace</i> cadastrado</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Computador ou smartphone com acesso a internet e com um navegador web instalado</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não possui acesso a internet</li>
                    <li>Usuário não possui computador ou smartphone</li>
                    <li>Usuário não possui navegador instalado em seus dispositivos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário ou organização que já estejam cadastrados e desejem criar uma nova página a partir de arquivos</td>
            <td>
              -
            </td>
        </tr>
        <tr>
            <td>Episódio</td>
            <td>
                <ol>
                    <li>O usuário acessa um workspace</li>
                    <li>O usuário clica nos botões <i>Add a page</i> ou <i>New page</i></li>
                    <li>O usuário digita um nome no campo dedicado e clica em <i>Import</i></li>
                    <li>O usuário clica no tipo de arquivo que deseja importar</li>
                    <li>O usuário seleciona o arquivo a partir do explorador</li>
                </ol>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não consegue encontrar os botões</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### C09 Cadastro de página a partir de base de dados

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
            <td>Cadastro de página a partir das bases de dados do Notion</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Cadastrar uma nova página a partir das bases de dados do Notion</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                  <li>Local: Tela inicial de um workspace</li>
                  <li>Tempo: 30 s</li>
                  <li>Pré-condição: Estar logado na aplicação e ter ao menos um workspace cadastrado</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Não estar logado na aplicação</li>
                    <li>Não dispor do tempo necessário</li>
                    <li>Não possuir nenhum <i>workspace</i> cadastrado</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Computador ou smartphone com acesso a internet e com um navegador web instalado</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não possui acesso a internet</li>
                    <li>Usuário não possui computador ou smartphone</li>
                    <li>Usuário não possui navegador instalado em seus dispositivos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário ou organização que já estejam cadastrados e desejem criar uma nova página a partir das bases de dados do Notion</td>
            <td>
              -
            </td>
        </tr>
        <tr>
            <td>Episódio</td>
            <td>
                <ol>
                    <li>O usuário acessa um workspace</li>
                    <li>O usuário clica nos botões <i>Add a page</i> ou <i>New page</i></li>
                    <li>O usuário digita um nome no campo dedicado</li>
                    <li>O usuário clica em algum base de dados na seção <i>Database</i></li>
                </ol>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não consegue encontrar os botões</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### C10 Adicionar link entre páginas

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
            <td>Adicionar link entre páginas</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Cadastrar um link para uma página dentro de outra página</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                  <li>Local: Página</li>
                  <li>Tempo: 30 s</li>
                  <li>Pré-condição: Estar logado na aplicação e ter ao menos um workspace e uma página cadastrados</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Não estar logado na aplicação</li>
                    <li>Não dispor do tempo necessário</li>
                    <li>Não possuir nenhum <i>workspace</i> cadastrado</li>
                    <li>Não possuir nenhuma página cadastrada</li>
                    <li>Possuir somente uma página cadastrada</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Computador ou smartphone com acesso a internet e com um navegador web instalado</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não possui acesso a internet</li>
                    <li>Usuário não possui computador ou smartphone</li>
                    <li>Usuário não possui navegador instalado em seus dispositivos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário ou organização que já estejam cadastrados e desejem criar links entre páginas</td>
            <td> - </td>
        </tr>
        <tr>
            <td>Episódio</td>
            <td>
                <ol>
                    <li>O usuário acessa uma página</li>
                    <li>O usuário identifica a linha na qual deseja adicionar um link</li>
                    <li>O usuário clica nos quatro pontos à esquerda dessa linha</li>
                    <li>O usuário clica na opção <i>Page</i></li>
                </ol>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não consegue encontrar os botões</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### C11 Sair da aplicação (<i>logout</i>)

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
            <td>Sair da aplicação (<i>logout</i>)</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Usuário deseja realizar <i>logout</i> da aplicação</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Contexto</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Local: Qualquer tela da aplicação</li>
                    <li>Tempo: 10 segundos</li>
                    <li>Pré-condição: Estar logado na aplicação e possuir acesso a internet</li>
                </ul>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Não estar logado na aplicação</li>
                    <li>Não dispor do tempo necessário</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>Computador ou smartphone com acesso a internet e com um navegador web instalado</td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não possui acesso a internet</li>
                    <li>Usuário não possui computador ou smartphone</li>
                    <li>Usuário não possui navegador instalado em seus dispositivos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Usuário ou organização que desejem deslogar da aplicação</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Episódio</td>
            <td>
                <ol>
                   <li>Usuário clica na imagem do workspace no canto superior esquerdo</li>
                    <li>Usuário clica em <i>Log out all</i></li>
                </ol>
            </td>
            <td>
                <ul style="list-style: none; padding-left: 0">
                    <li>Usuário não consegue encontrar os botões</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

## Referências Bibliográficas

[1] Leite, J., C., et al., Enhancing a Requirements Baseline with Scenarios, in
Proc. of the Third IEEE International Symposium on Requirements
Engineering (RE’97) – Annapolis, USA – IEEE Computer Society Press, p
44-53, 1997.

[2] Bourque, P., C., et al., Guide to the Software Engineering Body of Knowledge – IEEE Computer Society Press, p
37, 2004.

## Histórico de Versões

| Versão  | Data        | Descrição                               | Autor                    | Revisor  |
|---------|-------------|-----------------------------------------|--------------------------|----------|
| 1.0     | 16/07/2022  | Criação do documento e primeira escrita | Nícolas Georgeos Mantzos | Leonardo |
