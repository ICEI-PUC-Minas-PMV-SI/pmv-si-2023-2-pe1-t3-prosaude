# Especificações do Projeto

Este documento descreve as especificações do projeto para a aplicação web de Primeiros Socorros. O projeto foi desenvolvido considerando as necessidades de dois principais tipos de usuários:

## Personas

### Persona 1: Dr. Rafael Almeida (Médico)

Perfil: Dr. Rafael Almeida, 38 anos, é um médico experiente que trabalha em um hospital de grande porte. Ele tem conhecimento avançado em tecnologia e utiliza sistemas de registro eletrônico de saúde em sua prática diária.
Necessidades: Dr. Rafael busca uma aplicação que o ajude em sanar duvidas do publico de uma maneira rapida, eficaz e de graça.

### Persona 2: Maria Santos (Paciente)

Perfil: Maria Santos, 54 anos, é uma senhora com conhecimento em tecnologias e o mundo digital.
Necessidade: Com o passar da idade certas dores começaram a surgir e a mesma não quer se dirigir a um hospital pois não possui convenio e nao gostaria de ficar esperando muito tempo em uma fila apenas para saber o que está sentindo.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário  (Maria Santos) | Consultar informações sobre primeiros socorros | Para poder se previnir de futuras doenças e/ou alguma ocasião ja saber o que fazer|
|Usuário (Maria Santos) | Consultar um médico confiavel | Para poder tirar duvidas sobre o que está sentindo |
|Usuário (Dr. Rafael Almeida) | Poder cadastrar na plataforma | Para poder utilizala |
|Usuário (Dr. Rafael Almeida) | Sanar duvidas de usuarios sobre doenças, dores, etc | Para poder ajudar aqueles que necessitam |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | Responsável |
|------|-----------------------------------------|----| ----|
|RF-001| O sistema deve permitir que o médico, apenas ele se cadastre | ALTA |  |
|RF-002| O sistema deve oferecer informações de primeiros socorros | BAIXA | |
|RF-003| O sistema deve permitir responder perguntas | MEDIA | |
|RF-004| O sistema deve permitir recuperar a senha em caso de esquecimento | ALTA | |
|RF-006| O sistema deve permitir fazer login com uma conta ja existente | ALTA | |
|RF-007| O sistema deve permitir que os pacientes façam perguntas anonimas | MEDIA | |
|RF-008| O sistema deve permitir contatar os donos do site | BAIXA | |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema devera ter alta disponibilidade | MÉDIA | 
|RNF-002| O sistema sera executado a principio em web |  BAIXA | 
|RNF-003| O sistema devera atender as ordens legais | ALTA |


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| O projeto sera desenvolvido usando web responsivo     |



