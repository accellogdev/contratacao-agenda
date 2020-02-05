# Agenda

## Objetivo

Projeto de teste para vaga de emprego.

## Projeto

O tempo é um dos vilões entre as pessoas. Para isto, um bom controle das tarefas a serem executadas pode ajudar a muitos a cumprir seus objetivos, suas entregas, a realizar seus sonhos.

Devido a isto, vamos criar uma lista de tarefas a serem controladas. Neste projeto vamos precisar:

* Tela inicial com listagem de tarefas ordenadas por data de término.
* Cadastro de uma nova tarefa.
* Editar uma tarefa cadastrada.
* Excluir uma tarefa cadastrada.
* Marcar tarefa como concluída.

### Funcionalidades adicionais (Tarefas por usuário)

* Registro de usuário.
* Login e senha.
* Esqueci minha senha.
* Alterar senha.
* Logout.

## Funcionalidades

### Tela inicial com listagem de tarefas

Uma tela de listagem das tarefas a serem executadas. Precisamos listar na tela o título da tarefa, a data para finalizar a tarefa, o status da tarefa, um botão para concluir tarefa e um botão para excluir uma tarefa. Apresentar apenas tarefas abertas por padrão.
Ordenar as tarefas por data de entrega, ou seja, as primeiras entregas a serem feitas devem vir primeiro.

### Cadastro de uma nova tarefa

Na tela de listagem de tarefas, precisamos de um botão para incluir uma nova tarefa. Ao clicar neste botão o sistema deve direcionar o usuário para um formulário de cadastro de uma nova tarefa. Este formulário deve apresentar os seguintes campos:

* Título da tarefa.
* Descrição da tarefa.
* Data e hora de fim da tarefa.

Ao clicar em salvar o sistema deve gravar o registro no banco de dados e retornar para a tela de listagem de tarefas.

### Editar uma tarefa cadastrada

Ao clicar em alterar uma tarefa, o sistema deve direcionar o usuário para um formulário de edição. Informar os novos dados e salvar registro.

### Excluir uma tarefa cadastrada

Ao clicar no botão excluir tarefa, o sistema deve remover a tarefa do banco de dados e retornar para a tela de listagem de tarefas.

### Marcar tarefa como concluída

Ao clicar no botão concluir tarefa, o sistema deve alterar o status da tarefa como concluída e retornar a tela de listagem de tarefas.

## ENTREGA

* O layout é por conta do candidato.
* Qualquer dúvida pode entrar em contato com Gustavo da Accellog.
* Subir projeto no GitHub e encaminhar para Gustavo da Accellog o link do projeto.

## AVALIAÇÃO

* Entrega no prazo mesmo que seja parcial (não serão aceitos entregas fora do prazo).
* Apresentação do software (apresentar a entrega rodando na máquina do usuário - remoto). Como fez o projeto, como organizou o código, que bibliotecas utilizou.
* Aprendizado (em conversa com o candidato, como o período de aprendizado).
* Organização do código (avaliação feita depois da apresentação).

## Funcionalidades adicionais

Estas funcionalidades não são obrigatórias.

### Objetivo

Criar um controle de usuário de forma que cada usuário possa enchergar apenas as suas tarefas.

### Registro de usuário com perfil

Ao acessar a tela inicial do sistema, o usuário irá visualizar uma tela de login e um link para criar uma conta ou fazer um novo registro. Quando o usuário clicar no link, ele precisa ser direcionado para uma tela para fazer um novo cadastro. Para isto ele precisa informar:

* E-mail (não pode se duplicar e será utilizado como login).
* Senha (precisa ser criptografada).

Ao se cadastrar e enviar, ele precisa receber uma mensagem na tela informando que está registrado e ser direcionado para a tela principal onde irá fazer login no sistema.

### Login e senha

Ao informar usuário (e-mail) e senha corretamente, o usuário deve ser direcionado para a tela inicial. Se informar um usuário não existente ou se informar um usuário e senha incorretos, ele deve receber uma mensagem de "Login inválido" e retornar para a tela inicial.

### Esqueci minha senha

Na tela de login e senha, o sistema deve apresentar um link de esqueci minha senha. Ao clicar neste link, o sistema deve redirecionar ele para uma tela onde é necessário informar um e-mail para recuperar senha. Ao informar um e-mail cadastrado, o sistema deve encaminhar um e-mail para o usuário com uma nova senha para login.

### Alterar senha

Para um usuário logado, o sistema deve ter um menu com um link para visualizar perfil, alterar senha e logout. Ao clicar em alterar senha, o sistema deve direcionar o usuário para uma tela onde irá informar a senha atual, a nova senha, confirmar a nova senha e um botão salvar.

Validar se senha atual é válida antes de alterar para nova senha e verificar se a senha de confirmação está correta.

Se alteração de senha for confirmada, fazer logou do sistema e pedir para ele logar novamente com a nova senha.

### Alterar perfil

O usuário pode visualizar e alterar o seu perfil. Ao clicar no link visualizar perfil, o sistema deve mostrar para ele uma tela com suas informações de cadastro (Nome completo, Data de Nascimento, Cidade e Estado onde reside, E-mail de Login).

Com estas informações, o sistema precisa apresentar um botão para editar perfil. Ao clicar em editar perfil, o usuário deve ser direcionado a um formulário para alterar os dados de cadastro. O E-mail de Login e senha não devem ser alterados junto ao perfil.

Após alterar os dados de perfil, clicar no botão salvar para aplicar as alterações.

### Logout

Ao clicar no link "logout" o sistema deve ser fechado e precisa retornar para a tela de login.