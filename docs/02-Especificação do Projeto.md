# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

(FOTO)
Nome: Maria, 40 anos - Proprietária de uma loja de brechó.

Maria é uma empreendedora apaixonada por moda e sustentabilidade. Ela acredita que a moda pode ser uma forma de expressão pessoal e que também pode ter um impacto positivo no meio ambiente. Ela também é uma pessoa empática e valoriza a experiência de seus clientes, buscando criar um ambiente acolhedor e amigável em sua loja.

Maria é uma pessoa muito ocupada e trabalha muito para garantir que sua loja esteja sempre atualizada e oferecendo as melhores peças. Ela é muito exigente com a qualidade das peças que vende e se preocupa em oferecer um bom atendimento. Ela também valoriza a responsabilidade social e procura formas de apoiar a comunidade local.

Objetivos: Ela está sempre em busca de novas peças e tendências para sua loja e se preocupa em garantir que cada peça tenha qualidade e esteja em boas condições. Ela também se preocupa em oferecer preços justos e acessíveis para seus clientes e em criar um ambiente acolhedor e amigável em sua loja. 

Desafios: Como proprietária de uma loja de brechó, Maria enfrenta vários desafios diários. Ela também precisa lidar com a concorrência de outras lojas de brechó e de grandes varejistas. Além disso, ela se preocupa em promover a sustentabilidade e a responsabilidade social em sua loja, o que pode ser um desafio em uma sociedade que ainda não valoriza tanto esses aspectos. Maria precisa ser criativa e persistente para enfrentar esses desafios e garantir o sucesso de sua loja de brechó.

---------------------------------------------------------------------------------------------------------------------------------------------------------
(FOTO)
Nome: Jonas, 32 anos - Designer gráfico.

Jonas é um designer gráfico criativo que busca um estilo único e autêntico. Ele valoriza a originalidade e acredita que suas roupas são uma forma de expressar sua personalidade criativa. Ele também é uma pessoa consciente da sustentabilidade e está preocupado com o impacto de suas escolhas no meio ambiente. Por isso, ele prefere comprar roupas usadas em vez de comprar novas, já que isso ajuda a reduzir o desperdício de recursos naturais.

Jonas é está sempre busca peças de qualidade que possam durar muito tempo. Ele não se importa em pagar um pouco mais por peças que valem a pena, desde que estejam em boas condições. Ele também é um cliente que gosta de explorar e descobrir novas lojas de brechó, e adora garimpar peças raras.
 
Objetivos: Jonas prefere lojas que tenham uma boa seleção de roupas vintage, com um estilo único e autêntico. Jonas espera encontrar um brechó que esteja alinhado com seus valores pessoais, que seja comprometido com a sustentabilidade e a responsabilidade social.

Desafios: Como Jonas é um cliente exigente, ele precisa encontrar um brechó que ofereça peças de qualidade e em boas condições. Ele espera encontrar uma boa seleção de roupas exclusivas, o que pode ser um desafio em alguns brechós. 

--------------------------------------------------------------------------------------------------------------------------------------------------------

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
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
