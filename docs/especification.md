# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.



## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário  (Paciente) | Preencher meus dados uma vez       | Permitir serem usados de novo outra hora|
|Usuário (Profissional da saúde) | Ver em um clique informações sobre o paciente                 | Para poder fazer o trabalho mais eficiente de maneira mais rápida |
|Usuário (Paciente) | Poder editar meus dados quando necessario | Para poder facilitar o atendimento |
|Usuário (Centros Medicos) | Aderir o aplicativo ao banco de dados e atualizar em tempo real | Facilitar o atendimento de maneira rapida |
|Sistema | Como sistema devo ser seguro | Para poder terem confianca nos dados |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | Responsável |
|------|-----------------------------------------|----| ----|
|RF-001| Permitir a criptografia e segurança dos dados | ALTA |
|RF-002| Permitir que o usuário cadastre informações| ALTA |  |
|RF-003| Emitir um prontuário das informações    | ALTA | |
|RF-004| Permitir atualização em tempo real | MEDIA | |
|RF-005| Permitir editar dados | MEDIA | |
|RF-006| Oferecer informações de primeiros socorros | BAIXA | |



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
|02| Não pode ser desenvolvido um módulo de backend        |
|03| O projeto sera desenvolvido usando web responsivo     |



