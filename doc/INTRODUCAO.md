# 1 INTRODUÇÃO
## 1.1 - Objetivo
O objetivo do desenvolvimento deste projeto é aproximar a população e trazer todas as vozes para a discussão das políticas aplicadas pelos governantes de uma cidade nas mais diversas áreas, tal como segurança, habitação, educação, transporte e outros. O projeto permitirá com que cada pessoa, com um cadastro para ser identificada, poderá incluir, discutir e votar sobre os temas em pauta na câmara, bem como protestar contra projetos em prática pelos outras instancias do governo, como prefeito e secretários.

Esta aplicação será uma aplicação mobile desenvolvida em C# com Xamarin, inicialmente para dispositivos Androids porém, pelo caráter portável do Xamarin, porderá ser portada para IOs. Prevê-se utilizar a plataforma Jexia para Banco de Dados e também o IBM BlueMix para outras necessidades de servidores, como servidor de arquivos.

## 1.2 - Requisitos
### 1.2.1 - Análise dos Requisitos
Queremos um aplicativo com o qual todo usuário poderá opinar, criticar ou apoiar os projetos criados pelo prefeito, vereadores e secretários, portanto precisaremos de telas de cadastro para todos eles:
1. Usuário
1. Prefeito
1. Vereador
1. Secretário
1. Funcionários Públicos
1. Gestor do Sistema
1. Anunciantes

Precisaremos de cadastros para projetos e opniões, usuários comuns poderão cadastrar opniões enquanto os governantes e gestores poderão cadastrar projetos, todos estes terão opção de votação bem como de comentários, em projetos votados por veradores, o sistema mostrará como cada um votou.
1. Opniões
1. Projetos
1. Votações
1. Comentários

Como requisitos importantes precisaremos cadastrar os anúncios de diferentes tipos para faturamento da aplicação, teremos os seguintes cadastros:
1. Anúncios de Rodapé
1. Anúncios de Tela Cheia
1. Resultados dos Anúncios

E como requisito desejável teremos o chat entre os usuários, é claro que antes de conversar com um usuário, este primeiro precisará enviar uma solicitação de chat, se autorizado pelo outro usuário, eles poderão conversar, essa autorização de chat poderá ser revogada a qualquer momento por qualquer uma das partes.
1. Solicitação de Chat
1. Revogação de Chat
1. Bloqueio de Chat

Outro requisito desejável são as denúncias, cada usuário poderá denunciar uma opnião, comentário, conversa ou outro usuário que teve por chat com um usuário, os gestores do sistema poderão definir a punição ou não pela denuncia.
1. Denúncia de Opnião
1. Denúncia de Comentário
1. Denúncia de Chat
1. Denúncia de Usuário

Um requisito desejável é que o usuário possa compartilhar uma opnião, projeto ou comentário, com um texto e link que levará quem tem o aplicativo instalado e usuário configurado, diretamente ao compartilhado.
1. Compartilhamento

### 1.2.2 - Casos de Uso
#### Usuário
#### Gestores do Município(Prefeito, Vereadores e Secretários)
#### Funcionários Públicos
#### Gestores do Sistema
#### Anunciantes
#### Anuncios
#### Chat
#### Denúncias
#### Compartilhamento


### 1.2.# - Requisitos Funcionais
#### RF.001 - Cadastros
<table>
  <tr>
    <th>Identificador</th>
    <td colspan="3">RF.001.1</td>
  </tr>
  <tr>
    <th>Nome</th>
    <td colspan="3">Cadastro de usuários para acesso ao sistema</td>
  </tr>
    <th>Módulo</th>
    <td colspan="3">N/A</td>
  </tr>
    <th>Data Criação</th>
    <td>30/05/2018</td>
    <th>Autor</th>
    <td>Melky Salém</td>
  </tr>
  </tr>
    <th>Data Alteração</th>
    <td>30/05/2018</td>
    <th>Autor</th>
    <td>Melky Salém</td>
  </tr>
  </tr>
    <th>Versão</th>
    <td>1</td>
    <th>Prioridade</th>
    <td>Essencial</td>
  </tr>
  <tr>
    <th>Descrição</th>
    <td colspan="3">
      <p>Todo usuário que deseja acessar o sistema deverá ter um cadastro para tal.</p>
      <p>Este cadastro obrigatoriamente deverá incluir CPF, E-mail e Nome Completo.</p>     
      <p>O usuário poderá utilizar um email e senha para acesso ao sistema.</p>
      <p>O usuário poderá fazer o cadastro utilizando Google Account, Facebook ou Apple ID e preencher o restante dos dados.</p>
    </td>
</table>
