# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

### Persona 1: Dr. Rafael Almeida (Médico)

Perfil: Dr. Rafael Almeida, 38 anos, é um médico experiente que trabalha em um hospital de grande porte. Ele tem conhecimento avançado em tecnologia e utiliza sistemas de registro eletrônico de saúde em sua prática diária.
Necessidades: Dr. Rafael busca uma aplicação que simplifique a análise de históricos médicos de pacientes, economizando tempo em tarefas administrativas e fornecendo acesso rápido e seguro às informações dos pacientes. Ele valoriza a precisão e a eficiência.

### Persona 2: Maria Santos (Paciente)

Perfil: Maria Santos, 54 anos, é uma paciente ativa que lida com algumas condições médicas crônicas. Ela tem conhecimento básico em tecnologia e utiliza um smartphone para manter o controle de seus registros médicos.
Necessidades: Maria procura uma aplicação que facilite o acesso aos seus históricos médicos, permitindo um melhor acompanhamento de sua saúde. Ela deseja informações de saúde compreensíveis e dicas úteis para melhorar seu bem-estar.



## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário  (Paciente) | Preencher meus dados uma vez       | Permitir serem usados de novo outra hora|
|Usuário (Profissional da saúde) | Ver em um clique informações sobre o paciente                 | Para poder fazer o trabalho mais eficiente de maneira mais rápida |
|Usuário (Paciente) | Poder editar meus dados quando necessario | Para poder facilitar o atendimento |
|Usuário (Centros Medicos) | Aderir o aplicativo ao banco de dados e atualizar em tempo real | Facilitar o atendimento de maneira rapida |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | Responsável |
|------|-----------------------------------------|----| ----|
|RF-002| O sistema deve permitir que o usuário cadastre informações| ALTA |  |
|RF-003| O sistema deve emitir um prontuário das informações    | ALTA | |
|RF-004| O sistema deve permitir atualização em tempo real | MEDIA | |
|RF-005| O sistema deve permitir editar dados | MEDIA | |
|RF-006| O sistema deve oferecer informações de primeiros socorros | BAIXA | |



### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema devera ter alta disponibilidade | MÉDIA | 
|RNF-002| O sistema sera executado a principio em web |  BAIXA | 
|RNF-003| O sistema devera atender as ordens legais | ALTA |
|RNF-004| Permitir a criptografia e segurança dos dados | ALTA |



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
|03| O projeto sera desenvolvido usando web responsivo     |



